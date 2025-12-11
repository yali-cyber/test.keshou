import React, { useState, useEffect, useRef } from 'react';
import { Terminal, Scan, Activity, Droplets, Zap, Shield, MoveRight, Hexagon, X } from 'lucide-react';

/* ========================================
  THEME CONFIGURATION: MEN'S SKINCARE "BIO-OPTIMIZATION"
  STYLE: INDUSTRIAL BRUTALISM x CYBERPUNK
  ACCENT: TOXIC NEON GREEN (#39ff14)
  ========================================
*/

const THEME = {
  colors: {
    bg: '#050505',
    text: '#ffffff',
    accent: '#39ff14', // Toxic Green
    dim: '#333333',
    border: 'rgba(255, 255, 255, 0.1)',
  }
};

// Custom Hook for Scroll Reveal
const useOnScreen = (options) => {
  const ref = useRef(null);
  const [visible, setVisible] = useState(false);

  useEffect(() => {
    const observer = new IntersectionObserver(([entry]) => {
      if (entry.isIntersecting) {
        setVisible(true);
        observer.unobserve(entry.target);
      }
    }, options);
    if (ref.current) observer.observe(ref.current);
    return () => {
      if (ref.current) observer.unobserve(ref.current);
    };
  }, [ref, options]);

  return [ref, visible];
};

// Reveal Component
const Reveal = ({ children, className = "", delay = 0 }) => {
  const [ref, visible] = useOnScreen({ threshold: 0.1 });
  return (
    <div
      ref={ref}
      className={`transition-all duration-1000 cubic-bezier(0.2, 1, 0.2, 1) ${className}`}
      style={{
        opacity: visible ? 1 : 0,
        transform: visible ? 'translateY(0) scale(1)' : 'translateY(50px) scale(0.95)',
        transitionDelay: `${delay}ms`
      }}
    >
      {children}
    </div>
  );
};

