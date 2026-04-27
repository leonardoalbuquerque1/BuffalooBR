<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Buffaloobr Bot | Bot de Moderação pra Twitch e Kick</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Oxanium:wght@700;800&family=Inter:wght@400;600;700&display=swap');
  
  :root {
    --roxo: #9146FF; --preto: #0E0E10; --cinza: #18181B; 
    --branco: #EFEFF1; --verde: #00FF88;
  }
  
    * { margin: 0; padding: 0; box-sizing: border-box; }
  body { background: var(--preto); color: var(--branco); font-family: 'Inter', sans-serif; }
  
  .nav { background: var(--cinza); border-bottom: 2px solid var(--roxo); padding: 20px; }
  .nav-content { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; }
  .logo { font-family: 'Oxanium', sans-serif; font-size: 28px; font-weight: 800; background: linear-gradient(90deg, var(--branco), var(--roxo)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .btn { background: var(--roxo); color: var(--branco); text-decoration: none; padding: 12px 24px; border-radius: 10px; font-weight: 700; transition: 0.2s; }
  .btn:hover { background: #772CE8; transform: translateY(-2px); }
  
  .hero { max-width: 1200px; margin: 80px auto; padding: 0 20px; text-align: center; }
  .hero h1 { font-family: 'Oxanium', sans-serif; font-size: 56px; font-weight: 800; margin-bottom: 20px; }
  .hero h1 span { color: var(--roxo); }
  .hero p { font-size: 20px; opacity: 0.8; max-width: 700px; margin: 0 auto 40px auto; line-height: 1.6; }
  .btn-cta { background: var(--roxo); padding: 18px 40px; border-radius: 12px; font-size: 18px; display: inline-block; }
  
  .features { max-width: 1200px; margin: 100px auto; padding: 0 20px; display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; }
  .feature { background: var(--cinza); border: 2px solid #26262C; border-radius: 20px; padding: 35px; transition: 0.2s; }
  .feature:hover { border-color: var(--roxo); transform: translateY(-5px); }
  .feature-icon { font-size: 48px; margin-bottom: 15px; }
  .feature h3 { font-family: 'Oxanium', sans-serif; font-size: 24px; margin-bottom: 12px; }
  
  .comandos { max-width: 900px; margin: 80px auto; padding: 0 20px; }
  .comandos h2 { text-align: center; font-family: 'Oxanium'; font-size: 36px; margin-bottom: 40px; }
  .cmd-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; }
  .cmd { background: var(--cinza); padding: 15px; border-radius: 12px; border-left: 4px solid var(--roxo); }
  .cmd span { color: var(--verde); font-weight: 700; }
  
  @media (max-width: 768px) { .hero h1 { font-size: 36px; } }
</style>
</head>
<body>
  <nav class="nav">
    <div class="nav-content">
      <div class="logo">BUFFALOOBR BOT</div>
      <a href="#ativar" class="btn">Adicionar na Twitch</a>
    </div>
  </nav>

  <section class="hero">
    <h1>O bot da <span>Tropa Buffaloobr</span></h1>
    <p>Moderação, entretenimento e hype pra sua live na Twitch e Kick. Overlays insanos, comandos personalizados e gestão fácil do chat. Focado na resenha.</p>
    <a href="#ativar" class="btn btn-cta">Ativar na minha live</a>
  </section>

  <section class="features">
    <div class="feature">
      <div class="feature-icon">🎮</div>
      <h3>Overlay de Entretenimento</h3>
      <p>Alertas de follow, sub, raid com estilo Buffaloobr. Soundboard, roletas, metas e memes direto na tela pra deixar a live insana.</p>
    </div>
    <div class="feature">
      <div class="feature-icon">💬</div>
      <h3>Comandos de Chat</h3>
      <p>!pix, !discord, !social, !horario, !rank. Timer automático, respostas personalizadas e filtros anti-spam pra você não se estressar.</p>
    </div>
    <div class="feature">
      <div class="feature-icon">🛡️</div>
      <h3>Gestão de Comunidade</h3>
      <p>Sistema de pontos, sorteios, ranking de chat ativo, clipes automáticos e ban de palavra. Seus mods vão agradecer.</p>
    </div>
  </section>

  <section class="comandos" id="ativar">
    <h2>Comandos Padrão</h2>
    <div class="cmd-list">
      <div class="cmd"><span>!pix</span> - Mostra sua chave pix</div>
      <div class="cmd"><span>!discord</span> - Link do Discord da tropa</div>
      <div class="cmd"><span>!social</span> - Todas suas redes</div>
      <div class="cmd"><span>!horario</span> - Horário das lives</div>
      <div class="cmd"><span>!rank</span> - Ver top chat da live</div>
      <div class="cmd"><span>!clip</span> - Cria clip automático</div>
    </div>
  </section>
</body>
</html>
