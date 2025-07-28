<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Física Básica e Astrodinâmica: Uma Jornada pelo Sistema Solar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            position: relative;
        }
        .container {
            max-width: 960px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
            text-align: center;
            margin-bottom: 15px;
        }
        p {
            margin-bottom: 1em;
            text-align: justify;
        }
        .small-image-left {
            max-width: 120px;
            height: auto;
            float: left;
            margin-right: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
        }
        .small-image-right {
            max-width: 120px;
            height: auto;
            float: right;
            margin-left: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
        }
        .formula {
            font-family: 'Times New Roman', serif;
            font-size: 1.1em;
            text-align: center;
            margin: 15px 0;
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .formula span {
            display: block;
            margin-top: 5px;
            font-size: 0.9em;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 15px;
            border-top: 1px solid #ccc;
            font-size: 0.9em;
        }
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Física Básica e Astrodinâmica: Uma Jornada pelo Sistema Solar</h1>
            <p>Explorando conceitos fundamentais da física aplicados aos movimentos e características dos planetas.</p>
        </header>

        <main>
            <section class="clearfix">
                <h2>Mecânica: O Movimento dos Corpos</h2>
                <img src="newton_gravidade.jpg" alt="Isaac Newton e a Maçã" class="small-image-left">
                <h3>Força e Leis de Newton</h3>
                <p><strong>Força:</strong> Interação que pode alterar o estado de movimento ou a forma de um corpo.</p>
                <div class="formula">
                    $$F = m \cdot a$$
                    <span>Onde $F$ é a força, $m$ é a massa e $a$ é a aceleração.</span>
                </div>
                <p><strong>Exemplo Prático:</strong> A força que o Sol exerce sobre a Terra (gravidade) causa sua aceleração, mantendo-a em órbita.</p>
                <p><strong>Lei da Gravitação Universal:</strong> Força de atração entre dois corpos com massa.</p>
                <div class="formula">
                    $$F = G \frac{m_1 m_2}{r^2}$$
                    <span>Onde $G$ é a constante gravitacional, $m_1$ e $m_2$ são as massas dos corpos e $r$ é a distância entre eles.</span>
                </div>
                <p><strong>Exemplo Prático:</strong> A força gravitacional entre a Terra e a Lua é responsável pelas marés e pela órbita lunar.</p>
            </section>

            <section class="clearfix">
                <h2>Dinâmica de Órbitas: As Leis de Kepler</h2>
                <img src="kepler_orbita.jpg" alt="Ilustração de Órbita Elíptica" class="small-image-right">
                <h3>Primeira Lei (Órbitas Elípticas)</h3>
                <p><strong>Definição:</strong> Todos os planetas se movem em órbitas elípticas, com o Sol em um dos focos.</p>
                <p><strong>Exemplo Prático:</strong> A órbita de Marte é visivelmente mais elíptica que a da Terra.</p>

                <h3>Segunda Lei (Áreas Iguais em Tempos Iguais)</h3>
                <p><strong>Definição:</strong> O vetor posição de um planeta em relação ao Sol varre áreas iguais em intervalos de tempo iguais.</p>
                <p>Isso implica que os planetas se movem mais rápido quando estão mais próximos do Sol (no periélio) e mais devagar quando estão mais distantes (no afélio).</p>
                <p><strong>Exemplo Prático:</strong> A Terra se move mais rapidamente em sua órbita em janeiro (periélio) do que em julho (afélio).</p>

                <h3>Terceira Lei (Lei dos Períodos)</h3>
                <p><strong>Definição:</strong> O quadrado do período orbital ($T$) de um planeta é proporcional ao cubo do semieixo maior ($a$) de sua órbita.</p>
                <div class="formula">
                    $$\frac{T^2}{a^3} = k$$
                    <span>Onde $k$ é uma constante para todos os objetos orbitando o mesmo corpo central (ex: o Sol).</span>
                </div>
                <p><strong>Exemplo Prático:</strong> Netuno, estando muito mais distante do Sol (maior $a$), tem um período orbital ($T$) muito maior que o de Mercúrio.</p>
            </section>

            <section class="clearfix">
                <h2>Energia e Conservação</h2>
                <img src="energia_conservacao.jpg" alt="Diagrama de Energia Potencial e Cinética" class="small-image-left">
                <h3>Energia Cinética</h3>
                <p><strong>Definição:</strong> Energia associada ao movimento de um corpo.</p>
                <div class="formula">
                    $$E_k = \frac{1}{2}mv^2$$
                    <span>Onde $m$ é a massa e $v$ é a velocidade.</span>
                </div>
                <p><strong>Exemplo Prático:</strong> Um cometa se aproximando do Sol ganha energia cinética, aumentando sua velocidade.</p>

                <h3>Energia Potencial Gravitacional</h3>
                <p><strong>Definição:</strong> Energia armazenada em um corpo devido à sua posição em um campo gravitacional.</p>
                <div class="formula">
                    $$E_p = -\frac{GMm}{r}$$
                    <span>Onde $G$ é a constante gravitacional, $M$ e $m$ são as massas e $r$ é a distância.</span>
                </div>
                <p><strong>Exemplo Prático:</strong> Um satélite em órbita terrestre tem energia potencial gravitacional que varia com sua altitude.</p>

                <h3>Conservação da Energia Mecânica</h3>
                <p><strong>Definição:</strong> Em um sistema onde atuam apenas forças conservativas (como a gravitacional), a soma da energia cinética e potencial é constante.</p>
                <div class="formula">
                    $$E_{total} = E_k + E_p = \text{constante}$$
                </div>
                <p><strong>Exemplo Prático:</strong> A energia mecânica total de um planeta em sua órbita ao redor do Sol permanece constante, mesmo que sua velocidade e distância variem.</p>
            </section>

            <section class="clearfix">
                <h2>Momento Angular</h2>
                <img src="momento_angular.jpg" alt="Representação de Momento Angular" class="small-image-right">
                <h3>Conservação do Momento Angular</h3>
                <p><strong>Definição:</strong> Em um sistema isolado (sem torque externo), o momento angular total permanece constante.</p>
                <div class="formula">
                    $$L = I\omega$$
                    <span>Onde $L$ é o momento angular, $I$ é o momento de inércia e $\omega$ é a velocidade angular. Para um corpo pontual, $L = mvr$.</span>
                </div>
                <p><strong>Exemplo Prático:</strong> A conservação do momento angular explica por que a velocidade de rotação de um planeta é aproximadamente constante e por que os planetas aceleram quando se aproximam do Sol (diminuem $r$, aumentam $v$ para manter $mvr$ constante).</p>
            </section>
        </main>

        <footer>
            <p>&copy; 2025 Física & Astrodinâmica. Todos os direitos reservados.</p>
        </footer>
    </div>
</body>
</html>