export default function App() {
  const [scrollY, setScrollY] = useState(0);
  const [mousePos, setMousePos] = useState({ x: 0, y: 0 });

  useEffect(() => {
    const handleScroll = () => setScrollY(window.scrollY);
    const handleMouseMove = (e) => setMousePos({ x: e.clientX, y: e.clientY });
    
    window.addEventListener('scroll', handleScroll);
    window.addEventListener('mousemove', handleMouseMove);
    return () => {
      window.removeEventListener('scroll', handleScroll);
      window.removeEventListener('mousemove', handleMouseMove);
    };
  }, []);

  // --- CSS INJECTION FOR NOISE, GLITCH, MARQUEE ---
  const styles = `
    @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400&family=Oswald:wght@400;700&display=swap');
    
    body {
      background-color: ${THEME.colors.bg};
      color: ${THEME.colors.text};
      font-family: 'Oswald', sans-serif;
      overflow-x: hidden;
      cursor: none;
    }
    
    .font-mono { font-family: 'JetBrains Mono', monospace; }
    
    /* Custom Scrollbar */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: #000; }
    ::-webkit-scrollbar-thumb { background: ${THEME.colors.accent}; }

    /* Noise Texture */
    .noise-overlay {
      position: fixed;
      top: 0; left: 0; width: 100%; height: 100%;
      pointer-events: none;
      z-index: 9998;
      opacity: 0.05;
      background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48ZmlsdGVyIGlkPSJnoiPjxmZVR1cmJ1bGVuY2UgdHlwZT0iZnJhY3RhbE5vaXNlIiBiYXNlRnJlcXVlbmN5PSIwLjY1IiBudW1PY3RhdmVzPSIzIiBzdGl0Y2hUaWxlcz0ic3RpdGNoIi8+PC9maWx0ZXI+PHJlY3Qgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsdGVyPSJ1cmwjZykiIG9wYWNpdHk9IjEiLz48L3N2Zz4=');
    }

    /* Scanlines */
    .scanlines {
      position: fixed;
      top: 0; left: 0; width: 100%; height: 100%;
      background: linear-gradient(to bottom, rgba(255,255,255,0), rgba(255,255,255,0) 50%, rgba(0,0,0,0.2) 50%, rgba(0,0,0,0.2));
      background-size: 100% 4px;
      pointer-events: none;
      z-index: 9999;
      opacity: 0.15;
    }

    /* Kinetic Marquee */
    @keyframes marquee {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }
    .marquee-container { overflow: hidden; white-space: nowrap; }
    .marquee-content { display: inline-block; animation: marquee 20s linear infinite; }

    /* Glitch Effect */
    .glitch-text { position: relative; }
    .glitch-text::before, .glitch-text::after {
      content: attr(data-text);
      position: absolute; top: 0; left: 0; width: 100%; height: 100%;
      background: ${THEME.colors.bg};
    }
    .glitch-text::before {
      left: 2px; text-shadow: -1px 0 #ff00c1; clip-path: inset(44% 0 61% 0);
      animation: glitch-anim-1 2.5s infinite linear alternate-reverse;
    }
    .glitch-text::after {
      left: -2px; text-shadow: -1px 0 ${THEME.colors.accent}; clip-path: inset(50% 0 30% 0);
      animation: glitch-anim-2 3s infinite linear alternate-reverse;
    }
    @keyframes glitch-anim-1 {
      0% { clip-path: inset(20% 0 80% 0); }
      20% { clip-path: inset(60% 0 10% 0); }
      40% { clip-path: inset(40% 0 50% 0); }
      60% { clip-path: inset(80% 0 5% 0); }
      80% { clip-path: inset(10% 0 70% 0); }
      100% { clip-path: inset(30% 0 30% 0); }
    }
    @keyframes glitch-anim-2 {
      0% { clip-path: inset(10% 0 60% 0); }
      20% { clip-path: inset(30% 0 10% 0); }
      40% { clip-path: inset(70% 0 20% 0); }
      60% { clip-path: inset(20% 0 50% 0); }
      80% { clip-path: inset(50% 0 40% 0); }
      100% { clip-path: inset(0% 0 90% 0); }
    }
  `;

  return (
    <>
      <style>{styles}</style>
      
      {/* --- OVERLAYS --- */}
      <div className="noise-overlay" />
      <div className="scanlines" />
      
      {/* Custom Cursor */}
      <div 
        className="fixed w-8 h-8 border border-white rounded-full pointer-events-none z-[10000] mix-blend-difference transition-transform duration-100 ease-out flex items-center justify-center"
        style={{ left: mousePos.x - 16, top: mousePos.y - 16 }}
      >
        <div className="w-1 h-1 bg-white rounded-full" />
      </div>

      {/* --- HEADER --- */}
      <header className="fixed top-0 w-full z-50 px-6 py-4 flex justify-between items-center border-b border-white/10 bg-[#050505]/80 backdrop-blur-sm">
        <div className="flex items-center gap-2">
          <Hexagon className="w-6 h-6 animate-pulse" color={THEME.colors.accent} />
          <span className="text-lg tracking-widest font-bold">BIO-OPT<span style={{color: THEME.colors.accent}}>.LABS</span></span>
        </div>
        <div className="hidden md:flex gap-8 font-mono text-xs text-gray-400">
          <span>// SYSTEM STATUS: ONLINE</span>
          <span>// V.4.0.2</span>
          <span>// TOKYO_SERVER</span>
        </div>
        <button className="border border-white/20 px-4 py-1 font-mono text-sm hover:bg-white hover:text-black transition-colors uppercase">
          [ Access ]
        </button>
      </header>

      {/* --- HERO SECTION --- */}
      <section className="relative h-screen w-full flex flex-col justify-center items-center overflow-hidden">
        {/* Background Parallax */}
        <div 
          className="absolute inset-0 z-0 opacity-40 grayscale contrast-125"
          style={{ 
            backgroundImage: `url('https://images.unsplash.com/photo-1550684848-fac1c5b4e853?q=80&w=2070&auto=format&fit=crop')`, // Dark Cyberpunk Fluid
            backgroundSize: 'cover',
            backgroundPosition: 'center',
            transform: `translateY(${scrollY * 0.5}px) scale(1.1)`
          }}
        />
        
        {/* Hero Content */}
        <div className="z-10 text-center flex flex-col items-center">
          <div className="font-mono text-xs md:text-sm text-gray-400 mb-4 border border-white/10 px-3 py-1 bg-black/50">
            SYSTEM_OVERRIDE_INITIATED
          </div>
          <h1 
            className="text-[12vw] leading-[0.85] font-bold uppercase tracking-tighter mix-blend-overlay glitch-text select-none"
            data-text="DEBUG YOUR SKIN"
          >
            DEBUG YOUR<br />
            <span style={{ color: 'transparent', WebkitTextStroke: `2px ${THEME.colors.accent}` }}>SKIN</span>
          </h1>
          
          <Reveal delay={200} className="mt-8 max-w-md text-gray-400 text-center font-mono text-sm md:text-base leading-relaxed px-4">
            <p>肌という名のOSを最適化せよ。<br/>不要なノイズを除去し、本来のスペックを引き出す。<br/>これは化粧水ではない。生体機能拡張パッチだ。</p>
          </Reveal>

          <Reveal delay={400} className="mt-12">
            <button className="group relative px-8 py-4 bg-transparent border border-[#39ff14] text-[#39ff14] font-mono uppercase text-sm tracking-widest overflow-hidden hover:text-black transition-colors duration-300">
              <span className="absolute inset-0 bg-[#39ff14] translate-y-full group-hover:translate-y-0 transition-transform duration-300 ease-out" />
              <span className="relative z-10 flex items-center gap-2">
                Execute Protocol <Zap size={16} />
              </span>
            </button>
          </Reveal>
        </div>

        {/* Scroll Indicator */}
        <div className="absolute bottom-10 right-10 flex flex-col items-center gap-2 font-mono text-[10px] text-[#39ff14] animate-bounce">
          <span>SCROLL</span>
          <div className="w-[1px] h-12 bg-[#39ff14]" />
        </div>
      </section>

      {/* --- KINETIC MARQUEE --- */}
      <div className="w-full py-6 border-y border-white/10 bg-[#0a0a0a] relative overflow-hidden">
        <div className="marquee-container font-mono text-4xl md:text-6xl text-white/10 font-bold select-none">
          <div className="marquee-content">
            BIO-OPTIMIZATION // DEBUG YOUR SKIN // RECONSTRUCT SURFACE // HYDRATION PROTOCOL // ELIMINATE IMPURITIES // BIO-OPTIMIZATION // DEBUG YOUR SKIN //
          </div>
          <div className="marquee-content" aria-hidden="true">
             BIO-OPTIMIZATION // DEBUG YOUR SKIN // RECONSTRUCT SURFACE // HYDRATION PROTOCOL // ELIMINATE IMPURITIES // BIO-OPTIMIZATION // DEBUG YOUR SKIN //
          </div>
        </div>
      </div>

      {/* --- BENTO GRID: FEATURES --- */}
      <section className="py-24 px-4 md:px-12 max-w-7xl mx-auto">
        <Reveal>
          <div className="flex items-end justify-between mb-12 border-b border-white/10 pb-4">
            <h2 className="text-4xl md:text-6xl font-bold uppercase">System Modules</h2>
            <span className="font-mono text-[#39ff14] text-xs">[ FEATURES_LOADED: 100% ]</span>
          </div>
        </Reveal>

        <div className="grid grid-cols-1 md:grid-cols-3 gap-4 h-auto md:h-[600px]">
          {/* Card 1: Hydration */}
          <Reveal className="md:col-span-2 relative group overflow-hidden border border-white/10 bg-[#111] h-full min-h-[300px]">
            <div className="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1519638399535-1b036603ac77?q=80&w=2000&auto=format&fit=crop')] bg-cover bg-center opacity-40 group-hover:scale-105 transition-transform duration-700 grayscale group-hover:grayscale-0" />
            <div className="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent" />
            <div className="absolute bottom-0 left-0 p-8 w-full">
              <div className="flex items-center gap-2 text-[#39ff14] mb-2">
                <Droplets size={20} />
                <span className="font-mono text-xs">HYDRATION_ENGINE</span>
              </div>
              <h3 className="text-3xl font-bold mb-2 uppercase">Deep Moisture Core</h3>
              <p className="text-gray-400 text-sm max-w-md font-mono">
                角質層の深部まで到達するナノ粒子デリバリーシステムを搭載。乾燥というバグを根源から修正する。
              </p>
            </div>
          </Reveal>

          {/* Card 2: Protection */}
          <Reveal delay={100} className="relative group overflow-hidden border border-white/10 bg-[#111] h-full min-h-[300px]">
            <div className="absolute top-4 right-4 text-white/20">
              <Shield size={40} strokeWidth={1} />
            </div>
            <div className="absolute bottom-0 left-0 p-6">
              <span className="font-mono text-xs text-[#39ff14] block mb-2">// FIREWALL</span>
              <h3 className="text-2xl font-bold uppercase mb-2">Barrier Defense</h3>
              <p className="text-gray-400 text-xs font-mono">都市の汚染物質、紫外線、ブルーライトなどの外部攻撃から肌を守る強力なシールドを展開。</p>
            </div>
            <div className="absolute inset-0 border border-[#39ff14] opacity-0 group-hover:opacity-100 transition-opacity duration-300 pointer-events-none" />
          </Reveal>

          {/* Card 3: Recovery */}
          <Reveal delay={200} className="relative group overflow-hidden border border-white/10 bg-[#111] h-full min-h-[300px]">
             <div className="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1579546929518-9e396f3cc809?q=80&w=2070&auto=format&fit=crop')] bg-cover bg-center opacity-20 mix-blend-luminosity" />
             <div className="absolute top-0 left-0 w-full h-full flex flex-col justify-between p-6">
                <div className="font-mono text-xs text-right text-gray-500">ERR_00: NO_FATIGUE</div>
                <div>
                   <Activity className="text-[#39ff14] mb-2" />
                   <h3 className="text-2xl font-bold uppercase">Auto-Repair</h3>
                </div>
             </div>
          </Reveal>

          {/* Card 4: Analytics */}
          <Reveal delay={300} className="md:col-span-2 relative group overflow-hidden border border-white/10 bg-[#111] flex flex-col md:flex-row items-center h-full min-h-[300px]">
             <div className="flex-1 p-8">
               <span className="font-mono text-xs text-[#39ff14] mb-2 block">04 // ANALYTICS</span>
               <h3 className="text-3xl font-bold uppercase mb-4">Visible Results</h3>
               <ul className="space-y-4 font-mono text-sm text-gray-400">
                 <li className="flex items-center gap-4">
                   <div className="w-full bg-gray-800 h-1"><div className="bg-[#39ff14] h-1 w-[92%]"></div></div>
                   <span>92% MOISTURE</span>
                 </li>
                 <li className="flex items-center gap-4">
                   <div className="w-full bg-gray-800 h-1"><div className="bg-[#39ff14] h-1 w-[88%]"></div></div>
                   <span>88% ELASTICITY</span>
                 </li>
               </ul>
             </div>
             <div className="flex-1 h-full w-full bg-[#000] border-l border-white/10 flex items-center justify-center relative overflow-hidden">
                <div className="absolute inset-0 flex items-center justify-center opacity-20">
                    <div className="w-[200px] h-[200px] border border-[#39ff14] rounded-full animate-ping" />
                </div>
                <div className="text-5xl font-bold">14<span className="text-sm font-mono align-top text-gray-500">DAYS</span></div>
             </div>
          </Reveal>
        </div>
      </section>

      {/* --- SPLIT SHOWCASE: PRODUCT --- */}
      <section className="min-h-screen flex flex-col md:flex-row relative">
        <div className="w-full md:w-1/2 bg-[#080808] border-r border-white/10 flex items-center justify-center relative overflow-hidden p-12">
           {/* Decorative Grid */}
           <div className="absolute inset-0" 
             style={{ backgroundImage: `linear-gradient(${THEME.colors.border} 1px, transparent 1px), linear-gradient(90deg, ${THEME.colors.border} 1px, transparent 1px)`, backgroundSize: '40px 40px', opacity: 0.2 }} 
           />
           <div className="relative z-10 w-full max-w-sm aspect-[3/4] border border-white/20 bg-black/50 backdrop-blur-md flex items-center justify-center group">
              <div className="absolute top-0 left-0 p-4 font-mono text-xs text-[#39ff14]">MODEL: TX-01</div>
              <div className="absolute bottom-0 right-0 p-4 font-mono text-xs text-gray-500">150ML // 5.07FL.OZ</div>
              {/* Product Placeholder */}
              <div className="w-32 h-64 bg-gradient-to-b from-gray-800 to-black border border-white/10 rounded-sm relative shadow-[0_0_50px_rgba(57,255,20,0.2)]">
                  <div className="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 text-center w-full">
                     <div className="text-xs font-mono tracking-widest text-gray-400 mb-2">ESSENCE</div>
                     <div className="text-xl font-bold tracking-tighter text-white">REBOOT</div>
                  </div>
              </div>
              
              {/* Hover Effect Details */}
              <div className="absolute -right-12 top-20 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center gap-2">
                 <div className="w-12 h-[1px] bg-[#39ff14]" />
                 <span className="bg-[#39ff14] text-black text-xs font-bold px-2 py-1">DISPENSER</span>
              </div>
           </div>
        </div>

        <div className="w-full md:w-1/2 flex flex-col justify-center p-12 md:p-24 bg-[#050505]">
          <Reveal>
            <div className="flex items-center gap-2 mb-6">
              <Terminal size={18} className="text-[#39ff14]" />
              <h4 className="font-mono text-[#39ff14] tracking-widest text-sm">SPECIFICATION</h4>
            </div>
            <h2 className="text-5xl md:text-7xl font-bold uppercase mb-8 leading-none">
              Liquid<br />
              Hardware.
            </h2>
            <p className="text-gray-400 font-mono text-sm leading-relaxed mb-12 border-l-2 border-[#39ff14] pl-6">
              あなたの肌に必要な成分のみを厳選してコンパイル。
              香料、着色料、パラベンといった不要なコードは一切含まれていない。
              純粋な機能美だけが、ここにある。
            </p>

            <div className="grid grid-cols-2 gap-8 mb-12">
               <div>
                  <div className="text-3xl font-bold text-white mb-1">0.02<span className="text-sm text-gray-500 font-mono">sec</span></div>
                  <div className="text-xs font-mono text-gray-500 uppercase">Absorb Speed</div>
               </div>
               <div>
                  <div className="text-3xl font-bold text-white mb-1">24<span className="text-sm text-gray-500 font-mono">h</span></div>
                  <div className="text-xs font-mono text-gray-500 uppercase">Effect Duration</div>
               </div>
            </div>

            <button className="self-start px-8 py-3 bg-white text-black font-bold uppercase tracking-widest hover:bg-[#39ff14] transition-colors duration-300 flex items-center gap-4">
              Initialize Purchase <MoveRight />
            </button>
          </Reveal>
        </div>
      </section>

      {/* --- INFINITE GALLERY --- */}
      <section className="py-24 border-t border-white/10 overflow-hidden">
        <div className="text-center mb-12">
            <h3 className="text-xl font-mono uppercase tracking-[0.5em] text-gray-500">Visual Log</h3>
        </div>
        <div className="flex gap-4 w-[200%] animate-[marquee_40s_linear_infinite]">
            {[1,2,3,4,5,6].map((i) => (
                <div key={i} className="w-[400px] h-[250px] flex-shrink-0 relative grayscale hover:grayscale-0 transition-all duration-500 border border-white/10">
                    <img 
                        src={`https://images.unsplash.com/photo-${i === 1 ? '1534030347209-7147fd9e7b2a' : i === 2 ? '1552664730-d307ca884978' : i === 3 ? '1504384308090-c54beed199c8' : '1550751827-4bd374c3f58b'}?q=80&w=800&auto=format&fit=crop`} 
                        alt="Gallery" 
                        className="w-full h-full object-cover"
                    />
                    <div className="absolute inset-0 bg-[#39ff14]/10 opacity-0 hover:opacity-100 transition-opacity duration-300" />
                    <div className="absolute bottom-2 right-2 font-mono text-[10px] bg-black px-1 text-white">IMG_00{i}</div>
                </div>
            ))}
        </div>
      </section>

      {/* --- FOOTER --- */}
      <footer className="bg-black border-t border-white/10 pt-24 pb-12 px-6">
        <div className="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-12 mb-24">
           <div className="col-span-2">
             <h2 className="text-4xl font-bold uppercase mb-6 tracking-tighter">Bio-Opt<span className="text-[#39ff14]">.Labs</span></h2>
             <p className="font-mono text-gray-500 text-sm max-w-sm">
                Redefining human interface maintenance through advanced biotechnology and brutalist aesthetics.
             </p>
           </div>
           
           <div>
              <h4 className="font-mono text-[#39ff14] mb-4 text-xs uppercase">[ Directory ]</h4>
              <ul className="space-y-2 font-mono text-sm text-gray-400">
                 <li className="hover:text-white cursor-pointer hover:translate-x-2 transition-transform">Products</li>
                 <li className="hover:text-white cursor-pointer hover:translate-x-2 transition-transform">Research</li>
                 <li className="hover:text-white cursor-pointer hover:translate-x-2 transition-transform">Manifesto</li>
                 <li className="hover:text-white cursor-pointer hover:translate-x-2 transition-transform">Support</li>
              </ul>
           </div>

           <div>
              <h4 className="font-mono text-[#39ff14] mb-4 text-xs uppercase">[ Connect ]</h4>
              <div className="flex gap-4">
                 <div className="w-10 h-10 border border-white/20 flex items-center justify-center hover:bg-[#39ff14] hover:text-black hover:border-[#39ff14] transition-all cursor-pointer">IG</div>
                 <div className="w-10 h-10 border border-white/20 flex items-center justify-center hover:bg-[#39ff14] hover:text-black hover:border-[#39ff14] transition-all cursor-pointer">X</div>
              </div>
           </div>
        </div>

        <div className="flex flex-col md:flex-row justify-between items-end border-t border-white/10 pt-8 font-mono text-xs text-gray-600">
           <div>
              &copy; 2025 BIO-OPTIMIZATION LABS. ALL RIGHTS RESERVED.<br/>
              EST. TOKYO, JP.
           </div>
           <div className="mt-4 md:mt-0 text-right">
              SYSTEM STATUS: STABLE<br/>
              PING: 14ms
           </div>
        </div>
      </footer>
    </>
  );
}
