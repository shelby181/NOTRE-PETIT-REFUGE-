# NOTRE-PETIT-REFUGE-
Pour toi mon Cœur ❤🫂

<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Notre petit refuge ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #100b12;
    color: white;
    font-family: Georgia, serif;
    min-height: 100vh;
    overflow-x: hidden;
}

header {
    text-align: center;
    padding: 55px 15px 25px;
}

header h1 {
    color: #e9b8ce;
    font-size: 32px;
    margin-bottom: 15px;
}

header p {
    color: #d4c4ce;
    font-size: 15px;
}

.container {
    max-width: 650px;
    margin: auto;
    padding: 20px;
    text-align: center;
}

.card {
    background: linear-gradient(145deg, #261725, #17101b);
    border: 1px solid #a87991;
    border-radius: 20px;
    padding: 30px 20px;
    margin-top: 25px;
    box-shadow: 0 0 25px rgba(220, 140, 180, 0.12);
}

h2 {
    color: #edbfd4;
    margin-bottom: 20px;
}

.envelope {
    font-size: 95px;
    cursor: pointer;
    margin: 25px 0;
    transition: transform 0.5s;
    display: inline-block;
}

.envelope:hover {
    transform: scale(1.15) rotate(-8deg);
}

button {
    background: linear-gradient(135deg, #d58cac, #a85e85);
    color: white;
    border: none;
    padding: 14px 25px;
    border-radius: 30px;
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
    margin: 15px 5px;
}

button:hover {
    transform: scale(1.04);
}

#letter {
    display: none;
    background: #f8e8ef;
    color: #482b3c;
    padding: 25px 20px;
    border-radius: 15px;
    margin-top: 25px;
    line-height: 1.9;
    text-align: left;
    animation: openLetter 1s ease;
}

#letter h2 {
    color: #a34d77;
    text-align: center;
}

.signature {
    text-align: right;
    margin-top: 20px;
    font-weight: bold;
    color: #a34d77;
}

.secret {
    margin-top: 40px;
}

#secretMessage {
    display: none;
    color: #edbfd4;
    margin-top: 20px;
    line-height: 1.8;
    animation: openLetter 1s ease;
}

footer {
    text-align: center;
    padding: 35px 15px;
    color: #a99aa5;
    font-size: 13px;
}

.heart {
    position: fixed;
    bottom: -30px;
    color: #e9a6c4;
    font-size: 20px;
    animation: floatUp 7s linear infinite;
    pointer-events: none;
    z-index: -1;
}

@keyframes openLetter {
    from {
        opacity: 0;
        transform: translateY(25px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes floatUp {
    0% {
        transform: translateY(0) rotate(0deg);
        opacity: 0;
    }
    20% {
        opacity: 0.8;
    }
    100% {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}
</style>
</head>

<body>

<header>
    <h1>Notre petit refuge 💗</h1>
    <p>Un endroit où nos deux cœurs peuvent se retrouver.</p>
</header>

<div class="container">

    <div class="card">

        <h2>💌 Une lettre pour toi</h2>

        <p>
            J'ai gardé quelques mots quelque part...
            et j'aimerais que tu les découvres.
        </p>

        <div class="envelope" onclick="openLetter()">
            💌
        </div>

        <br>

        <button onclick="openLetter()">
            Ouvrir mon enveloppe ❤️
        </button>

        <div id="letter">

            <h2>À toi, mon amour ❤️</h2>

            <p>
                Je ne sais pas toujours trouver les mots
                parfaits pour expliquer ce que tu représentes
                pour moi.
            </p>

            <p>
                Mais je veux que tu saches une chose :
                ta présence dans ma vie est un cadeau
                que je ne prends pas pour acquis.
            </p>

            <p>
                Même lorsque tu n'est pas prêt de moi,
                tu gardes une place particulière dans mes pensées.
                J'aimerais toujours être là pour tes sourires,
                tes réussites, tes petits moments de joie
                et même tes journées difficiles.
            </p>

            <p>
                Je ne te promets pas une histoire parfaite,
                mais je souhaite une histoire sincère,
                construite avec de la patience,
                du respect et beaucoup d'amour.
            </p>

            <p>
                Et si je devais choisir encore une fois
                la personne avec qui continuer cette belle aventure,
                mon cœur saurait déjà où aller.
            </p>

            <p class="signature">
                Avec amour,<br>
                Ton Papi ❤️💋
            </p>

        </div>

    </div>

    <div class="card secret">

        <h2>🔐 Un petit secret</h2>

        <p>
            Il y a encore quelque chose que j'aimerais
            te faire découvrir...
        </p>

        <button onclick="showSecret()">
            Découvrir mon secret ✨
        </button>

        <div id="secretMessage">

            <h2>🥹❤️</h2>

            <p>
                Si tu savais combien de fois ton sourire
                traverse mes pensées...
                Tu es une personne précieuse pour moi.
                N'oublie jamais que tu as quelqu'un
                qui souhaite te voir heureuse.
            </p>

            <p>
                Bienvenue dans notre petit refuge,
                Manmi. 🫂💗
            </p>

        </div>

    </div>

</div>

<footer>
    <p>Un petit monde créé avec amour ❤️</p>
    <p>Notre petit refuge — Papi & Manmi 💍</p>
</footer>

<script>

function openLetter() {
    const letter = document.getElementById("letter");

    letter.style.display = "block";

    letter.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });
}

function showSecret() {
    const secret = document.getElementById("secretMessage");

    secret.style.display = "block";

    secret.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });
}

// Petits cœurs animés

function createHeart() {
    const heart = document.createElement("div");

    heart.className = "heart";
    heart.textContent = "♥";

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (5 + Math.random() * 5) + "s";

    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 10000);
}

setInterval(createHeart, 800);

</script>

</body>
</html>
