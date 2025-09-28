<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Portfolio's Radja Gani</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;500;700&display=swap" rel="stylesheet">
    <style>
        /* --- Reset --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            font-family: 'Montserrat', sans-serif;
            background: #fff;
            color: #111;
            transition: background 0.3s, color 0.3s;
            padding-top: 60px;
        }
        body.dark-mode {
            background: #111;
            color: #fff;
        }

        /* --- Header --- */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px 20px;
            z-index: 1000;
            transition: background 0.3s;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }
        body.dark-mode header {
            background: #222;
        }
        nav {
            display: flex;
            gap: 25px;
            align-items: center;
        }
        nav a {
            text-decoration: none;
            color: inherit;
            font-weight: 500;
            transition: color 0.3s, border-bottom 0.3s;
        }
        nav a:hover {
            color: #007BFF;
            border-bottom: 2px solid #007BFF;
        }
        .mode-toggle {
            background: #007BFF;
            color: #fff;
            border: none;
            font-size: 12px;
            padding: 5px 13px;
            border-radius: 15px;
            cursor: pointer;
            font-weight: 500;
            transition: background 0.3s, transform 0.2s;
            margin-left: 10px;
        }
        .mode-toggle:hover {
            background: #0056b3;
            transform: scale(1.05);
        }

        /* --- Hero --- */
        .hero {
            text-align: center;
            padding: 60px 20px 40px;
        }
        .hero h1 {
            margin-bottom: 5px;
            font-size: 2.5em;
        }
        .hero p {
            font-size: 1.1em;
            color: #666;
        }
        body.dark-mode .hero p {
            color: #ccc;
        }

        /* --- Gallery (Masonry Layout) --- */
        .gallery {
            /* ⭐ Perubahan Poin 4: Menggunakan CSS Column untuk Masonry Effect */
            column-count: 4; /* Default 4 kolom untuk desktop besar */
            column-gap: 20px;
            padding: 20px;
            max-width: 1400px;
            margin: 0 auto;
        }
        .project {
            /* Penting untuk tata letak kolom */
            break-inside: avoid;
            display: block; 
            width: 100%; /* Lebar harus 100% dari kolom */

            margin-bottom: 20px; 
            border-radius: 12px; 
            overflow: hidden;
            position: relative;
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: pointer;
            outline: none;
        }
        .project:focus, .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
            z-index: 10;
        }
        .project::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 12px;
            box-shadow: 0 0 0 3px rgba(0,153,255,0.8);
            opacity: 0;
            transition: opacity 0.3s;
        }
        .project:focus::after, .project:hover::after {
            opacity: 1;
        }
        .project img,
        .project video {
            width: 100%;
            height: auto; /* ⭐ Dihapus: Fixed height agar rasio asli dipertahankan */
            display: block;
            object-fit: cover;
            border-radius: 12px 12px 0 0;
            pointer-events: none;
            background: #eee;
        }
        .project p {
            padding: 10px 15px;
            text-align: center;
            font-weight: 400;
            color: #626262;
            font-size: 11px;
            background: #fff;
            border-radius: 0 0 12px 12px;
        }
        body.dark-mode .project p {
            background: #333;
            color: #aaa;
        }

        /* Media Queries for Gallery (Masonry) */
        @media (max-width: 1200px) {
            .gallery { column-count: 3; }
        }
        @media (max-width: 800px) {
            .gallery { column-count: 2; }
        }
        @media (max-width: 500px) {
            .gallery { 
                column-count: 1; 
                column-gap: 10px;
                padding: 10px;
            }
        }

        /* --- Popup --- */
        .popup {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,0.9);
            justify-content: center;
            align-items: center;
            z-index: 2000;
        }
        .popup-content {
            position: relative;
            background: transparent;
            padding: 0;
            max-width: 90vw;
            max-height: 90vh;
            overflow: hidden;
            opacity: 0;
            transition: opacity 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .popup-content img,
        .popup-content video {
            max-width: 90vw;
            max-height: 90vh;
            width: auto;
            height: auto;
            object-fit: contain;
            border-radius: 5px;
        }
        .popup-header {
            position: fixed;
            top: 20px;
            right: 20px;
            font-size: 14px;
            font-weight: 400;
            color: #ccc;
            background: rgba(0,0,0,0.5);
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: color 0.3s, transform 0.2s, background 0.3s;
        }
        .popup-header:hover {
            color: #fff;
            background: rgba(0,0,0,0.8);
            transform: scale(1.05);
        }
        .popup-buttons {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 10px;
        }
        .popup-buttons button {
            padding: 8px 20px;
            border: none;
            border-radius: 20px;
            background: #007BFF;
            color: #fff;
            cursor: pointer;
            font-weight: 500;
            transition: background 0.3s, transform 0.2s;
        }
        .popup-buttons button:hover:not(:disabled) {
            background: #0056b3;
            transform: scale(1.05);
        }
        .popup-buttons button:disabled {
            background-color: #ffcc00;
            color: #111;
            font-weight: bold;
            cursor: not-allowed;
            opacity: 0.8;
        }
        .popup-nav-left,
        .popup-nav-right {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            /* ⭐ Perubahan Poin 1: Ukuran lebih kecil */
            font-size: 18px; 
            font-weight: bold;
            color: #fff;
            background: rgba(0,0,0,0.3); /* Sedikit lebih transparan */
            border-radius: 50%;
            width: 35px; /* Lebih kecil */
            height: 35px; /* Lebih kecil */
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            user-select: none;
            transition: background 0.3s, transform 0.2s;
        }
        .popup-nav-left:hover,
        .popup-nav-right:hover {
            background: rgba(0,0,0,0.7);
            transform: translateY(-50%) scale(1.1);
        }
        .popup-nav-left { left: 10px; }
        .popup-nav-right { right: 10px; }
        
        /* --- Welcome Popup (Initial) --- */
        #welcomePopup.popup-overlay {
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,0.85);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 3000;
            opacity: 1;
            transition: opacity 0.5s;
        }
        #welcomePopup.popup-overlay.hidden {
            display: none;
            opacity: 0;
        }
        #welcomePopup .popup-content {
            background: #fff;
            color: #111;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.5);
            max-width: 350px;
            max-height: auto;
            opacity: 1;
            flex-direction: column;
        }
        #welcomePopup h1 {
            margin-bottom: 15px;
            font-size: 1.5em;
        }
        #welcomePopup p {
            margin-bottom: 20px;
            line-height: 1.5;
        }
        #welcomePopup button {
            background: #007BFF;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.3s;
        }
        #welcomePopup button:hover {
            background: #0056b3;
        }

        /* --- About & Contact --- */
        .about, .contact {
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        .about h2, .contact h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
            padding-top: 20px;
        }
        .about p {
            margin-bottom: 15px;
            text-indent: 0;
            text-align: left;
        }
        .about p:first-of-type {
            margin-top: 15px;
        }
        .about a, .contact a {
            color: #007BFF;
            text-decoration: none;
            font-weight: 500;
        }
        .about a:hover, .contact a:hover {
            text-decoration: underline;
        }

        /* --- Footer --- */
        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.8em;
            color: #888;
            border-top: 1px solid #eee;
        }
        body.dark-mode footer {
            border-top: 1px solid #333;
            color: #666;
        }
    </style>
