<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Работа в «Этажах» — Йошкар-Ола. Рынок жилья растёт. Твой доход — тоже.</title>
<meta name="description" content="Карьера в недвижимости в Йошкар-Оле: бесплатное обучение, наставник, первая сделка за месяц, доход без потолка.">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='24' fill='%23EF3224'/%3E%3Cpath d='M53 25 21 41 20 75 57 75Z' fill='%23fff'/%3E%3Cpath d='M53 25 79 41 81 75 57 75Z' fill='%23fff'/%3E%3Cpath d='M55 44h24v7H55z M55.5 55h24v7H55.5z M56 66h24v7H56z' fill='%23EF3224'/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Golos+Text:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
:root{
  --red:#EF3224; --red-hover:#D62619; --red-deep:#A31410; --red-soft:#FF6B5E; --red-bright:#FF4A3C;
  --dark:#170509; --dark-2:#1D070C; --dark-3:#24090F; --footer:#0F0305;
  --paper:#FFF6F4; --paper-2:#FBEDEA; --card:#FFFFFF;
  --ink:#2B1114; --muted:#8A6A66; --muted-dark:#C9A8A2; --line:#F1DAD5;
  --radius:18px; --header-h:66px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth;-webkit-tap-highlight-color:transparent}
html,body{overflow-x:clip}
@supports not (overflow-x:clip){html,body{overflow-x:hidden}}
body{font-family:'Golos Text',system-ui,sans-serif;color:var(--ink);background:var(--paper);line-height:1.55;-webkit-font-smoothing:antialiased;padding-top:var(--header-h)}
a{color:inherit;text-decoration:none} ul{list-style:none}
img,svg{display:block}
[hidden]{display:none!important}
.container{max-width:1180px;margin:0 auto;padding:0 20px;position:relative;z-index:2}
section{scroll-margin-top:84px;position:relative;overflow:hidden}
::selection{background:var(--red);color:#fff}

/* ============ Кнопки ============ */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;font-weight:800;font-size:15px;
  border-radius:14px;padding:13px 24px;border:0;cursor:pointer;transition:.2s;font-family:inherit;white-space:nowrap}
