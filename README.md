<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Avarin | Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background: linear-gradient(180deg, #020617, #0f172a);
    color: #e5e7eb;
    overflow-x: hidden;
}

/* NAVBAR */
nav {
    position: fixed;
    top: 0;
    width: 100%;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(2,6,23,0.85);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid rgba(255,255,255,0.05);
    z-index: 1000;
}

nav h1 {
    font-size: 1.4rem;
    font-weight: 900;
    background: linear-gradient(90deg,#38bdf8,#818cf8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

nav ul {
    display: flex;
    gap: 30px;
}

nav li {
    list-style: none;
}

nav a {
    font-weight: 500;
    opacity: 0.8;
    text-decoration: none;
}

nav a:hover {
    opacity: 1;
}

/* SECTIONS */
section {
    padding: 140px 8% 120px;
    scroll-margin-top: 90px;
}

h2 {
    font-size: 2.6rem;
    margin-bottom: 40px;
}

.gradient {
    background: linear-gradient(90deg,#38bdf8,#818cf8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

/* HERO */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
}

.hero-content {
    max-width: 850px;
}

.hero h2 {
    font-size: 3.5rem;
    line-height: 1.1;
}

.hero p {
    margin-top: 25px;
    font-size: 1.1rem;
    opacity: 0.85;
}

.hero-buttons {
    margin-top: 45px;
    display: flex;
    gap: 20px;
}

button {
    padding: 14px 30px;
    border-radius: 12px;
    font-weight: 600;
    cursor: pointer;
    border: none;
}

.primary {
    background: linear-gradient(90deg,#38bdf8,#818cf8);
    color: #020617;
}

.primary:hover {
    box-shadow: 0 10px 30px rgba(56,189,248,0.4);
}

.outline {
    background: transparent;
    color: white;
    border: 1px solid rgba(255,255,255,0.25);
}

/* GRID */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(260px,1fr));
    gap: 25px;
}

.card {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.06);
    border-radius: 18px;
    padding: 30px;
}

.card h3 {
    margin-bottom: 12px;
}

/* CONTACT */
.contact-box {
    max-width: 700px;
    margin: auto;
    text-align: center;
    background: rgba(255,255,255,0.04);
    border-radius: 20px;
    padding: 45px;
    border: 1px solid rgba(255,255,255,0.08);
}

.contact-box p {
    margin: 14px 0;
    font-size: 1.05rem;
}

/* FOOTER */
footer {
    padding: 30px;
    text-align: center;
    opacity: 0.6;
    font-size: 0.9rem;
}

/* MOBILE */
@media (max-width: 768px) {
    .hero h2 {
        font-size: 2.6rem;
    }
}
</style>
</head>
