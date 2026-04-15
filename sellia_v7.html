<!DOCTYPE html>

<html lang="fr" data-theme="light">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sellia — Dashboard</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;600;700;800&family=DM+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
[data-theme="light"]{--bg:#f4f4f8;--surface:#fff;--s2:#f0f0f5;--s3:#e8e8ed;--border:rgba(0,0,0,.07);--border2:rgba(0,0,0,.04);--text:#0a0a12;--text2:#6b7280;--text3:#b0b0c0;--sh:0 2px 12px rgba(0,0,0,.06);--sh2:0 8px 32px rgba(0,0,0,.1);--tb:rgba(244,244,248,.9)}
[data-theme="dark"]{--bg:#0c0c14;--surface:#14141e;--s2:#1a1a26;--s3:#20202e;--border:rgba(255,255,255,.07);--border2:rgba(255,255,255,.04);--text:#f0f0f8;--text2:#8080a0;--text3:#404060;--sh:0 2px 12px rgba(0,0,0,.3);--sh2:0 8px 32px rgba(0,0,0,.5);--tb:rgba(12,12,20,.9)}
:root{--blue:#2563eb;--blue-bg:rgba(37,99,235,.08);--blue-bd:rgba(37,99,235,.2);--green:#10b981;--green-bg:rgba(16,185,129,.08);--green-bd:rgba(16,185,129,.2);--amber:#f59e0b;--amber-bg:rgba(245,158,11,.08);--amber-bd:rgba(245,158,11,.2);--red:#ef4444;--red-bg:rgba(239,68,68,.08);--red-bd:rgba(239,68,68,.2);--purple:#7c3aed;--purple-bg:rgba(124,58,237,.08);--purple-bd:rgba(124,58,237,.2);--font:'Bricolage Grotesque',sans-serif;--body:'DM Sans',sans-serif;--r:16px;--rsm:10px;--rxs:7px}
html{-webkit-font-smoothing:antialiased}
body{background:var(--bg);color:var(--text);font-family:var(--body);min-height:100vh;transition:background .3s,color .3s}
::-webkit-scrollbar{width:4px}::-webkit-scrollbar-thumb{background:var(--border);border-radius:2px}
@keyframes up{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.2}}
@keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(16,185,129,.4)}60%{box-shadow:0 0 0 6px rgba(16,185,129,0)}}
.an{opacity:0;animation:up .35s forwards}

