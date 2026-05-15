<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>محمد الإسماعيلي — Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700;800&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Cairo', 'Inter', 'sans-serif'],
            arabic: ['Cairo', 'sans-serif'],
            latin: ['Inter', 'sans-serif'],
          },
          colors: {
            luxury: {
              950: '#0c0a09',
              900: '#1c1917',
              800: '#292524',
              400: '#a8a29e',
              300: '#d6d3d1',
            },
            sage: {
              DEFAULT: '#5f8d7e',
              light: '#7c9a92',
              dark: '#4a6b60',
              muted: 'rgba(95,141,126,0.12)'
            }
          }
        }
      }
    }
  </script>
  <style>
    :root {
      --bg: #090908;
      --glass: rgba(255,255,255,0.03);
      --glass-border: rgba(255,255,255,0.07);
      --glass-highlight: rgba(255,255,255,0.05);
    }

    * { margin: 0; padding: 0; box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Cairo', 'Inter', sans-serif;
      background: var(--bg);
      color: #fafaf9;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
    }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 5px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: rgba(255,255,255,0.12); border-radius: 20px; }
    ::-webkit-scrollbar-thumb:hover { background: rgba(255,255,255,0.2); }

    /* Noise overlay */
    .noise {
      position: fixed; inset: 0; pointer-events: none; z-index: 9999; opacity: 0.025;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
    }

    /* Glass */
    .glass {
      background: linear-gradient(135deg, rgba(255,255,255,0.04) 0%, rgba(255,255,255,0.01) 100%);
      backdrop-filter: blur(24px) saturate(180%);
      -webkit-backdrop-filter: blur(24px) saturate(180%);
      border: 1px solid var(--glass-border);
      box-shadow: 0 8px 32px rgba(0,0,0,0.35), inset 0 1px 0 rgba(255,255,255,0.04);
    }

    .glass-card {
      background: linear-gradient(160deg, rgba(255,255,255,0.05) 0%, rgba(255,255,255,0.01) 100%);
      backdrop-filter: blur(20px) saturate(160%);
      -webkit-backdrop-filter: blur(20px) saturate(160%);
      border: 1px solid rgba(255,255,255,0.06);
      box-shadow: 0 4px 24px rgba(0,0,0,0.2), inset 0 1px 0 rgba(255,255,255,0.04);
      transition: all 0.6s cubic-bezier(0.22, 1, 0.36, 1);
    }

    .glass-card:hover {
      transform: translateY(-6px) scale(1.01);
      border-color: rgba(255,255,255,0.12);
      box-shadow: 0 24px 48px rgba(0,0,0,0.45), inset 0 1px 0 rgba(255,255,255,0.08);
      background: linear-gradient(160deg, rgba(255,255,255,0.08) 0%, rgba(255,255,255,0.02) 100%);
    }

    /* Spotlight mouse tracking */
    .spotlight {
      position: relative; overflow: hidden;
    }
    .spotlight::before {
      content: ''; position: absolute;
      top: var(--mouse-y, 50%); left: var(--mouse-x, 50%);
      width: 350px; height: 350px;
      background: radial-gradient(circle, rgba(124,154,146,0.10) 0%, transparent 70%);
      transform: translate(-50%, -50%); pointer-events: none; opacity: 0;
      transition: opacity 0.4s ease;
    }
    .spotlight:hover::before { opacity: 1; }

    /* Typography */
    .text-gradient {
      background: linear-gradient(135deg, #fafaf9 0%, #a8a29e 100%);
      -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
    }
    .text-gradient-sage {
      background: linear-gradient(135deg, #9ab3a9 0%, #5f8d7e 100%);
      -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
    }

    /* Orbs */
    .orb {
      position: absolute; border-radius: 50%; filter: blur(100px); opacity: 0.35;
      animation: drift 25s infinite ease-in-out;
    }
    @keyframes drift {
      0%,100% { transform: translate(0,0) scale(1); }
      33% { transform: translate(40px,-60px) scale(1.08); }
      66% { transform: translate(-30px,30px) scale(0.95); }
    }

    /* Buttons */
    .btn-glass {
      background: linear-gradient(135deg, rgba(255,255,255,0.08) 0%, rgba(255,255,255,0.03) 100%);
      border: 1px solid rgba(255,255,255,0.1);
      backdrop-filter: blur(12px);
      transition: all 0.4s cubic-bezier(0.22, 1, 0.36, 1);
    }
    .btn-glass:hover {
      background: rgba(255,255,255,0.12);
      border-color: rgba(255,255,255,0.2);
      transform: translateY(-2px);
      box-shadow: 0 12px 40px rgba(0,0,0,0.35);
    }

    .btn-sage {
      background: linear-gradient(135deg, #5f8d7e 0%, #4a6b60 100%);
      border: 1px solid rgba(95,141,126,0.25);
      transition: all 0.4s cubic-bezier(0.22, 1, 0.36, 1);
      position: relative; overflow: hidden;
    }
    .btn-sage::before {
      content: ''; position: absolute; inset: 0;
      background: linear-gradient(135deg, rgba(255,255,255,0.15) 0%, transparent 60%);
      opacity: 0; transition: opacity 0.4s;
    }
    .btn-sage:hover::before { opacity: 1; }
    .btn-sage:hover {
      transform: translateY(-2px);
      box-shadow: 0 12px 40px rgba(95,141,126,0.2);
    }

    /* Tag pill */
    .tag-pill {
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.08);
      backdrop-filter: blur(8px);
    }

    /* Line deco */
    .line-deco {
      width: 48px; height: 1.5px;
      background: linear-gradient(90deg, transparent, #5f8d7e, transparent);
    }

    /* Reveal class */
    .reveal { opacity: 0; transform: translateY(40px); }

    /* Nav */
    .nav-glass {
      background: rgba(9,9,8,0.75);
      backdrop-filter: blur(20px) saturate(160%);
      border-bottom: 1px solid rgba(255,255,255,0.04);
    }

    /* Selection */
    ::selection { background: rgba(95,141,126,0.25); color: #fff; }

    /* Timeline dot */
    .timeline-dot {
      box-shadow: 0 0 0 4px rgba(9,9,8,0.9);
    }
  </style>
<base target="_blank">
</head>
<body class="antialiased">

  <div class="noise"></div>

  <!-- Navigation -->
  <nav class="nav-glass fixed top-0 w-full z-50 transition-all duration-500" id="navbar">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#" class="text-lg font-bold tracking-tight text-gradient">محمد الإسماعيلي</a>
      
      <div class="hidden md:flex items-center gap-8 text-[13px] font-medium text-stone-400">
        <a href="#about" class="hover:text-white transition-colors duration-300">نبذة</a>
        <a href="#skills" class="hover:text-white transition-colors duration-300">مهارات</a>
        <a href="#achievements" class="hover:text-white transition-colors duration-300">إنجازات</a>
        <a href="#experience" class="hover:text-white transition-colors duration-300">خبرات</a>
        <a href="#contact" class="hover:text-white transition-colors duration-300">تواصل</a>
      </div>

      <a href="https://drive.google.com/file/d/1iIo2xZ85yRnfpB2D6B_dMRKBNXX0_1tZ/view" download class="hidden md:inline-flex btn-glass px-5 py-2 rounded-full text-[13px] font-medium text-white items-center gap-2">
        <i class="fas fa-arrow-down text-[10px]"></i>
        السيرة الذاتية
      </a>

      <button id="menu-btn" class="md:hidden text-stone-300 hover:text-white transition-colors">
        <i class="fas fa-bars text-lg"></i>
      </button>
    </div>

    <div id="mobile-menu" class="hidden md:hidden px-6 pb-6 pt-2 border-t border-white/5">
      <div class="flex flex-col gap-4 text-sm text-stone-400">
        <a href="#about" class="hover:text-white transition-colors py-1">نبذة</a>
        <a href="#skills" class="hover:text-white transition-colors py-1">مهارات</a>
        <a href="#achievements" class="hover:text-white transition-colors py-1">إنجازات</a>
        <a href="#experience" class="hover:text-white transition-colors py-1">خبرات</a>
        <a href="#contact" class="hover:text-white transition-colors py-1">تواصل</a>
        <a href="https://drive.google.com/file/d/1iIo2xZ85yRnfpB2D6B_dMRKBNXX0_1tZ/view" download class="btn-glass px-4 py-2.5 rounded-full text-center text-white text-sm mt-2 inline-flex items-center justify-center gap-2">
          <i class="fas fa-download text-xs"></i>
          تحميل السيرة الذاتية
        </a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="relative min-h-screen flex items-center justify-center overflow-hidden pt-24">
    <div class="orb w-[28rem] h-[28rem] bg-sage/15 -top-20 -right-20"></div>
    <div class="orb w-[24rem] h-[24rem] bg-stone-500/10 bottom-0 left-0" style="animation-delay:-8s;"></div>
    <div class="orb w-80 h-80 bg-white/[0.03] top-1/3 left-1/3" style="animation-delay:-15s;"></div>

    <div class="max-w-7xl mx-auto px-6 relative z-10 w-full">
      <div class="grid lg:grid-cols-5 gap-16 items-center">
        
        <div class="lg:col-span-3 space-y-8">
          <div class="inline-flex items-center gap-2.5 tag-pill px-4 py-2 rounded-full text-xs font-medium text-stone-300 reveal">
            <span class="w-1.5 h-1.5 rounded-full bg-sage animate-pulse"></span>
            متاح للفرص التقنية والإعلامية
          </div>

          <h1 class="text-5xl md:text-7xl lg:text-8xl font-extrabold leading-[1.1] tracking-tight reveal">
            <span class="text-gradient block">محمد</span>
            <span class="text-gradient-sage block mt-1">الإسماعيلي</span>
          </h1>

          <p class="text-lg md:text-xl text-stone-400 font-light leading-relaxed max-w-xl reveal">
            طالب أمن سيبراني & مطور ويب · مقدم إذاعي & مصور ومونتير
          </p>

          <p class="text-stone-500 leading-[1.9] max-w-lg text-[15px] reveal">
            أجمع بين التميز التقني في الأمن السيبراني والحضور الإعلامي في التقديم والتصوير، بسجل حافل من الإنجازات المحلية والدولية وتمثيل السلطنة في محافل تقنية وإعلامية مرموقة.
          </p>

          <div class="flex flex-wrap gap-4 reveal">
            <a href="#contact" class="btn-sage px-8 py-3.5 rounded-full text-white text-sm font-semibold inline-flex items-center gap-2">
              تواصل معي
              <i class="fas fa-arrow-left text-[10px]"></i>
            </a>
            <a href="https://drive.google.com/file/d/1iIo2xZ85yRnfpB2D6B_dMRKBNXX0_1tZ/view?usp=sharing" download class="btn-glass px-8 py-3.5 rounded-full text-white text-sm font-medium inline-flex items-center gap-2">
              <i class="fas fa-download text-xs"></i>
              تحميل السيرة الذاتية
            </a>
          </div>

          <div class="flex flex-wrap gap-6 text-stone-500 text-xs pt-2 reveal">
            <span class="inline-flex items-center gap-2">
              <i class="fas fa-location-dot text-sage text-[10px]"></i>
              سلطنة عُمان، نزوى، حي التراث
            </span>
            <span class="inline-flex items-center gap-2">
              <i class="fas fa-envelope text-sage text-[10px]"></i>
              mohammed500ameer@gmail.com
            </span>
          </div>
        </div>

        <div class="lg:col-span-2 hidden lg:block reveal">
          <div class="glass rounded-[2rem] p-8 relative">
            <div class="space-y-7">
              <div class="flex items-center justify-between">
                <span class="text-stone-400 text-sm">المسابقات التقنية</span>
                <span class="text-3xl font-bold text-white tracking-tight">6+</span>
              </div>
              <div class="h-px bg-white/[0.06]"></div>
              <div class="flex items-center justify-between">
                <span class="text-stone-400 text-sm">المراكز المتقدمة</span>
                <span class="text-3xl font-bold text-sage tracking-tight">5</span>
              </div>
              <div class="h-px bg-white/[0.06]"></div>
              <div class="flex items-center justify-between">
                <span class="text-stone-400 text-sm">الخبرات الإعلامية</span>
                <span class="text-3xl font-bold text-white tracking-tight">8+</span>
              </div>
              <div class="h-px bg-white/[0.06]"></div>
              <div class="flex items-center justify-between">
                <span class="text-stone-400 text-sm">اللغات</span>
                <span class="text-3xl font-bold text-sage tracking-tight">2</span>
              </div>
            </div>
            
            <!-- Decorative squares -->
            <div class="absolute -top-5 -right-5 w-20 h-20 border border-white/[0.08] rounded-2xl -z-10"></div>
            <div class="absolute -bottom-6 -left-6 w-28 h-28 border border-sage/20 rounded-full -z-10"></div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-28 relative">
    <div class="max-w-4xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">النبذة الاحترافية</h2>
        <p class="text-stone-500 text-sm">ملخص السيرة المهنية والشخصية</p>
      </div>

      <div class="glass rounded-[2rem] p-8 md:p-14 reveal">
        <div class="prose prose-lg max-w-none text-stone-300 leading-[2.2] text-justify text-[15px] md:text-base">
          <p class="mb-6">
            طالب أمن سيبراني يتمتع بسجل بارز في المسابقات التقنية، خصوصًا مسابقات الأمن السيبراني والتقاط العلم. يمتلك خبرة عملية في العمل ضمن فرق تنافسية، وتمثيل المحافظة والسلطنة في فعاليات طلابية ورسمية، إلى جانب مهارات قوية في التقديم الإذاعي، الإلقاء أمام الجمهور، التصوير، المونتاج، وتصميم البوسترات والإعلانات.
          </p>
          <p>
            سيرة مركزة تجمع بين التميز التقني في الأمن السيبراني والحضور الإعلامي في التقديم والتصوير، مع تحقيق مراكز متقدمة على مستوى السلطنة ومستويات تنافسية أوسع.
          </p>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-12">
          <div class="text-center p-5 rounded-2xl bg-white/[0.03] border border-white/[0.05] hover:border-sage/20 transition-colors">
            <div class="text-xl font-bold text-sage mb-1">الأول</div>
            <div class="text-[11px] text-stone-500">التقط العلم 2024</div>
          </div>
          <div class="text-center p-5 rounded-2xl bg-white/[0.03] border border-white/[0.05] hover:border-sage/20 transition-colors">
            <div class="text-xl font-bold text-white mb-1">الثاني</div>
            <div class="text-[11px] text-stone-500">سور للأمن السيبراني</div>
          </div>
          <div class="text-center p-5 rounded-2xl bg-white/[0.03] border border-white/[0.05] hover:border-sage/20 transition-colors">
            <div class="text-xl font-bold text-white mb-1">الثاني</div>
            <div class="text-[11px] text-stone-500">الأولمبياد الوطني</div>
          </div>
          <div class="text-center p-5 rounded-2xl bg-white/[0.03] border border-white/[0.05] hover:border-sage/20 transition-colors">
            <div class="text-xl font-bold text-sage mb-1">16/600</div>
            <div class="text-[11px] text-stone-500">هاكاثون تحدي المجرات</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-28 relative bg-stone-950/40">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">المهارات التقنية والإعلامية</h2>
        <p class="text-stone-500 text-sm">المجالات التي أتخصص فيها وأمارسها باحترافية</p>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-5">
        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-sage-muted flex items-center justify-center mb-5 text-sage text-lg">
            <i class="fas fa-shield-halved"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">الأمن السيبراني</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">خبرة في مسابقات CTF والتحديات الأمنية، أساسيات الأمن السيبراني، والعمل ضمن فرق تقنية تنافسية.</p>
        </div>

        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-white/[0.04] flex items-center justify-center mb-5 text-white text-lg">
            <i class="fas fa-code"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">البرمجة والتطوير</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">Python، Cython، تطوير الويب، والمشاركة في مسابقات برمجية على مستوى المملكة العربية السعودية.</p>
        </div>

        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-sage-muted flex items-center justify-center mb-5 text-sage text-lg">
            <i class="fas fa-video"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">التصوير والمونتاج</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">إنتاج محتوى بصري احترافي، مونتاج الفيديو، والمشاركة في مسابقات التصوير والإبداع المرئي.</p>
        </div>

        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-white/[0.04] flex items-center justify-center mb-5 text-white text-lg">
            <i class="fas fa-microphone-lines"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">التقديم الإذاعي</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">تقديم حفلات رسمية، برامج إذاعية، الإلقاء أمام الجمهور، والتواصل الفعّال مع الحضور.</p>
        </div>

        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-sage-muted flex items-center justify-center mb-5 text-sage text-lg">
            <i class="fas fa-pen-nib"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">التصميم الجرافيكي</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">تصميم البوسترات والإعلانات، الهوية البصرية، والتغطية الإعلامية للفعاليات الرياضية والثقافية.</p>
        </div>

        <div class="glass-card spotlight rounded-2xl p-7 reveal">
          <div class="w-11 h-11 rounded-xl bg-white/[0.04] flex items-center justify-center mb-5 text-white text-lg">
            <i class="fas fa-users"></i>
          </div>
          <h3 class="text-base font-bold text-white mb-2">العمل الجماعي</h3>
          <p class="text-[13px] text-stone-400 leading-[1.8]">التمثيل الرسمي للمحافظة والسلطنة، العمل ضمن فرق متعددة التخصصات، والقيادة في البيئات التنافسية.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Achievements -->
  <section id="achievements" class="py-28 relative">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">الإنجازات والمسابقات</h2>
        <p class="text-stone-500 text-sm">سجل من الإنجازات التقنية على المستويين المحلي والدولي</p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-sage border-sage/20">التقط العلم</span>
            <span class="text-3xl font-extrabold text-sage">الأول</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">مهرجان عُمان للعلوم 2024</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">المركز الأول على مستوى المحافظات التعليمية في مسابقة التقط العلم للأمن السيبراني.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-calendar text-[9px]"></i>
            <span>2024</span>
            <span class="mx-1.5">•</span>
            <span>المحافظات التعليمية</span>
          </div>
        </div>

        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-white border-white/10">مسابقة سور</span>
            <span class="text-3xl font-extrabold text-white">الثاني</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">الأمن السيبراني — طلبة الجامعات</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">المركز الثاني مع كونه ضمن فريق من طلبة المدارس والفريق الوحيد المتأهل من هذه الفئة.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-users text-[9px]"></i>
            <span>فريق مختلط</span>
            <span class="mx-1.5">•</span>
            <span>المركز الثاني</span>
          </div>
        </div>

        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-sage border-sage/20">الأولمبياد الوطني</span>
            <span class="text-3xl font-extrabold text-sage">الثاني</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">الأمن السيبراني 2025-2026</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">المركز الثاني على مستوى طلبة مدارس السلطنة، ممثلاً لمحافظة الداخلية.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-school text-[9px]"></i>
            <span>طلبة مدارس السلطنة</span>
            <span class="mx-1.5">•</span>
            <span>ممثل المحافظة</span>
          </div>
        </div>

        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-white border-white/10">Cyber Yard</span>
            <span class="text-3xl font-extrabold text-white">12/50</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">المملكة العربية السعودية</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">المركز الثاني عشر من أصل 50 فريقاً على مستوى جميع فئات المملكة، والفريق الوحيد المتأهل من السلطنة.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-globe text-[9px]"></i>
            <span>دولي</span>
            <span class="mx-1.5">•</span>
            <span>جميع الفئات</span>
          </div>
        </div>

        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-sage border-sage/20">هاكاثون تحدي المجرات</span>
            <span class="text-3xl font-extrabold text-sage">16/600</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">مهرجان عُمان للعلوم</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">الاختيار ضمن 16 طالباً من أصل 600 طالب للمنافسة النهائية ضمن 4 فرق.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-rocket text-[9px]"></i>
            <span>هاكاثون</span>
            <span class="mx-1.5">•</span>
            <span>المرحلة النهائية</span>
          </div>
        </div>

        <div class="glass-card spotlight rounded-2xl p-8 reveal">
          <div class="flex justify-between items-start mb-5">
            <span class="tag-pill px-3 py-1.5 rounded-full text-[11px] text-white border-white/10">Cython</span>
            <span class="text-3xl font-extrabold text-white">الثاني</span>
          </div>
          <h3 class="text-lg font-bold text-white mb-2">مسابقة Cython — طلبة المدارس</h3>
          <p class="text-stone-400 text-[13px] leading-[1.8] mb-5">المركز الثاني مع فريق Cyber_Flood في مسابقة البرمجة الموجهة لطلبة المدارس.</p>
          <div class="flex items-center gap-2 text-[11px] text-stone-500">
            <i class="fas fa-laptop-code text-[9px]"></i>
            <span>برمجة</span>
            <span class="mx-1.5">•</span>
            <span>فريق Cyber_Flood</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="py-28 relative bg-stone-950/40">
    <div class="max-w-5xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">الخبرات الإعلامية والقيادية</h2>
        <p class="text-stone-500 text-sm">الفعاليات والأنشطة والتمثيل الرسمي</p>
      </div>

      <div class="relative">
        <div class="absolute right-[31px] top-3 bottom-3 w-px bg-gradient-to-b from-sage/40 via-white/5 to-transparent hidden md:block"></div>

        <div class="space-y-7">
          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-sage timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-sage">تقديم رسمي</span>
                <span class="text-[11px] text-stone-500">2024/2025</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">تقديم حفل «من أجل الوطن»</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">تقديم رسمي أمام جمهور وقيادات تربوية، تحت رعاية وحضور شخصيات تربوية بارزة.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-white timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-white">تدشين</span>
                <span class="text-[11px] text-stone-500">حفل تدشين</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">تدشين شعار فريق وادي كليوه</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">ممارسة عملية في التقديم وتنظيم الفعاليات والتواصل الفعّال مع الحضور.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-sage timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-sage">تمثيل رسمي</span>
                <span class="text-[11px] text-stone-500">حقوق الإنسان</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">جلسة حوارية مع رئيس اللجنة العمانية لحقوق الإنسان</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">تمثيل طلابي وحضور في فعالية حوارية رسمية ضمن سباق مرتبط باليونيسف.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-white timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-white">اليونيسف</span>
                <span class="text-[11px] text-stone-500">منظمة دولية</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">اجتماع منظمة الأمم المتحدة للطفولة</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">اختيار ضمن النخبة الممثلة لطلبة الداخلية بحضور شخصيات رسمية.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-sage timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-sage">إذاعة</span>
                <span class="text-[11px] text-stone-500">إعلام</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">برنامج إذاعة الشباب</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">استضافة إعلامية بعد إنجاز مسابقة سور للأمن السيبراني.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-white timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-white">برلمان الطفل</span>
                <span class="text-[11px] text-stone-500">عربي</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">البرلمان العربي للطفل</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">الوصول إلى مرحلة المقابلة الشفوية لعضوية البرلمان العربي للطفل من بين آلاف الطلبة.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-sage timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-sage">تصوير</span>
                <span class="text-[11px] text-stone-500">المركز الثالث</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">«الجيولوجيا في عُمان: كهف الهوتة»</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">المركز الثالث في مسابقة «وطني سياحة وإبداع» على مستوى طلبة محافظة الداخلية.</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-white timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-white">تغطية إعلامية</span>
                <span class="text-[11px] text-stone-500">المركز الخامس</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">تغطية اليوم الرياضي الموحد</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">المركز الخامس في مسابقة «أفضل تغطية إعلامية لفعالية اليوم الرياضي الموحد لمدارس سلطنة عُمان».</p>
            </div>
          </div>

          <div class="relative md:pr-20 reveal">
            <div class="absolute right-0 top-3 w-4 h-4 rounded-full bg-sage timeline-dot hidden md:block"></div>
            <div class="glass-card rounded-2xl p-7">
              <div class="flex flex-wrap items-center gap-3 mb-3">
                <span class="tag-pill px-3 py-1 rounded-full text-[11px] text-sage">تمثيل دولي</span>
                <span class="text-[11px] text-stone-500">2020</span>
              </div>
              <h3 class="text-base font-bold text-white mb-2">الملتقى الخليجي العاشر للأطفال — البحرين</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">تم اختياره للمشاركة ممثلاً للسلطنة في البحرين خلال الفترة من 15 إلى 17 يناير 2020 تحت رعاية سمو الشيخ عيسى بن علي آل خليفة.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Certificates -->
  <section class="py-28 relative">
    <div class="max-w-5xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">الشهادات والتدريب</h2>
        <p class="text-stone-500 text-sm">المؤهلات التعليمية والبرامج التدريبية</p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="glass-card rounded-2xl p-7 reveal">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 rounded-xl bg-sage-muted flex items-center justify-center text-sage text-xl shrink-0">
              <i class="fas fa-certificate"></i>
            </div>
            <div>
              <h3 class="text-base font-bold text-white mb-1">أساسيات الأمن السيبراني</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">شهادة تخصصية في مجال الأمن السيبراني والحماية الرقمية.</p>
            </div>
          </div>
        </div>

        <div class="glass-card rounded-2xl p-7 reveal">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 rounded-xl bg-white/[0.04] flex items-center justify-center text-white text-xl shrink-0">
              <i class="fas fa-graduation-cap"></i>
            </div>
            <div>
              <h3 class="text-base font-bold text-white mb-1">البرنامج التدريبي في التقنية العليا</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">مسقط — إكمال البرنامج التدريبي والحصول على شهادة إكمال الكورس.</p>
            </div>
          </div>
        </div>

        <div class="glass-card rounded-2xl p-7 reveal">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 rounded-xl bg-sage-muted flex items-center justify-center text-sage text-xl shrink-0">
              <i class="fas fa-award"></i>
            </div>
            <div>
              <h3 class="text-base font-bold text-white mb-1">شهادات شكر وتقدير متعددة</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">شهادات مرتبطة بالمشاركات والمسابقات والأنشطة الظاهرة في الملف.</p>
            </div>
          </div>
        </div>

        <div class="glass-card rounded-2xl p-7 reveal">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 rounded-xl bg-white/[0.04] flex items-center justify-center text-white text-xl shrink-0">
              <i class="fas fa-language"></i>
            </div>
            <div>
              <h3 class="text-base font-bold text-white mb-1">اللغات</h3>
              <p class="text-stone-400 text-[13px] leading-[1.8]">العربية: إتقان بطلاقة · الإنجليزية: ممتاز</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-28 relative bg-stone-950/40">
    <div class="max-w-4xl mx-auto px-6">
      <div class="text-center mb-16 reveal">
        <div class="line-deco mx-auto mb-6"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-gradient mb-3">تواصل معي</h2>
        <p class="text-stone-500 text-sm">جاهز للفرص التقنية والإعلامية والتعاون المهني</p>
      </div>

      <div class="glass rounded-[2rem] p-8 md:p-12 reveal">
        <div class="grid md:grid-cols-2 gap-8">
          <div class="space-y-5">
            <a href="mailto:mohammed500ameer@gmail.com" class="flex items-center gap-4 p-4 rounded-xl bg-white/[0.03] border border-white/[0.06] hover:border-sage/30 transition-all group">
              <div class="w-11 h-11 rounded-full bg-sage-muted flex items-center justify-center text-sage group-hover:scale-110 transition-transform">
                <i class="fas fa-envelope text-sm"></i>
              </div>
              <div>
                <div class="text-[11px] text-stone-500 mb-0.5">البريد الإلكتروني</div>
                <div class="text-white text-sm group-hover:text-sage transition-colors">mohammed500ameer@gmail.com</div>
              </div>
            </a>

            <a href="tel:+96896904500" class="flex items-center gap-4 p-4 rounded-xl bg-white/[0.03] border border-white/[0.06] hover:border-sage/30 transition-all group">
              <div class="w-11 h-11 rounded-full bg-white/[0.05] flex items-center justify-center text-white group-hover:scale-110 transition-transform">
                <i class="fas fa-phone text-sm"></i>
              </div>
              <div>
                <div class="text-[11px] text-stone-500 mb-0.5">الهاتف</div>
                <div class="text-white text-sm group-hover:text-sage transition-colors">+968-9690-4500</div>
              </div>
            </a>

            <div class="flex items-center gap-4 p-4 rounded-xl bg-white/[0.03] border border-white/[0.06]">
              <div class="w-11 h-11 rounded-full bg-sage-muted flex items-center justify-center text-sage">
                <i class="fas fa-location-dot text-sm"></i>
              </div>
              <div>
                <div class="text-[11px] text-stone-500 mb-0.5">الموقع</div>
                <div class="text-white text-sm">سلطنة عُمان، نزوى، حي التراث</div>
              </div>
            </div>
          </div>

          <div class="flex flex-col justify-center items-center text-center p-8 rounded-2xl bg-gradient-to-br from-sage-muted to-transparent border border-sage/10">
            <div class="w-14 h-14 rounded-full bg-sage/20 flex items-center justify-center text-sage text-xl mb-5">
              <i class="fas fa-paper-plane"></i>
            </div>
            <h3 class="text-lg font-bold text-white mb-2">لنبدأ حواراً</h3>
            <p class="text-stone-400 text-[13px] leading-[1.8] mb-8 max-w-xs">سواء كنت تبحث عن تعاون تقني، إعلامي، أو استشارة في مجال الأمن السيبراني.</p>
            <a href="mailto:mohammed500ameer@gmail.com" class="btn-sage px-10 py-3.5 rounded-full text-white text-sm font-semibold w-full md:w-auto inline-flex items-center justify-center gap-2">
              إرسال رسالة
              <i class="fas fa-arrow-left text-[10px]"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-14 border-t border-white/[0.04]">
    <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-6">
      <div class="text-center md:text-right">
        <div class="text-lg font-bold text-gradient mb-1">محمدالإسماعيلي
        </div>
        <p class="text-stone-500 text-[12px]">طالب أمن سيبراني & مطور ويب · مقدم إذاعي & مصور</p>
      </div>

      <div class="flex gap-3">
        <a href="mailto:mohammed500ameer@gmail.com" class="w-10 h-10 rounded-full glass flex items-center justify-center text-stone-400 hover:text-white hover:border-sage/30 transition-all duration-300">
          <i class="fas fa-envelope text-sm"></i>
        </a>
        <a href="tel:+96896904500" class="w-10 h-10 rounded-full glass flex items-center justify-center text-stone-400 hover:text-white hover:border-sage/30 transition-all duration-300">
          <i class="fas fa-phone text-sm"></i>
        </a>
      </div>

      <div class="text-stone-600 text-[11px]">
        جميع الحقوق محفوظة © 2026
      </div>
    </div>
  </footer>

  <script>
    // Mobile menu
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));
    mobileMenu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => mobileMenu.classList.add('hidden')));

    // Spotlight tracking
    document.querySelectorAll('.spotlight').forEach(card => {
      card.addEventListener('mousemove', e => {
        const r = card.getBoundingClientRect();
        card.style.setProperty('--mouse-x', ((e.clientX - r.left) / r.width * 100) + '%');
        card.style.setProperty('--mouse-y', ((e.clientY - r.top) / r.height * 100) + '%');
      });
    });

    // GSAP
    gsap.registerPlugin(ScrollTrigger);

    gsap.utils.toArray('.reveal').forEach((el, i) => {
      gsap.fromTo(el, 
        { opacity: 0, y: 50 },
        { 
          opacity: 1, y: 0, duration: 1, ease: "power3.out",
          scrollTrigger: { trigger: el, start: "top 88%", toggleActions: "play none none reverse" },
          delay: (i % 3) * 0.08
        }
      );
    });

    // Parallax orbs
    gsap.to(".orb", {
      yPercent: 40, ease: "none",
      scrollTrigger: { trigger: "body", start: "top top", end: "bottom top", scrub: 0.6 }
    });

    // Nav scroll effect
    const nav = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 60) {
        nav.style.background = 'rgba(9,9,8,0.88)';
        nav.style.boxShadow = '0 4px 30px rgba(0,0,0,0.3)';
      } else {
        nav.style.background = 'rgba(9,9,8,0.75)';
        nav.style.boxShadow = 'none';
      }
    });

    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', function(e) {
        e.preventDefault();
        const t = document.querySelector(this.getAttribute('href'));
        if (t) t.scrollIntoView({ behavior: 'smooth', block: 'start' });
      });
    });
  </script>
</body>
</html>
