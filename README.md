<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Voltage Vault | Custom Car Audio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#0a0a0a;
    color:white;
}

header{
    position:fixed;
    width:100%;
    top:0;
    background:rgba(0,0,0,.9);
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    border-bottom:2px solid #ff0000;
    z-index:1000;
}

.logo{
    color:#ff0000;
    font-size:2rem;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:#ff0000;
}

.hero{
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    background:
    linear-gradient(rgba(0,0,0,.75), rgba(0,0,0,.75)),
    url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=1600');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:800px;
    padding:20px;
}

.hero h1{
    font-size:4rem;
    color:#ff0000;
    margin-bottom:15px;
}

.hero h2{
    font-size:2rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
    color:#ddd;
    line-height:1.6;
}

.btn{
    display:inline-block;
    margin:15px;
    padding:15px 30px;
    background:#ff0000;
    color:white;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.05);
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    color:#ff0000;
    font-size:2.5rem;
    margin-bottom:40px;
}

.about{
    text-align:center;
    max-width:900px;
    margin:auto;
    line-height:1.8;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#161616;
    padding:30px;
    border-radius:10px;
    border:1px solid #333;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    border-color:#ff0000;
}

.card h3{
    color:#ff0000;
    margin-bottom:10px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:10px;
}

.reviews{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.review{
    background:#161616;
    padding:25px;
    border-radius:10px;
}

.contact{
    max-width:700px;
    margin:auto;
}

.contact input,
.contact textarea{
    width:100%;
    padding:15px;
    margin-bottom:15px;
    background:#161616;
    border:1px solid #333;
    color:white;
    border-radius:5px;
}

.contact button{
    width:100%;
    padding:15px;
    border:none;
    background:#ff0000;
    color:white;
    font-size:1rem;
    cursor:pointer;
}

footer{
    text-align:center;
    padding:30px;
    border-top:1px solid #222;
    color:#888;
}

@media(max-width:768px){
    .hero h1{
        font-size:2.8rem;
    }

    .hero h2{
        font-size:1.4rem;
    }

    nav{
        display:none;
    }
}
</style>
</head>
<body>

<header>
    <div class="logo">⚡ VOLTAGE VAULT</div>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#builds">Builds</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>VOLTAGE VAULT</h1>
        <h2>Power. Precision. Performance.</h2>

        <p>
            Professional car audio systems, custom enclosures,
            amplifier installs, electrical upgrades, and
            competition-ready bass builds.
        </p>

        <a href="#contact" class="btn">Get A Quote</a>
        <a href="#services" class="btn">Our Services</a>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Us</h2>

    <div class="about">
        Voltage Vault specializes in custom car audio installations,
        amplifier wiring, subwoofer systems, electrical upgrades,
        and SPL-focused builds. Whether you want clean sound quality
        or earth-shaking bass, we'll build a system designed around
        your goals.
    </div>
</section>

<section id="services">
    <h2 class="section-title">Services</h2>

    <div class="services">
        <div class="card">
            <h3>Custom Subwoofer Builds</h3>
            <p>Single, dual, and wall builds designed for maximum output.</p>
        </div>

        <div class="card">
            <h3>Amplifier Installation</h3>
            <p>Professional wiring, tuning, and setup.</p>
        </div>

        <div class="card">
            <h3>Custom Enclosures</h3>
            <p>Ported and sealed boxes built to exact specifications.</p>
        </div>

        <div class="card">
            <h3>Electrical Upgrades</h3>
            <p>Alternators, batteries, Big 3 upgrades, and power systems.</p>
        </div>
    </div>
</section>

<section id="builds">
    <h2 class="section-title">Featured Builds</h2>

    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1489824904134-891ab64532f1?w=800">
        <img src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?w=800">
        <img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?w=800">
    </div>
</section>

<section>
    <h2 class="section-title">Customer Reviews</h2>

    <div class="reviews">
        <div class="review">
            ★★★★★<br><br>
            "Truck hits harder than ever. Clean install."
        </div>

        <div class="review">
            ★★★★★<br><br>
            "Professional work and incredible bass."
        </div>

        <div class="review">
            ★★★★★<br><br>
            "Best audio shop experience I've had."
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="section-title">Request A Quote</h2>

    <div class="contact">
        <input type="text" placeholder="Name">
        <input type="email" placeholder="Email">
        <input type="text" placeholder="Vehicle">
        <textarea rows="6" placeholder="Tell us about your build..."></textarea>

        <button>Submit Request</button>
    </div>
</section>

<footer>
    © 2026 Voltage Vault | Custom Car Audio & Electrical Solutions
</footer>

</body>
</html>
