
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agrinho 2026 - Campo e Cidade Conectados</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#f4f8f4;
    color:#333;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#2e7d32,#66bb6a);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:15px;
}

header p{
    font-size:1.2rem;
    max-width:800px;
    margin:auto;
}

nav{
    background:#1b5e20;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:#c8e6c9;
}

section{
    padding:60px 10%;
}

.titulo{
    text-align:center;
    color:#2e7d32;
    margin-bottom:30px;
    font-size:2rem;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:15px;
    padding:25px;
    box-shadow:0 4px 12px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#2e7d32;
    margin-bottom:10px;
}

.banner{
    background:url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&w=1400&q=80');
    background-size:cover;
    background-position:center;
    height:350px;
    border-radius:20px;
}

.objetivos{
    background:#e8f5e9;
    border-radius:20px;
    padding:40px;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:25px;
}

.botao{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:white;
    color:#2e7d32;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
    transition:0.3s;
}

.botao:hover{
    background:#c8e6c9;
}

@media(max-width:768px){
    header h1{
        font-size:2.2rem;
    }
}
</style>
</head>
<body>

<header>
    <h1>🌱 Projeto Agrinho 2026</h1>
    <p>
        Promovendo a integração entre campo e cidade por meio da
        sustentabilidade, inovação tecnológica e valorização do
        trabalho agrícola.
    </p>

    <a href="#sobre" class="botao">Conheça o Projeto</a>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#temas">Temas</a>
    <a href="#objetivos">Objetivos</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre">
    <h2 class="titulo">Sobre o Agrinho 2026</h2>

    <div class="banner"></div>

    <p style="margin-top:30px; text-align:center;">
        O Programa Agrinho busca desenvolver a consciência cidadã,
        ambiental e tecnológica dos estudantes, incentivando ações
        que contribuam para um futuro mais sustentável e inovador.
        Em 2026, o foco está na conexão entre o campo e a cidade,
        destacando a importância da agricultura para a sociedade.
    </p>
</section>

<section id="temas">
    <h2 class="titulo">Temas em Destaque</h2>

    <div class="cards">

        <div class="card">
            <h3>🌾 Agricultura Sustentável</h3>
            <p>
                Práticas agrícolas que preservam os recursos naturais
                e garantem a produção de alimentos para as futuras gerações.
            </p>
        </div>

        <div class="card">
            <h3>🚜 Tecnologia no Campo</h3>
            <p>
                Uso de drones, sensores e inteligência artificial para
                aumentar a produtividade e reduzir impactos ambientais.
            </p>
        </div>

        <div class="card">
            <h3>🌎 Meio Ambiente</h3>
            <p>
                Conservação da biodiversidade, proteção das águas e
                incentivo ao desenvolvimento sustentável.
            </p>
        </div>

        <div class="card">
            <h3>🏙️ Campo e Cidade</h3>
            <p>
                Fortalecimento da relação entre produtores rurais e
                consumidores urbanos.
            </p>
        </div>

    </div>
</section>

<section id="objetivos">
    <div class="objetivos">
        <h2 class="titulo">Objetivos do Projeto</h2>

        <ul style="font-size:1.1rem;">
            <li>✔ Incentivar a educação ambiental.</li>
            <li>✔ Valorizar o produtor rural.</li>
            <li>✔ Promover a sustentabilidade.</li>
            <li>✔ Estimular a inovação tecnológica.</li>
            <li>✔ Desenvolver a cidadania e responsabilidade social.</li>
            <li>✔ Aproximar campo e cidade.</li>
        </ul>
    </div>
</section>

<section id="contato">
    <h2 class="titulo">Participação</h2>

    <p style="text-align:center;">
        Faça parte do Agrinho 2026 e contribua para um futuro mais
        sustentável, inovador e conectado.
    </p>

    <div style="text-align:center; margin-top:20px;">
        <a href="#" class="botao">Saiba Mais</a>
    </div>
</section>

<footer>
    <p>© 2026 Projeto Agrinho | Educação, Sustentabilidade e Inovação</p>
</footer>

</body>
</html>
