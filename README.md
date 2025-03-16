<link href="https://fonts.googleapis.com/css2?family=Lexend:wght@100..900&family=VT323&display=swap" rel="stylesheet">

<a href="https://saifq.co/" target="_blank" style="outline: 0; margin: 35px; display: flex; justify-content: center; align-items: center;">
<img src="https://readme-typing-svg.herokuapp.com?font=Chakra+Petch&weight=600&size=25&duration=3000&pause=2000&color=22F888&center=true&vCenter=true&width=400&height=100&lines=Hi%2C+I'm+Saif+Quazi;I'm+a+web+developer+and+designer!;Tap+here+to+visit+my+site!" alt="Typing SVG" />
<div id="waveEmoji">👋</div>
</a>

<p id="skillTxt">My Skills</p>

<p style="text-align: center; padding-inline: 30px;">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=css,html,js,py,react,vite,p5js,md,svg,windows,vscode,codepen,replit,netlify,github,git,npm,dotnet,webflow,stackoverflow,gmail,instagram,notion,arduino&perline=12" />
  </a>
</p>

<style>
    html, body {
        width: 100vw;
        height: 200vh;
        padding: 0;
        margin: 0;
    }

    * {
        font-family: 'Lexend', serif;
    }
    
    a:hover {
        text-decoration: none;
    }

    #waveEmoji {
        width: 30px;
        height: 30px;
        margin-left: -30px;
        position: relative;
        font-size: 25px;
        text-align: center;
        display: flex;
        align-items: center;
        justify: content: center;
        transform: translateY(-5px);
        transform-origin: 85% 90%; 
        animation: fadeInOut 15s ease infinite, wave 15s ease infinite;
    }

    #skillTxt {
        width: 150px;
        height: 50px;
        position: relative;
        left: 50%;
        transform: translateX(-50%);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 20px;
        font-weight: 200;
        font-style: italic;
        border-radius: 15px;
        background-color: #00000044;
    }

    @keyframes fadeInOut {
        0% {
            opacity: 0;
        } 19% {
            opacity: 1;
        } 31% {
            opacity: 1;
        } 34% {
            opacity: 0;
        } 100% {
            opacity: 0;
        }
    }

    @keyframes wave {
        0% {
            rotate: 0deg;
        } 19% {
            rotate: 0deg;
        } 20% {
            rotate: 12deg;
        } 22% {
            rotate: -12deg;
        } 24% {
            rotate: 8deg;
        } 26% {
            rotate: -8deg;
        } 28% {
            rotate: 4deg;
        } 26% {
            rotate: -4deg;
        } 31% {
            rotate: 0deg;
        } 100% {
            rotate: 0deg;
        }
    }
</style>