.btn-red{background:var(--red);color:#fff;box-shadow:0 10px 26px rgba(239,50,36,.4)}
.btn-red:hover{background:var(--red-hover);transform:translateY(-2px)}
.btn-pulse{animation:ctapulse 2.8s ease-in-out infinite}
@keyframes ctapulse{0%,100%{box-shadow:0 10px 26px rgba(239,50,36,.4)}50%{box-shadow:0 12px 38px rgba(239,50,36,.7)}}
.btn-ghost{border:1.5px solid rgba(255,255,255,.4);color:#fff}
.btn-ghost:hover{border-color:#fff;background:rgba(255,255,255,.08)}
.btn-lg{padding:16px 32px;font-size:16px}

/* ============ Шапка (fixed) ============ */
.header{position:fixed;top:0;left:0;right:0;z-index:100;background:rgba(18,4,7,.92);backdrop-filter:blur(12px);border-bottom:1px solid rgba(239,50,36,.25)}
.header-in{display:flex;align-items:center;gap:24px;height:var(--header-h)}
.logo{display:flex;align-items:center;gap:12px}
.logo-plaque{height:36px;width:auto;color:var(--red);flex:none}
.logo-city{font-size:11px;font-weight:700;color:var(--muted-dark);letter-spacing:.14em;text-transform:uppercase;white-space:nowrap}
.nav{margin-left:auto;display:flex;align-items:center;gap:22px}
.nav a:not(.btn){font-weight:600;font-size:14px;color:#F3E2DE}
.nav a:not(.btn):hover{color:var(--red-soft)}
.nav .btn{padding:10px 18px;font-size:14px}
.burger{display:none;flex-direction:column;gap:5px;background:none;border:0;cursor:pointer;padding:8px;margin-left:auto}
.burger span{width:22px;height:2px;background:#fff;border-radius:2px}

/* ============ Маскот: полоска В ПОТОКЕ ============ */
.chudik-strip{position:relative;z-index:6;display:flex;align-items:flex-end;gap:4px;margin-top:44px}
.chudik-strip.to-left{justify-content:flex-start}
.chudik-strip.to-right{justify-content:flex-end}
.cd{position:relative;width:96px;flex:none;animation:cdBob 4.5s ease-in-out infinite alternate;
  filter:drop-shadow(0 12px 22px rgba(0,0,0,.25))}
.cd svg{width:100%;height:auto}
.cd-name{position:absolute;top:calc(100% - 2px);left:50%;transform:translateX(-50%);background:var(--red);color:#fff;
  font-size:9.5px;font-weight:900;letter-spacing:.08em;padding:2.5px 9px;border-radius:8px;white-space:nowrap;
  box-shadow:0 4px 12px rgba(239,50,36,.4)}
@keyframes cdBob{from{transform:translateY(-6px)}to{transform:translateY(6px)}}
.chudik-bubble{position:relative;background:#fff;color:var(--ink);font-weight:700;font-size:13.5px;line-height:1.35;
  padding:11px 15px;border-radius:14px;border:2px solid rgba(239,50,36,.35);
  box-shadow:0 12px 28px rgba(239,50,36,.18);max-width:300px;margin-bottom:34px}
.chudik-bubble b{color:var(--red)}
.chudik-bubble::after{content:"";position:absolute;left:-9px;bottom:14px;width:16px;height:16px;background:#fff;
  border-left:2px solid rgba(239,50,36,.35);border-bottom:2px solid rgba(239,50,36,.35);transform:rotate(45deg)}
.chudik-bubble.tail-right::after{left:auto;right:-9px;border:0;border-top:2px solid rgba(239,50,36,.35);
  border-right:2px solid rgba(239,50,36,.35);transform:rotate(45deg)}

/* ============ Чат поддержки ============ */
.chat-fab{position:fixed;right:20px;bottom:20px;z-index:110;width:66px;height:66px;border-radius:50%;
  background:#fff;border:2.5px solid var(--red);cursor:pointer;display:grid;place-items:center;
  box-shadow:0 14px 34px rgba(239,50,36,.4);transition:.25s;padding:5px}
.chat-fab:hover{transform:scale(1.08) rotate(-4deg)}
.chat-fab svg{width:100%;height:auto}
.chat-fab-badge{position:absolute;top:-4px;right:-4px;background:var(--red);color:#fff;font-size:12px;font-weight:900;
  width:22px;height:22px;border-radius:50%;display:grid;place-items:center;border:2px solid #fff;
  animation:badgePop 1.6s ease-in-out infinite}
@keyframes badgePop{0%,100%{transform:scale(1)}50%{transform:scale(1.18)}}
.chat-panel{position:fixed;right:20px;bottom:98px;z-index:120;width:min(370px,calc(100vw - 32px));
  background:#fff;border-radius:22px;box-shadow:0 30px 70px rgba(0,0,0,.45);
  display:flex;flex-direction:column;overflow:hidden;border:1px solid var(--line);
  animation:chatIn .3s cubic-bezier(.34,1.4,.64,1)}
@keyframes chatIn{from{opacity:0;transform:translateY(18px) scale(.96)}to{opacity:1;transform:none}}
.chat-head{display:flex;align-items:center;gap:12px;padding:14px 16px;background:var(--red);color:#fff}
.chat-ava{width:46px;height:46px;border-radius:50%;background:#fff;display:grid;place-items:center;flex:none;padding:3px;box-shadow:0 4px 12px rgba(0,0,0,.2)}
.chat-ava svg{width:100%;height:auto}
.chat-meta{flex:1;line-height:1.25}
.chat-meta b{font-size:15.5px;font-weight:900;display:block}
.chat-meta span{font-size:12px;font-weight:600;color:#FFD9D4;display:flex;align-items:center;gap:6px}
.chat-meta i{width:8px;height:8px;border-radius:50%;background:#7DFF9C;box-shadow:0 0 8px #7DFF9C;display:inline-block;animation:blink 1.6s infinite}
.chat-close{background:rgba(255,255,255,.18);border:0;color:#fff;width:32px;height:32px;border-radius:10px;
  font-size:19px;cursor:pointer;line-height:1;transition:.2s}
.chat-close:hover{background:rgba(255,255,255,.3)}
.chat-body{flex:1;overflow-y:auto;padding:16px 14px 8px;display:flex;flex-direction:column;gap:10px;background:var(--paper);min-height:200px;max-height:320px}
.msg{max-width:82%;padding:10px 13px;border-radius:15px;font-size:13.5px;line-height:1.4;font-weight:500;animation:msgIn .25s ease}
@keyframes msgIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.msg.bot{background:#fff;border:1.5px solid var(--line);border-bottom-left-radius:5px;align-self:flex-start;color:var(--ink)}
.msg.user{background:var(--red);color:#fff;border-bottom-right-radius:5px;align-self:flex-end}
.msg.typing{display:flex;gap:4px;align-items:center;padding:13px 15px}
.msg.typing span{width:7px;height:7px;border-radius:50%;background:#C9A8A2;animation:tp 1s infinite}
.msg.typing span:nth-child(2){animation-delay:.15s}
.msg.typing span:nth-child(3){animation-delay:.3s}
@keyframes tp{0%,100%{transform:translateY(0);opacity:.5}50%{transform:translateY(-4px);opacity:1}}
.chat-chips{display:flex;gap:8px;flex-wrap:wrap;padding:10px 14px;background:var(--paper);border-top:1px solid var(--line)}
.chat-chips button{font-family:inherit;font-size:12px;font-weight:700;color:var(--red-deep);background:#fff;
  border:1.5px solid rgba(239,50,36,.4);border-radius:100px;padding:7px 12px;cursor:pointer;transition:.2s}
.chat-chips button:hover{background:var(--red);color:#fff;border-color:var(--red)}
.chat-input{display:flex;gap:8px;padding:10px 12px;border-top:1px solid var(--line);background:#fff}
.chat-input input{flex:1;border:1.5px solid var(--line);border-radius:12px;padding:11px 13px;font:inherit;font-size:14px;background:#FDF7F6;min-width:0}
.chat-input input:focus{outline:none;border-color:var(--red)}
.chat-input button{width:46px;border:0;border-radius:12px;background:var(--red);color:#fff;font-size:17px;cursor:pointer;transition:.2s;flex:none}
.chat-input button:hover{background:var(--red-hover)}

/* ============ HERO ============ */
.hero{min-height:calc(100svh - var(--header-h));display:flex;flex-direction:column;justify-content:center;padding:88px 0 90px;
  background:radial-gradient(1300px 750px at 50% -12%, #3D0A11 0%, #24070C 48%, #140306 100%)}
.hero-wrap{width:100%}
.hero-fx{position:absolute;inset:-3%;pointer-events:none;will-change:transform}
.fx-glow{position:absolute;left:50%;top:46%;width:min(900px,94vw);aspect-ratio:1;transform:translate(-50%,-50%);
  background:radial-gradient(circle, rgba(239,50,36,.32), transparent 62%);
  animation:glowPulse 6s ease-in-out infinite}
@keyframes glowPulse{0%,100%{opacity:.6;transform:translate(-50%,-50%) scale(1)}
  50%{opacity:1;transform:translate(-50%,-50%) scale(1.12)}}
.fx-floor{position:absolute;left:-30%;right:-30%;bottom:-8%;height:42%;
  background:repeating-linear-gradient(0deg, rgba(255,90,78,.3) 0 2px, transparent 2px 46px),
             repeating-linear-gradient(90deg, rgba(255,90,78,.15) 0 2px, transparent 2px 72px);
  transform:perspective(480px) rotateX(64deg);transform-origin:50% 100%;
  animation:floorMove 2.6s linear infinite;opacity:.5;
  -webkit-mask-image:linear-gradient(to top,#000 22%,transparent 92%);
          mask-image:linear-gradient(to top,#000 22%,transparent 92%)}
@keyframes floorMove{to{background-position:0 46px,0 0}}
.fx-orbit{position:absolute;left:50%;top:46%;aspect-ratio:1;border-radius:50%}
.fx-orbit::after{content:"";position:absolute;top:-6px;left:calc(50% - 6px);width:12px;height:12px;border-radius:50%;
  background:#FF6B5E;box-shadow:0 0 16px #FF6B5E}
.fx-orbit::before{content:"";position:absolute;bottom:-4px;left:calc(50% - 4px);width:8px;height:8px;border-radius:50%;
  background:#FFB3A6;box-shadow:0 0 10px #FFB3A6}
.orbit-1{width:min(500px,74vw);border:1.5px dashed rgba(255,170,160,.5);animation:spinA 16s linear infinite}
.orbit-2{width:min(740px,98vw);border:1.5px dotted rgba(255,170,160,.28);animation:spinB 30s linear infinite}
.orbit-3{width:min(1020px,124vw);border:1px dashed rgba(255,170,160,.15);animation:spinA 46s linear infinite reverse}
.orbit-3::after,.orbit-3::before{display:none}
@keyframes spinA{from{transform:translate(-50%,-50%) rotateX(66deg) rotateZ(0)}
                 to{transform:translate(-50%,-50%) rotateX(66deg) rotateZ(360deg)}}
@keyframes spinB{from{transform:translate(-50%,-50%) rotateX(72deg) rotateZ(0)}
                 to{transform:translate(-50%,-50%) rotateX(72deg) rotateZ(-360deg)}}
.fx-slab{position:absolute;height:16px;border-radius:10px;
  background:linear-gradient(90deg, rgba(255,90,78,.04), rgba(255,90,78,.42), rgba(255,90,78,.04));
  animation:slabFloat 9s ease-in-out infinite alternate}
@keyframes slabFloat{from{transform:translateX(-30px) translateY(-6px)}to{transform:translateX(30px) translateY(6px)}}
.sl-1{width:230px;top:17%;left:7%;opacity:.5}
.sl-2{width:150px;height:12px;top:29%;right:9%;opacity:.4;animation-delay:-3s}
.sl-3{width:270px;height:20px;bottom:33%;left:12%;opacity:.32;animation-delay:-5s}
.sl-4{width:130px;bottom:23%;right:15%;opacity:.45;animation-delay:-7s}
.sl-5{width:190px;top:11%;right:30%;opacity:.3;animation-delay:-2s}
.fx-chip{position:absolute;display:flex;align-items:center;gap:11px;padding:13px 19px;border-radius:16px;
  background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.15);backdrop-filter:blur(6px);
  color:#F3CFC8;font-weight:700;font-size:13.5px;white-space:nowrap;
  box-shadow:0 14px 34px rgba(0,0,0,.35);animation:chipFloat 7s ease-in-out infinite alternate}
.fx-chip i{font-style:normal;color:var(--red-bright);font-weight:900;font-size:19px;
  text-shadow:0 0 14px rgba(255,74,60,.5)}
.chip-1{top:21%;left:6%;animation-delay:-1s}
.chip-2{top:38%;right:5%;animation-delay:-3.5s}
.chip-3{bottom:30%;left:9%;animation-delay:-5.2s}
@keyframes chipFloat{from{transform:translateY(-11px)}to{transform:translateY(11px)}}
.particles{position:absolute;inset:0;overflow:hidden}
.particle{position:absolute;bottom:-14px;border-radius:50%;background:var(--red-bright);
  box-shadow:0 0 10px rgba(255,74,60,.9);opacity:0;animation:rise linear infinite}
@keyframes rise{0%{transform:translateY(0);opacity:0}12%{opacity:.9}80%{opacity:.5}100%{transform:translateY(-720px);opacity:0}}

.hero-content{position:relative;z-index:5;text-align:center;max-width:840px;margin:0 auto;transform:translateY(-3vh)}
.hero-strip{margin-top:36px}
.hero-badges{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-bottom:8px}
.hero-badge{display:inline-flex;align-items:center;gap:9px;border:1px solid rgba(255,255,255,.25);border-radius:100px;
  padding:8px 18px;font-size:13px;font-weight:600;color:#FFD9C2;background:rgba(239,50,36,.12)}
.hero-live{display:inline-flex;align-items:center;gap:9px;border:1px solid rgba(255,255,255,.18);border-radius:100px;
  padding:8px 16px;font-size:13px;font-weight:700;color:#FFD9C2;background:rgba(255,255,255,.07)}
.hero-live i{width:9px;height:9px;border-radius:50%;background:var(--red-bright);box-shadow:0 0 12px var(--red-bright);animation:blink 1.6s ease-in-out infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.25}}
.hero h1{font-size:clamp(30px,4.8vw,56px);line-height:1.1;font-weight:900;color:#fff;margin:20px 0 16px;letter-spacing:-.01em}
.accent{background:linear-gradient(92deg,#FF8A7E,var(--red-bright));-webkit-background-clip:text;background-clip:text;color:transparent}
.hero-sub{font-size:17px;color:#DDBDB7;max-width:620px;margin:0 auto}
.hero-actions{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;margin:28px 0 22px}
.hero-chips{display:flex;gap:20px;justify-content:center;flex-wrap:wrap;color:#C9A8A2;font-size:14px;font-weight:600}
.chk{color:var(--red-soft);font-weight:800;margin-right:6px}

/* ============ Бегущая строка ============ */
.marquee-wrap{position:relative;z-index:6;background:var(--red);transform:rotate(-1.2deg);
  width:104%;margin:-22px -2% -6px;box-shadow:0 14px 40px rgba(239,50,36,.35);overflow:hidden}
.marquee-track{display:flex;width:max-content;animation:marq 26s linear infinite}
.marquee-group{display:flex;align-items:center;gap:30px;padding:14px 15px}
.marquee-group span{color:#fff;font-weight:900;font-size:14.5px;letter-spacing:.12em;text-transform:uppercase;white-space:nowrap}
.marquee-group i{font-style:normal;color:rgba(255,255,255,.65);font-size:11px}
@keyframes marq{to{transform:translateX(-50%)}}

/* ============ Секции ============ */
.section{padding:72px 0}
.section-light{background:var(--paper)}
.section-light-2{background:var(--paper-2)}
.section-dark{background:var(--dark);color:#F7E9E6}
.section-head{margin-bottom:36px;position:relative}
.eyebrow{color:var(--red);font-weight:800;letter-spacing:.14em;text-transform:uppercase;font-size:13px;position:relative;z-index:1}
.section-dark .eyebrow{color:#FF6B5E}
h2{font-size:clamp(26px,3.6vw,40px);font-weight:900;letter-spacing:-.01em;line-height:1.15;margin:12px 0 14px;position:relative;z-index:1}
.section-dark h2{color:#fff}
.section-sub{color:var(--muted);font-size:17px;max-width:660px}
.section-dark .section-sub{color:var(--muted-dark)}
.sub-h{font-size:clamp(19px,2.4vw,24px);font-weight:900;margin:40px 0 22px}

/* Фоны секций */
.bg-dots::before{content:"";position:absolute;inset:0;pointer-events:none;
  background-image:radial-gradient(rgba(239,50,36,.13) 1.2px, transparent 1.6px);background-size:24px 24px}
.bg-lines::before{content:"";position:absolute;inset:0;pointer-events:none;
  background:repeating-linear-gradient(0deg, rgba(255,255,255,.04) 0 1px, transparent 1px 30px),
             repeating-linear-gradient(90deg, rgba(255,255,255,.028) 0 1px, transparent 1px 30px)}
.bg-rings::before{content:"";position:absolute;width:720px;height:720px;border-radius:50%;
  border:60px solid rgba(239,50,36,.05);top:-260px;right:-260px;pointer-events:none}
.bg-rings::after{content:"";position:absolute;width:520px;height:520px;border-radius:50%;
  border:50px solid rgba(239,50,36,.05);bottom:-220px;left:-200px;pointer-events:none}
.bg-rays::before{content:"";position:absolute;inset:-20% -10% 0;pointer-events:none;
  background:repeating-conic-gradient(from 150deg at 88% -18%, rgba(255,90,78,.065) 0 5deg, transparent 5deg 14deg)}
.bg-beams::before{content:"";position:absolute;inset:0;pointer-events:none;
  background:repeating-linear-gradient(90deg, rgba(255,255,255,.045) 0 2px, transparent 2px 120px);
  -webkit-mask-image:linear-gradient(to bottom, transparent, #000 35%, #000 65%, transparent);
          mask-image:linear-gradient(to bottom, transparent, #000 35%, #000 65%, transparent)}
.glow-tr::after{content:"";position:absolute;width:620px;height:620px;border-radius:50%;top:-240px;right:-180px;
  background:radial-gradient(circle, rgba(239,50,36,.22), transparent 68%);pointer-events:none}
.glow-bl::after{content:"";position:absolute;width:560px;height:560px;border-radius:50%;bottom:-220px;left:-180px;
  background:radial-gradient(circle, rgba(239,50,36,.16), transparent 68%);pointer-events:none}

.pat-layer{position:absolute;inset:0;width:100%;height:100%;pointer-events:none;z-index:0}
.pat-red{opacity:.06}
.pat-white{opacity:.05}

.deco-house{position:absolute;color:var(--red);opacity:.06;pointer-events:none}
.deco-house svg{width:100%;height:auto}
.float-house{position:absolute;color:var(--red);opacity:.16;pointer-events:none;animation:lf 8s ease-in-out infinite alternate}
.section-dark .float-house{color:#FF5A4E;opacity:.2}
.float-house svg{width:100%;height:auto}
@keyframes lf{from{transform:translateY(-10px)}to{transform:translateY(10px)}}

/* Лесенка */
.divider{display:block;width:100%;height:110px;margin-top:10px;color:var(--red);opacity:.85}
.on-dark{opacity:1}
.st-main{fill:none;stroke:currentColor;stroke-width:2;stroke-linecap:round;stroke-linejoin:round;
  vector-effect:non-scaling-stroke;stroke-dasharray:5 9;animation:march 1.1s linear infinite}
@keyframes march{to{stroke-dashoffset:-14}}
.st-ghost{fill:none;stroke:currentColor;stroke-width:1.5;stroke-linecap:round;stroke-linejoin:round;
  vector-effect:non-scaling-stroke;stroke-dasharray:2 10;opacity:.32;animation:march 1.8s linear infinite reverse}

/* ============ О компании ============ */
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(185px,1fr));gap:18px}
.stat{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:26px 22px 22px;position:relative;overflow:hidden;transition:.25s}
.stat:hover{transform:translateY(-6px);box-shadow:0 16px 40px rgba(239,50,36,.14);border-color:rgba(239,50,36,.3)}
.stat-house{width:44px;height:auto;color:var(--red);margin-bottom:10px}
.stat-num{font-size:clamp(34px,4vw,46px);font-weight:900;color:var(--red);line-height:1}
.stat-num-sm{font-size:clamp(24px,3vw,32px)}
.stat-label{margin-top:10px;color:var(--muted);font-size:14px;font-weight:600}

.gauges{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:26px}
.gauge{text-align:center;display:flex;flex-direction:column;align-items:center;gap:14px}
.gauge-ring{width:172px;height:172px;border-radius:50%;display:grid;place-items:center;
  background:conic-gradient(from -90deg, var(--red) calc(var(--p,0)*1%), rgba(239,50,36,.13) 0);
  box-shadow:0 14px 34px rgba(239,50,36,.16)}
.gauge-hole{width:132px;height:132px;border-radius:50%;background:var(--paper);display:grid;place-items:center}
.gauge-num{font-size:32px;font-weight:900;color:var(--red);line-height:1}
.gauge p{font-size:14px;color:var(--muted);font-weight:600;max-width:220px}

/* ============ Кому подойдёт ============ */
.aud-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:22px}
.aud{background:#fff;color:var(--ink);border:1px solid rgba(255,255,255,.14);border-radius:22px;padding:28px 26px;position:relative;overflow:hidden;transition:.25s;display:flex;flex-direction:column;gap:16px}
.aud:hover{transform:translateY(-8px);box-shadow:0 22px 50px rgba(239,50,36,.28)}
.aud::before{content:"";position:absolute;top:0;left:0;right:0;height:4px;background:linear-gradient(90deg,var(--red),#FF8A7E)}
.aud-wm{position:absolute;right:-26px;bottom:-26px;width:150px;height:auto;color:var(--red);opacity:.07;pointer-events:none}
.aud-head{display:flex;gap:14px;align-items:center;position:relative;z-index:1}
.aud-icon{width:54px;height:54px;border-radius:15px;background:rgba(239,50,36,.1);display:grid;place-items:center;color:var(--red);flex:none;border:1px solid rgba(239,50,36,.22)}
.aud h3{font-size:19px;font-weight:900;line-height:1.2}
.aud-quote{font-style:italic;color:var(--muted);font-size:14px;margin-top:-6px;position:relative;z-index:1}
.ps{display:flex;flex-direction:column;gap:12px;position:relative;z-index:1}
.ps-row{display:flex;flex-direction:column;gap:6px}
.pain,.sol{display:flex;gap:10px;align-items:flex-start;font-size:14.5px}
.pain{color:#6B5450;font-weight:500}
.sol{font-weight:700}
.mk{flex:0 0 auto;width:20px;height:20px;border-radius:50%;display:grid;place-items:center;font-size:11px;font-weight:800;margin-top:1px}
.pain .mk{background:#F4E4E0;color:#B08A85}
.sol .mk{background:var(--red);color:#fff}

/* ============ Ценности ============ */
.val-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(225px,1fr));gap:18px;margin-bottom:48px}
.val{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:26px 22px;position:relative;overflow:hidden;transition:.25s}
.val::after{content:"";position:absolute;left:0;top:0;bottom:0;width:4px;background:var(--red);transform:scaleY(0);transform-origin:top;transition:.3s}
.val:hover{transform:translateY(-5px);box-shadow:0 14px 34px rgba(239,50,36,.13)}
.val:hover::after{transform:scaleY(1)}
.val-icon{width:48px;height:48px;border-radius:13px;background:rgba(239,50,36,.1);display:grid;place-items:center;color:var(--red);margin-bottom:14px;border:1px solid rgba(239,50,36,.2)}
.val h3{font-size:17px;font-weight:900;margin-bottom:6px}
.val p{font-size:14px;color:var(--muted)}
.life h3{font-size:clamp(20px,2.4vw,26px);font-weight:900;margin-bottom:24px}
.life-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:44px;align-items:start}
.life-item{display:flex;gap:16px;padding:16px 0;border-bottom:1px dashed var(--line)}
.life-item:last-child{border-bottom:0}
.life-emoji{width:50px;height:50px;background:rgba(239,50,36,.1);border:1px solid rgba(239,50,36,.2);border-radius:13px;display:grid;place-items:center;font-size:24px;flex:none}
.life-item h4{font-size:17px;font-weight:900}
.life-item p{color:var(--muted);font-size:14.5px;margin-top:4px}
.life-photos{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.ph{position:relative;border-radius:18px;overflow:hidden;border:1.5px solid rgba(239,50,36,.25);transition:.25s;min-height:130px}
.ph:hover{border-color:var(--red);transform:translateY(-4px);box-shadow:0 14px 34px rgba(239,50,36,.2)}
.ph img{width:100%;height:100%;object-fit:cover;display:block}
.ph figcaption{position:absolute;left:0;right:0;bottom:0;padding:20px 14px 10px;
  background:linear-gradient(to top, rgba(23,5,9,.78), transparent);
  color:#fff;font-size:12.5px;font-weight:700}

/* ============ Быстрый старт ============ */
.steps{display:grid;grid-template-columns:repeat(5,1fr);gap:20px;margin-bottom:40px;align-items:start}
.step{background:#fff;color:var(--ink);border-radius:18px;padding:22px 20px;position:relative;transition:.25s;border:1px solid rgba(255,255,255,.12)}
.step:hover{transform:translateY(-8px);box-shadow:0 20px 46px rgba(239,50,36,.3)}
.step:nth-child(1){margin-top:120px}
.step:nth-child(2){margin-top:90px}
.step:nth-child(3){margin-top:60px}
.step:nth-child(4){margin-top:30px}
.step:nth-child(5){margin-top:0}
.floor-tag{display:inline-flex;align-items:center;gap:8px;background:var(--red);color:#fff;font-size:11px;font-weight:900;
  letter-spacing:.08em;text-transform:uppercase;padding:6px 12px;border-radius:9px;box-shadow:0 6px 16px rgba(239,50,36,.4)}
.step h3{font-size:17px;font-weight:900;margin:14px 0 6px}
.step p{font-size:14px;color:var(--muted)}
.steps-cta{text-align:center}

/* ============ График ============ */
.chart-wrap{background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.1);border-radius:22px;padding:26px 26px 20px;margin-top:40px}
.chart-head{display:flex;align-items:center;justify-content:space-between;gap:14px;flex-wrap:wrap;margin-bottom:16px}
.chart-head h3{font-size:clamp(19px,2.4vw,24px);font-weight:900;color:#fff}
.chart-scroll{overflow-x:auto;scrollbar-width:thin}
.chart{width:100%;min-width:620px;height:auto;display:block}
.chart-grid{stroke:rgba(255,255,255,.09);stroke-dasharray:4 8;stroke-width:1}
.chart-axis{stroke:rgba(255,255,255,.18);stroke-width:1}
.chart-label{font-family:'Golos Text',sans-serif;font-size:12.5px;fill:#B98F89;font-weight:600}
.chart-ceiling{stroke:rgba(255,255,255,.28);stroke-dasharray:6 8;stroke-width:1.3}
.chart-area{opacity:0;transition:opacity 1.1s ease 1.15s}
.chart-wrap.in .chart-area{opacity:1}
.chart-line{fill:none;stroke:var(--red-bright);stroke-width:3.5;stroke-linecap:round;stroke-linejoin:round;
  stroke-dasharray:1;stroke-dashoffset:1;filter:drop-shadow(0 0 7px rgba(239,50,36,.55))}
.chart-wrap.in .chart-line{transition:stroke-dashoffset 1.9s ease .15s;stroke-dashoffset:0}
.dot{fill:var(--red-bright);transform:scale(0);transform-box:fill-box;transform-origin:center;
  transition:transform .45s cubic-bezier(.34,1.56,.64,1) calc(.35s + var(--i)*.12s)}
.dot-big{fill:#fff;stroke:var(--red-bright);stroke-width:2.5}
.chart-wrap.in .dot{transform:scale(1)}
.ceiling-x{opacity:0;transition:opacity .4s ease 1.75s}
.chart-wrap.in .ceiling-x{opacity:1}

/* ============ Отзывы ============ */
.st-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:22px}
.story{background:var(--card);border:1px solid var(--line);border-radius:20px;padding:28px 26px 24px;display:flex;flex-direction:column;gap:14px;transition:.25s;position:relative;overflow:hidden}
.story:hover{transform:translateY(-6px);box-shadow:0 18px 44px rgba(239,50,36,.15)}
.story::before{content:"“";position:absolute;top:-14px;right:14px;font-size:120px;font-weight:900;color:rgba(239,50,36,.09);font-family:Georgia,serif;line-height:1}
.story-head{display:flex;align-items:center;gap:14px}
.avatar{width:54px;height:54px;border-radius:50%;background:linear-gradient(135deg,var(--red),#FF8A7E);color:#fff;display:grid;place-items:center;font-size:24px;flex:none;box-shadow:0 6px 16px rgba(239,50,36,.35)}
.story-name{font-weight:900;font-size:16px;line-height:1.2}
.story-tag{display:inline-block;background:rgba(239,50,36,.09);color:var(--red-deep);font-size:12px;font-weight:800;padding:4px 11px;border-radius:100px;margin-top:4px}
.story-quote{font-size:15px;color:#4A2E2A;flex:1;position:relative;z-index:1}

/* ============ Форма ============ */
.apply{background:var(--dark-3)}
.apply h2{text-shadow:0 0 30px rgba(239,50,36,.45)}
.apply-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:44px;align-items:start}
.form-card{background:#fff;color:var(--ink);border-radius:24px;padding:32px;box-shadow:0 30px 70px rgba(0,0,0,.5);position:relative;z-index:2}
.field{margin-bottom:16px}
.field label{display:block;font-size:13px;font-weight:800;margin-bottom:6px;color:#5A3A36}
.field input,.field select{width:100%;padding:13px 16px;border:1.5px solid var(--line);border-radius:12px;font:inherit;font-size:15px;background:#FDF7F6;transition:.2s}
.field input:focus,.field select:focus{border-color:var(--red);outline:none;box-shadow:0 0 0 3px rgba(239,50,36,.14)}
.consent{display:flex;gap:10px;font-size:12.5px;color:var(--muted);align-items:flex-start;margin:4px 0 18px}
.consent input{accent-color:var(--red);margin-top:2px}
.consent a{color:var(--red);font-weight:700}
.form-card .btn{width:100%}
.form-note{font-size:12.5px;color:var(--muted);margin-top:14px;text-align:center}
.form-success{text-align:center;padding:30px 10px}
.fs-emoji{font-size:52px;margin-bottom:12px}
.form-success h3{font-size:22px;font-weight:900;margin-bottom:8px}
.contact-card{display:flex;flex-direction:column;padding:6px 0;position:relative;z-index:2}
.contact-title{font-weight:900;font-size:18px;margin-bottom:10px;color:#fff}
.contact-item{display:flex;gap:14px;align-items:flex-start;padding:14px 0;border-bottom:1px solid rgba(255,255,255,.1)}
.contact-item:last-child{border-bottom:0}
.ci-icon{width:46px;height:46px;border-radius:13px;background:rgba(239,50,36,.14);border:1px solid rgba(239,50,36,.3);display:grid;place-items:center;color:#FF8A7E;flex:none}
.ci-label{font-size:12px;font-weight:800;color:#B98F89;text-transform:uppercase;letter-spacing:.08em}
.ci-value{font-weight:800;font-size:16px;margin-top:2px;color:#fff}
.ci-value a:hover{color:#FF8A7E}

/* ============ Футер ============ */
.footer{background:var(--footer);color:#B98F89;padding:52px 0 28px;font-size:14px;position:relative;overflow:hidden}
.footer-wm{position:absolute;right:-40px;bottom:-30px;width:280px;height:auto;color:var(--red);opacity:.07;pointer-events:none}
.footer-in{display:flex;flex-wrap:wrap;gap:24px;justify-content:space-between;align-items:center;margin-bottom:26px;position:relative;z-index:1}
.footer nav{display:flex;flex-wrap:wrap;gap:18px}
.footer nav a:hover{color:#FF8A7E}
.footer-legal{border-top:1px solid rgba(255,255,255,.08);padding-top:20px;font-size:12.5px;display:flex;flex-wrap:wrap;gap:8px;justify-content:space-between;position:relative;z-index:1}

/* ============ Появление при скролле ============ */
.reveal{opacity:0;transform:translateY(26px);transition:.65s ease}
.reveal.in{opacity:1;transform:none}
@media(prefers-reduced-motion:reduce){
  .reveal{opacity:1;transform:none;transition:none}
  .fx-glow,.fx-floor,.fx-orbit,.fx-slab,.fx-chip,.float-house,.marquee-track,.st-main,.st-ghost,.btn-pulse,.hero-live i,.cd,.chat-fab-badge,.chat-meta i,.msg.typing span{animation:none!important}
  .particles{display:none}
  .fx-orbit::after,.fx-orbit::before{display:none}
  .fx-floor{opacity:.3}
  .hero-content{transform:none}
  .chart-line{stroke-dashoffset:0!important}
  .chart-area,.ceiling-x{opacity:1!important}
  .dot{transform:scale(1)!important}
}

/* ============ Адаптив ============ */
@media(max-width:1100px){
  .fx-chip{display:none}
  .chudik-bubble{max-width:240px;font-size:12.5px}
}
@media(max-width:960px){
  .hero{padding:84px 0 84px}
  .orbit-3{display:none}
  .life-grid{grid-template-columns:1fr}
  .steps{grid-template-columns:repeat(2,1fr)}
  .step:nth-child(n){margin-top:0}
  .chart-wrap{padding:22px 16px 16px}
}
@media(max-width:900px){
  .burger{display:flex}
  .nav{position:fixed;top:var(--header-h);left:0;right:0;background:#160407;flex-direction:column;align-items:flex-start;
    padding:22px;gap:16px;border-bottom:1px solid rgba(239,50,36,.25);box-shadow:0 20px 50px rgba(0,0,0,.5);
    opacity:0;pointer-events:none;transform:translateY(-10px);transition:.25s;z-index:99}
  body.nav-open .nav{opacity:1;pointer-events:auto;transform:none}
  .nav a:not(.btn){font-size:16px}
  .apply-grid{grid-template-columns:1fr}
  .marquee-wrap{margin-top:-14px}
  .marquee-group span{font-size:12.5px}
  .cd{width:62px}
  .chudik-bubble{font-size:11.5px;padding:8px 11px;max-width:210px;margin-bottom:18px}
  .chudik-bubble::after{display:none}
  .cd-name{font-size:8px;padding:2px 7px}
  .chudik-strip{margin-top:30px;gap:2px}
}
@media(max-width:640px){
  .section{padding:52px 0}
  .hero{padding:78px 0 78px}
  .hero-content{transform:translateY(-2vh)}
  .hero h1{font-size:clamp(28px,8vw,38px)}
  .hero-sub{font-size:15.5px}
  .hero-chips{gap:12px;font-size:13px}
  .sl-3,.sl-5{display:none}
  .fx-floor{opacity:.35}
  .steps{grid-template-columns:1fr}
  .form-card{padding:28px 20px}
  .gauge-ring{width:150px;height:150px}
  .gauge-hole{width:112px;height:112px}
  .gauge-num{font-size:26px}
  .divider{height:64px;margin-top:6px}
  .float-house{opacity:.1}
  .logo-plaque{height:32px}
  .mobile-cta{display:flex;position:fixed;left:16px;right:16px;bottom:16px;z-index:90;justify-content:center;
    box-shadow:0 12px 30px rgba(239,50,36,.5)}
  body{padding-bottom:78px}
  .chat-fab{right:14px;bottom:96px;width:56px;height:56px}
  .chat-panel{left:12px;right:12px;bottom:160px;width:auto}
}
.mobile-cta{display:none}
</style>
</head>
<body>

<!-- ======= SVG-БИБЛИОТЕКА БРЕНДА + МАСКОТ ======= -->
<svg aria-hidden="true" style="position:absolute;width:0;height:0;overflow:hidden">
  <defs>
    <pattern id="hatch" width="9" height="9" patternUnits="userSpaceOnUse" patternTransform="rotate(45)">
      <rect width="2.2" height="9" fill="#EF3224"/>
    </pattern>
    <pattern id="et-pattern" width="220" height="170" patternUnits="userSpaceOnUse">
      <use href="#et-house" x="16" y="10" width="60" height="49" style="color:#EF3224"/>
      <use href="#et-house" x="120" y="86" width="60" height="49" style="color:#EF3224"/>
    </pattern>
    <pattern id="et-pattern-w" width="220" height="170" patternUnits="userSpaceOnUse">
      <use href="#et-house" x="16" y="10" width="60" height="49" style="color:#fff"/>
      <use href="#et-house" x="120" y="86" width="60" height="49" style="color:#fff"/>
    </pattern>
  </defs>

  <!-- Знак дома (v5) -->
  <symbol id="et-house" viewBox="0 0 200 163">
    <g fill="currentColor">
      <path d="M110 0 2 53 0 163 118 163Z"/>
      <path d="M110 0 190 63 190.9 71.6 110.7 14Z"/>
      <path d="M112.1 42 192.6 88.8 193.2 94.9 112.6 52Z"/>
      <path d="M113.9 80 194.9 112.1 195.5 118.2 114.4 90Z"/>
      <path d="M115.8 118 197.2 135.4 197.9 141.5 116.3 128Z"/>
      <path d="M117.7 156 199.6 158.7 200 163 118 163Z"/>
    </g>
  </symbol>

  <!-- Плашка-логотип -->
  <symbol id="et-plaque" viewBox="0 0 640 150">
    <rect width="640" height="150" rx="30" fill="currentColor"/>
    <g style="color:#fff">
      <use href="#et-house" x="38" y="34" width="101" height="82.3"/>
      <text x="163" y="106" font-family="'Golos Text',system-ui,sans-serif" font-size="90" font-weight="900"
        fill="#fff" letter-spacing="2" textLength="437" lengthAdjust="spacingAndGlyphs">ЭТАЖИ</text>
    </g>
  </symbol>

  <!-- Лесенка -->
  <symbol id="divider-art" viewBox="0 0 1200 150">
    <polygon points="8,140 205,140 205,116 405,116 405,92 605,92 605,68 805,68 805,44 1005,44 1005,20 1080,20 1080,140"
      fill="url(#hatch)" opacity=".13"/>
    <path class="st-ghost" transform="translate(0,-12)"
      d="M8 140 H205 V116 H405 V92 H605 V68 H805 V44 H1005 V20 H1080"/>
    <path class="st-main" d="M8 140 H205 V116 H405 V92 H605 V68 H805 V44 H1005 V20 H1080"/>
    <g fill="none" stroke="currentColor" stroke-width="1.6">
      <circle cx="205" cy="116" r="3.6"/><circle cx="405" cy="92" r="3.6"/>
      <circle cx="605" cy="68" r="3.6"/><circle cx="805" cy="44" r="3.6"/>
      <circle cx="1005" cy="20" r="3.6"/>
    </g>
    <circle cx="1064" cy="16" r="14" fill="none" stroke="currentColor" stroke-width="1.5" opacity=".4">
      <animate attributeName="r" values="10;24" dur="2.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values=".45;0" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <use href="#et-house" x="1046" y="1" width="34" height="27.7"/>
    <circle r="4.5" fill="#EF3224">
      <animateMotion dur="7s" repeatCount="indefinite"
        path="M8 140 H205 V116 H405 V92 H605 V68 H805 V44 H1005 V20 H1080"/>
    </circle>
    <circle r="3.2" fill="#FF8A7E" opacity=".7">
      <animateMotion dur="7s" begin="-3.5s" repeatCount="indefinite"
        path="M8 140 H205 V116 H405 V92 H605 V68 H805 V44 H1005 V20 H1080"/>
    </circle>
  </symbol>

  <!-- ============ ДОМОВЁНОК ЧУДИК v7 — по референсу: круглый, компактный,
       пухлая голова-облачко, глазки-блюдца, крошечное тельце в косоворотке.
       Милый, спокойный, добрый. ============ -->
  <symbol id="chudik" viewBox="0 0 240 252">
    <!-- тень -->
    <ellipse cx="120" cy="246" rx="54" ry="7" fill="#000" opacity=".1"/>
    <!-- ноги -->
    <rect x="99"  y="222" width="15" height="14" rx="7.5" fill="#F7C9A6"/>
    <rect x="126" y="222" width="15" height="14" rx="7.5" fill="#F7C9A6"/>
    <!-- ботики -->
    <ellipse cx="104" cy="239" rx="14.5" ry="8.5" fill="#D62619"/>
    <ellipse cx="136" cy="239" rx="14.5" ry="8.5" fill="#D62619"/>
    <ellipse cx="102" cy="237" rx="4.5" ry="2.4" fill="#fff" opacity=".55"/>
    <ellipse cx="134" cy="237" rx="4.5" ry="2.4" fill="#fff" opacity=".55"/>
    <!-- руки (за телом), опущены -->
    <rect x="56"  y="170" width="13" height="38" rx="6.5" fill="#F7C9A6" transform="rotate(8 62 190)"/>
    <rect x="171" y="170" width="13" height="38" rx="6.5" fill="#F7C9A6" transform="rotate(-8 178 190)"/>
    <circle cx="60"  cy="207" r="7" fill="#F7C9A6"/>
    <circle cx="180" cy="207" r="7" fill="#F7C9A6"/>
    <!-- косоворотка -->
    <path d="M120 148 C97 148 79 160 75 182 L71 224 L169 224 L165 182 C161 160 143 148 120 148 Z"
      fill="#FDF9F3" stroke="#EFE2D3" stroke-width="2"/>
    <!-- воротник -->
    <path d="M104 152 L120 170 L136 152" fill="none" stroke="#E8201B" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
    <!-- орнамент на груди -->
    <path d="M120 179 l5 5 -5 5 -5 -5 Z" fill="#E8201B"/>
    <path d="M106 181 l4 4.5 -4 4.5 -4 -4.5 Z" fill="#274B9F"/>
    <path d="M134 181 l4 4.5 -4 4.5 -4 -4.5 Z" fill="#274B9F"/>
    <!-- пояс -->
    <rect x="71" y="198" width="98" height="11" fill="#274B9F"/>
    <path d="M84 198 l5 5.5 -5 5.5 -5 -5.5 Z" fill="#E8201B"/>
    <path d="M102 198 l5 5.5 -5 5.5 -5 -5.5 Z" fill="#E8201B"/>
    <path d="M120 198 l5 5.5 -5 5.5 -5 -5.5 Z" fill="#E8201B"/>
    <path d="M138 198 l5 5.5 -5 5.5 -5 -5.5 Z" fill="#E8201B"/>
    <path d="M156 198 l5 5.5 -5 5.5 -5 -5.5 Z" fill="#E8201B"/>
    <!-- подол с узором -->
    <rect x="71" y="213" width="98" height="11" fill="#FDF9F3" stroke="#EFE2D3" stroke-width="1.5"/>
    <path d="M82 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <path d="M97 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <path d="M112 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <path d="M128 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <path d="M143 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <path d="M158 213 l4.5 5.5 -4.5 5.5 -4.5 -5.5 Z" fill="#E8201B"/>
    <!-- шевелюра: тёмная подложка -->
    <g fill="#D01810">
      <circle cx="62"  cy="104" r="36"/>
      <circle cx="178" cy="104" r="36"/>
      <circle cx="52"  cy="126" r="22"/>
      <circle cx="188" cy="126" r="22"/>
    </g>
    <!-- шевелюра: пухлое облако -->
    <g fill="#F2382B">
      <circle cx="120" cy="90"  r="64"/>
      <circle cx="66"  cy="86"  r="32"/>
      <circle cx="174" cy="86"  r="32"/>
      <circle cx="48"  cy="114" r="24"/>
      <circle cx="192" cy="114" r="24"/>
      <circle cx="88"  cy="44"  r="26"/>
      <circle cx="152" cy="44"  r="26"/>
      <circle cx="120" cy="32"  r="22"/>
      <path d="M106 22 C102 8 112 0 122 2 C112 7 110 14 114 24 Z"/>
      <path d="M132 22 C138 8 148 4 156 8 C146 10 140 16 138 26 Z"/>
    </g>
    <!-- пряди-блики -->
    <g fill="none" stroke="#FF8570" stroke-width="3" stroke-linecap="round">
      <path d="M78 60 Q68 92 72 122"/>
      <path d="M162 60 Q172 92 168 122"/>
      <path d="M108 26 Q105 38 107 48"/>
      <path d="M132 26 Q135 38 133 48"/>
    </g>
    <!-- ушки (маленькие, выглядывают из-под волос) -->
    <path d="M52 130 C40 128 36 116 46 112 C54 116 57 124 56 133 Z" fill="#F7C9A6"/>
    <path d="M188 130 C200 128 204 116 194 112 C186 116 183 124 184 133 Z" fill="#F7C9A6"/>
    <!-- лицо -->
    <ellipse cx="120" cy="126" rx="45" ry="41" fill="#FFDDBE"/>
    <!-- чёлка -->
    <path d="M77 112 C82 90 100 82 120 84 C140 82 158 90 163 112 C151 98 137 93 120 93 C103 93 89 98 77 112 Z" fill="#F2382B"/>
    <!-- глазки-блюдца -->
    <ellipse cx="100" cy="120" rx="13" ry="15" fill="#fff"/>
    <ellipse cx="140" cy="120" rx="13" ry="15" fill="#fff"/>
    <circle cx="100" cy="121" r="10" fill="#1FA04E"/>
    <circle cx="140" cy="121" r="10" fill="#1FA04E"/>
    <circle cx="100" cy="121" r="5" fill="#12351F"/>
    <circle cx="140" cy="121" r="5" fill="#12351F"/>
    <circle cx="96.5" cy="116.5" r="3.4" fill="#fff"/>
    <circle cx="136.5" cy="116.5" r="3.4" fill="#fff"/>
    <circle cx="104" cy="126" r="1.6" fill="#fff" opacity=".85"/>
    <circle cx="144" cy="126" r="1.6" fill="#fff" opacity=".85"/>
    <!-- румяные щёчки -->
    <circle cx="80"  cy="138" r="8.5" fill="#FF9480" opacity=".55"/>
    <circle cx="160" cy="138" r="8.5" fill="#FF9480" opacity=".55"/>
    <!-- веснушки -->
    <circle cx="86"  cy="131" r="1.2" fill="#E8A87F"/>
    <circle cx="90"  cy="135" r="1.2" fill="#E8A87F"/>
    <circle cx="154" cy="131" r="1.2" fill="#E8A87F"/>
    <circle cx="150" cy="135" r="1.2" fill="#E8A87F"/>
    <!-- добрая улыбка -->
    <path d="M111 140 Q120 149 129 140" stroke="#A85B33" stroke-width="4" fill="none" stroke-linecap="round"/>
  </symbol>
</svg>

<!-- ======= ШАПКА (fixed) ======= -->
<header class="header" id="top">
  <div class="container header-in">
    <a class="logo" href="#top" aria-label="Этажи — на главную">
      <svg class="logo-plaque" viewBox="0 0 640 150" aria-hidden="true"><use href="#et-plaque"/></svg>
      <span class="logo-city">Йошкар-Ола</span>
    </a>
    <nav class="nav" id="nav">
      <a href="#about">О компании</a>
      <a href="#audience">Кому подойдёт</a>
      <a href="#life">Жизнь в Этажах</a>
      <a href="#start">Быстрый старт</a>
      <a href="#stories">Отзывы</a>
      <a href="#apply" class="btn btn-red">Хочу в команду</a>
    </nav>
    <button class="burger" id="burger" aria-label="Меню"><span></span><span></span><span></span></button>
  </div>
</header>

<!-- ======= 1. HERO ======= -->
<section class="hero">
  <div class="hero-fx" id="fx" aria-hidden="true">
    <div class="fx-glow"></div>
    <div class="fx-floor"></div>
    <div class="fx-orbit orbit-1"></div>
    <div class="fx-orbit orbit-2"></div>
    <div class="fx-orbit orbit-3"></div>
    <div class="fx-slab sl-1"></div>
    <div class="fx-slab sl-2"></div>
    <div class="fx-slab sl-3"></div>
    <div class="fx-slab sl-4"></div>
    <div class="fx-slab sl-5"></div>
    <div class="particles" id="particles"></div>
  </div>

  <div class="fx-chip chip-1" aria-hidden="true"><i>×2</i><span>доход за первый год</span></div>
  <div class="fx-chip chip-2" aria-hidden="true"><i>30</i><span>дней до первой сделки</span></div>
  <div class="fx-chip chip-3" aria-hidden="true"><i>1500+</i><span>сделок в год</span></div>

  <div class="container hero-wrap">
    <div class="hero-content">
      <div class="hero-badges">
        <span class="hero-badge">Агентство недвижимости «Этажи» · Йошкар-Ола</span>
        <span class="hero-live"><i></i>Открытый набор в команду</span>
      </div>
      <h1>Рынок жилья растёт.<br><span class="accent">Твой доход — тоже.</span></h1>
      <p class="hero-sub">Начни карьеру в недвижимости в команде лидеров города: бесплатное обучение, наставник рядом и первая сделка уже в первый месяц.</p>
      <div class="hero-actions">
        <a href="#apply" class="btn btn-red btn-lg btn-pulse">Хочу в команду</a>
        <a href="#start" class="btn btn-ghost btn-lg">Как всё устроено →</a>
      </div>
      <ul class="hero-chips">
        <li><span class="chk">✓</span>7 лет в городе</li>
        <li><span class="chk">✓</span>Обучение за счёт компании</li>
        <li><span class="chk">✓</span>Наставник с первого дня</li>
      </ul>
    </div>

    <div class="chudik-strip to-right hero-strip" aria-hidden="true">
      <div class="chudik-bubble tail-right">Привет! Я домовёнок <b>Чудик</b> 🏠 Живу на этом сайте — листай вниз, покажу все этажи!</div>
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
    </div>
  </div>
</section>

<!-- ======= Бегущая строка ======= -->
<div class="marquee-wrap" aria-hidden="true">
  <div class="marquee-track">
    <div class="marquee-group">
      <span>Бесплатное обучение</span><i>◆</i><span>Наставник с первого дня</span><i>◆</i>
      <span>Первая сделка за месяц</span><i>◆</i><span>Доход без потолка</span><i>◆</i>
      <span>7 лет в Йошкар-Оле</span><i>◆</i><span>ТОП-20 работодателей страны</span><i>◆</i>
    </div>
    <div class="marquee-group">
      <span>Бесплатное обучение</span><i>◆</i><span>Наставник с первого дня</span><i>◆</i>
      <span>Первая сделка за месяц</span><i>◆</i><span>Доход без потолка</span><i>◆</i>
      <span>7 лет в Йошкар-Оле</span><i>◆</i><span>ТОП-20 работодателей страны</span><i>◆</i>
    </div>
  </div>
</div>

<!-- ======= 2. О КОМПАНИИ ======= -->
<section class="section section-light bg-dots" id="about">
  <div class="float-house" style="width:80px;height:auto;right:6%;top:50px;animation-delay:-2s" aria-hidden="true"><svg viewBox="0 0 200 163"><use href="#et-house"/></svg></div>
  <div class="deco-house" style="width:280px;height:auto;left:-80px;bottom:30px" aria-hidden="true"><svg viewBox="0 0 200 163"><use href="#et-house"/></svg></div>
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">О компании в Йошкар-Оле</span>
      <h2>7 лет мы — часть Йошкар-Олы.<br>И мы здесь надолго</h2>
      <p class="section-sub">Мы — не вакансия на месяц, а федеральный бренд с локальной командой. У нас есть база клиентов, маркетинг и репутация — тебе остаётся самое интересное: работать и расти.</p>
    </div>
    <div class="stats reveal">
      <div class="stat"><svg class="stat-house" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg><div class="stat-num" data-count="7">0</div><div class="stat-label">лет на рынке недвижимости Йошкар-Олы</div></div>
      <div class="stat"><svg class="stat-house" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg><div class="stat-num" data-count="20" data-prefix="ТОП-">0</div><div class="stat-label">работодателей страны</div></div>
      <div class="stat"><svg class="stat-house" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg><div class="stat-num" data-count="1500" data-suffix="+">0</div><div class="stat-label">сделок в год</div></div>
      <div class="stat"><svg class="stat-house" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg><div class="stat-num" data-count="50" data-suffix="+">0</div><div class="stat-label">агентов в команде</div></div>
      <div class="stat"><svg class="stat-house" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg><div class="stat-num stat-num-sm">Лидеры</div><div class="stat-label">по количеству сделок в городе</div></div>
    </div>

    <h3 class="sub-h reveal">Команда в цифрах</h3>
    <div class="gauges reveal">
      <div class="gauge">
        <div class="gauge-ring" data-val="82"><div class="gauge-hole"><span class="gauge-num" data-num="82" data-suffix="%">0%</span></div></div>
        <p>новичков закрывают первую сделку в первый месяц</p>
      </div>
      <div class="gauge">
        <div class="gauge-ring" data-val="100"><div class="gauge-hole"><span class="gauge-num" data-num="2" data-prefix="×" data-suffix="">×0</span></div></div>
        <p>в среднем вырастает доход агента за первый год</p>
      </div>
      <div class="gauge">
        <div class="gauge-ring" data-val="93"><div class="gauge-hole"><span class="gauge-num" data-num="93" data-suffix="%">0%</span></div></div>
        <p>остаются в команде после первого года</p>
      </div>
    </div>

    <div class="chudik-strip to-right" aria-hidden="true">
      <div class="chudik-bubble tail-right">7 лет в Йошкар-Оле — я тут почти местная достопримечательность 😎</div>
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
    </div>
  </div>
</section>

<!-- ======= 3. КОМУ ПОДОЙДЁТ ======= -->
<section class="section section-dark bg-lines glow-tr" id="audience">
  <div class="float-house" style="width:66px;height:auto;left:5%;top:60px;animation-delay:-4s" aria-hidden="true"><svg viewBox="0 0 200 163"><use href="#et-house"/></svg></div>
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Кому подойдёт эта работа</span>
      <h2>Неважно, откуда ты стартуешь.<br>Важно — куда хочешь прийти</h2>
    </div>
    <div class="aud-grid">

      <div class="aud reveal">
        <svg class="aud-wm" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg>
        <div class="aud-head">
          <span class="aud-icon"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 10L12 5 2 10l10 5 10-5z"/><path d="M6 12v5c0 1.66 2.69 3 6 3s6-1.34 6-3v-5"/></svg></span>
          <h3>Студентам и новичкам</h3>
        </div>
        <p class="aud-quote">«Тебе 18–25. Опыта нет — энергии хоть отбавляй»</p>
        <div class="ps">
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Без опыта никуда не берут»</div><div class="sol"><span class="mk">✓</span>Учим с нуля и бесплатно — своя система обучения «Этажей»</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Стажировки не платят»</div><div class="sol"><span class="mk">✓</span>Первые деньги — с первой сделки, уже через месяц</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Не знаю, чего хочу»</div><div class="sol"><span class="mk">✓</span>Попробуешь профессию вживую: наставник покажет всё на практике</div></div>
        </div>
      </div>

      <div class="aud reveal">
        <svg class="aud-wm" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg>
        <div class="aud-head">
          <span class="aud-icon"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M23 4v6h-6"/><path d="M1 20v-6h6"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10"/><path d="M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg></span>
          <h3>Тем, кто меняет профессию</h3>
        </div>
        <p class="aud-quote">«Тебе 28–40. Есть опыт — но не в недвижимости»</p>
        <div class="ps">
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Страшно потерять стабильность»</div><div class="sol"><span class="mk">✓</span>Наставник рядом + готовые лиды: не останешься один на один с рынком</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Поздно начинать заново»</div><div class="sol"><span class="mk">✓</span>Опыт в продажах и общении — твой капитал. У нас его оценят</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«А вдруг не получится?»</div><div class="sol"><span class="mk">✓</span>Большинство наших агентов когда-то тоже меняли сферу. Познакомься с ними на собеседовании</div></div>
        </div>
      </div>

      <div class="aud reveal">
        <svg class="aud-wm" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg>
        <div class="aud-head">
          <span class="aud-icon"><svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M23 6l-9.5 9.5-5-5L1 18"/><path d="M17 6h6v6"/></svg></span>
          <h3>Опытным риелторам</h3>
        </div>
        <p class="aud-quote">«Ты уже в недвижимости. И хочешь большего»</p>
        <div class="ps">
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Доход упёрся в потолок»</div><div class="sol"><span class="mk">✓</span>Потолка нет: прозрачная система комиссий — растёт сделка, растёт чек</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Клиентов ищу сам»</div><div class="sol"><span class="mk">✓</span>Поток лидов от федерального бренда + маркетинговая поддержка</div></div>
          <div class="ps-row"><div class="pain"><span class="mk">✕</span>«Документы и юристы — головная боль»</div><div class="sol"><span class="mk">✓</span>Своя юридическая служба, сопровождение каждой сделки</div></div>
        </div>
      </div>

    </div>

    <div class="chudik-strip to-left" aria-hidden="true">
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
      <div class="chudik-bubble">Где бы ты ни стартовал — у меня найдётся ключик 🔑 от нужного этажа!</div>
    </div>
  </div>
</section>

<!-- ======= 4. ЦЕННОСТИ И ЖИЗНЬ ======= -->
<section class="section section-light-2 bg-rings" id="life">
  <div class="float-house" style="width:62px;height:auto;right:7%;top:60px;animation-delay:-1s" aria-hidden="true"><svg viewBox="0 0 200 163"><use href="#et-house"/></svg></div>
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Наши ценности</span>
      <h2>Жизнь в Этажах — это не только сделки</h2>
      <p class="section-sub">Мы работаем на результат — и умеем радоваться ему вместе.</p>
    </div>

    <div class="val-grid reveal">
      <div class="val"><span class="val-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg></span><h3>Драйв</h3><p>Скорость, амбиции, результат. Скучно у нас не бывает — проверено.</p></div>
      <div class="val"><span class="val-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></span><h3>Партнёрство</h3><p>Наставник — не конкурент, а напарник. Делимся сделками, опытом и пиццей.</p></div>
      <div class="val"><span class="val-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="M9 12l2 2 4-4"/></svg></span><h3>Честность</h3><p>Говорим как есть — клиентам, друг другу и тебе на собеседовании.</p></div>
      <div class="val"><span class="val-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg></span><h3>Забота</h3><p>Поможем и в работе, и в жизни: от разбора сложной сделки до поддержки в трудный день.</p></div>
    </div>

    <div class="life">
      <h3 class="reveal">Как это выглядит в жизни</h3>
      <div class="life-grid">
        <div class="reveal">
          <div class="life-item"><span class="life-emoji">🧠</span><div><h4>Квизы</h4><p>Раз в месяц собираемся на квиз: команды, призы, а победители вопят так, что слышит весь офис.</p></div></div>
          <div class="life-item"><span class="life-emoji">🏐</span><div><h4>Спорт</h4><p>Турниры по волейболу и футболу, совместные забеги. Соперники — коллеги, азарт — настоящий.</p></div></div>
          <div class="life-item"><span class="life-emoji">🎤</span><div><h4>«Э:Форум»</h4><p>Крупное корпоративное событие для риелторов и сотрудников сети: деловая программа, награждение лучших, мотивационные выступления и концерт.</p></div></div>
        </div>
        <div class="life-photos reveal">
          <figure class="ph"><img src="https://avatars.mds.yandex.net/i?id=583a345a427d9f9362bbc6b6cefaf54b7b519ace-9099160-images-thumbs&n=13" alt="Команда на квизе" loading="lazy"><figcaption>Квиз</figcaption></figure>
          <figure class="ph"><img src="https://directevent.ru/upload/iblock/939/9399c6acd449dde0ff37819788e1044f.jpg" alt="Спорттурнир команды" loading="lazy"><figcaption>Спорттурнир</figcaption></figure>
          <figure class="ph"><img src="https://economy.kbr.ru/upload/iblock/2fd/a7d4y5lapeuskk9q5xdhyvabxy1hi4hh/photo_2026_03_19_12_39_43.jpg" alt="Э:Форум" loading="lazy"><figcaption>«Э:Форум»</figcaption></figure>
          <figure class="ph"><img src="https://static.tildacdn.com/tild3761-6462-4162-b163-666234623562/Rectangle_34.jpg" alt="Команда на празднике" loading="lazy"><figcaption>Команда на празднике</figcaption></figure>
        </div>
      </div>
    </div>

    <div class="chudik-strip to-right" aria-hidden="true">
      <div class="chudik-bubble tail-right">Про квизы и «Э:Форум» знаю всё — я же сам участник! 🎉</div>
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
    </div>
  </div>
</section>

<!-- ======= 5. БЫСТРЫЙ СТАРТ + ГРАФИК ======= -->
<section class="section section-dark bg-rays glow-bl" id="start">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Твой быстрый старт</span>
      <h2>Поднимись на пятый этаж карьеры — за 30 дней</h2>
      <p class="section-sub">Каждый шаг — новый этаж. Ты не один: на каждом уровне рядом наставник.</p>
    </div>

    <div class="steps reveal">
      <div class="step">
        <span class="floor-tag">Этаж 1 · День 1–2</span>
        <h3>Знакомство</h3>
        <p>Звонок с HR, собеседование и экскурсия по офису. Решение — за тобой.</p>
      </div>
      <div class="step">
        <span class="floor-tag">Этаж 2 · Неделя 1–2</span>
        <h3>Обучение</h3>
        <p>Бесплатный курс «Этажей»: техника продаж, законодательство, объекты, CRM.</p>
      </div>
      <div class="step">
        <span class="floor-tag">Этаж 3 · Неделя 2–4</span>
        <h3>Наставник</h3>
        <p>Совместные звонки и показы, разбор ошибок, первые клиенты.</p>
      </div>
      <div class="step">
        <span class="floor-tag">Этаж 4 · Месяц 1</span>
        <h3>Первая сделка</h3>
        <p>Твой первый чек — и первая строчка в портфолио.</p>
      </div>
      <div class="step">
        <span class="floor-tag">Этаж 5 · Дальше</span>
        <h3>Рост</h3>
        <p>Агент → старший агент → руководитель группы. Или горизонталь: коммерческая, загородная, элитная недвижимость.</p>
      </div>
    </div>

    <div class="steps-cta reveal">
      <a href="#apply" class="btn btn-red btn-lg">Начать подъём →</a>
    </div>

    <div class="chudik-strip to-left" aria-hidden="true">
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
      <div class="chudik-bubble">Поднимайся — я уже на пятом этаже, чай поставил ☕</div>
    </div>

    <div class="chart-wrap reveal">
      <div class="chart-head">
        <h3>Как растёт доход агента</h3>
      </div>
      <div class="chart-scroll">
        <svg class="chart" viewBox="0 0 760 340" role="img" aria-label="График роста дохода агента за 12 месяцев">
          <defs>
            <linearGradient id="gArea" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0" stop-color="#EF3224" stop-opacity=".42"/>
              <stop offset="1" stop-color="#EF3224" stop-opacity="0"/>
            </linearGradient>
          </defs>
          <line class="chart-grid" x1="60" y1="231" x2="720" y2="231"/>
          <line class="chart-grid" x1="60" y1="172" x2="720" y2="172"/>
          <line class="chart-grid" x1="60" y1="113" x2="720" y2="113"/>
          <line class="chart-ceiling" x1="60" y1="54" x2="720" y2="54"/>
          <text class="chart-label" x="66" y="44">условный «потолок» дохода</text>
          <line class="chart-axis" x1="60" y1="290" x2="720" y2="290"/>
          <text class="chart-label" x="52" y="294" text-anchor="end">0</text>
          <text class="chart-label" x="52" y="235" text-anchor="end">50</text>
          <text class="chart-label" x="52" y="176" text-anchor="end">100</text>
          <text class="chart-label" x="52" y="117" text-anchor="end">150</text>
          <text class="chart-label" x="52" y="58" text-anchor="end">200</text>
          <text class="chart-label" x="60" y="16">тыс. ₽ / мес</text>
          <path class="chart-area" fill="url(#gArea)"
            d="M60 243 C100 235 140 226 180 216 C220 205 260 190 300 178 C340 166 380 152 420 136 C460 120 500 104 540 89 C580 74 620 62 660 55 C680 51 700 45 720 40 L720 290 L60 290 Z"/>
          <path class="chart-line" pathLength="1"
            d="M60 243 C100 235 140 226 180 216 C220 205 260 190 300 178 C340 166 380 152 420 136 C460 120 500 104 540 89 C580 74 620 62 660 55 C680 51 700 45 720 40"/>
          <circle class="dot" style="--i:0"  cx="60"  cy="243" r="4"/>
          <circle class="dot" style="--i:1"  cx="120" cy="229" r="4"/>
          <circle class="dot" style="--i:2"  cx="180" cy="216" r="4"/>
          <circle class="dot" style="--i:3"  cx="240" cy="198" r="4"/>
          <circle class="dot" style="--i:4"  cx="300" cy="178" r="4"/>
          <circle class="dot dot-big" style="--i:5" cx="360" cy="158" r="5.5"/>
          <circle class="dot" style="--i:6"  cx="420" cy="136" r="4"/>
          <circle class="dot" style="--i:7"  cx="480" cy="113" r="4"/>
          <circle class="dot" style="--i:8"  cx="540" cy="89"  r="4"/>
          <circle class="dot" style="--i:9"  cx="600" cy="70"  r="4"/>
          <circle class="dot" style="--i:10" cx="660" cy="55"  r="4"/>
          <circle class="dot dot-big" style="--i:11" cx="720" cy="40" r="5.5"/>
          <g class="ceiling-x">
            <circle cx="652" cy="54" r="10" fill="#170509" stroke="#fff" stroke-width="1.5"/>
            <path d="M647 49l10 10M657 49l-10 10" stroke="#FF6B5E" stroke-width="2.5" stroke-linecap="round"/>
          </g>
          <text x="66" y="268" class="chart-label">40</text>
          <text x="716" y="26" text-anchor="end" style="font-family:'Golos Text',sans-serif;font-size:14px;font-weight:900;fill:#fff">212 тыс ₽</text>
          <text class="chart-label" x="60"  y="318" text-anchor="middle">М1</text>
          <text class="chart-label" x="120" y="318" text-anchor="middle">М2</text>
          <text class="chart-label" x="180" y="318" text-anchor="middle">М3</text>
          <text class="chart-label" x="240" y="318" text-anchor="middle">М4</text>
          <text class="chart-label" x="300" y="318" text-anchor="middle">М5</text>
          <text class="chart-label" x="360" y="318" text-anchor="middle">М6</text>
          <text class="chart-label" x="420" y="318" text-anchor="middle">М7</text>
          <text class="chart-label" x="480" y="318" text-anchor="middle">М8</text>
          <text class="chart-label" x="540" y="318" text-anchor="middle">М9</text>
          <text class="chart-label" x="600" y="318" text-anchor="middle">М10</text>
          <text class="chart-label" x="660" y="318" text-anchor="middle">М11</text>
          <text class="chart-label" x="720" y="318" text-anchor="middle">М12</text>
        </svg>
      </div>
    </div>
  </div>
  <svg class="divider on-dark" viewBox="0 0 1200 150" aria-hidden="true"><use href="#divider-art"/></svg>
</section>

<!-- ======= 6. ОТЗЫВЫ ======= -->
<section class="section section-light" id="stories">
  <svg class="pat-layer pat-red" aria-hidden="true"><rect width="100%" height="100%" fill="url(#et-pattern)"/></svg>
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Отзывы сотрудников</span>
      <h2>Так говорят те, кто уже с нами</h2>
    </div>
    <div class="st-grid">
      <div class="story reveal">
        <div class="story-head"><div class="avatar">⭐</div><div><div class="story-name">Специалист по продажам</div><span class="story-tag">3–5 лет в «Этажах» · Йошкар-Ола</span></div></div>
        <p class="story-quote">«Свободный график, норм руководители, понятная система оплаты труда. В начале — учёба: к работе не допускают, пока не сдашь экзамен, но готовиться к нему тоже норм — все материалы есть, и спросить есть у кого. Хорошая база и клиентов, и объектов: всегда были клиенты от компании, с которыми можно было работать. Репутация отличная, клиенты обращаются сами. Стал работать — даже удивился, сколько знакомых вокруг уже сотрудничали с ними».</p>
      </div>
      <div class="story reveal">
        <div class="story-head"><div class="avatar">🚀</div><div><div class="story-name">Менеджер по продажам</div><span class="story-tag">1–2 года в «Этажах» · Йошкар-Ола</span></div></div>
        <p class="story-quote">«Возможность развития в сфере недвижимости, неограниченный доход. График строится исходя из задач — всё чётко и прозрачно. В компании «Этажи» обучение поэтапное и с развивающими реальными примерами».</p>
      </div>
      <div class="story reveal">
        <div class="story-head"><div class="avatar">🎯</div><div><div class="story-name">Менеджер по продажам</div><span class="story-tag">3–5 лет в «Этажах» · Йошкар-Ола</span></div></div>
        <p class="story-quote">«Отличное место для роста и развития. Развивающая компания, молодой, дружный коллектив. Можно достичь результата без опыта работы в продажах. Качественное обучение в первый месяц работы, далее — опытный наставник. Доход зависит от твоего желания, возможностей и времени. График работы выстраиваешь самостоятельно».</p>
      </div>
    </div>

    <div class="chudik-strip to-right" aria-hidden="true">
      <div class="chudik-bubble tail-right">Не веришь мне — поверь коллегам. Отзывы настоящие! 🤝</div>
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
    </div>
  </div>
</section>

<!-- ======= 7. ФОРМА + КОНТАКТЫ ======= -->
<section class="section section-dark apply bg-beams" id="apply">
  <svg class="pat-layer pat-white" aria-hidden="true"><rect width="100%" height="100%" fill="url(#et-pattern-w)"/></svg>
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Отклик</span>
      <h2>Сделай первый шаг — остальное покажем</h2>
    </div>
    <div class="apply-grid">

      <div class="form-card reveal">
        <form id="lead-form">
          <div id="form-body">
            <div class="field"><label for="f-name">Имя</label><input id="f-name" type="text" placeholder="Как к тебе обращаться" required></div>
            <div class="field"><label for="f-phone">Телефон</label><input id="f-phone" type="tel" inputmode="tel" placeholder="+7 (___) ___-__-__" required></div>
            <div class="field"><label for="f-exp">Твой опыт</label>
              <select id="f-exp" required>
                <option value="" disabled selected>Выбери вариант…</option>
                <option>Без опыта</option>
                <option>Есть опыт в продажах</option>
                <option>Работаю в недвижимости</option>
              </select>
            </div>
            <label class="consent"><input type="checkbox" required><span>Соглашаюсь с <a href="#">политикой конфиденциальности</a> и обработкой персональных данных (152-ФЗ)</span></label>
            <button type="submit" class="btn btn-red btn-lg">Хочу в команду</button>
            <p class="form-note">Перезвоним в течение рабочего дня. Честно расскажем, сколько реально зарабатывают агенты и как всё устроено. Без навязывания — решать тебе.</p>
          </div>
          <div class="form-success" id="form-success" hidden>
            <div class="fs-emoji">🎉</div>
            <h3>Заявка отправлена!</h3>
            <p>HR «Этажей» перезвонит в течение рабочего дня.</p>
          </div>
        </form>
      </div>

      <div class="contact-card reveal">
        <p class="contact-title">Или напиши нам сам:</p>
        <div class="contact-item">
          <span class="ci-icon"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg></span>
          <div><div class="ci-label">Телефон HR-отдела</div><div class="ci-value"><a href="tel:+78000000000">+7 (800) 000-00-00</a></div></div>
        </div>
        <div class="contact-item">
          <span class="ci-icon"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 2L11 13"/><path d="M22 2l-7 20-4-9-9-4 22-7z"/></svg></span>
          <div><div class="ci-label">Telegram</div><div class="ci-value"><a href="#">@etagi_hr_yoshkarola</a></div></div>
        </div>
        <div class="contact-item">
          <span class="ci-icon"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="M22 7l-10 5L2 7"/></svg></span>
          <div><div class="ci-label">Почта</div><div class="ci-value"><a href="mailto:hr@etagi-yoshkarola.ru">hr@etagi-yoshkarola.ru</a></div></div>
        </div>
        <div class="contact-item">
          <span class="ci-icon"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13S3 17 3 10a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg></span>
          <div><div class="ci-label">Офис в Йошкар-Оле</div><div class="ci-value">ул. Йывана Кырли, 21Б, этаж 2 · пн–пт 8:00–20:00</div></div>
        </div>
      </div>

    </div>

    <div class="chudik-strip to-right" aria-hidden="true">
      <div class="chudik-bubble tail-right">Заполни анкету — я лично отнесу её в HR! 📬</div>
      <div class="cd"><svg viewBox="0 0 240 252"><use href="#chudik"/></svg><span class="cd-name">Чудик</span></div>
    </div>
  </div>
</section>

<!-- ======= ФУТЕР ======= -->
<footer class="footer">
  <svg class="footer-wm" viewBox="0 0 200 163" aria-hidden="true"><use href="#et-house"/></svg>
  <div class="container">
    <div class="footer-in">
      <a class="logo" href="#top" aria-label="Этажи — наверх">
        <svg class="logo-plaque" viewBox="0 0 640 150" aria-hidden="true"><use href="#et-plaque"/></svg>
        <span class="logo-city">Йошкар-Ола</span>
      </a>
      <nav>
        <a href="#about">О компании</a>
        <a href="#audience">Кому подойдёт</a>
        <a href="#life">Жизнь в Этажах</a>
        <a href="#start">Быстрый старт</a>
        <a href="#">Вакансии на hh.ru</a>
        <a href="#">ВКонтакте</a>
      </nav>
    </div>
    <div class="footer-legal">
      <span>© 2025 «Этажи» · Йошкар-Ола. «Этажи» — зарегистрированный товарный знак (свидетельство Роспатента № 1013254).</span>
      <a href="#">Политика конфиденциальности</a>
    </div>
  </div>
</footer>

<a href="#apply" class="btn btn-red mobile-cta">Хочу в команду</a>

<!-- ======= ЧАТ ПОДДЕРЖКИ С ЧУДИКОМ ======= -->
<button class="chat-fab" id="chatFab" aria-label="Открыть чат с Чудиком">
  <svg viewBox="0 0 240 252" aria-hidden="true"><use href="#chudik"/></svg>
  <span class="chat-fab-badge" id="chatBadge">1</span>
</button>

<div class="chat-panel" id="chatPanel" hidden role="dialog" aria-label="Чат с помощником Чудиком">
  <div class="chat-head">
    <div class="chat-ava"><svg viewBox="0 0 240 252" aria-hidden="true"><use href="#chudik"/></svg></div>
    <div class="chat-meta">
      <b>Чудик · помощник</b>
      <span><i></i>онлайн · отвечаю сразу</span>
    </div>
    <button class="chat-close" id="chatClose" aria-label="Закрыть чат">×</button>
  </div>
  <div class="chat-body" id="chatBody">
    <div class="msg bot">Привет! Я домовёнок Чудик 🏠 Помогу разобраться: про обучение, доход, график и офис. Спрашивай!</div>
  </div>
  <div class="chat-chips" id="chatChips">
    <button type="button">Нужен ли опыт?</button>
    <button type="button">Сколько зарабатывают?</button>
    <button type="button">Как устроиться?</button>
    <button type="button">Где офис?</button>
  </div>
  <form class="chat-input" id="chatForm">
    <input id="chatText" type="text" placeholder="Спроси меня…" autocomplete="off" maxlength="300">
    <button type="submit" aria-label="Отправить">➤</button>
  </form>
</div>

<script>
// Появление блоков
const io = new IntersectionObserver(es => {
  es.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in'); io.unobserve(e.target); } });
}, { threshold: .12 });
document.querySelectorAll('.reveal').forEach(el => io.observe(el));

// Счётчики
document.querySelectorAll('[data-count]').forEach(el => {
  const target = +el.dataset.count, prefix = el.dataset.prefix || '', suffix = el.dataset.suffix || '';
  const obs = new IntersectionObserver(([e]) => {
    if (!e.isIntersecting) return; obs.disconnect();
    const t0 = performance.now(), dur = 1400;
    const tick = t => {
      const p = Math.min((t - t0) / dur, 1), ease = 1 - Math.pow(1 - p, 3);
      el.textContent = prefix + Math.round(target * ease).toLocaleString('ru-RU') + suffix;
      if (p < 1) requestAnimationFrame(tick);
    };
    requestAnimationFrame(tick);
  }, { threshold: .5 });
  obs.observe(el);
});

// Кольцевые диаграммы
const reduced = matchMedia('(prefers-reduced-motion: reduce)').matches;
document.querySelectorAll('.gauge-ring').forEach(ring => {
  const val = +ring.dataset.val;
  const num = ring.querySelector('.gauge-num');
  const target = +num.dataset.num;
  const pre = num.dataset.prefix || '';
  const suf = num.dataset.suffix !== undefined ? num.dataset.suffix : '%';
  const obs = new IntersectionObserver(([e]) => {
    if (!e.isIntersecting) return; obs.disconnect();
    if (reduced) { ring.style.setProperty('--p', val); num.textContent = pre + target + suf; return; }
    const t0 = performance.now(), dur = 1300;
    const step = now => {
      const p = Math.min((now - t0) / dur, 1), ease = 1 - Math.pow(1 - p, 3);
      ring.style.setProperty('--p', (val * ease).toFixed(1));
      num.textContent = pre + Math.round(target * ease) + suf;
      if (p < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  }, { threshold: .4 });
  obs.observe(ring);
});

// Частицы в hero
(() => {
  const wrap = document.getElementById('particles');
  if (!wrap || reduced) return;
  for (let i = 0; i < 22; i++) {
    const p = document.createElement('i');
    p.className = 'particle';
    const size = 3 + Math.random() * 6;
    p.style.width = p.style.height = size + 'px';
    p.style.left = Math.random() * 100 + '%';
    p.style.animationDuration = (5 + Math.random() * 8) + 's';
    p.style.animationDelay = (-Math.random() * 12) + 's';
    wrap.appendChild(p);
  }
})();

// Параллакс fx-слоя
(() => {
  if (reduced) return;
  const fx = document.getElementById('fx');
  if (!fx) return;
  let tx = 0, ty = 0, cx = 0, cy = 0;
  addEventListener('pointermove', e => {
    if (e.pointerType === 'touch') return;
    tx = (e.clientX / innerWidth - .5) * 26;
    ty = (e.clientY / innerHeight - .5) * 16;
  });
  (function raf() {
    cx += (tx - cx) * .05; cy += (ty - cy) * .05;
    fx.style.transform = `translate(${cx}px, ${cy}px)`;
    requestAnimationFrame(raf);
  })();
})();

// Пауза SMIL при reduced motion
if (reduced) document.querySelectorAll('svg.divider').forEach(s => { try { s.pauseAnimations(); } catch(_) {} });

// Мобильное меню
const burger = document.getElementById('burger'), nav = document.getElementById('nav');
burger.addEventListener('click', () => document.body.classList.toggle('nav-open'));
nav.querySelectorAll('a').forEach(a => a.addEventListener('click', () => document.body.classList.remove('nav-open')));

// Форма (прототип)
document.getElementById('lead-form').addEventListener('submit', e => {
  e.preventDefault();
  document.getElementById('form-body').style.display = 'none';
  document.getElementById('form-success').hidden = false;
});

/* ============ ЧАТ С ЧУДИКОМ (прототип с заготовленными ответами) ============ */
(() => {
  const fab = document.getElementById('chatFab'),
        badge = document.getElementById('chatBadge'),
        panel = document.getElementById('chatPanel'),
        closeBtn = document.getElementById('chatClose'),
        body = document.getElementById('chatBody'),
        form = document.getElementById('chatForm'),
        input = document.getElementById('chatText'),
        chips = document.getElementById('chatChips');

  function addMsg(text, who) {
    const m = document.createElement('div');
    m.className = 'msg ' + who;
    m.textContent = text;
    body.appendChild(m);
    body.scrollTop = body.scrollHeight;
    return m;
  }

  function showTyping() {
    const t = document.createElement('div');
    t.className = 'msg bot typing';
    t.innerHTML = '<span></span><span></span><span></span>';
    body.appendChild(t);
    body.scrollTop = body.scrollHeight;
    return t;
  }

  const rules = [
    { keys: ['привет','здравств','хай','добр'], reply: 'Привет-привет! 👋 Рад знакомству. Могу рассказать про обучение, доход, график, наставников и офис — или сразу проводу к анкете!' },
    { keys: ['кто ты','ты кто','чудик'], reply: 'Я домовёнок Чудик — живу в «Этажах» 🏠 Слежу за порядком на этажах и помогаю новичкам!' },
    { keys: ['опыт','новичок','студент','без опыта'], reply: 'Опыт не нужен! 🎓 Учим с нуля и бесплатно: поэтапное обучение с реальными примерами, к работе допускаем после экзамена — но готовиться легко, все материалы дают. Первая сделка — уже в первый месяц!' },
    { keys: ['заработ','доход','платят','деньг','зарплат','сколько получ'], reply: 'Доход без потолка 💰 Прозрачная система комиссий: больше сделок — больше чек. Наши коллеги в отзывах говорят, что «доход зависит от твоего желания, возможностей и времени». Точные цифры честно назовёт HR на собеседовании!' },
    { keys: ['график','время','смен','удаленн'], reply: 'График гибкий — выстраиваешь сам под свои задачи ⏰ Всё чётко и прозрачно, как пишут наши сотрудники в отзывах!' },
    { keys: ['офис','адрес','где вы','где находит','как найти'], reply: 'ул. Йывана Кырли, 21Б, этаж 2 · пн–пт 8:00–20:00 🏠 Заходи — я на кухне чайник грею ☕' },
    { keys: ['обуч','экзамен','учеб','курс','учат'], reply: 'Обучение бесплатное и поэтапное 📚 С развивающими реальными примерами. К работе допускают после экзамена — но спросить есть у кого, наставники всегда рядом!' },
    { keys: ['настав'], reply: 'У каждого новичка — опытный наставник 🤝 Совместные звонки, показы, разбор ошибок. Проведут за руку через первые сделки — проверено!' },
    { keys: ['форум','квиз','спорт','мероприят','праздн','команд'], reply: 'О, это моё любимое! 🎉 Квизы каждый месяц, спорттурниры, а «Э:Форум» — событие года: деловая программа, награждение лучших и концерт!' },
    { keys: ['спасибо','благодар','спс'], reply: 'Всегда рад помочь! Домовые — они такие 😊 Если что — я тут всегда.' },
    { keys: ['анкет','отклик','заявк','форм','устро','ваканс','работа','хочу'], reply: 'Ура! 🎉 Сейчас отнесу тебя к анкете — заполни её, а я лично доставлю её в HR!', scroll: true }
  ];
  const fallback = 'Хороший вопрос! 🤔 Точнее всего расскажет HR — оставь заявку в форме внизу страницы. А пока могу подсказать про опыт, доход, обучение, график, мероприятия или адрес офиса 😉';

  function answerFor(text) {
    const s = ' ' + text.toLowerCase() + ' ';
    for (const r of rules) if (r.keys.some(k => s.includes(k))) return r;
    return { reply: fallback };
  }

  function botReply(userText) {
    const typing = showTyping();
    setTimeout(() => {
      typing.remove();
      const r = answerFor(userText);
      addMsg(r.reply, 'bot');
      if (r.scroll) {
        setTimeout(() => {
          closeChat();
          document.getElementById('apply').scrollIntoView({ behavior: 'smooth' });
        }, 900);
      }
    }, 700 + Math.random() * 500);
  }

  function openChat() {
    panel.hidden = false;
    fab.hidden = true;
    badge.hidden = true;
    setTimeout(() => input.focus(), 150);
  }
  function closeChat() {
    panel.hidden = true;
    fab.hidden = false;
  }

  fab.addEventListener('click', openChat);
  closeBtn.addEventListener('click', closeChat);
  addEventListener('keydown', e => { if (e.key === 'Escape' && !panel.hidden) closeChat(); });

  form.addEventListener('submit', e => {
    e.preventDefault();
    const v = input.value.trim();
    if (!v) return;
    addMsg(v, 'user');
    input.value = '';
    botReply(v);
  });

  chips.querySelectorAll('button').forEach(b => b.addEventListener('click', () => {
    input.value = b.textContent;
    form.dispatchEvent(new Event('submit'));
  }));
})();
</script>
</body>
</html>