/* ── SETUP SCREEN ── */
.setup{position:fixed;inset:0;background:var(–bg);display:flex;align-items:center;justify-content:center;z-index:9999;padding:20px}
.setup.out{display:none}
.setup-box{background:var(–surface);border-radius:20px;border:1px solid var(–border);box-shadow:var(–sh2);padding:36px;width:480px;max-width:100%}
.setup-logo{width:48px;height:48px;background:var(–blue);border-radius:14px;display:flex;align-items:center;justify-content:center;margin-bottom:16px;box-shadow:0 4px 14px rgba(37,99,235,.3)}
.setup-logo svg{width:24px;height:24px;stroke:#fff}
.setup-title{font-family:var(–font);font-size:22px;font-weight:800;letter-spacing:-.5px;margin-bottom:6px}
.setup-sub{font-size:14px;color:var(–text2);margin-bottom:24px;line-height:1.5}
.setup-label{font-size:11px;font-weight:700;color:var(–text2);text-transform:uppercase;letter-spacing:.6px;margin-bottom:6px}
.setup-input{width:100%;padding:10px 14px;background:var(–s2);border:1px solid var(–border);border-radius:var(–rsm);font-family:var(–body);font-size:14px;color:var(–text);outline:none;transition:all .2s;margin-bottom:14px}
.setup-input:focus{border-color:var(–blue);background:var(–surface);box-shadow:0 0 0 3px var(–blue-bg)}
.setup-btn{width:100%;padding:12px;background:var(–blue);color:#fff;border:none;border-radius:var(–rsm);font-family:var(–body);font-size:15px;font-weight:700;cursor:pointer;transition:all .18s;box-shadow:0 2px 8px rgba(37,99,235,.3)}
.setup-btn:hover{filter:brightness(1.1)}
.setup-note{font-size:12px;color:var(–text3);text-align:center;margin-top:12px;line-height:1.5}
.setup-skip{color:var(–blue);cursor:pointer;text-decoration:underline}

/* ── TOPBAR ── */
.topbar{position:sticky;top:0;z-index:100;height:58px;background:var(–tb);backdrop-filter:blur(24px);-webkit-backdrop-filter:blur(24px);border-bottom:1px solid var(–border);display:flex;align-items:center;padding:0 20px;gap:12px}
.brand{display:flex;align-items:center;gap:8px;flex-shrink:0}
.brand-ico{width:30px;height:30px;background:var(–blue);border-radius:8px;display:flex;align-items:center;justify-content:center;box-shadow:0 2px 6px rgba(37,99,235,.3)}
.brand-ico svg{width:15px;height:15px;stroke:#fff}
.brand-name{font-family:var(–font);font-size:16px;font-weight:800;letter-spacing:-.5px}
.live-pill{display:flex;align-items:center;gap:6px;background:var(–green-bg);border:1px solid var(–green-bd);border-radius:20px;padding:5px 10px;font-size:11px;font-weight:700;color:#065f46}
[data-theme=“dark”] .live-pill{color:var(–green)}
.live-pill.demo{background:var(–amber-bg);border-color:var(–amber-bd);color:#92400e}
[data-theme=“dark”] .live-pill.demo{color:var(–amber)}
.live-dot{width:6px;height:6px;border-radius:50%;background:var(–green);animation:pulse 2s infinite}
.live-dot.demo{background:var(–amber)}

.nav{display:flex;gap:1px;margin-left:auto;overflow-x:auto}
.nbtn{display:flex;align-items:center;gap:5px;padding:6px 10px;border-radius:var(–rxs);font-size:12px;font-weight:600;color:var(–text2);cursor:pointer;border:none;background:transparent;font-family:var(–body);transition:all .15s;white-space:nowrap}
.nbtn svg{width:13px;height:13px}
.nbtn:hover{background:var(–s2);color:var(–text)}
.nbtn.on{color:var(–blue);background:var(–blue-bg)}
.nbb{font-size:9px;font-weight:800;background:var(–red);color:#fff;border-radius:8px;padding:1px 4px;display:none;min-width:14px;text-align:center}
.nbb.on{display:inline-block}

.tba{display:flex;gap:7px;align-items:center;flex-shrink:0}
.ico-btn{width:32px;height:32px;background:var(–s2);border:1px solid var(–border);border-radius:var(–rxs);cursor:pointer;display:flex;align-items:center;justify-content:center;color:var(–text2);transition:all .2s}
.ico-btn:hover{color:var(–text);border-color:var(–blue-bd)}
.ico-btn svg{width:14px;height:14px}
.btn-primary{display:flex;align-items:center;gap:5px;padding:7px 13px;background:var(–blue);color:#fff;border:none;border-radius:var(–rxs);font-family:var(–body);font-size:12px;font-weight:700;cursor:pointer;transition:all .18s;box-shadow:0 2px 6px rgba(37,99,235,.25)}
.btn-primary:hover{filter:brightness(1.1);transform:translateY(-1px)}
.btn-primary svg{width:12px;height:12px}
.btn-ghost{display:flex;align-items:center;gap:5px;padding:7px 12px;background:var(–s2);color:var(–text2);border:1px solid var(–border);border-radius:var(–rxs);font-family:var(–body);font-size:12px;font-weight:600;cursor:pointer;transition:all .18s}
.btn-ghost:hover{color:var(–text);border-color:var(–blue-bd)}
.btn-ghost svg{width:12px;height:12px}

/* ── VIEWS ── */
.view{display:none}.view.on{display:block}
.cnt{max-width:1300px;margin:0 auto;padding:20px 22px}

/* ── BANNER ── */
.banner{background:linear-gradient(135deg,var(–blue),var(–purple));border-radius:var(–r);padding:16px 20px;display:flex;align-items:center;gap:14px;margin-bottom:16px;color:#fff;box-shadow:0 4px 16px rgba(37,99,235,.2)}
.banner-ico{width:40px;height:40px;background:rgba(255,255,255,.15);border-radius:10px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.banner-ico svg{width:18px;height:18px;stroke:#fff}
.banner-title{font-size:14px;font-weight:700;margin-bottom:2px}
.banner-sub{font-size:12px;color:rgba(255,255,255,.7)}
.banner-stats{display:flex;gap:20px;margin-left:auto;flex-shrink:0}
.bstat{text-align:center}
.bstat-v{font-family:var(–font);font-size:20px;font-weight:800;letter-spacing:-1px;line-height:1}
.bstat-l{font-size:10px;color:rgba(255,255,255,.6);margin-top:1px}

/* ── METRICS ── */
.metrics{display:grid;grid-template-columns:repeat(4,1fr);gap:11px;margin-bottom:18px}
.metric{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);padding:16px 18px;box-shadow:var(–sh);display:flex;align-items:center;gap:12px}
.mico{width:40px;height:40px;border-radius:10px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.mico svg{width:17px;height:17px}
.mv{font-family:var(–font);font-size:28px;font-weight:800;letter-spacing:-1.5px;line-height:1;margin-bottom:2px}
.ml{font-size:12px;color:var(–text2)}
.metric.g .mico{background:var(–green-bg);color:var(–green)}.metric.g .mv{color:var(–green)}
.metric.a .mico{background:var(–amber-bg);color:var(–amber)}.metric.a .mv{color:var(–amber)}
.metric.r .mico{background:var(–red-bg);color:var(–red)}.metric.r .mv{color:var(–red)}
.metric.b .mico{background:var(–blue-bg);color:var(–blue)}.metric.b .mv{color:var(–blue)}

/* ── LAYOUT ── */
.lay{display:grid;grid-template-columns:1fr 308px;gap:14px;align-items:start}

/* ── CARD ── */
.card{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);overflow:hidden}
.ch{display:flex;align-items:center;justify-content:space-between;padding:13px 18px;border-bottom:1px solid var(–border2)}
.ct{font-size:14px;font-weight:700}
.cmeta{font-size:12px;color:var(–text2);background:var(–s2);border-radius:20px;padding:3px 9px}

/* ── FILTERS ── */
.fil{display:flex;gap:5px;padding:8px 18px;border-bottom:1px solid var(–border2);background:var(–s2);overflow-x:auto}
.fb{padding:4px 11px;border-radius:20px;font-size:11px;font-weight:700;color:var(–text2);border:1px solid transparent;background:transparent;cursor:pointer;font-family:var(–body);transition:all .15s;white-space:nowrap}
.fb:hover{background:var(–s3);color:var(–text)}
.fb.on{background:var(–blue-bg);border-color:var(–blue-bd);color:var(–blue)}
.fb.g.on{background:var(–green-bg);border-color:var(–green-bd);color:var(–green)}
.fb.a.on{background:var(–amber-bg);border-color:var(–amber-bd);color:var(–amber)}
.fb.r.on{background:var(–red-bg);border-color:var(–red-bd);color:var(–red)}

/* ── ORDER ROW ── */
.or{display:flex;align-items:center;gap:11px;padding:11px 18px;border-bottom:1px solid var(–border2);cursor:pointer;transition:background .12s;position:relative}
.or:last-child{border-bottom:none}
.or:hover{background:var(–s2)}
.or.on{background:var(–blue-bg)}
.or.on::before{content:’’;position:absolute;left:0;top:8px;bottom:8px;width:2px;background:var(–blue);border-radius:0 2px 2px 0}
.av{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:800;flex-shrink:0;color:#fff}
.oi{flex:1;min-width:0}
.on2{font-size:13px;font-weight:600;margin-bottom:2px;display:flex;align-items:center;gap:5px}
.os{font-size:11px;color:var(–text2);display:flex;gap:4px;align-items:center}
.osp{color:var(–text3)}
.chip{display:inline-flex;align-items:center;gap:3px;padding:2px 7px;border-radius:20px;font-size:10px;font-weight:800}
.chip.g{background:var(–green-bg);color:var(–green);border:1px solid var(–green-bd)}
.chip.a{background:var(–amber-bg);color:var(–amber);border:1px solid var(–amber-bd)}
.chip.r{background:var(–red-bg);color:var(–red);border:1px solid var(–red-bd)}
.cdot{width:4px;height:4px;border-radius:50%}
.chip.g .cdot{background:var(–green)}.chip.a .cdot{background:var(–amber)}
.chip.r .cdot{background:var(–red);animation:blink 1.3s infinite}
.real-tag{font-size:9px;font-weight:800;color:var(–green);background:var(–green-bg);border:1px solid var(–green-bd);border-radius:4px;padding:2px 5px}
.demo-tag{font-size:9px;font-weight:800;color:var(–amber);background:var(–amber-bg);border:1px solid var(–amber-bd);border-radius:4px;padding:2px 5px}

/* ── EMPTY ── */
.empty{padding:48px 20px;text-align:center}
.eico{width:46px;height:46px;border-radius:12px;background:var(–s2);display:flex;align-items:center;justify-content:center;margin:0 auto 12px;color:var(–text3)}
.eico svg{width:20px;height:20px}
.et{font-size:14px;font-weight:700;color:var(–text2);margin-bottom:3px}
.es{font-size:12px;color:var(–text3)}

/* ── RIGHT STACK ── */
.rs{display:flex;flex-direction:column;gap:11px}
.sc{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);padding:22px 17px 16px;display:flex;flex-direction:column;align-items:center}
.rw{position:relative;width:124px;height:124px;margin-bottom:13px}
.rsv{width:124px;height:124px;transform:rotate(-90deg)}
.rbg{fill:none;stroke:var(–s2);stroke-width:8}
.rfg{fill:none;stroke-width:8;stroke-linecap:round;stroke-dasharray:314;stroke-dashoffset:314;transition:stroke-dashoffset 1s cubic-bezier(.4,0,.2,1),stroke .5s}
.rin{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}
.rnum{font-family:var(–font);font-size:32px;font-weight:800;letter-spacing:-2px;line-height:1;transition:color .5s;color:var(–text3)}
.runit{font-size:11px;color:var(–text2);margin-top:2px}
.bn{font-size:15px;font-weight:700;text-align:center;margin-bottom:2px;font-family:var(–font)}
.bfp{font-size:10px;color:var(–text3);font-family:monospace;text-align:center;margin-bottom:10px}
.verd{display:inline-flex;align-items:center;gap:5px;padding:5px 13px;border-radius:20px;font-size:12px;font-weight:700;margin-bottom:11px;opacity:0;transition:opacity .3s}
.verd.g{background:var(–green-bg);color:var(–green);border:1px solid var(–green-bd)}
.verd.a{background:var(–amber-bg);color:var(–amber);border:1px solid var(–amber-bd)}
.verd.r{background:var(–red-bg);color:var(–red);border:1px solid var(–red-bd)}

.vn{width:100%;margin-bottom:11px;display:none}
.vni{width:100%;padding:7px 10px;background:var(–s2);border:1px solid var(–border);border-radius:var(–rxs);font-family:var(–body);font-size:12px;color:var(–text);outline:none;resize:none;height:52px;transition:all .2s}
.vni:focus{border-color:var(–blue);background:var(–surface)}
.vni::placeholder{color:var(–text3)}
.vns{display:flex;align-items:center;gap:4px;margin-top:4px;padding:5px 9px;background:var(–s2);border:1px solid var(–border);border-radius:var(–rxs);font-family:var(–body);font-size:11px;font-weight:700;color:var(–text2);cursor:pointer;transition:all .15s}
.vns:hover{color:var(–blue);border-color:var(–blue-bd)}
.vns svg{width:10px;height:10px}

.ap{display:grid;grid-template-columns:1fr 1fr;gap:6px;width:100%;opacity:0;pointer-events:none;transition:opacity .3s}
.act{display:flex;align-items:center;justify-content:center;gap:4px;padding:8px;border-radius:var(–rsm);font-size:12px;font-weight:700;font-family:var(–body);border:none;cursor:pointer;transition:all .18s}
.act svg{width:11px;height:11px}
.act.app{background:var(–green-bg);color:var(–green);border:1px solid var(–green-bd)}
.act.app:hover{filter:brightness(1.1)}
.act.dec{background:var(–red-bg);color:var(–red);border:1px solid var(–red-bd)}
.act.dec:hover{filter:brightness(1.1)}

.ip{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);overflow:hidden}
.iph{padding:10px 14px;border-bottom:1px solid var(–border2);display:flex;align-items:center;gap:6px}
.iph svg{width:12px;height:12px;color:var(–text3)}
.ipht{font-size:10px;font-weight:800;color:var(–text2);text-transform:uppercase;letter-spacing:.6px}
.ipb{padding:12px 14px}

.sig{display:flex;align-items:center;gap:7px;margin-bottom:8px}
.sig:last-child{margin-bottom:0}
.sn{font-size:11px;color:var(–text2);width:100px;flex-shrink:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.st{flex:1;height:3px;background:var(–s2);border-radius:2px;overflow:hidden}
.sb{height:100%;border-radius:2px;transition:width .7s cubic-bezier(.4,0,.2,1)}
.sp2{font-size:10px;font-weight:800;width:24px;text-align:right;font-family:monospace}

.hi{display:flex;gap:8px;align-items:flex-start;margin-bottom:9px}
.hi:last-child{margin-bottom:0}
.hic{width:22px;height:22px;border-radius:6px;background:var(–s2);display:flex;align-items:center;justify-content:center;flex-shrink:0;color:var(–text2)}
.hic svg{width:10px;height:10px}
.ht{font-size:11px;line-height:1.5;color:var(–text)}
.hd{font-size:10px;color:var(–text3);margin-top:1px}

.rl{padding:11px 14px}
.ri{display:flex;align-items:center;gap:9px;padding:8px 9px;background:var(–s2);border-radius:var(–rxs);margin-bottom:5px;border:1px solid var(–border2)}
.rico{font-size:13px;width:20px;text-align:center}
.rtx{flex:1;font-size:11px;color:var(–text)}
.rtog{width:32px;height:17px;border-radius:9px;background:var(–s3);border:none;cursor:pointer;position:relative;transition:all .2s;flex-shrink:0}
.rtog::after{content:’’;position:absolute;width:13px;height:13px;border-radius:50%;background:#fff;top:2px;left:2px;transition:all .2s;box-shadow:0 1px 2px rgba(0,0,0,.2)}
.rtog.on{background:var(–blue)}.rtog.on::after{left:17px}

/* ── SHOPIFY PAGE ── */
.shopify-box{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);padding:24px;margin-bottom:14px}
.shopify-box-title{font-family:var(–font);font-size:16px;font-weight:800;margin-bottom:4px}
.shopify-box-sub{font-size:13px;color:var(–text2);margin-bottom:20px}
.step{display:flex;gap:12px;align-items:flex-start;margin-bottom:18px}
.step:last-child{margin-bottom:0}
.step-num{width:28px;height:28px;border-radius:50%;background:var(–blue);color:#fff;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:800;flex-shrink:0;margin-top:1px}
.step-title{font-size:14px;font-weight:700;margin-bottom:4px}
.step-desc{font-size:13px;color:var(–text2);line-height:1.6}
.step-code{background:var(–s2);border:1px solid var(–border);border-radius:4px;padding:2px 7px;font-family:monospace;font-size:12px;color:var(–blue);display:inline}
.code-block{background:#09090e;border-radius:var(–rsm);padding:14px;font-family:monospace;font-size:11px;color:#7ee8a2;line-height:1.8;overflow-x:auto;white-space:pre;border:1px solid rgba(255,255,255,.06);margin:10px 0}

/* ── STATS ── */
.sgrid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
.spanel{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);padding:18px}
.spt{font-size:12px;font-weight:700;color:var(–text2);margin-bottom:14px}
.brow{display:flex;align-items:center;gap:8px;margin-bottom:8px}
.brow:last-child{margin-bottom:0}
.brl{font-size:11px;color:var(–text2);width:72px;flex-shrink:0}
.brt{flex:1;height:5px;background:var(–s2);border-radius:3px;overflow:hidden}
.brf{height:100%;border-radius:3px;transition:width .8s cubic-bezier(.4,0,.2,1)}
.brv{font-size:11px;font-weight:700;color:var(–text2);width:22px;text-align:right}

/* Profiles */
.pgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:12px}
.pcard{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);padding:16px;cursor:pointer;transition:all .2s}
.pcard:hover{box-shadow:var(–sh2);transform:translateY(-2px)}
.pct{display:flex;align-items:center;gap:10px;margin-bottom:12px}
.pcn{font-size:13px;font-weight:700}
.pcf{font-size:10px;color:var(–text3);font-family:monospace;margin-top:1px}
.pcst{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-bottom:10px}
.pcs{background:var(–s2);border-radius:var(–rsm);padding:8px 6px;text-align:center}
.pcsv{font-family:var(–font);font-size:16px;font-weight:800;line-height:1}
.pcsl{font-size:9px;color:var(–text2);margin-top:2px}
.pcbr{display:flex;align-items:center;gap:6px}
.pcbl{font-size:10px;color:var(–text2);width:44px}
.pcbt{flex:1;height:4px;background:var(–s2);border-radius:2px;overflow:hidden}
.pcbf{height:100%;border-radius:2px;transition:width .7s}
.pcbn{font-size:11px;font-weight:700;width:22px;text-align:right}

/* Alerts */
.alrt{background:var(–surface);border-radius:var(–r);border:1px solid var(–border);box-shadow:var(–sh);padding:12px 16px;display:flex;align-items:center;gap:11px;margin-bottom:9px}
.alrt-ico{width:38px;height:38px;border-radius:9px;background:var(–red-bg);border:1px solid var(–red-bd);display:flex;align-items:center;justify-content:center;flex-shrink:0;color:var(–red)}
.alrt-ico svg{width:16px;height:16px}
.alrt-n{font-size:13px;font-weight:700;margin-bottom:2px}
.alrt-d{font-size:11px;color:var(–text2)}
.alrt-t{font-size:10px;color:var(–text3);flex-shrink:0;margin-left:auto}
.alrt-tag{padding:2px 7px;border-radius:20px;font-size:10px;font-weight:800;background:var(–red-bg);color:var(–red);border:1px solid var(–red-bd)}

/* Export */
.exp{display:flex;align-items:center;gap:4px;padding:4px 9px;background:var(–s2);border:1px solid var(–border);border-radius:var(–rxs);font-size:11px;font-weight:700;color:var(–text2);cursor:pointer;transition:all .15s;font-family:var(–body)}
.exp:hover{color:var(–text);border-color:var(–blue-bd)}
.exp svg{width:10px;height:10px}

/* Toast */
.toast{position:fixed;bottom:20px;right:20px;background:var(–surface);border:1px solid var(–border);border-radius:12px;padding:11px 14px 11px 17px;z-index:999;width:280px;box-shadow:var(–sh2);transform:translateY(70px);opacity:0;transition:all .4s cubic-bezier(.4,0,.2,1);pointer-events:none;border-left:3px solid var(–blue)}
.toast.on{transform:translateY(0);opacity:1}
.tlbl{font-size:9px;font-weight:800;text-transform:uppercase;letter-spacing:.8px;color:var(–text3);margin-bottom:3px}
.ttit{font-size:13px;font-weight:700;margin-bottom:2px}
.tdesc{font-size:11px;color:var(–text2)}

/* Copy btn */
.copy-btn{display:flex;align-items:center;gap:5px;padding:8px 14px;background:var(–blue);color:#fff;border:none;border-radius:var(–rxs);font-family:var(–body);font-size:12px;font-weight:700;cursor:pointer;transition:all .18s;margin-top:8px}
.copy-btn:hover{filter:brightness(1.1)}
.copy-btn svg{width:12px;height:12px}

@media(max-width:1100px){.lay{grid-template-columns:1fr}.metrics{grid-template-columns:repeat(2,1fr)}.sgrid{grid-template-columns:1fr}}
@media(max-width:700px){.topbar{flex-wrap:wrap;height:auto;padding:10px 14px}.nav{display:none}.cnt{padding:14px}.metrics{grid-template-columns:1fr 1fr;gap:9px}}
</style>

</head>
<body>

<!-- SETUP SCREEN -->

<div class="setup" id="setup">
  <div class="setup-box">
    <div class="setup-logo">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M12 2L2 7l10 5 10-5-10-5z"/>
        <path d="M2 17l10 5 10-5"/>
        <path d="M2 12l10 5 10-5"/>
      </svg>
    </div>
    <div class="setup-title">Sellia — Configuration</div>
    <div class="setup-sub">Entrez vos informations Supabase pour connecter votre base de données réelle.</div>

```
<div class="setup-label">URL Supabase</div>
<input class="setup-input" id="setupUrl" type="text" placeholder="https://xxxx.supabase.co" value="https://lsefxxipjzllxdxmrqbr.supabase.co">

<div class="setup-label">Clé API (anon public — commence par eyJ)</div>
<input class="setup-input" id="setupKey" type="text" placeholder="eyJhbGciOiJIUzI1NiIs…">

<button class="setup-btn" onclick="connectSupabase()">Connecter et démarrer</button>
<div class="setup-note">
  La clé "anon public" se trouve dans Supabase → Settings → API<br>
  <span class="setup-skip" onclick="startDemo()">Continuer en mode démo sans base de données</span>
</div>
```

  </div>
</div>

<!-- TOPBAR -->

<div class="topbar">
  <div class="brand">
    <div class="brand-ico"><svg viewBox="0 0 24 24" fill="none" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/></svg></div>
    <span class="brand-name">Sellia</span>
  </div>

  <div class="live-pill" id="livePill">
    <div class="live-dot" id="liveDot"></div>
    <span id="liveText">Connexion…</span>
  </div>

  <nav class="nav">
    <button class="nbtn on" onclick="goTo('dashboard',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><rect x="14" y="14" width="7" height="7" rx="1"/></svg>
      Dashboard
    </button>
    <button class="nbtn" onclick="goTo('commandes',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/></svg>
      Commandes<span class="nbb" id="riskBadge">0</span>
    </button>
    <button class="nbtn" onclick="goTo('profils',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/></svg>
      Profils
    </button>
    <button class="nbtn" onclick="goTo('stats',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
      Stats
    </button>
    <button class="nbtn" onclick="goTo('alertes',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 006 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 01-3.46 0"/></svg>
      Alertes<span class="nbb" id="alertBadge">0</span>
    </button>
    <button class="nbtn" onclick="goTo('shopify',this)">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
      Shopify
    </button>
  </nav>

  <div class="tba">
    <button class="ico-btn" onclick="toggleTheme()">
      <svg id="thIco" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="5"/><line x1="12" y1="1" x2="12" y2="3"/><line x1="12" y1="21" x2="12" y2="23"/><line x1="4.22" y1="4.22" x2="5.64" y2="5.64"/><line x1="18.36" y1="18.36" x2="19.78" y2="19.78"/><line x1="1" y1="12" x2="3" y2="12"/><line x1="21" y1="12" x2="23" y2="12"/><line x1="4.22" y1="19.78" x2="5.64" y2="18.36"/><line x1="18.36" y1="5.64" x2="19.78" y2="4.22"/></svg>
    </button>
    <button class="btn-ghost" onclick="addOrder()">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
      Simuler
    </button>
    <button class="btn-primary" onclick="goTo('shopify',document.querySelectorAll('.nbtn')[5])">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/></svg>
      Installer Shopify
    </button>
  </div>
</div>

<!-- DASHBOARD -->

<div class="view on" id="view-dashboard">
  <div class="cnt">
    <div class="banner an">
      <div class="banner-ico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="5" r="3"/><circle cx="5" cy="19" r="3"/><circle cx="19" cy="19" r="3"/><path d="M12 8v3M7.5 17.5l3-2M16.5 17.5l-3-2"/></svg></div>
      <div>
        <div class="banner-title" id="bannerTitle">Sellia connecté</div>
        <div class="banner-sub" id="bannerSub">Base de données prête · Installez le snippet sur Shopify pour recevoir les vraies commandes</div>
      </div>
      <div class="banner-stats">
        <div class="bstat"><div class="bstat-v" id="bsOrders">0</div><div class="bstat-l">Commandes</div></div>
        <div class="bstat"><div class="bstat-v" id="bsProfiles">0</div><div class="bstat-l">Profils</div></div>
        <div class="bstat"><div class="bstat-v" id="bsRisk">0</div><div class="bstat-l">Alertes</div></div>
      </div>
    </div>

```
<div class="metrics">
  <div class="metric g an" style="animation-delay:.00s"><div class="mico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div><div><div class="mv" id="mG">0</div><div class="ml">Fiables</div></div></div>
  <div class="metric a an" style="animation-delay:.05s"><div class="mico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg></div><div><div class="mv" id="mA">0</div><div class="ml">Surveillance</div></div></div>
  <div class="metric r an" style="animation-delay:.10s"><div class="mico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/></svg></div><div><div class="mv" id="mR">0</div><div class="ml">À risque</div></div></div>
  <div class="metric b an" style="animation-delay:.15s"><div class="mico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg></div><div><div class="mv" id="mAvg">—</div><div class="ml">Score moyen</div></div></div>
</div>

<div class="lay">
  <div class="card an" style="animation-delay:.08s">
    <div class="ch">
      <div class="ct">Commandes</div>
      <div style="display:flex;gap:6px;align-items:center">
        <button class="exp" onclick="loadOrders()"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="1 4 1 10 7 10"/><path d="M3.51 15a9 9 0 102.13-9.36L1 10"/></svg>Actualiser</button>
        <button class="exp" onclick="exportCSV()"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>CSV</button>
        <div class="cmeta" id="oCnt">0</div>
      </div>
    </div>
    <div class="fil">
      <button class="fb on" onclick="setF('all',this)">Toutes</button>
      <button class="fb g" onclick="setF('g',this)">Fiables</button>
      <button class="fb a" onclick="setF('a',this)">Surveillance</button>
      <button class="fb r" onclick="setF('r',this)">Risque</button>
    </div>
    <div id="orderList"></div>
  </div>

  <div class="rs">
    <div class="sc an" style="animation-delay:.1s">
      <div class="rw">
        <svg class="rsv" viewBox="0 0 124 124"><circle class="rbg" cx="62" cy="62" r="50"/><circle class="rfg" id="rfg" cx="62" cy="62" r="50"/></svg>
        <div class="rin"><div class="rnum" id="rnum">—</div><div class="runit">/ 100</div></div>
      </div>
      <div class="bn" id="bname">Sélectionnez une commande</div>
      <div class="bfp" id="bfp">—</div>
      <div class="verd" id="verd">—</div>
      <div class="vn" id="vnw">
        <textarea class="vni" id="vni" placeholder="Note sur cet acheteur…"></textarea>
        <button class="vns" onclick="saveNote()"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 21H5a2 2 0 01-2-2V5a2 2 0 012-2h11l5 5v11a2 2 0 01-2 2z"/><polyline points="17 21 17 13 7 13 7 21"/></svg>Enregistrer</button>
      </div>
      <div class="ap" id="actpair">
        <button class="act app" id="appBtn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>Accepter</button>
        <button class="act dec" id="decBtn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>Refuser</button>
      </div>
    </div>

    <div class="ip an" style="animation-delay:.12s">
      <div class="iph"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 12h-4l-3 9L9 3l-3 9H2"/></svg><div class="ipht">Signaux</div></div>
      <div class="ipb" id="sigBody"><div style="font-size:11px;color:var(--text3)">Sélectionnez une commande.</div></div>
    </div>

    <div class="ip an" style="animation-delay:.13s">
      <div class="iph"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg><div class="ipht">Historique</div></div>
      <div class="ipb" id="histBody"><div style="font-size:11px;color:var(--text3)">Aucun historique.</div></div>
    </div>

    <div class="ip an" style="animation-delay:.14s">
      <div class="iph"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg><div class="ipht">Règles automatiques</div></div>
      <div class="rl" id="rulesList"></div>
    </div>
  </div>
</div>
```

  </div>
</div>

<!-- COMMANDES -->

<div class="view" id="view-commandes">
  <div class="cnt">
    <div class="card an">
      <div class="ch">
        <div class="ct">Toutes les commandes</div>
        <div style="display:flex;gap:6px;align-items:center">
          <button class="exp" onclick="exportCSV()"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>Exporter CSV</button>
          <div class="cmeta" id="allCnt">0</div>
        </div>
      </div>
      <div class="fil">
        <button class="fb on" onclick="setF2('all',this)">Toutes</button>
        <button class="fb g" onclick="setF2('g',this)">Fiables</button>
        <button class="fb a" onclick="setF2('a',this)">Surveillance</button>
        <button class="fb r" onclick="setF2('r',this)">Risque</button>
      </div>
      <div id="allList"></div>
    </div>
  </div>
</div>

<!-- PROFILS -->

<div class="view" id="view-profils">
  <div class="cnt"><div class="pgrid" id="pgrid"></div></div>
</div>

<!-- STATS -->

<div class="view" id="view-stats">
  <div class="cnt">
    <div class="sgrid">
      <div class="spanel an"><div class="spt">Répartition des scores</div><div id="scoreChart"></div></div>
      <div class="spanel an" style="animation-delay:.05s"><div class="spt">Pays</div><div id="countryChart"></div></div>
    </div>
  </div>
</div>

<!-- ALERTES -->

<div class="view" id="view-alertes">
  <div class="cnt"><div id="alertList"></div></div>
</div>

<!-- SHOPIFY -->

<div class="view" id="view-shopify">
  <div class="cnt">

```
<div class="shopify-box an">
  <div class="shopify-box-title">Étape 1 — Créer les tables dans Supabase</div>
  <div class="shopify-box-sub">Copie ce SQL dans Supabase → SQL Editor → New query → Run</div>
  <div class="code-block" id="sqlCode">-- Coller dans Supabase SQL Editor
```

create table if not exists profiles (
id uuid default gen_random_uuid() primary key,
fingerprint_id text unique not null,
name text, email_hash text, platform text default ‘Shopify’,
country text, total_orders int default 0,
total_disputes int default 0, last_score int default 50,
score_history jsonb default ‘[]’,
vendor_note text, created_at timestamptz default now()
);

create table if not exists orders (
id uuid default gen_random_uuid() primary key,
order_id text unique not null,
fingerprint_id text,
buyer_name text, amount decimal, platform text default ‘Shopify’,
country text, score int, classification text,
label text, action text, signals jsonb, breakdown jsonb,
is_real boolean default false,
created_at timestamptz default now()
);

create table if not exists audit_log (
id uuid default gen_random_uuid() primary key,
action text, detail text, order_id text,
created_at timestamptz default now()
);

alter table profiles enable row level security;
alter table orders enable row level security;
alter table audit_log enable row level security;

create policy “Public” on profiles for all using (true);
create policy “Public” on orders for all using (true);
create policy “Public” on audit_log for all using (true);</div>
<button class="copy-btn" onclick="copySQL()">
<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 01-2-2V4a2 2 0 012-2h9a2 2 0 012 2v1"/></svg>
Copier le SQL
</button>
</div>

```
<div class="shopify-box an" style="animation-delay:.06s">
  <div class="shopify-box-title">Étape 2 — Installer le snippet sur Shopify</div>
  <div class="shopify-box-sub">Admin Shopify → Boutique en ligne → Thèmes → Actions → Modifier le code → theme.liquid → colle juste avant &lt;/head&gt;</div>
  <div class="code-block" id="snippetCode"></div>
  <button class="copy-btn" onclick="copySnippet()">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 01-2-2V4a2 2 0 012-2h9a2 2 0 012 2v1"/></svg>
    Copier le snippet
  </button>
</div>

<div class="shopify-box an" style="animation-delay:.12s">
  <div class="shopify-box-title">Étape 3 — Configurer le webhook Shopify</div>
  <div class="shopify-box-sub">Admin Shopify → Paramètres → Notifications → Webhooks → Créer un webhook</div>
  <div class="step">
    <div class="step-num">1</div>
    <div><div class="step-title">Événement</div><div class="step-desc">Sélectionne <strong>Création d'une commande</strong></div></div>
  </div>
  <div class="step">
    <div class="step-num">2</div>
    <div><div class="step-title">Format</div><div class="step-desc">Sélectionne <strong>JSON</strong></div></div>
  </div>
  <div class="step">
    <div class="step-num">3</div>
    <div>
      <div class="step-title">URL</div>
      <div class="step-desc">Colle cette URL dans le champ URL :</div>
      <div class="code-block" id="webhookUrl">https://lsefxxipjzllxdxmrqbr.supabase.co/functions/v1/sellia-webhook</div>
      <button class="copy-btn" style="margin-top:6px" onclick="copyWebhook()">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 01-2-2V4a2 2 0 012-2h9a2 2 0 012 2v1"/></svg>
        Copier l'URL
      </button>
    </div>
  </div>
</div>
```

  </div>
</div>

<!-- TOAST -->

<div class="toast" id="toast">
  <div class="tlbl" id="tlbl">Sellia</div>
  <div class="ttit" id="ttit">—</div>
  <div class="tdesc" id="tdesc">—</div>
</div>

<script>
/* ══════════════════════════════════════
   CONFIG SUPABASE
══════════════════════════════════════ */
let SUPABASE_URL = 'https://lsefxxipjzllxdxmrqbr.supabase.co';
let SUPABASE_KEY = '';
let isLive = false;
let isDemoMode = false;

/* ══════════════════════════════════════
   SUPABASE API
══════════════════════════════════════ */
async function sbFetch(table, method='GET', body=null, query='') {
  const url = `${SUPABASE_URL}/rest/v1/${table}${query}`;
  const headers = {
    'Content-Type': 'application/json',
    'apikey': SUPABASE_KEY,
    'Authorization': `Bearer ${SUPABASE_KEY}`,
    'Prefer': method === 'POST' ? 'return=representation' : ''
  };
  const res = await fetch(url, {
    method,
    headers,
    body: body ? JSON.stringify(body) : null
  });
  if (!res.ok) {
    const err = await res.text();
    throw new Error(err);
  }
  return method === 'DELETE' ? null : res.json();
}

async function sbInsert(table, data) {
  return sbFetch(table, 'POST', data);
}

async function sbSelect(table, query='?order=created_at.desc&limit=100') {
  return sbFetch(table, 'GET', null, query);
}

async function sbUpdate(table, id, data) {
  return sbFetch(table, 'PATCH', data, `?id=eq.${id}`);
}

/* ══════════════════════════════════════
   SETUP
══════════════════════════════════════ */
async function connectSupabase() {
  const url = document.getElementById('setupUrl').value.trim();
  const key = document.getElementById('setupKey').value.trim();

  if (!key || !key.startsWith('eyJ')) {
    showMsg('Clé invalide', 'La clé anon doit commencer par eyJ — visible dans Supabase → Settings → API', 'var(--red)');
    return;
  }

  SUPABASE_URL = url;
  SUPABASE_KEY = key;

  try {
    // Test connection
    const test = await sbSelect('orders', '?limit=1');
    isLive = true;
    localStorage.setItem('sellia_url', url);
    localStorage.setItem('sellia_key', key);
    launchApp(true);
  } catch(e) {
    showMsg('Erreur de connexion', 'Vérifiez votre clé API et que les tables sont créées (Étape 1 dans Shopify)', 'var(--red)');
  }
}

function startDemo() {
  isDemoMode = true;
  launchApp(false);
}

function launchApp(live) {
  document.getElementById('setup').classList.add('out');
  isLive = live;

  // Update live pill
  const pill = document.getElementById('livePill');
  const dot = document.getElementById('liveDot');
  const txt = document.getElementById('liveText');

  if (live) {
    pill.classList.remove('demo');
    dot.classList.remove('demo');
    txt.textContent = 'Connecté · Supabase Live';
    showMsg('Connecté', 'Base de données Supabase active', 'var(--green)');
    loadOrders();
    // Poll every 30s for new orders
    setInterval(loadOrders, 30000);
  } else {
    pill.classList.add('demo');
    dot.classList.add('demo');
    txt.textContent = 'Mode démo';
    // Boot with simulated orders
    renderRules();
    [0,100,200,300,400].forEach(d => setTimeout(addOrder, d));
  }

  renderRules();
  buildSnippet();
}

/* ══════════════════════════════════════
   LOAD REAL ORDERS FROM SUPABASE
══════════════════════════════════════ */
async function loadOrders() {
  if (!isLive) return;
  try {
    const data = await sbSelect('orders');
    if (data && data.length > 0) {
      orders = data.map(o => ({
        id: o.order_id,
        name: o.buyer_name || 'Acheteur',
        initials: (o.buyer_name||'??').split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase(),
        color: colorForScore(o.score),
        amount: o.amount || '0.00',
        platform: o.platform || 'Shopify',
        time: new Date(o.created_at).toLocaleTimeString('fr-FR',{hour:'2-digit',minute:'2-digit'}),
        score: o.score || 50,
        c: o.classification || 'a',
        label: o.label || 'À analyser',
        action: o.action || 'flag',
        bd: o.breakdown || [],
        signals: o.signals || {},
        history: {},
        fp: o.fingerprint_id || '—',
        isReal: o.is_real || false,
        dbId: o.id
      }));
      render();
      showMsg('Données chargées', `${data.length} commande(s) depuis Supabase`, 'var(--green)');
    }
    // Update banner
    document.getElementById('bsOrders').textContent = orders.length;
    document.getElementById('bsRisk').textContent = orders.filter(o=>o.c==='r').length;
  } catch(e) {
    showMsg('Erreur de chargement', e.message, 'var(--red)');
  }
}

function colorForScore(s) {
  if (s === null || s === undefined) return '#6b7280';
  const hue = Math.round((s / 100) * 120);
  return `hsl(${hue},70%,45%)`;
}

/* ══════════════════════════════════════
   ENGINE — SCORING
══════════════════════════════════════ */
const Engine = {
  profiles: {},
  fpId(s) {
    const k = [s.payment?.token, s.identity?.email, s.device?.ip].filter(Boolean).join('|');
    return btoa(unescape(encodeURIComponent(k))).slice(0,14);
  },
  compute(sig, hist) {
    let sc = 100; const bd = [];
    const add = (l,p) => { sc+=p; bd.push({l,p}); };
    if (hist.disputes>0) add('Litiges',-(hist.disputes*15));
    if (hist.refunds>0) add('Remboursements',-(hist.refunds*5));
    if (sig.device?.vpn) add('VPN détecté',-10);
    if (sig.device?.proxy) add('Proxy détecté',-15);
    if (sig.anomalies?.burst) add('Comptes en rafale',-20);
    if ((sig.payment?.multi||1)>2) add('Paiement multi-comptes',-20);
    if (sig.behavior?.bot) add('Comportement bot',-15);
    if (hist.orders>0) add('Historique achats',Math.min(hist.orders*1.5,15));
    if (hist.recent>0) add('Litiges récents',-(hist.recent*20));
    return { score: Math.max(0,Math.min(100,Math.round(sc))), bd };
  },
  cls(s) {
    if (s>=70) return {c:'g',label:'Acheteur fiable',action:'allow'};
    if (s>=40) return {c:'a',label:'À surveiller',action:'flag'};
    return {c:'r',label:'Acheteur à risque',action:'alert'};
  },
  eval(data) {
    const fp = this.fpId(data.signals);
    const p = this.profiles[fp]||{orders:0,scoreHistory:[]};
    const {score,bd} = this.compute(data.signals,data.history);
    const cl = this.cls(score);
    p.orders++;p.lastScore=score;p.name=data.name;p.initials=data.initials;p.color=data.color;
    p.history=data.history;p.breakdown=bd;p.scoreHistory=[...(p.scoreHistory||[]),score].slice(-10);
    this.profiles[fp]=p;
    return {fp,score,bd,...cl};
  }
};

/* ══════════════════════════════════════
   RULES
══════════════════════════════════════ */
const RULES = [
  {id:1,label:'Bloquer si score < 30',icon:'🛡',on:true},
  {id:2,label:'Alerter si VPN détecté',icon:'🔒',on:true},
  {id:3,label:'Partager au réseau si litige',icon:'🌐',on:true},
];

function renderRules() {
  document.getElementById('rulesList').innerHTML = RULES.map(r=>`
    <div class="ri"><div class="rico">${r.icon}</div><div class="rtx">${r.label}</div>
    <button class="rtog ${r.on?'on':''}" onclick="toggleRule(${r.id},this)"></button></div>`
  ).join('');
}

function toggleRule(id,btn) {
  const r=RULES.find(x=>x.id===id);
  if(r){r.on=!r.on;btn.classList.toggle('on');showMsg('Règle '+(r.on?'activée':'désactivée'),'','var(--blue)');}
}

/* ══════════════════════════════════════
   STATE
══════════════════════════════════════ */
let orders=[], selId=null, curF='all', curF2='all', alerts=[];

const BUYERS = [
  {name:'Sophie Martin',initials:'SM',color:'#5e5ce6',platform:'Shopify',amount:89.90},
  {name:'Karim Benali',initials:'KB',color:'#0ea5e9',platform:'Shopify',amount:245.00},
  {name:'Élodie Dupont',initials:'ÉD',color:'#ec4899',platform:'Shopify',amount:34.50},
  {name:'Marc Dubois',initials:'MD',color:'#ef4444',platform:'Shopify',amount:890.00},
  {name:'Laura Bernard',initials:'LB',color:'#8b5cf6',platform:'Shopify',amount:42.00},
];

function rnd(){return Math.random().toString(36).slice(2,10);}
function randIp(){return [Math.floor(Math.random()*200)+10,Math.floor(Math.random()*200)+10,1,1].join('.');}

function mockSignals(risk) {
  const hi=risk==='high',med=risk==='medium';
  return {
    signals:{
      identity:{email:rnd()+'@test.fr'},
      payment:{token:'tok_'+rnd(),multi:hi?4:1},
      device:{ip:randIp(),vpn:hi,proxy:hi&&Math.random()>.6,country:['FR','BE','MA','DE'][Math.floor(Math.random()*4)],type:Math.random()>.5?'mobile':'desktop'},
      behavior:{bot:hi,secs:hi?3:80+Math.floor(Math.random()*200)},
      anomalies:{idChanges:hi?3:0,geo:(med||hi)&&Math.random()>.5,burst:hi&&Math.random()>.7}
    },
    history:{orders:hi?1:Math.floor(Math.random()*18),disputes:hi?Math.floor(1+Math.random()*3):(med&&Math.random()>.7?1:0),refunds:hi?Math.floor(Math.random()*3):0,won:hi?1:0,recent:hi?Math.floor(1+Math.random()*2):0}
  };
}

async function addOrder() {
  const b = BUYERS[Math.floor(Math.random()*BUYERS.length)];
  const risks = ['low','low','low','medium','medium','high'];
  const risk = risks[Math.floor(Math.random()*risks.length)];
  const d = mockSignals(risk);
  const res = Engine.eval({...d,name:b.name,initials:b.initials,color:b.color,platform:'Shopify'});

  const o = {
    id: 'DEMO-'+Date.now().toString(36).toUpperCase().slice(-6),
    ...b,
    amount: (b.amount+(Math.random()*20-10)).toFixed(2),
    time: new Date().toLocaleTimeString('fr-FR',{hour:'2-digit',minute:'2-digit'}),
    score: res.score, c: res.c, label: res.label, action: res.action,
    bd: res.bd, signals: d.signals, history: d.history, fp: res.fp,
    isReal: false
  };

  orders.unshift(o);

  // Save to Supabase if connected
  if (isLive) {
    try {
      await sbInsert('orders', {
        order_id: o.id,
        fingerprint_id: o.fp,
        buyer_name: o.name,
        amount: parseFloat(o.amount),
        platform: 'Shopify',
        country: d.signals.device.country,
        score: o.score,
        classification: o.c,
        label: o.label,
        action: o.action,
        signals: d.signals,
        breakdown: res.bd,
        is_real: false
      });
    } catch(e) { /* continue offline */ }
  }

  if (o.c==='r') {
    alerts.unshift(o);
    const ab=document.getElementById('alertBadge');
    ab.textContent=alerts.length;ab.classList.add('on');
  }

  const rc=orders.filter(x=>x.c==='r').length;
  document.getElementById('riskBadge').textContent=rc;
  document.getElementById('riskBadge').classList.toggle('on',rc>0);

  render(); showToast(o); selectOrder(o.id);
}

/* ══════════════════════════════════════
   RENDER
══════════════════════════════════════ */
function oHTML(o,i=0) {
  const tag = o.isReal
    ? `<span class="real-tag">RÉEL</span>`
    : `<span class="demo-tag">DÉMO</span>`;
  return `<div class="or ${o.id===selId?'on':''}" onclick="selectOrder('${o.id}')" style="animation-delay:${i*.03}s">
    <div class="av" style="background:${o.color}22;color:${o.color}">${o.initials}</div>
    <div class="oi">
      <div class="on2">${o.name} ${tag}</div>
      <div class="os"><span>${o.id}</span><span class="osp">·</span><span>${o.platform}</span><span class="osp">·</span><span>${o.time}</span></div>
    </div>
    <div style="display:flex;flex-direction:column;align-items:flex-end;gap:4px;flex-shrink:0">
      <div style="font-size:13px;font-weight:700">${o.amount}€</div>
      <div class="chip ${o.c}"><div class="cdot"></div>${o.score}·${o.label}</div>
    </div>
  </div>`;
}

function emEl(t,s) {
  return `<div class="empty"><div class="eico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/></svg></div><div class="et">${t}</div><div class="es">${s}</div></div>`;
}

function render() {
  const n=orders.length;
  document.getElementById('oCnt').textContent=n;
  document.getElementById('allCnt').textContent=n;
  document.getElementById('bsOrders').textContent=n;
  document.getElementById('bsProfiles').textContent=Object.keys(Engine.profiles).length;
  document.getElementById('bsRisk').textContent=alerts.length;

  const fm={'all':()=>true,'g':o=>o.c==='g','a':o=>o.c==='a','r':o=>o.c==='r'};
  document.getElementById('orderList').innerHTML=(curF==='all'?orders:orders.filter(fm[curF])).map(oHTML).join('')||emEl('Aucune commande','Cliquez sur "Simuler" ou installez Shopify pour les vraies commandes');
  document.getElementById('allList').innerHTML=(curF2==='all'?orders:orders.filter(fm[curF2])).map(oHTML).join('')||emEl('Aucune commande','');

  updateMetrics(); renderProfiles(); renderStats(); renderAlerts();
}

/* ── SELECT ── */
function selectOrder(id) {
  selId=id; render();
  const o=orders.find(x=>x.id===id); if(!o) return;
  const cm={g:'var(--green)',a:'var(--amber)',r:'var(--red)'};const c=cm[o.c];
  document.getElementById('rnum').textContent=o.score;
  document.getElementById('rnum').style.color=c;
  const rf=document.getElementById('rfg');
  rf.style.strokeDasharray='314';rf.style.strokeDashoffset=314-(o.score/100)*314;rf.style.stroke=c;
  document.getElementById('bname').textContent=o.name;
  document.getElementById('bfp').textContent='FP·'+o.fp;
  const ve=document.getElementById('verd');
  ve.className='verd '+o.c;
  const icos={g:`<svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>`,a:`<svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>`,r:`<svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/></svg>`};
  ve.innerHTML=(icos[o.c]||'')+' '+o.label; ve.style.opacity='1';

  document.getElementById('vnw').style.display='block';
  const p=Engine.profiles[o.fp];
  document.getElementById('vni').value=p?.note||'';

  const ap=document.getElementById('actpair');
  ap.style.opacity='1';ap.style.pointerEvents='all';
  document.getElementById('appBtn').onclick=async()=>{
    if(isLive&&o.dbId){try{await sbInsert('audit_log',{action:'Acceptée',detail:o.name+' · '+o.id,order_id:o.id});}catch(e){}}
    showMsg('Acceptée','Commande '+o.id+' validée','var(--green)');
  };
  document.getElementById('decBtn').onclick=async()=>{
    if(isLive&&o.dbId){try{await sbInsert('audit_log',{action:'Refusée',detail:o.name+' · '+o.id,order_id:o.id});}catch(e){}}
    showMsg('Refusée','Profil mis à jour · '+o.id,'var(--red)');
  };

  // Signals
  const sb=document.getElementById('sigBody');
  if(!o.bd||!o.bd.length){sb.innerHTML=`<div style="font-size:11px;color:var(--green);font-weight:700">✓ Aucun signal négatif</div>`;}
  else{sb.innerHTML=o.bd.map(b=>{const neg=b.p<0,bc=neg?(b.p<-10?'var(--red)':'var(--amber)'):'var(--green)';const pct=Math.min(Math.abs(b.p),30)/30*100;return`<div class="sig"><div class="sn">${b.l}</div><div class="st"><div class="sb" style="width:${pct}%;background:${bc}"></div></div><div class="sp2" style="color:${bc}">${neg?'':'+'}${Math.round(b.p)}</div></div>`;}).join('');}

  // History
  const hb=document.getElementById('histBody');
  const country=o.signals?.device?.country||'?';
  const vpn=o.signals?.device?.vpn;
  const dis=o.history?.disputes||0;
  hb.innerHTML=`
    <div class="hi"><div class="hic"><svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg></div><div><div class="ht">Score <strong>${o.score}/100</strong> — ${o.label}</div><div class="hd">${o.time}</div></div></div>
    <div class="hi"><div class="hic"><svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="5" y="2" width="14" height="20" rx="2"/></svg></div><div><div class="ht">${o.platform} · ${country}${vpn?' · <span style="color:var(--red);font-weight:700">VPN</span>':''}</div><div class="hd">Appareil</div></div></div>
    <div class="hi"><div class="hic"><svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/></svg></div><div><div class="ht">${dis>0?`<strong style="color:var(--red)">${dis} litige(s)</strong>`:'Aucun litige connu'}</div><div class="hd">Historique</div></div></div>
    ${o.isReal?`<div class="hi"><div class="hic" style="background:var(--green-bg)"><svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="var(--green)" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg></div><div><div class="ht" style="color:var(--green);font-weight:700">Vraie commande Shopify</div><div class="hd">Données réelles</div></div></div>`:''}
  `;
}

async function saveNote() {
  if(!selId)return;
  const o=orders.find(x=>x.id===selId);if(!o)return;
  const note=document.getElementById('vni').value.trim();
  const p=Engine.profiles[o.fp];if(p)p.note=note;
  if(isLive){try{await sbInsert('audit_log',{action:'Note enregistrée',detail:note,order_id:o.id});}catch(e){}}
  showMsg('Note enregistrée','','var(--blue)');
}

/* ── METRICS ── */
function updateMetrics() {
  const n=orders.length,g=orders.filter(o=>o.c==='g').length,a=orders.filter(o=>o.c==='a').length,r=orders.filter(o=>o.c==='r').length;
  const avg=n?Math.round(orders.reduce((s,o)=>s+o.score,0)/n):null;
  document.getElementById('mG').textContent=g;document.getElementById('mA').textContent=a;
  document.getElementById('mR').textContent=r;document.getElementById('mAvg').textContent=avg??'—';
}

/* ── PROFILES ── */
function renderProfiles() {
  const el=document.getElementById('pgrid');
  const ps=Object.entries(Engine.profiles);
  if(!ps.length){el.innerHTML=`<div style="grid-column:1/-1">${emEl('Aucun profil','Simulez ou recevez des commandes')}</div>`;return;}
  const cm={g:'var(--green)',a:'var(--amber)',r:'var(--red)'};
  el.innerHTML=ps.map(([fp,p],i)=>{
    const sc=p.lastScore||50,cl=sc>=70?'g':sc>=40?'a':'r',c=cm[cl];
    return`<div class="pcard an" style="animation-delay:${i*.04}s">
      <div class="pct"><div class="av" style="width:36px;height:36px;font-size:11px;font-weight:800;background:${p.color||'#888'}18;color:${p.color||'#888'}">${p.initials||'??'}</div><div><div class="pcn">${p.name||'Inconnu'}</div><div class="pcf">${fp}</div></div><div class="chip ${cl}" style="margin-left:auto">${sc}</div></div>
      <div class="pcst"><div class="pcs"><div class="pcsv">${p.orders||0}</div><div class="pcsl">Commandes</div></div><div class="pcs"><div class="pcsv" style="color:${c}">${sc}</div><div class="pcsl">Score</div></div><div class="pcs"><div class="pcsv">${p.history?.disputes||0}</div><div class="pcsl">Litiges</div></div></div>
      <div class="pcbr"><div class="pcbl">Fiabilité</div><div class="pcbt"><div class="pcbf" style="width:${sc}%;background:${c}"></div></div><div class="pcbn" style="color:${c}">${sc}</div></div>
    </div>`;
  }).join('');
}

/* ── STATS ── */
function renderStats() {
  if(!orders.length)return;
  const n=orders.length;
  const bar=(l,v,mx,col)=>`<div class="brow"><div class="brl">${l}</div><div class="brt"><div class="brf" style="width:${mx?v/mx*100:0}%;background:${col}"></div></div><div class="brv">${v}</div></div>`;
  const ranges=[['90–100',orders.filter(o=>o.score>=90).length],['70–89',orders.filter(o=>o.score>=70&&o.score<90).length],['40–69',orders.filter(o=>o.score>=40&&o.score<70).length],['0–39',orders.filter(o=>o.score<40).length]];
  document.getElementById('scoreChart').innerHTML=ranges.map(([l,v])=>bar(l,v,n,'var(--blue)')).join('');
  const ctry={};orders.forEach(o=>{const c=(o.signals?.device?.country)||'?';ctry[c]=(ctry[c]||0)+1;});
  const maxC=Math.max(...Object.values(ctry)||[1]);
  document.getElementById('countryChart').innerHTML=Object.entries(ctry).sort((a,b)=>b[1]-a[1]).map(([k,v])=>bar(k,v,maxC,'var(--amber)')).join('');
}

/* ── ALERTS ── */
function renderAlerts() {
  const el=document.getElementById('alertList');
  if(!alerts.length){el.innerHTML=emEl('Aucune alerte','Tout est calme');return;}
  el.innerHTML=alerts.map((o,i)=>`
    <div class="alrt an" style="animation-delay:${i*.04}s">
      <div class="alrt-ico"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/></svg></div>
      <div style="flex:1"><div class="alrt-n">${o.name} — Score ${o.score}/100</div><div class="alrt-d">${o.id} · ${o.platform}</div></div>
      <div class="alrt-t">${o.time}</div>
      <div class="alrt-tag">Risque</div>
    </div>`).join('');
}

/* ── FILTERS ── */
function setF(f,btn){curF=f;document.querySelectorAll('#view-dashboard .fb').forEach(b=>b.classList.remove('on'));btn.classList.add('on');render();}
function setF2(f,btn){curF2=f;document.querySelectorAll('#view-commandes .fb').forEach(b=>b.classList.remove('on'));btn.classList.add('on');render();}

/* ── NAV ── */
function goTo(view,btn) {
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('on'));
  document.querySelectorAll('.nbtn').forEach(b=>b.classList.remove('on'));
  document.getElementById('view-'+view).classList.add('on');
  if(btn)btn.classList.add('on');
}

/* ── SNIPPET BUILDER ── */
function buildSnippet() {
  const snippet = `<!-- Sellia Buyer Intelligence -->
<script>
(function(){
  var S = {
    url: '${SUPABASE_URL}',
    key: '${SUPABASE_KEY||'VOTRE_CLE_SUPABASE_ANON'}',
    fp: function() {
      return btoa([navigator.userAgent, navigator.language,
        screen.width+'x'+screen.height,
        new Date().getTimezoneOffset()].join('|')).slice(0,32);
    },
    score: function(order) {
      var sc = 100;
      if (order.vpn) sc -= 10;
      if (order.disputes > 0) sc -= order.disputes * 15;
      return Math.max(0, Math.min(100, sc));
    },
    save: function(data) {
      fetch(this.url+'/rest/v1/orders', {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json',
          'apikey': this.key,
          'Authorization': 'Bearer '+this.key,
          'Prefer': 'return=minimal'
        },
        body: JSON.stringify(data)
      }).catch(function(){});
    },
    init: function() {
      var self = this;
      var fp = this.fp();
      var sc = this.score({disputes:0});
      var cl = sc >= 70 ? 'g' : sc >= 40 ? 'a' : 'r';
      
      // Hook checkout form
      document.addEventListener('DOMContentLoaded', function() {
        var form = document.querySelector('form[action*="checkout"]');
        if (!form) return;
        form.addEventListener('submit', function() {
          self.save({
            order_id: 'SHO-' + Date.now().toString(36).toUpperCase(),
            fingerprint_id: fp,
            buyer_name: (document.querySelector('[name="checkout[shipping_address][first_name]"]') || {}).value || 'Client',
            platform: 'Shopify',
            score: sc,
            classification: cl,
            label: cl==='g'?'Acheteur fiable':cl==='a'?'À surveiller':'À risque',
            action: cl==='r'?'alert':cl==='a'?'flag':'allow',
            is_real: true,
            signals: {device:{ip:'',country:'',vpn:false,type:/Mobile/.test(navigator.userAgent)?'mobile':'desktop'},payment:{token:''},behavior:{secs:0},anomalies:{}}
          });
        }, {once: true});
      });
    }
  };
  S.init();
  window.Sellia = S;
})();
<\/script>`;
  const el = document.getElementById('snippetCode');
  if(el) el.textContent = snippet;
}

/* ── COPY ── */
function copySQL() {
  navigator.clipboard.writeText(document.getElementById('sqlCode').textContent)
    .then(()=>showMsg('SQL copié','Colle-le dans Supabase → SQL Editor → Run','var(--green)'));
}

function copySnippet() {
  navigator.clipboard.writeText(document.getElementById('snippetCode').textContent)
    .then(()=>showMsg('Snippet copié','Colle-le dans theme.liquid avant </head>','var(--green)'));
}

function copyWebhook() {
  navigator.clipboard.writeText(document.getElementById('webhookUrl').textContent.trim())
    .then(()=>showMsg('URL copiée','Colle-la dans le webhook Shopify','var(--green)'));
}

/* ── EXPORT ── */
function exportCSV() {
  const rows=[['ID','Acheteur','Montant','Score','Statut','Type','Heure']];
  orders.forEach(o=>rows.push([o.id,o.name,o.amount+'€',o.score,o.label,o.isReal?'Réel':'Démo',o.time]));
  const a=document.createElement('a');
  a.href='data:text/csv;charset=utf-8,'+encodeURIComponent(rows.map(r=>r.join(',')).join('\n'));
  a.download='sellia_commandes.csv';a.click();
  showMsg('CSV téléchargé','','var(--green)');
}

/* ── THEME ── */
let dark=false;
function toggleTheme() {
  dark=!dark;
  document.documentElement.setAttribute('data-theme',dark?'dark':'light');
  document.getElementById('thIco').innerHTML=dark?'<path d="M21 12.79A9 9 0 1111.21 3 7 7 0 0021 12.79z"/>':'<circle cx="12" cy="12" r="5"/><line x1="12" y1="1" x2="12" y2="3"/><line x1="12" y1="21" x2="12" y2="23"/><line x1="4.22" y1="4.22" x2="5.64" y2="5.64"/><line x1="18.36" y1="18.36" x2="19.78" y2="19.78"/><line x1="1" y1="12" x2="3" y2="12"/><line x1="21" y1="12" x2="23" y2="12"/><line x1="4.22" y1="19.78" x2="5.64" y2="18.36"/><line x1="18.36" y1="5.64" x2="19.78" y2="4.22"/>';
}

/* ── TOAST ── */
let tT;
function showToast(o) {
  const cm={g:'var(--green)',a:'var(--amber)',r:'var(--red)'};
  showMsg(o.isReal?'Vraie commande Shopify':'Commande simulée', o.name+' · '+o.amount+'€ · Score '+o.score, cm[o.c]);
}

function showMsg(title, desc, color) {
  document.getElementById('tlbl').textContent='Sellia';
  document.getElementById('ttit').textContent=title;
  document.getElementById('tdesc').textContent=desc;
  const t=document.getElementById('toast');
  t.style.borderLeftColor=color||'var(--blue)';
  t.classList.add('on');
  clearTimeout(tT);
  tT=setTimeout(()=>t.classList.remove('on'),3500);
}

/* ── BOOT ── */
window.addEventListener('load', () => {
  // Check saved credentials
  const savedUrl = localStorage.getItem('sellia_url');
  const savedKey = localStorage.getItem('sellia_key');
  if (savedUrl && savedKey) {
    document.getElementById('setupUrl').value = savedUrl;
    document.getElementById('setupKey').value = savedKey;
  }
  buildSnippet();
});
</script>

</body>
</html>