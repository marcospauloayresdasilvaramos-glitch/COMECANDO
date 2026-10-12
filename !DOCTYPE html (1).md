<!DOCTYPE html>

<html lang="pt-BR">

<head>

&#x20;   <meta charset="UTF-8">

&#x20;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&#x20;   <title>Mister Refrigeração - Especialistas em Goiânia</title>

&#x20;   <style>

&#x20;       /\* Reset básico e fontes \*/

&#x20;       \* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; }

&#x20;       body { background-color: #f4f7f6; color: #333; }

&#x20;       a { text-decoration: none; color: inherit; }



&#x20;       /\* Cabeçalho (Azul) \*/

&#x20;       header {

&#x20;           background-color: #1565C0; /\* Azul escuro similar ao original \*/

&#x20;           color: white;

&#x20;           text-align: center;

&#x20;           padding: 20px 0 10px 0;

&#x20;       }

&#x20;       header h1 { font-size: 28px; letter-spacing: 2px; margin-bottom: 5px; }

&#x20;       header p { font-size: 14px; letter-spacing: 4px; font-weight: 300; }

&#x20;       

&#x20;       /\* Menu de Navegação \*/

&#x20;       nav { margin-top: 20px; padding-bottom: 10px; }

&#x20;       nav a {

&#x20;           color: white;

&#x20;           margin: 0 15px;

&#x20;           font-weight: bold;

&#x20;           font-size: 16px;

&#x20;           padding: 8px 15px;

&#x20;           border-radius: 5px;

&#x20;           transition: background 0.3s;

&#x20;       }

&#x20;       nav a:hover, nav a.active { background-color: #42A5F5; }



&#x20;       /\* Banner Principal (Hero) \*/

&#x20;       .hero {

&#x20;           position: relative;

&#x20;           background-image: url('banner-compressor.jpg'); /\* Substitua pela sua imagem gerada \*/

&#x20;           background-size: cover;

&#x20;           background-position: center;

&#x20;           height: 500px;

&#x20;           display: flex;

&#x20;           flex-direction: column;

&#x20;           justify-content: center;

&#x20;           align-items: center;

&#x20;           text-align: center;

&#x20;           color: white;

&#x20;       }

&#x20;       /\* Overlay escuro para o texto ficar legível \*/

&#x20;       .hero::before {

&#x20;           content: '';

&#x20;           position: absolute;

&#x20;           top: 0; left: 0; right: 0; bottom: 0;

&#x20;           background: rgba(0, 0, 0, 0.5); /\* Escurece a imagem de fundo \*/

&#x20;       }

&#x20;       .hero-content { position: relative; z-index: 1; padding: 20px; }

&#x20;       .hero h2 { font-size: 36px; margin-bottom: 15px; line-height: 1.3; }

&#x20;       .hero p { font-size: 18px; margin-bottom: 30px; max-width: 700px; }



&#x20;       /\* Botão WhatsApp \*/

&#x20;       .btn-whatsapp {

&#x20;           display: inline-block;

&#x20;           background-color: #25D366; /\* Verde WhatsApp \*/

&#x20;           color: white;

&#x20;           padding: 15px 35px;

&#x20;           font-size: 20px;

&#x20;           font-weight: bold;

&#x20;           border-radius: 50px;

&#x20;           box-shadow: 0 4px 10px rgba(0,0,0,0.2);

&#x20;           transition: transform 0.2s, background 0.2s;

&#x20;       }

&#x20;       .btn-whatsapp:hover { background-color: #1EBE5D; transform: scale(1.05); }



&#x20;       /\* Seção de Serviços Rápida \*/

&#x20;       .services-section {

&#x20;           max-width: 800px;

&#x20;           margin: 40px auto;

&#x20;           padding: 0 20px;

&#x20;           text-align: center;

&#x20;       }

&#x20;       .services-section h2 { color: #1565C0; font-size: 32px; margin-bottom: 10px; }

&#x20;       .services-section p { color: #666; margin-bottom: 30px; font-size: 18px; }



&#x20;       .service-btn {

&#x20;           display: block;

&#x20;           background-color: #25D366;

&#x20;           color: white;

&#x20;           padding: 18px;

&#x20;           margin-bottom: 15px;

&#x20;           border-radius: 8px;

&#x20;           font-size: 18px;

&#x20;           font-weight: bold;

&#x20;           box-shadow: 0 3px 6px rgba(0,0,0,0.1);

&#x20;           transition: background 0.3s;

&#x20;           text-align: center;

&#x20;       }

&#x20;       .service-btn:hover { background-color: #1EBE5D; }



&#x20;       /\* Cards de Detalhes dos Serviços \*/

&#x20;       .details-section {

&#x20;           max-width: 1000px;

&#x20;           margin: 50px auto;

&#x20;           padding: 0 20px;

&#x20;           display: grid;

&#x20;           grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));

&#x20;           gap: 30px;

&#x20;       }

&#x20;       .card {

&#x20;           background: white;

&#x20;           padding: 30px;

&#x20;           border-radius: 12px;