</head>

<body>

<header>
    <nav>
        <a href="#home" id="homeNav">Home</a>
        <a href="#about" id="aboutNav">About Me</a>
        <button class="mode-toggle" onclick="toggleMode()">Dark Mode</button>
    </nav>
</header>

<section id="home" class="hero">
    <h1>Hi, I'm Radja Gani</h1>
    <p>Below are several of my works as my own portfolio, thank you!</p>
</section>

<div id="welcomePopup" class="popup-overlay">
    <div class="popup-content">
        <h1>Welcome to My Portfolio!</h1>
        <p>Use <strong>←</strong> and <strong>→</strong> to navigate slides.<br>
        Press <strong>Esc</strong> anytime to close popups.</p>
        <button id="closeWelcomePopup">Get Started</button>
    </div>
</div>

<section class="gallery" role="list" aria-label="Portfolio Gallery">
    </section>

<div class="popup" id="popup" role="dialog" aria-modal="true" aria-label="Project Slideshow" onclick="backgroundClose(event)">
    <div class="popup-nav-left" role="button" aria-label="Previous Slide" onclick="changeSlide(-1)">❮</div> 
    <div class="popup-nav-right" role="button" aria-label="Next Slide" onclick="changeSlide(1)">❯</div>
    <div id="popupContent" class="popup-content"></div>
    <div class="popup-buttons">
        <button onclick="changeSlide(-1)">Prev</button>
        <button class="toggle-slideshow" onclick="toggleSlideshow()">Play</button>
        <button onclick="changeSlide(1)">Next</button>
    </div>
    <div class="popup-header" role="button" aria-label="Close" onclick="closePopup()">Close / ESC</div>
