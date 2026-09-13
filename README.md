<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Profil Ridho Joewandilnata</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    color: white;
    background: linear-gradient(
        135deg,
        #ff0080,
        #7928ca,
        #0072ff,
        #00c9a7,
        #ffcc00
    );
    background-size: 400% 400%;
    animation: warna 12s ease infinite;
}

@keyframes warna {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}

header {
    text-align: center;
    padding: 45px 20px;
    background: rgba(0,0,0,0.35);
}

header h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

header p {
    font-size: 18px;
}

nav {
    background: rgba(0,0,0,0.55);
    padding: 15px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 7px;
    font-weight: bold;
}

nav a:hover {
    color: #ffe600;
}

section {
    max-width: 900px;
    margin: 30px auto;
    padding: 30px;
    background: rgba(255,255,255,0.16);
    border-radius: 20px;
    backdrop-filter: blur(8px);
}

h2 {
    color: #ffe600;
    text-align: center;
    margin-bottom: 20px;
}

.profile {
    text-align: center;
}

.profile img {
    width: 190px;
    height: 190px;
    object-fit: cover;
    border-radius: 50%;
    border: 6px solid white;
    margin-bottom: 20px;
}

.info {
    line-height: 2;
    font-size: 17px;
}

.card {
    background: rgba(0,0,0,0.22);
    padding: 20px;
    margin: 12px 0;
    border-radius: 15px;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
    );
    gap: 20px;
}

.gallery div {
    text-align: center;
}

.gallery img {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 15px;
    border: 4px solid white;
}

.gallery p {
    margin-top: 10px;
    font-weight: bold;
}

footer {
    text-align: center;
    padding: 30px;
    margin-top: 30px;
    background: rgba(0,0,0,0.45);
}

@media (max-width: 600px) {

    header h1 {
        font-size: 27px;
    }

    section {
        margin: 15px;
        padding: 20px;
    }

    nav a {
        display: inline-block;
        margin: 5px;
    }
}
</style>
</head>

<body>

<header id="beranda">
    <h1>Ridho Joewandilnata</h1>
    <p>Website Profil Pribadi</p>
</header>

<nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang</a>
    <a href="#pendidikan">Pendidikan</a>
    <a href="#organisasi">Organisasi</a>
    <a href="#hobi">Hobi</a>
    <a href="#galeri">Galeri</a>
</nav>

<section id="tentang">

    <div class="profile">

        <!-- FOTO PROFIL -->
        <img src="foto_profil.jpg" alt="Foto Profil">

        <h2>
            Halo, saya Ridho Joewandilnata 👋
        </h2>

        <div class="info">

            <p>
                <b>Nama:</b>
                Ridho Joewandilnata
            </p>

            <p>
                <b>Tempat, tanggal lahir:</b>
                Trenggalek, 22 Januari 2010
            </p>

            <p>
                <b>Kelas:</b>
                XI 4
            </p>

            <p>
                <b>Sekolah:</b>
                MA Al-Ma'arif Singosari
            </p>

        </div>

    </div>

</section>

<section id="pendidikan">

    <h2>🎓 Pendidikan</h2>

    <div class="card">

        <h3>MA Al-Ma'arif Singosari</h3>

        <p>
            Kelas XI 4
        </p>

    </div>

</section>

<section id="organisasi">

    <h2>🤝 Organisasi</h2>

    <div class="card">
        <p>
            PK IPNU MA Al-Ma'arif Singosari
        </p>
    </div>

    <div class="card">
        <p>
            Pimpinan Anak Cabang IPNU Kecamatan Lawang
        </p>
    </div>

</section>

<section id="hobi">

    <h2>🎧 Hobi</h2>

    <div class="card">
        <p>
            Mendengarkan musik 🎵
        </p>
    </div>

</section>

<section id="galeri">

    <h2>📸 Galeri Kegiatan</h2>

    <div class="gallery">

        <!-- FOTO KEGIATAN 1 -->
        <div>

            <img
                src="foto_kegiatan1.jpg"
                alt="Foto Kegiatan 1"
            >

            <p>
                Kegiatan 1
            </p>

        </div>

        <!-- FOTO KEGIATAN 2 -->
        <div>

            <img
                src="foto_kegiatan2.jpg"
                alt="Foto Kegiatan 2"
            >

            <p>
                Kegiatan 2
            </p>

        </div>

        <!-- FOTO KEGIATAN 3 -->
        <div>

            <img
                src="foto_kegiatan3.jpg"
                alt="Foto Kegiatan 3"
            >

            <p>
                Kegiatan 3
            </p>

        </div>

    </div>

</section>

<footer>

    <p>
        © 2026 Ridho Joewandilnata
    </p>

</footer>

</body>
</html>