&#x20;           box-shadow: 0 5px 15px rgba(0,0,0,0.05);

&#x20;           text-align: left;

&#x20;       }

&#x20;       .card h3 { color: #1565C0; font-size: 24px; margin: 15px 0 10px 0; }

&#x20;       .card p { color: #555; line-height: 1.6; font-size: 16px; }

&#x20;       .card .icon { font-size: 40px; }



&#x20;       /\* Rodapé \*/

&#x20;       footer {

&#x20;           background-color: #1565C0;

&#x20;           color: white;

&#x20;           text-align: center;

&#x20;           padding: 30px 20px;

&#x20;           margin-top: 50px;

&#x20;           font-size: 14px;

&#x20;       }

&#x20;       footer strong { font-size: 16px; }

&#x20;   </style>

</head>

<body>



&#x20;   <!-- Cabeçalho -->

&#x20;   <header>

&#x20;       <h1>MISTER REFRIGERAÇÃO</h1>

&#x20;       <p>R E F R I G E R A Ç Ã O</p>

&#x20;       <nav>

&#x20;           <a href="#" class="active">Início</a>

&#x20;           <a href="#servicos">Serviços</a>

&#x20;           <a href="#sobre">Sobre</a>

&#x20;           <a href="#contato">Contato</a>

&#x20;       </nav>

&#x20;   </header>



&#x20;   <!-- Banner Principal -->

&#x20;   <section class="hero">

&#x20;       <div class="hero-content">

&#x20;           <h2>Restaurando o frio,<br>renovando o conforto.</h2>

&#x20;           <p>Especialistas em Geladeiras, Freezers e Ar-Condicionado em Goiânia.</p>

&#x20;           <!-- Link do WhatsApp com o seu número -->

&#x20;           <a href="https://wa.me/5562992812135" target="\_blank" class="btn-whatsapp">

&#x20;               📲 Solicitar Orçamento

&#x20;           </a>

&#x20;       </div>

&#x20;   </section>



&#x20;   <!-- Serviços Rápidos (Botões) -->

&#x20;   <section id="servicos" class="services-section">

&#x20;       <h2>Qual o problema do seu equipamento?</h2>

&#x20;       <p>Selecione uma opção e fale conosco pelo WhatsApp.</p>

&#x20;       

&#x20;       <!-- Links com o número do WhatsApp pré-preenchido -->

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Gostaria%20de%20um%20orçamento%20para%20consertar%20minha%20geladeira." target="\_blank" class="service-btn">

&#x20;           📦 Consertar Geladeira

&#x20;       </a>

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Gostaria%20de%20um%20orçamento%20para%20consertar%20meu%20freezer." target="\_blank" class="service-btn">

&#x20;           ❄️ Consertar Freezer

&#x20;       </a>

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Gostaria%20de%20um%20orçamento%20para%20consertar%20meu%20ar-condicionado." target="\_blank" class="service-btn">

&#x20;           💨 Consertar Ar-Condicionado

&#x20;       </a>

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Preciso%20de%20um%20serviço%20de%20vazamento%20de%20gás." target="\_blank" class="service-btn">

&#x20;           🔧 Vazamento de Gás

&#x20;       </a>

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Preciso%20trocar%20o%20compressor." target="\_blank" class="service-btn">

&#x20;           ⚙️ Troca de Compressor

&#x20;       </a>

&#x20;       <a href="https://wa.me/5562992812135?text=Olá!%20Gostaria%20de%20agendar%20uma%20visita%20técnica." target="\_blank" class="service-btn">

&#x20;           📅 Agendar Visita Técnica

&#x20;       </a>

&#x20;   </section>



&#x20;   <!-- Detalhes dos Serviços -->

&#x20;   <section id="sobre" class="details-section">

&#x20;       <div class="card">

&#x20;           <div class="icon">❄️</div>

&#x20;           <h3>Conserto de Geladeiras</h3>

&#x20;           <p>Diagnóstico completo, troca de peças e reparos em todas as marcas.</p>

&#x20;       </div>

&#x20;       <div class="card">

&#x20;           <div class="icon">⚙️</div>

&#x20;           <h3>Troca de Compressor</h3>

&#x20;           <p>Serviço profissional com instalação e testes completos.</p>

&#x20;       </div>

&#x20;       <div class="card">

&#x20;           <div class="icon">🔧</div>

&#x20;           <h3>Recarga de Gás</h3>

&#x20;           <p>Recarga realizada após diagnóstico e correção do sistema.</p>

&#x20;       </div>

&#x20;   </section>



&#x20;   <!-- Rodapé -->

&#x20;   <footer id="contato">

&#x20;       <p><strong>Mister Refrigeração</strong></p>

&#x20;       <p>Atendimento em Goiânia e Região Metropolitana</p>

&#x20;       <p>📞 (62) 9 9281-2135</p>

&#x20;       <p style="margin-top: 15px; font-size: 12px; color: #a0c4e8;">\&copy; 2026 Mister Refrigeração. Todos os direitos reservados.</p>

&#x20;   </footer>



</body>

</html>