</div>

<section id="about" class="about">
    <h2>About Me</h2>
    <p>For me, every gift, every potential, every opportunity is sacred — and wasting them would be a form of ingratitude.
    That’s why I approach every task — whether it's creative, strategic, or operational — with a mindset to maximize whatever’s given, pushing it to be the absolute best it can possibly be.</p>

    <p>Sure, I might seem intense sometimes, maybe even get lost in deep, philosophical conversations...
    But underneath that intensity is a simple belief: everything we do matters.
    And it’s a privilege to bring ideas, people, and visions to life with passion, precision, and purpose.</p>

    <p>This deeper connection to ideas, emotions, and the human experience is the reason why I chose the creative industry as my life’s work.
    For me, creativity isn’t just passion — it’s destiny.
    I believe that through our work, we can deliver emotions, feelings, and even subtle messages that transcend time.
    At its best, art and creativity aren't just crafts; they're the next evolution of human consciousness.</p>

    <p>And honestly?</p>
    <p>For me, there’s no other way.
    I wasn’t just born to create — I was born to push the boundaries of what creation can mean for the future of humankind.</p>

    <h2>Contact</h2>
    <p>Email: <a href="mailto:radja.zr@outlook.com">radja.zr@outlook.com</a></p>
    <p>Whatsapp: <a href="https://wa.me/6285156024506" target="_blank">+6285156024506</a></p>
</section>

<footer>
    <p>© 2025 Radja Gani. All rights reserved.</p>
</footer>

<script>
const projectData = [
    { desc: 'NR Management Logo & Branding', slides: ['https://i.imgur.com/TLPpNnb.jpeg', 'https://i.imgur.com/3YtFktq.jpeg', 'https://i.imgur.com/Mk5zB99.jpeg', 'https://i.imgur.com/7EXnx1i.jpeg', 'https://i.imgur.com/A9S2bCw.jpeg', 'https://i.imgur.com/4iwIci8.jpeg', 'https://i.imgur.com/pv0BNK1.jpeg', 'https://i.imgur.com/WfQJ9wx.jpeg'] },
    { desc: 'Locaahands x Club Soda', slides: ['https://i.imgur.com/VHmAySW.mp4', 'https://i.imgur.com/VvoJmmc.png', 'https://i.imgur.com/LigeDyp.png', 'https://i.imgur.com/0RT02Uq.png'] },
    { desc: 'Imaginary Creative Agency', slides: ['https://i.imgur.com/Q8YlXOA.jpeg'] },
    { desc: 'Sailors Club Motion Snapgram', slides: ['https://i.imgur.com/WXOb6Ie.mp4'] },
    { desc: 'Sailors Club Invitation Card Mockup', slides: ['https://i.imgur.com/ipv55T7.jpeg'] },
    { desc: 'Ola Bracelet Spoiler Content', slides: ['https://i.imgur.com/in48HjN.mp4', 'https://i.imgur.com/tyOSB8f.mp4'] },
    { desc: 'Sailors Club - Go Skate Day Doc 1', slides: ['https://i.imgur.com/DbhJCvq.jpeg'] },
    { desc: 'Instagram Reels Content', slides: ['https://i.imgur.com/zzl8L2B.mp4'] },
    { desc: 'Sailors Club - Go Skate Day Doc 2', slides: ['https://i.imgur.com/30NTdHV.jpeg'] },
    { desc: 'Timeless Elucidation!', slides: ['https://i.imgur.com/5GNXZYc.jpeg'] },
    { desc: 'Unen-Unen Ambyar 2019 Poster', slides: ['https://i.imgur.com/ZZpZnFR.jpeg'] },
    { desc: 'Unnecessary Thing But look Cool', slides: ['https://i.imgur.com/AwNiusG.mp4'] },
    { desc: 'Make A Scene Bali', slides: ['https://files.catbox.moe/zr3387.mp4'] },
    { desc: 'Locaahands Dining Club Design Menu on Mockup', slides: ['https://i.imgur.com/lmES8LK.jpeg'] },
    { desc: 'Prolessnesia - Taiwan Doc', slides: ['https://i.imgur.com/VqOfUgj.mp4'] },
    { desc: 'Sailors Club - Go Skate Day Doc 3', slides: ['https://i.imgur.com/mSdp1zm.jpeg'] },
    { desc: 'Just A Poster - Nothing Else', slides: ['https://i.imgur.com/UDxPZ67.jpeg'] },
    { desc: 'Just Filler - Because I Love Analog', slides: ['https://i.imgur.com/KdCJTT9.jpeg'] },
    { desc: 'A Visak Celebration Content', slides: ['https://i.imgur.com/2pRbd4p.mp4'] },
    { desc: 'IDK, is only wed invitation', slides: ['https://i.imgur.com/xZytvIQ.jpeg'] },
    { desc: 'Just filler.', slides: ['https://i.imgur.com/2aEtT94.jpeg'] },
    { desc: 'King Fat Loss UK Promotional Vid', slides: ['https://i.imgur.com/ePrCcSX.mp4'] },
    { desc: 'Another filler again', slides: ['https://i.imgur.com/ZGjXuuG.jpeg'] },
    { desc: 'Omicron Logo Bumper', slides: ['https://i.imgur.com/eoZUz7N.mp4'] },
    { desc: 'Unen-Unen Ambyar Logo Mockup', slides: ['https://i.imgur.com/VPykTdV.jpeg'] },
    { desc: 'Sailors Club Short Film', slides: ['https://i.imgur.com/kG6aIPx.mp4'] }
];

