# babache-a.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Élection de délégué - Albara pour 1G2</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #87CEEB, #FF69B4);
            color: #333;
        }
        header {
            background-color: #FF69B4;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: relative;
            overflow: hidden;
        }
        header::before, header::after {
            content: '🦄';
            font-size: 3rem;
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
        }
        header::before { left: 1rem; }
        header::after { right: 1rem; }
        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .serious {
            margin-bottom: 2rem;
        }
        .fun {
            background-color: #FF69B4;
            color: #fff;
            padding: 1rem;
            border-radius: 10px;
            text-align: center;
        }
        .rainbow {
            background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 5px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }
        .button:hover {
            transform: scale(1.1);
        }
        .dolphin, .unicorn {
            font-size: 2rem;
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body>
    <header>
        <h1 class="rainbow">Élection de délégué - Classe 1G2</h1>
    </header>
    <main>
        <section class="serious">
            <h2>Candidature d'Albara</h2>
            <p>Chers camarades de classe,</p>
            <p>Je me présente, Albara, et je sollicite votre confiance pour devenir le délégué de notre classe de 1G2. Je m'engage à représenter nos intérêts avec sérieux et détermination auprès de l'administration et des enseignants.</p>
            <p>Mes objectifs principaux seront :</p>
            <ul>
                <li>Améliorer la communication entre les élèves et les professeurs</li>
                <li>Organiser des événements pour renforcer la cohésion de classe</li>
                <li>Défendre vos droits et vos idées, nous sommes tous égaux, pas vrais Noah?</li>
            </ul>
        </section>
        <section class="fun">
            <h2 class="rainbow">Mais attendez, ce n'est pas tout !</h2>
            <p>Si vous votez pour moi, je promets solennellement de :</p>
            <ul>
                <li>Organiser une bataille de licornes géantes dans la cour de récré <span class="unicorn">🦄</span></li>
                <li>Remplacer la sonnerie par le cri du dauphin (I just wanna be part of your symphony) <span class="dolphin">🐬</span></li>
                <li>Convaincre la cantine de servir des pizzas arc-en-ciel tous les jours</li>
                <li>Instaurer le vendredi "tous en femboy" obligatoire pour TOUS(cadeau pour andry)</li>
                <li>Créer un club secret de lanceurs de paillettes professionnels</li>
            </ul>
            <p>Alors, vous voulez du sérieux ou du délire les djeuns ? Avec moi, vous aurez les deux !</p>
            <h3 class="rainbow">Votez Albara, le délégué qui déchire sa race !</h3>
            <button class="button" onclick="alert('Wesh, tu viens de t\'engager à voter pour moi !')">Voter pour Albara</button>
            <button class="button" onclick="document.body.style.transform = 'rotate(180deg)'">Retourner la page</button>
            <button class="button" onclick="this.innerHTML = '🦄'.repeat(10)">Licorniser</button>
        </section>
    </main>
    <script>
        document.querySelectorAll('.button').forEach(button => {
            button.addEventListener('mouseover', () => {
                button.style.backgroundColor = `rgb(${Math.random()*255},${Math.random()*255},${Math.random()*255})`;
            });
        });
    </script>
</body>
</html>
