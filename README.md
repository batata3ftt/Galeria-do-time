```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>ETERNALS • Galeria do Time</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=Poppins:wght@500;600;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#04070d;
  --line:rgba(255,255,255,0.08);
  --text:#ffffff;
  --muted:#9fb0cf;
  --blue:#1e4fff;
  --blue2:#0f2ea3;
  --gold:#ffe08a;
  --gold2:#fff0b8;
  --shadow:0 20px 60px rgba(0,0,0,0.45);
}
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:Inter,sans-serif;color:var(--text);
  background:
    radial-gradient(circle at top left,rgba(30,79,255,0.20),transparent 25%),
    radial-gradient(circle at bottom right,rgba(255,224,138,0.07),transparent 20%),
    linear-gradient(180deg,#02040e 0%,#050a18 40%,#02040e 100%);
  overflow-x:hidden;
}
.bg{position:fixed;inset:0;overflow:hidden;pointer-events:none;z-index:-1;}
.blur1,.blur2{position:absolute;border-radius:999px;filter:blur(100px);opacity:.5;}
.blur1{width:340px;height:340px;background:rgba(30,79,255,0.28);top:-70px;left:-70px;}
.blur2{width:280px;height:280px;background:rgba(255,224,138,0.10);right:-80px;bottom:-80px;}
.container{width:min(1250px,calc(100% - 26px));margin:auto;padding:24px 0 40px;}
.panel{
  position:relative;overflow:hidden;border-radius:36px;
  border:1px solid var(--line);background:rgba(7,11,20,0.92);
  box-shadow:var(--shadow);padding:28px;margin-top:26px;
}
.panel::before{
  content:"";position:absolute;inset:0;
  background:linear-gradient(135deg,rgba(30,79,255,0.13),transparent 30%,transparent 70%,rgba(255,224,138,0.04));
  pointer-events:none;
}
.top{
  display:flex;justify-content:space-between;align-items:center;
  gap:16px;flex-wrap:wrap;position:relative;z-index:1;margin-bottom:20px;
}
.brand{display:flex;gap:18px;align-items:center;}
.logo{width:88px;height:88px;border-radius:24px;object-fit:cover;border:1px solid rgba(255,255,255,0.1);box-shadow:0 0 30px rgba(30,79,255,0.30);}
h1,h2,h3,.btn{font-family:Poppins,sans-serif;}
h1{font-size:clamp(2rem,4vw,3.2rem);letter-spacing:-0.05em;line-height:1;}
.badge{
  display:inline-flex;align-items:center;gap:8px;padding:8px 14px;border-radius:999px;
  background:rgba(30,79,255,0.14);border:1px solid rgba(30,79,255,0.28);
  color:#dce8ff;font-size:13px;font-weight:700;margin-bottom:12px;
}
.sub{color:var(--muted);margin-top:10px;line-height:1.7;max-width:760px;position:relative;z-index:1;}
.buttons{display:flex;gap:14px;flex-wrap:wrap;margin-top:24px;position:relative;z-index:1;}
.btn{
  display:inline-flex;text-decoration:none;align-items:center;justify-content:center;
  padding:14px 18px;border-radius:16px;font-weight:700;border:1px solid transparent;
  transition:.25s ease;color:#fff;
}
.btn:hover{transform:translateY(-2px);}
.btn-primary{background:linear-gradient(135deg,var(--blue),var(--blue2));box-shadow:0 12px 30px rgba(30,79,255,0.28);}
.moments{
  margin-top:28px;padding:28px;border-radius:36px;
  border:1px solid var(--line);background:rgba(7,11,20,0.92);
  box-shadow:var(--shadow);position:relative;overflow:hidden;
}
.moments::before{
  content:"";position:absolute;inset:0;
  background:linear-gradient(135deg,rgba(30,79,255,0.08),transparent 30%,transparent 70%,rgba(255,224,138,0.04));
}
.section-top{
  display:flex;justify-content:space-between;align-items:center;
  flex-wrap:wrap;gap:12px;margin-bottom:18px;position:relative;z-index:1;
}
.section-top p{color:var(--muted);}
.empty-box{
  position:relative;z-index:1;border-radius:28px;padding:40px 24px;
  border:1px dashed rgba(255,224,138,0.24);
  background:linear-gradient(180deg,rgba(255,224,138,0.05),rgba(30,79,255,0.03));
  text-align:center;color:var(--muted);line-height:1.8;
}
.empty-box-icon{font-size:2.2rem;display:block;margin-bottom:12px;}
.empty-box strong{display:block;font-family:Poppins,sans-serif;font-size:1.1rem;color:var(--gold2);margin-bottom:8px;}
.footer{margin-top:22px;text-align:center;color:var(--muted);}
@media(max-width:640px){
  .panel,.moments{padding:20px;border-radius:28px;}
  .logo{width:72px;height:72px;}
}
</style>
</head>
<body>
  <div class="bg">
    <div class="blur1"></div>
    <div class="blur2"></div>
  </div>
  <main class="container">

    <section class="panel">
      <div class="top">
        <div class="brand">
          <img class="logo" src="https://i.imgur.com/2JUG8yz.png" alt="Logo Impact Zero">
          <div>
            <div class="badge">📸 ETERNALS • GALERIA DO TIME</div>
            <h1>Galeria do Time</h1>
          </div>
        </div>
      </div>
      <p class="sub">
        Aqui ficarão os momentos do time, fotos especiais, conquistas e registros importantes.
      </p>
      <div class="buttons">
        <a class="btn btn-primary" href="index.html">Voltar ao Time</a>
      </div>
    </section>

    <section class="moments">
      <div class="section-top">
        <h2>🎞️ Momentos do Time</h2>
        <p>Em breve novas fotos</p>
      </div>
      <div class="empty-box">
        <span class="empty-box-icon">🖼️</span>
        <strong>Galeria em breve</strong>
        Nenhuma foto adicionada ainda.<br>
        Essa área está pronta para receber os momentos do ETERNALS.
      </div>
    </section>

    <div class="footer">✦ ETERNALS • Galeria do Time ✦</div>
  </main>
</body>
</html>

```