let currentProjectIndex = 0;
let currentSlideIndex = 0;
let slideshowInterval;
let isPlaying = false;
const GALLERY_SELECTOR = '.gallery';
const WELCOME_POPUP_ID = 'welcomePopup';
const videoStates = {}; 

document.addEventListener('DOMContentLoaded', () => {
    const isDarkMode = localStorage.getItem('darkMode') === 'true';
    if (isDarkMode) {
        document.body.classList.add('dark-mode');
        document.querySelector('.mode-toggle').textContent = 'Light Mode';
    } else {
        document.querySelector('.mode-toggle').textContent = 'Dark Mode';
    }

    renderProjects();
    setupLazyLoading();

    const welcomePopup = document.getElementById(WELCOME_POPUP_ID);
    const hasVisited = sessionStorage.getItem('hasVisited');

    if (hasVisited) {
        welcomePopup.classList.add('hidden');
    } else {
        welcomePopup.style.display = 'flex';
        document.getElementById('closeWelcomePopup').onclick = () => {
            sessionStorage.setItem('hasVisited', 'true');
            welcomePopup.style.opacity = '0';
            setTimeout(() => {
                welcomePopup.style.display = 'none';
                const firstProject = document.querySelector('.project');
                if (firstProject) firstProject.focus();
            }, 500);
        };
    }
});

function renderProjects() {
    const gallery = document.querySelector(GALLERY_SELECTOR);
    projectData.forEach((item, idx) => {
        const div = document.createElement('div');
        div.className = 'project';
        div.setAttribute('role', 'listitem');
        div.setAttribute('tabindex', '0');
        div.setAttribute('aria-label', item.desc);
        
        const thumbnailUrl = item.slides[0];
        const isVideo = thumbnailUrl.endsWith('.mp4');

        div.onclick = () => openPopup(idx);
        div.onkeydown = (e) => {
            if (e.key === 'Enter' || e.key === ' ') {
                e.preventDefault();
                openPopup(idx);
            }
        };

        let mediaElement;
        if (isVideo) {
            mediaElement = document.createElement('video');
            mediaElement.muted = true; 
            mediaElement.setAttribute('loop', '');
            mediaElement.setAttribute('playsinline', '');
            mediaElement.setAttribute('preload', 'none');
            mediaElement.setAttribute('data-src', thumbnailUrl);
            mediaElement.setAttribute('aria-label', `Video thumbnail for ${item.desc}`);
            mediaElement.className = 'lazy';
        } else {
            mediaElement = document.createElement('img');
            mediaElement.setAttribute('data-src', thumbnailUrl);
            mediaElement.setAttribute('alt', `Image thumbnail for ${item.desc}`);
            mediaElement.setAttribute('loading', 'lazy');
            mediaElement.className = 'lazy';
        }

        div.appendChild(mediaElement);

        const p = document.createElement('p');
        p.textContent = item.desc;
        div.appendChild(p);
        gallery.appendChild(div);
    });
}

