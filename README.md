<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>SAVAR FACTORY WORK</title>
<style>
:root{--ink:#f8fafc;--neon:#00f58a}
*{box-sizing:border-box}
body{margin:0;font-family:Arial,"Noto Sans Bengali",sans-serif;background:#020b0a;color:#f8fafc}
header{background:linear-gradient(120deg,#031b13,#002d20);color:#fff;padding:11px 15px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:5;border-bottom:1px solid #00df83}
header h2{font-size:16px;margin:0;letter-spacing:.4px}
#adminBtn{border:2px solid #facc15;background:#071c15;color:#facc15;border-radius:50%;width:40px;height:40px;font-size:20px;font-weight:900}
main{max-width:560px;margin:auto;padding:10px 10px 88px}
.card{background:#fff;color:#172033;border-radius:17px;padding:16px;margin:12px 0;box-shadow:0 5px 18px #0006;border:1px solid #dbeafe}
h3{margin:0 0 13px;color:#253b76}.muted{color:#64748b;font-size:13px}
input,select,textarea,button{font:inherit}input,select,textarea{width:100%;padding:11px;border:1px solid #cbd5e1;border-radius:10px;background:#fbfdff;margin:5px 0 10px}label{font-size:13px;font-weight:bold;color:#334155}
button,.btn{border:0;border-radius:10px;padding:11px 15px;background:linear-gradient(100deg,#2563eb,#7541c8);color:white;font-weight:bold;cursor:pointer}button.secondary{background:#e8efff;color:#24438c}button.danger{background:#dc3545}.full{width:100%}
#homePage{background:radial-gradient(ellipse at top,#063b25 0%,#00110d 48%,#000 100%);padding:12px 9px 18px;border-radius:22px;overflow:hidden;min-height:0 !important;height:auto !important}
.brand-head{display:flex;align-items:center;gap:12px;padding:8px 7px 17px;position:relative}
.factory-mark{font-size:54px;line-height:1;color:#ffe000;filter:drop-shadow(0 0 8px #c8ff00)}
.brand-title{font-size:27px;line-height:1.12;font-weight:900;color:#fff;text-shadow:0 2px 8px #000}
.brand-sub{color:#ffe000;font-weight:800;font-size:15px;margin-top:7px}
.brand-admin{margin-left:auto;display:flex;flex-direction:column;align-items:center;gap:3px}
.brand-admin button{border:2px solid #facc15;color:#ffdf00;background:#06130e;border-radius:50%;width:55px;height:55px;font-size:28px;padding:0;box-shadow:0 0 12px #e6d00055}
.brand-admin small{border:1px solid #8b7a13;border-radius:18px;padding:3px 8px;color:#fff;font-size:11px}
.profile-strip{display:grid;grid-template-columns:1fr 130px;gap:9px;margin:4px 0 17px}
.user-panel,.date-panel{background:linear-gradient(110deg,#03182b,#061e35);border:2px solid #087bd7;border-radius:20px;min-height:118px;display:flex;align-items:center;padding:10px;box-shadow:0 0 14px #007bff33}
.user-panel{gap:10px;min-width:0}.avatar{width:82px;height:82px;border-radius:50%;border:4px solid #dfff00;background:linear-gradient(135deg,#214d69,#0a1725);display:flex;align-items:center;justify-content:center;font-size:35px;flex-shrink:0;overflow:hidden}
.avatar img{width:100%;height:100%;object-fit:cover}
.user-meta{font-size:16px;font-weight:800;min-width:0;overflow-wrap:anywhere}.user-meta small{display:block;font-size:14px;font-weight:600;margin-top:5px}
.active-dot{color:#22f65d;font-size:14px;margin-top:7px}.date-panel{border-color:#00e6ba;background:linear-gradient(140deg,#003c36,#005b48);justify-content:center;gap:8px;color:#fff;font-weight:800;font-size:16px;text-align:center}
.date-panel span{font-size:28px}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px}
.tile{min-height:116px;border:2px solid transparent;border-radius:20px;color:white;font-weight:900;font-size:16px;box-shadow:0 5px 14px #0008,inset 0 0 10px #ffffff20;padding:10px 5px;text-shadow:0 1px 3px #0008;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:7px;line-height:1.25}
.tile span{display:block;font-size:35px;margin:0;line-height:1}
.t1{background:linear-gradient(145deg,#00d900,#008c12);border-color:#54ff19;box-shadow:0 0 13px #39ff00aa,inset 0 0 13px #fff3}
.t2{background:linear-gradient(145deg,#087bff,#0038b7);border-color:#00aaff;box-shadow:0 0 13px #008dffaa,inset 0 0 13px #fff3}
.t3{background:linear-gradient(145deg,#ff9e00,#e65b00);border-color:#ffbd32;box-shadow:0 0 13px #ff8a00aa,inset 0 0 13px #fff3}
.t4{background:linear-gradient(145deg,#9200ff,#5100bd);border-color:#d000ff;box-shadow:0 0 13px #a000ffaa,inset 0 0 13px #fff3}
.t5{background:linear-gradient(145deg,#00a92b,#006c20);border-color:#00f52c;box-shadow:0 0 13px #00ed35aa,inset 0 0 13px #fff3}
.t6{background:linear-gradient(145deg,#075dff,#0029a5);border-color:#1688ff;box-shadow:0 0 13px #006effaa,inset 0 0 13px #fff3}
.t7{background:linear-gradient(145deg,#ff1d27,#bd0012);border-color:#ff4b4b;box-shadow:0 0 13px #ff002baa,inset 0 0 13px #fff3}
.t8{background:linear-gradient(145deg,#00c82b,#008318);border-color:#35ff28;box-shadow:0 0 13px #00ed35aa,inset 0 0 13px #fff3}
.t9{background:linear-gradient(145deg,#9b00ed,#5100a8);border-color:#db36ff;box-shadow:0 0 13px #a000ffaa,inset 0 0 13px #fff3}
.hidden{display:none!important}.row{display:flex;gap:8px;align-items:center}.row>*{flex:1}.tablewrap{overflow:auto}table{width:100%;border-collapse:collapse;font-size:13px;min-width:320px}th,td{padding:9px;border-bottom:1px solid #e5e7eb;text-align:left}th{background:#eef2ff;color:#263b78}.pill{padding:4px 8px;border-radius:20px;font-size:12px;font-weight:bold}.present{background:#d1fae5;color:#047857}.absent{background:#fee2e2;color:#b91c1c}.leave{background:#fef3c7;color:#92400e}
.calendar{display:grid;grid-template-columns:repeat(7,1fr);gap:5px}.day{background:#f1f5f9;border-radius:8px;text-align:center;padding:9px 2px;font-size:12px;min-height:45px}.day.present{background:#bbf7d0}.day.absent{background:#fecaca}.day.leave{background:#fde68a}
nav{position:fixed;bottom:0;left:0;right:0;background:#020c0a;border:1px solid #00d878;box-shadow:0 -3px 18px #00e88733;display:flex;justify-content:space-around;padding:8px 3px calc(8px + env(safe-area-inset-bottom));z-index:8;border-radius:18px 18px 0 0}
nav button{background:transparent;color:#f8fafc;padding:7px 12px;font-size:12px}nav button b{display:block;font-size:23px;color:#00f58a}
.auth{max-width:440px;margin:5vh auto;background:transparent!important;border:0!important;box-shadow:none!important;padding:0!important;color:#fff}
.auth-shell{width:100%;background:linear-gradient(145deg,#062b20,#03130f);border:1px solid #00e88a;border-radius:24px;padding:23px 20px;box-shadow:0 0 35px #00f58a33;text-align:left;animation:adminPop .25s ease}
.auth-brand-icon{width:76px;height:76px;margin:0 auto 13px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:39px;background:#06452e;border:2px solid #00f58a;box-shadow:0 0 20px #00f58a55}
.auth h1{text-align:center;color:#00f58a;font-size:22px;margin:5px 0 4px;text-shadow:0 0 10px #00f58a44}
.auth-subtitle{text-align:center;color:#b7d9ca;font-size:13px;margin:0 0 22px}
.auth h3{color:#00f58a;font-size:18px;margin:0 0 17px;text-align:center}
.auth label{display:block;color:#d5eee4;font-size:13px;margin-top:5px}
.auth input,.auth select{background:#f8fffb;color:#10251b;border:1px solid #74cba5;border-radius:12px;padding:13px;margin:6px 0 12px}
.auth input:focus,.auth select:focus{outline:2px solid #00e88a;border-color:#00e88a}
.auth button.full{background:linear-gradient(100deg,#00a96b,#00d987);color:#002719;border:1px solid #59ffc0;border-radius:12px;padding:13px;font-weight:900;box-shadow:0 5px 16px #00e88733;margin-top:7px}
.auth .muted{text-align:center;color:#b7d9ca;margin:17px 0 0;font-size:13px}
.auth a{color:#00f58a;font-weight:800;text-decoration:none}
.contactline{display:grid;grid-template-columns:1fr 1fr auto;gap:7px;align-items:center;padding:8px 0;border-bottom:1px solid #edf0f5;font-size:13px}.contactline a{background:#0d9b68;color:white;text-decoration:none;padding:8px 11px;border-radius:8px}
.notice{background:#fff7ed;border-left:4px solid #f59e0b;padding:12px;border-radius:9px;font-size:13px}
@media(max-width:520px){main{padding:7px 7px 85px}.brand-title{font-size:23px}.factory-mark{font-size:45px}.profile-strip{grid-template-columns:minmax(0,1fr) 112px;gap:7px}.user-panel,.date-panel{min-height:104px;padding:7px}.avatar{width:65px;height:65px}.user-meta{font-size:13px}.user-meta small{font-size:12px}.date-panel{font-size:14px}.tile{font-size:13px;min-height:104px;border-radius:17px}.tile span{font-size:31px}.grid{gap:8px}}
@media(max-width:360px){.brand-title{font-size:20px}.profile-strip{grid-template-columns:minmax(0,1fr) 100px}.avatar{width:55px;height:55px}.tile{font-size:11px;min-height:95px}}
body.app-open>header{display:none}
body.home-open main{padding-bottom:8px!important}
body.admin-open main{padding-bottom:18px!important}
.admin-dashboard{background:linear-gradient(145deg,#041c16,#00100c);color:#fff;border:1px solid #00d878;border-radius:20px;padding:16px;margin:8px 0;box-shadow:0 0 18px #00e88722}
.admin-top{display:flex;align-items:center;justify-content:space-between;gap:10px;margin-bottom:16px}
.admin-top h2{font-size:21px;color:#00f58a;margin:0}
.admin-top small{color:#b5d9ca}
.admin-stats{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px;margin-bottom:18px}
.admin-stat{background:linear-gradient(135deg,#073c2a,#092b48);border:1px solid #00c879;border-radius:15px;padding:14px;text-align:center}
.admin-stat b{display:block;font-size:26px;color:#00f58a;margin-top:5px}
.admin-stat span{font-size:12px;color:#d5eee4}
.admin-dashboard h3{color:#00f58a;margin:12px 0}
.admin-worker{display:flex;align-items:center;gap:9px;background:#f8fafc;color:#172033;padding:10px;border-radius:12px;margin:8px 0}
.admin-worker-info{flex:1;min-width:0;font-size:13px;overflow-wrap:anywhere}
.admin-worker-info small{display:block;color:#64748b;margin-top:4px}
.admin-worker button{padding:8px 10px;font-size:12px}
.admin-actions{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin-top:15px}
.admin-actions button{font-size:13px}

/* Home screen: remove viewport-sized empty area below the dashboard tiles */
#appView{height:auto!important;min-height:0!important}
#homePage{
  min-height:unset!important;
  height:auto!important;
  block-size:fit-content!important;
  padding-bottom:4px!important;
  margin-bottom:0!important;
 }

/* PREMIUM ADMIN LOGIN */
.admin-modal{position:fixed;inset:0;background:rgba(0,0,0,.82);backdrop-filter:blur(8px);display:flex;align-items:center;justify-content:center;z-index:9999;padding:20px}
.admin-login-box{width:100%;max-width:360px;background:linear-gradient(145deg,#062b20,#03130f);border:1px solid #00e88a;border-radius:24px;padding:25px 22px;box-shadow:0 0 35px #00f58a44;text-align:center;animation:adminPop .25s ease}
@keyframes adminPop{from{transform:scale(.85);opacity:0}to{transform:scale(1);opacity:1}}
.admin-lock{width:75px;height:75px;margin:0 auto 15px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:38px;background:#06452e;border:2px solid #00f58a;box-shadow:0 0 20px #00f58a55}
.admin-login-box h2{color:#00f58a;margin:8px 0;font-size:23px}
.admin-login-box p{color:#b7d9ca;font-size:13px;margin-bottom:20px}
.admin-password-wrap{position:relative}
.admin-password-wrap input{background:#fff;color:#111;padding:14px;padding-right:48px;border-radius:12px}
.admin-password-wrap span{position:absolute;right:14px;top:17px;font-size:20px;cursor:pointer}
.admin-error{color:#ff6565;font-size:13px;margin:5px 0 12px;min-height:18px}
.admin-login-box button{width:100%;margin-top:8px}
.admin-cancel{background:#263c35;color:#fff}


/* PREMIUM GREEN GLASS THEME — visual styling only; app logic and markup remain unchanged */
:root{--theme-green:#00f58a;--theme-mint:#b7d9ca;--theme-panel:#062b20;--theme-deep:#03130f;--theme-line:#087b55}
.page.card:not(#homePage){
 background:linear-gradient(145deg,rgba(6,43,32,.98),rgba(2,18,14,.99))!important;
 color:#f4fff9!important;border:1px solid #00c879!important;border-radius:22px!important;
 box-shadow:0 8px 28px #0008,0 0 20px #00e88720!important;padding:19px!important;
}
.page.card h3,.page.card h2{color:var(--theme-green)!important;text-shadow:0 0 12px #00f58a22}
.page.card p,.page.card .muted{color:#c0d9ce!important}
.page.card label{color:#d5eee4!important}
.page.card input,.page.card select,.page.card textarea{
 background:#f5fff9!important;color:#10251b!important;border:1px solid #65bd98!important;
 border-radius:12px!important;padding:12px!important;box-shadow:inset 0 1px 3px #001b1030;
}
.page.card input:focus,.page.card select:focus,.page.card textarea:focus{outline:2px solid #00e88a!important;border-color:#00e88a!important}
.page.card input:disabled{background:#dcebe3!important;color:#52665c!important}
.page.card button:not(.tile),.page.card .btn{
 background:linear-gradient(110deg,#008e5a,#00d987)!important;color:#002719!important;
 border:1px solid #56f6b5!important;border-radius:12px!important;font-weight:900!important;
 box-shadow:0 5px 15px #00e88725!important;
}
.page.card button.secondary{background:linear-gradient(110deg,#174d3b,#236b50)!important;color:#eafff4!important;border-color:#3d9d76!important}
.page.card button.danger{background:linear-gradient(110deg,#a82e3d,#e34a55)!important;color:#fff!important;border-color:#ff8c91!important}
.page.card .contactline{color:#eafff4!important;border-bottom:1px solid #1d5943!important;padding:11px 2px}
.page.card .contactline a{background:linear-gradient(110deg,#008e5a,#00d987)!important;color:#002719!important;font-weight:900}
.page.card .notice{background:linear-gradient(120deg,#173d2d,#23472f)!important;color:#eaffd5!important;border-left:4px solid #b7ef62!important;border-radius:12px!important}
.page.card .tablewrap{border:1px solid #176044;border-radius:12px;overflow:auto}
.page.card table{color:#eafff4!important}
.page.card th{background:#0b4a34!important;color:#9dffd0!important;border-bottom:1px solid #23845c!important}
.page.card td{border-bottom:1px solid #194b39!important;color:#e1f4e9!important}
.page.card .day{background:linear-gradient(145deg,#123c2d,#0b2a20)!important;color:#eafff4!important;border:1px solid #236348!important;border-radius:9px}
.page.card .day.present{background:#145b3b!important;color:#baffd8!important;border-color:#36d88b!important}
.page.card .day.absent{background:#632b32!important;color:#ffd5d8!important;border-color:#e56a75!important}
.page.card .day.leave{background:#65501d!important;color:#fff0b8!important;border-color:#d9b84d!important}
.admin-worker{background:linear-gradient(120deg,#0b3a2a,#102d3b)!important;color:#effff6!important;border:1px solid #16845a!important;box-shadow:0 4px 12px #0004}
.admin-worker-info small{color:#b7d9ca!important}
.admin-worker button{background:linear-gradient(110deg,#008e5a,#00d987)!important;color:#002719!important}
#otList p{background:#0b3a2a;border:1px solid #176044;border-radius:10px;padding:10px;color:#eafff4}
@media(max-width:520px){.page.card:not(#homePage){padding:15px!important;border-radius:19px!important}}


/* PREMIUM HOME PAGE FINISH — CSS only; no app logic or functionality changed */
#homePage{
  position:relative!important;
  isolation:isolate;
  background:
    radial-gradient(ellipse at 50% -8%,rgba(0,245,138,.20),transparent 42%),
    radial-gradient(circle at 100% 48%,rgba(0,126,86,.16),transparent 32%),
    linear-gradient(155deg,#06251b 0%,#031710 48%,#010907 100%)!important;
  border:1px solid rgba(0,245,138,.32)!important;
  border-radius:26px!important;
  padding:15px 11px 13px!important;
  box-shadow:0 12px 32px #0009,inset 0 1px 0 #baffdf18,0 0 24px #00e88718!important;
}
#homePage .brand-head{
  padding:9px 8px 19px!important;
  margin-bottom:7px;
  border-bottom:1px solid rgba(0,245,138,.22);
}
#homePage .factory-mark{
  filter:drop-shadow(0 0 8px #00f58a88)!important;
}
#homePage .brand-title{
  letter-spacing:.7px!important;
  text-shadow:0 2px 4px #000,0 0 18px #00f58a38!important;
}
#homePage .brand-sub{
  display:inline-block;
  padding:5px 10px;
  border:1px solid #00b87566;
  border-radius:20px;
  background:linear-gradient(90deg,#06452e99,#06332366);
  color:#aaffd5!important;
  font-size:11px!important;
  letter-spacing:.7px;
}
#homePage .brand-admin button{
  background:linear-gradient(145deg,#0b5439,#031a12)!important;
  border:1px solid #00f58a!important;
  color:#baffdc!important;
  box-shadow:0 0 0 4px #00f58a12,0 0 19px #00f58a55!important;
}
#homePage .brand-admin small{
  background:#062b20!important;
  border-color:#16845a!important;
  color:#baffdc!important;
  letter-spacing:.4px;
}
#homePage .profile-strip{gap:10px!important;margin:7px 0 18px!important}
#homePage .user-panel,#homePage .date-panel{
  background:linear-gradient(135deg,#0b3b2a,#092b25 58%,#08253a)!important;
  border:1px solid #159b68!important;
  border-radius:19px!important;
  box-shadow:0 7px 18px #0005,inset 0 1px 0 #ffffff18,0 0 13px #00d87818!important;
}
#homePage .avatar{
  border:3px solid #00f5a0!important;
  background:linear-gradient(145deg,#17664a,#09271d)!important;
  box-shadow:0 0 0 4px #00f58a16,0 0 16px #00f58a33!important;
}
#homePage .user-meta{color:#f2fff8!important}
#homePage .user-meta small{color:#b7d9ca!important}
#homePage .active-dot{color:#75ffb7!important;text-shadow:0 0 9px #00f58a66}
#homePage .date-panel{
  background:linear-gradient(145deg,#07513b,#063a32)!important;
  border-color:#00d995!important;
  color:#dffff0!important;
}
#homePage .date-panel span{color:#83ffc2;text-shadow:0 0 12px #00f58a77}
#homePage .grid{gap:10px!important}
#homePage .tile{
  position:relative;
  overflow:hidden;
  min-height:116px!important;
  border:1px solid rgba(118,255,195,.62)!important;
  border-radius:19px!important;
  background:linear-gradient(145deg,#126746 0%,#08432f 55%,#06271d 100%)!important;
  color:#f1fff8!important;
  box-shadow:0 7px 17px #0007,inset 0 1px 0 #ffffff30,inset 0 -13px 24px #001c123d!important;
  text-shadow:0 1px 4px #00180f!important;
  transition:transform .16s ease,box-shadow .16s ease;
}
#homePage .tile:before{
  content:"";
  position:absolute;
  width:90px;height:90px;
  right:-36px;top:-43px;
  border-radius:50%;
  background:rgba(173,255,215,.10);
  pointer-events:none;
}
#homePage .tile:active{transform:scale(.97);box-shadow:0 3px 9px #0008,inset 0 1px 0 #ffffff25!important}
#homePage .tile span{
  width:49px;height:49px;
  display:flex!important;align-items:center;justify-content:center;
  border-radius:15px;
  background:linear-gradient(145deg,#d5ffeb20,#00f58a12);
  border:1px solid #aaffd533;
  font-size:30px!important;
  filter:drop-shadow(0 2px 4px #00180f88);
}
#homePage .tile.t1,#homePage .tile.t2,#homePage .tile.t3,
#homePage .tile.t4,#homePage .tile.t5,#homePage .tile.t6,
#homePage .tile.t7,#homePage .tile.t8,#homePage .tile.t9{
  background:linear-gradient(145deg,#126746 0%,#08432f 55%,#06271d 100%)!important;
  border-color:#32c98c!important;
  box-shadow:0 7px 17px #0007,inset 0 1px 0 #ffffff30,inset 0 -13px 24px #001c123d!important;
}
@media(max-width:520px){
 #homePage{padding:12px 9px 12px!important;border-radius:22px!important}
 #homePage .grid{gap:8px!important}
 #homePage .tile{min-height:106px!important;border-radius:17px!important}
 #homePage .tile span{width:43px;height:43px;font-size:27px!important;border-radius:13px}
}


/* ALTERNATE PREMIUM HOME STYLE — CSS only; all app functions remain unchanged */
#homePage{
  background:
    linear-gradient(rgba(0,245,138,.035) 1px,transparent 1px),
    linear-gradient(90deg,rgba(0,245,138,.035) 1px,transparent 1px),
    radial-gradient(ellipse at 50% 0%,#0b4933 0%,#06271d 38%,#020d09 100%)!important;
  background-size:24px 24px,24px 24px,auto!important;
  border:1px solid #38d99a!important;
  border-radius:28px!important;
  box-shadow:0 16px 38px #000a,inset 0 1px 0 #d6ffea22,0 0 28px #00f58a20!important;
  padding:16px 12px 14px!important;
}
