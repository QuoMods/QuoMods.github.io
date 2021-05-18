<html>
    <head>
        <title>Home - BlockSploit</title>
        <link rel="stylesheet" href="style.css">
        <link rel="icon" type="image/png" href="src/favicon.png" />
    </head>
    <body class="dark" onload="theme()"> <!-- Dark by default -->        
        <div class="header">
            <a href="#youAlreadyHereLMAO" class="logo">BlockSploit</a>
            <div class="header-right">
              <a class="active" href="#youAlreadyHereLMAO">Home</a>
              <a href="https://raw.githubusercontent.com/blocksploit/blocksploit/main/skidsInjector_kickBypasser.user.js" target="_blank">Download</a>
              <a href="https://discord.com/invite/kQeAMm6EZX" target="_blank"><svg width="23" height="15" viewBox="0 0 28 20"><path fill="currentColor" d="M20.6644 20C20.6644 20 19.8014 18.9762 19.0822 18.0714C22.2226 17.1905 23.4212 15.2381 23.4212 15.2381C22.4384 15.881 21.5034 16.3334 20.6644 16.6429C19.4658 17.1429 18.3151 17.4762 17.1884 17.6667C14.887 18.0953 12.7774 17.9762 10.9795 17.6429C9.61301 17.381 8.43836 17 7.45548 16.6191C6.90411 16.4048 6.30479 16.1429 5.70548 15.8096C5.63356 15.7619 5.56164 15.7381 5.48973 15.6905C5.44178 15.6667 5.41781 15.6429 5.39384 15.6191C4.96233 15.381 4.7226 15.2143 4.7226 15.2143C4.7226 15.2143 5.87329 17.1191 8.91781 18.0238C8.19863 18.9286 7.31164 20 7.31164 20C2.0137 19.8333 0 16.381 0 16.381C0 8.7144 3.45205 2.50017 3.45205 2.50017C6.90411 -0.07123 10.1884 0.000197861 10.1884 0.000197861L10.4281 0.285909C6.11301 1.52399 4.12329 3.40493 4.12329 3.40493C4.12329 3.40493 4.65068 3.11921 5.53767 2.71446C8.10274 1.59542 10.1404 1.2859 10.9795 1.21447C11.1233 1.19066 11.2432 1.16685 11.387 1.16685C12.8493 0.976379 14.5034 0.92876 16.2295 1.11923C18.5068 1.38114 20.9521 2.0478 23.4452 3.40493C23.4452 3.40493 21.5514 1.61923 17.476 0.381146L17.8116 0.000197861C17.8116 0.000197861 21.0959 -0.07123 24.5479 2.50017C24.5479 2.50017 28 8.7144 28 16.381C28 16.381 25.9623 19.8333 20.6644 20ZM9.51712 8.88106C8.15068 8.88106 7.07192 10.0715 7.07192 11.5239C7.07192 12.9763 8.17466 14.1667 9.51712 14.1667C10.8836 14.1667 11.9623 12.9763 11.9623 11.5239C11.9863 10.0715 10.8836 8.88106 9.51712 8.88106ZM18.2671 8.88106C16.9007 8.88106 15.8219 10.0715 15.8219 11.5239C15.8219 12.9763 16.9247 14.1667 18.2671 14.1667C19.6336 14.1667 20.7123 12.9763 20.7123 11.5239C20.7123 10.0715 19.6336 8.88106 18.2671 8.88106Z"></path></svg> Join Discord</a>
              <a href="documentation.html">Documentation</a>
              <a href="versions.html">Version Log</a>
              <a href="#theme" onclick="theme(theme() == 'dark' ? 'white' : 'dark')" style="padding-top: 8px;">
                <svg viewBox="-12 0 480 480" style="fill: var(--primcolor)" height="30px" width="30px">
                    <path d="m114.34375 117.65625c3.140625 3.03125 8.128906 2.988281 11.214844-.097656 3.085937-3.085938 3.128906-8.074219.097656-11.214844l-48-48c-3.140625-3.03125-8.128906-2.988281-11.214844.097656-3.085937 3.085938-3.128906 8.074219-.097656 11.214844zm0 0"></path>
                    <path d="m72 248c4.417969 0 8-3.582031 8-8s-3.582031-8-8-8h-64c-4.417969 0-8 3.582031-8 8s3.582031 8 8 8zm0 0"></path><path d="m114.34375 362.34375-48 48c-2.078125 2.007812-2.914062 4.984375-2.179688 7.78125.730469 2.796875 2.914063 4.980469 5.710938 5.710938 2.796875.734374 5.773438-.101563 7.78125-2.179688l48-48c3.03125-3.140625 2.988281-8.128906-.097656-11.214844-3.085938-3.085937-8.074219-3.128906-11.214844-.097656zm0 0"></path>
                    <path d="m232 374.976562v-269.953124c-68.429688 8.074218-119.988281 66.074218-119.988281 134.976562s51.558593 126.902344 119.988281 134.976562zm0 0"></path>
                    <path d="m432 306.59375c-12.027344 4.140625-24.6875 6.15625-37.40625 5.957031-61.351562-.703125-110.558594-50.929687-110-112.277343.410156-38.417969 19.6875-74.175782 51.558594-95.632813-6.542969-.519531-13.128906-.640625-19.296875-.640625-24.351563.007812-48.210938 6.863281-68.855469 19.777344v232.445312c30.652344 19.175782 67.902344 24.726563 102.8125 15.316406 34.910156-9.414062 64.324219-32.933593 81.1875-64.914062zm0 0"></path>
                    <path d="m455.398438 178.222656-17.773438-2.71875c-2.636719-.402344-4.898438-2.089844-6.03125-4.503906l-7.59375-16.167969-7.59375 16.167969c-1.132812 2.414062-3.394531 4.101562-6.03125 4.503906l-17.773438 2.71875 13.125 13.457032c1.773438 1.816406 2.578126 4.367187 2.167969 6.871093l-3.015625 18.480469 15.257813-8.429688c2.40625-1.328124 5.320312-1.328124 7.726562 0l15.257813 8.429688-3.015625-18.480469c-.410157-2.503906.394531-5.054687 2.167969-6.871093zm0 0"></path>
                    <path d="m240 480c4.417969 0 8-3.582031 8-8v-80c-5.34375-.007812-10.683594-.292969-16-.855469v80.855469c0 4.417969 3.582031 8 8 8zm0 0"></path>
                    <path d="m248 8c0-4.417969-3.582031-8-8-8s-8 3.582031-8 8v80.855469c5.316406-.5625 10.65625-.847657 16-.855469zm0 0"></path>
                </svg>
            </a>
            </div>
        </div>
        <div id="main">
                <div id="wraper">
                    <div id="wraper-content">
                        <div id="wraper-content-coloumn">
                            <h1>BlockSploit</h1>
                            <p>BlockSploit - Free working cheat on a popular browser game venge.io. This unique cheat with good functionality will please many players. It has all the features you need to be able to dominate the game's game servers venge.io. There are such functions as: Aimbot for perfect shooting, SpeedHack for fast movement on the map, ESP for seeing enemies through walls, AutoJump and many other functions. Use this cheat yourself in your browser and take the first place in the game table.</p>
                            <div style="display: flex;justify-content: space-evenly;width: 450px;">
                                <a class="primary simp-btn" href="https://raw.githubusercontent.com/blocksploit/blocksploit/main/skidsInjector_kickBypasser.user.js" target="_blank">Download</a>
                                <a class="simp-btn" href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo" target="_blank">Tampermonkey</a>
                                <a class="gold simp-btn" href="#https://paypal.me/blockman02135" onclick="window.open(this.href.split('#')[1],'name','width=600,height=700')">Donate</a>
                            </div>
                        </div>
                        <img src="src/w_venge_mod.png" alt="Mod">
                    </div>
                </div>
                <div id="imgswraper">
                    <div class="zoomImg">
                        <img id="myImg" src="src/w_ss1.png" alt="ESP & Traces" style="width:100%;max-width:300px">
                        <div id="modal">
                        <span id="close">&times;</span>
                        <img id="modal-content">
                        <div id="caption"></div>
                        </div> 
                    </div>
                    <div class="zoomImg">
                        <img id="myImg" src="src/w_ss2.png" alt="Aimbot" style="width:100%;max-width:300px">
                        <div id="modal">
                        <span id="close">&times;</span>
                        <img id="modal-content">
                        <div id="caption"></div>
                        </div> 
                    </div>
                    <div class="zoomImg">
                        <img id="myImg" src="src/w_ss3.png" alt="Fun features like Custom FOV" style="width:100%;max-width:300px">
                        <div id="modal">
                        <span id="close">&times;</span>
                        <img id="modal-content">
                        <div id="caption"></div>
                        </div> 
                    </div>
                    <div class="zoomImg">
                        <img id="myImg" src="src/w_ss4.png" alt="Infinity Granades & Melee" style="width:100%;max-width:300px">
                        <div id="modal">
                        <span id="close">&times;</span>
                        <img id="modal-content">
                        <div id="caption"></div>
                        </div> 
                    </div>
                    <div class="zoomImg">
                        <img id="myImg" src="src/w_ss5.png" alt="Infinity Ammo & No Recoil|Spread|Cam Shake & Rapid Fire & No Cooldown on Weapon Change" style="width:100%;max-width:300px">
                        <div id="modal">
                        <span id="close">&times;</span>
                        <img id="modal-content">
                        <div id="caption"></div>
                        </div> 
                </div>
            </div>
        </div>
        <script>
            function theme(theme) {
                [...document.all].map(e=>e.getAttribute('color')&&(e.style.color=e.getAttribute('color'))); // Color attr
                if (theme) {
                    return ['dark','white'].indexOf(theme) !== -1 ? (window.localStorage.setItem('theme',theme),document.body.className=theme) : null;
                }
                return document.body.className = window.localStorage.getItem('theme') || document.body.className;
            };
            [...document.getElementsByClassName('zoomImg')].map(e => {
                e.children["myImg"].onclick = function(){
                    e.children["modal"].style.display = "block";
                    e.children["modal"].children["modal-content"].src = this.src;
                    e.children["modal"].children["caption"].innerHTML = this.alt;
                }
                e.children["modal"].children["close"].onclick = function() {
                    e.children["modal"].style.display = "none";
                } 
            });
        </script>
    </body>
</html>