function setupLazyLoading() {
    const lazyElements = document.querySelectorAll('.lazy');
    const lazyObserver = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const el = entry.target;
                const src = el.dataset.src;
                if (!el.src && src) {
                    el.src = src;
                    if (el.tagName === 'VIDEO') {
                        el.play().catch(e => console.log('Autoplay failed (muted):', e));
                    }
                }
                observer.unobserve(el);
            }
        });
    }, { threshold: 0.1 });
    lazyElements.forEach(el => lazyObserver.observe(el));
}

function toggleMode() {
    const body = document.body;
    body.classList.toggle('dark-mode');
    const isDarkMode = body.classList.contains('dark-mode');
    document.querySelector('.mode-toggle').textContent = isDarkMode ? 'Light Mode' : 'Dark Mode';
    localStorage.setItem('darkMode', isDarkMode);
}

function openPopup(index) {
    currentProjectIndex = index;
    currentSlideIndex = 0;
    loadSlide();
    document.getElementById('popup').style.display = 'flex';
    document.getElementById('popupContent').focus();
    // ⭐ Poin 2: Sembunyikan panah next/prev project (yang sekarang jadi slide)
    updateSlideNavVisibility(); 
}

function closePopup() {
    stopSlideshow();
    document.getElementById('popup').style.display = 'none';

    const videoInPopup = document.getElementById('popupContent').querySelector('video');
    if (videoInPopup) {
        videoStates[videoInPopup.src] = videoInPopup.currentTime; 
        videoInPopup.pause();
    }

    document.getElementById('popupContent').innerHTML = '';
}

function backgroundClose(e) {
    if (e.target.id === 'popup') closePopup();
}

// ⭐ NEW: Fungsi untuk mengatur visibilitas tombol navigasi slide
function updateSlideNavVisibility() {
    const slidesLength = projectData[currentProjectIndex].slides.length;
    const navLeft = document.querySelector('.popup-nav-left');
    const navRight = document.querySelector('.popup-nav-right');

    if (slidesLength <= 1) {
        navLeft.style.display = 'none';
        navRight.style.display = 'none';
    } else {
        navLeft.style.display = 'flex';
        navRight.style.display = 'flex';
    }
}

function loadSlide() {
    stopSlideshow();
    const popupContent = document.getElementById('popupContent');
    popupContent.style.opacity = '0';

    setTimeout(() => {
        const existingVideo = popupContent.querySelector('video');
        if (existingVideo) {
            videoStates[existingVideo.src] = existingVideo.currentTime;
            existingVideo.pause();
        }

        popupContent.innerHTML = '';
        const project = projectData[currentProjectIndex];
        const currentSlide = project.slides[currentSlideIndex];
        const slidesLength = project.slides.length;
        const isVideo = currentSlide.endsWith('.mp4');
        const playPauseBtn = document.querySelector('.toggle-slideshow');

        let mediaElement;

        if (isVideo) {
            mediaElement = document.createElement('video');
            mediaElement.src = currentSlide;
            mediaElement.controls = true;
            mediaElement.autoplay = true;
            mediaElement.muted = false;
            mediaElement.setAttribute('playsinline', '');
            
            if (videoStates[currentSlide] > 0) {
                 mediaElement.currentTime = videoStates[currentSlide]; 
            }
            
            mediaElement.onloadeddata = () => { 
                mediaElement.play().catch(e => console.log('Autoplay failed:', e));
            };
            
            // Atur tombol play/pause dan visibilitas panah
            playPauseBtn.textContent = 'Video';
            playPauseBtn.disabled = true;

            // Pastikan panah slide disembunyikan jika video (meski bisa berpindah, tapi agar tidak konflik kontrol)
            updateSlideNavVisibility();

        } else {
            mediaElement = document.createElement('img');
            mediaElement.src = currentSlide;
            
            // ⭐ Poin 3: Pastikan gambar selesai dimuat sebelum transisi dan memulai slideshow
            mediaElement.onload = () => {
                popupContent.style.opacity = '1';
                if (slidesLength > 1) {
                    playPauseBtn.textContent = 'Play Slideshow';
                    playPauseBtn.disabled = false;
                    startSlideshow(); 
                } else {
                    playPauseBtn.textContent = 'Only 1 Page';
                    playPauseBtn.disabled = true;
                }
            };
            
            // Fallback untuk gambar yang sudah dicache
            if (mediaElement.complete) {
                mediaElement.onload();
            }

            if (slidesLength <= 1) {
                playPauseBtn.textContent = 'Only 1 Page';
                playPauseBtn.disabled = true;
            } else {
                playPauseBtn.textContent = 'Play Slideshow';
                playPauseBtn.disabled = false;
            }
        }
        
        popupContent.appendChild(mediaElement);
        // Tampilkan konten jika itu video (video tidak menunggu onload)
        if (isVideo) {
             popupContent.style.opacity = '1';
        }
        
        // Perbarui visibilitas panah (hanya berlaku untuk slide gambar/video dalam proyek)
        updateSlideNavVisibility();
        
    }, 100);
}

function changeSlide(direction) {
    const slides = projectData[currentProjectIndex].slides;
    if (slides.length <= 1) return; // Tidak geser jika hanya 1 slide

    currentSlideIndex = (currentSlideIndex + direction + slides.length) % slides.length;
    loadSlide();
}

function toggleSlideshow() {
    const slidesLength = projectData[currentProjectIndex].slides.length;
    if (slidesLength <= 1 || projectData[currentProjectIndex].slides[currentSlideIndex].endsWith('.mp4')) return;

    isPlaying ? stopSlideshow() : startSlideshow();
}

function startSlideshow() {
    if (isPlaying) return;

    isPlaying = true;
    const playPauseBtn = document.querySelector('.toggle-slideshow');
    playPauseBtn.textContent = 'Pause Slideshow';

    slideshowInterval = setInterval(() => {
        changeSlide(1);
    }, 3500);
}

function stopSlideshow() {
    isPlaying = false;
    const playPauseBtn = document.querySelector('.toggle-slideshow');
    if (!playPauseBtn.disabled && !projectData[currentProjectIndex].slides[currentSlideIndex].endsWith('.mp4')) {
        playPauseBtn.textContent = 'Play Slideshow';
    }
    clearInterval(slideshowInterval);
}

// ⭐ Fungsi nextProject dan previousProject diubah fungsinya menjadi changeSlide()
// Agar tombol panah besar di popup menggeser slide, bukan proyek
function nextProject() {
    changeSlide(1);
}

function previousProject() {
    changeSlide(-1);
}

// Keyboard controls
document.addEventListener('keydown', (e) => {
    if (document.getElementById('popup').style.display === 'flex') {
        if (e.key === 'ArrowRight') nextProject();
        if (e.key === 'ArrowLeft') previousProject();
        if (e.key === 'Escape') closePopup();
    }
    if (e.key === 'Home') {
        e.preventDefault();
        goHome();
    }
});

// Swipe gesture (mobile)
let touchStartX = 0;
document.getElementById('popup').addEventListener('touchstart', (e) => {
    touchStartX = e.changedTouches[0].screenX;
});
document.getElementById('popup').addEventListener('touchend', (e) => {
    const deltaX = e.changedTouches[0].screenX - touchStartX;
    if (deltaX > 50) {
        changeSlide(-1); // Swipe right → previous slide
    } else if (deltaX < -50) {
        changeSlide(1); // Swipe left → next slide
    }
});

// Anchor smooth scrolling
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Play/pause videos only when visible in viewport
setTimeout(() => {
  const videoElements = document.querySelectorAll('.project video');
  const playObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      const video = entry.target;
      if (entry.isIntersecting) {
        if (video.src) video.play().catch(()=>{});
      } else {
        video.pause();
      }
    });
  }, { threshold: 0.5 });
  videoElements.forEach(video => playObserver.observe(video));
}, 500); // wait for gallery render
</script>

</body>
</html>
