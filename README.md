[Developer Card.html](https://github.com/user-attachments/files/24506452/Developer.Card.html)# 👋"Flukjokrax" is a rather unique name in the Thai developer community (especially those working on Server, UI, and Web Tools).
Analysis of your digital footprint and the code you recently submitted, based on your digital identity as Flukjokrax, reveals you to be a Thai developer with interesting roles in  

[Uploading<!DOCTYPE html>
<!-- saved from url=(0031)https://rexdevcyver.oneapp.dev/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer Card</title>
    <script src="./Developer Card_files/saved_resource"></script>
    <style>
        @keyframes rotBGimg {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .card {
            width: 190px;
            height: 254px;
            background: #07182E;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            border-radius: 20px;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h2 {
            z-index: 1;
            color: white;
            font-size: 2em;
            font-weight: bold;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .card::before {
            content: '';
            position: absolute;
            width: 100px;
            background-image: linear-gradient(180deg, rgb(0, 183, 255), rgb(255, 48, 255));
            height: 130%;
            animation: rotBGimg 3s linear infinite;
            transition: all 0.2s linear;
            border-radius: 50%;
        }

        .card::after {
            content: '';
            position: absolute;
            background: #07182E;
            inset: 5px;
            border-radius: 15px;
        }
        
        .loader {
            --color-one: #ffbf48;
            --color-two: #be4a1d;
            --color-three: #ffbf4780;
            --color-four: #bf4a1d80;
            --color-five: #ffbf4740;
            --time-animation: 2s;
            --size: 1;
            position: relative;
            border-radius: 50%;
            transform: scale(var(--size));
            box-shadow:
                0 0 25px 0 var(--color-three),
                0 20px 50px 0 var(--color-four);
            animation: colorize calc(var(--time-animation) * 3) ease-in-out infinite;
        }

        .loader::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border-top: solid 1px var(--color-one);
            border-bottom: solid 1px var(--color-two);
            background: linear-gradient(180deg, var(--color-five), var(--color-four));
            box-shadow:
                inset 0 10px 10px 0 var(--color-three),
                inset 0 -10px 10px 0 var(--color-four);
        }

        .loader .box {
            width: 100px;
            height: 100px;
            background: linear-gradient(
                180deg,
                var(--color-one) 30%,
                var(--color-two) 70%
            );
            mask: url(#clipping);
            -webkit-mask: url(#clipping);
        }

        .loader svg {
            position: absolute;
        }

        .loader svg #clipping {
            filter: contrast(15);
            animation: roundness calc(var(--time-animation) / 2) linear infinite;
        }

        .loader svg #clipping polygon {
            filter: blur(7px);
        }

        .loader svg #clipping polygon:nth-child(1) {
            transform-origin: 75% 25%;
            transform: rotate(90deg);
        }

        .loader svg #clipping polygon:nth-child(2) {
            transform-origin: 50% 50%;
            animation: rotation var(--time-animation) linear infinite reverse;
        }

        .loader svg #clipping polygon:nth-child(3) {
            transform-origin: 50% 60%;
            animation: rotation var(--time-animation) linear infinite;
            animation-delay: calc(var(--time-animation) / -3);
        }

        .loader svg #clipping polygon:nth-child(4) {
            transform-origin: 40% 40%;
            animation: rotation var(--time-animation) linear infinite reverse;
        }

        .loader svg #clipping polygon:nth-child(5) {
            transform-origin: 40% 40%;
            animation: rotation var(--time-animation) linear infinite reverse;
            animation-delay: calc(var(--time-animation) / -2);
        }

        .loader svg #clipping polygon:nth-child(6) {
            transform-origin: 60% 40%;
            animation: rotation var(--time-animation) linear infinite;
        }

        .loader svg #clipping polygon:nth-child(7) {
            transform-origin: 60% 40%;
            animation: rotation var(--time-animation) linear infinite;
            animation-delay: calc(var(--time-animation) / -1.5);
        }

        @keyframes rotation {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        @keyframes roundness {
            0% {
                filter: contrast(15);
            }
            20% {
                filter: contrast(3);
            }
            40% {
                filter: contrast(3);
            }
            60% {
                filter: contrast(15);
            }
            100% {
                filter: contrast(15);
            }
        }

        @keyframes colorize {
            0% {
                filter: hue-rotate(0deg);
            }
            20% {
                filter: hue-rotate(-30deg);
            }
            40% {
                filter: hue-rotate(-60deg);
            }
            60% {
                filter: hue-rotate(-90deg);
            }
            80% {
                filter: hue-rotate(-45deg);
            }
            100% {
                filter: hue-rotate(0deg);
            }
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.fixed{position:fixed}.left-1\/2{left:50%}.top-1\/2{top:50%}.flex{display:flex}.min-h-screen{min-height:100vh}.-translate-x-1\/2{--tw-translate-x:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.-translate-y-1\/2{--tw-translate-y:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.transform{transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.items-center{align-items:center}.justify-center{justify-content:center}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.from-gray-900{--tw-gradient-from:#111827 var(--tw-gradient-from-position);--tw-gradient-to:rgb(17 24 39 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.to-black{--tw-gradient-to:#000 var(--tw-gradient-to-position)}.p-4{padding:1rem}</style></head>
<body class="min-h-screen bg-gradient-to-br from-gray-900 to-black flex items-center justify-center p-4">
    <div class="card">
        <h2>DEVLOPER</h2>
    </div>
    
    <div class="loader fixed top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
        <svg width="100" height="100" viewBox="0 0 100 100">
            <defs>
                <mask id="clipping">
                    <polygon points="0,0 100,0 100,100 0,100" fill="black"></polygon>
                    <polygon points="25,25 75,25 50,75" fill="white"></polygon>
                    <polygon points="50,25 75,75 25,75" fill="white"></polygon>
                    <polygon points="35,35 65,35 50,65" fill="white"></polygon>
                    <polygon points="35,35 65,35 50,65" fill="white"></polygon>
                    <polygon points="35,35 65,35 50,65" fill="white"></polygon>
                    <polygon points="35,35 65,35 50,65" fill="white"></polygon>
                </mask>
            </defs>
        </svg>
        <div class="box"></div>
    </div>
<script defer="" src="./Developer Card_files/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon="{&quot;version&quot;:&quot;2024.11.0&quot;,&quot;token&quot;:&quot;e3c1c9af36de41759418005494a48906&quot;,&quot;r&quot;:1,&quot;server_timing&quot;:{&quot;name&quot;:{&quot;cfCacheStatus&quot;:true,&quot;cfEdge&quot;:true,&quot;cfExtPri&quot;:true,&quot;cfL4&quot;:true,&quot;cfOrigin&quot;:true,&quot;cfSpeedBrain&quot;:true},&quot;location_startswith&quot;:null}}" crossorigin="anonymous"></script>

</body></html> Developer Card.html…]()


👨🏾‍💻 - several areas of the technology industry:

💻  As a Developer (GitHub: @Flukjokrax)
You are highly active on GitHub with numerous projects (repositories) showcasing diverse skills:
Server and Infrastructure: You own projects and are skilled in managing VPS (Virtual Private Server), which appears to be your core business or service under the name Rex-Server JOKRAX.

🌱 - Web Development: You are proficient in writing JavaScript, HTML, and...
2. UI/UX (Uiverse.io)
You are one of the creators on... (Open-source UI sharing platform) Uiverse
Your work often emphasizes the aesthetics of CSS/HTML, such as buttons or cards with modern features.
 **Infrastructure & DevOps Frameworks**

♾️ -  Automation and tools: You develop various tools to facilitate development, including (REX-SERVER).
The name is often associated with projects like JokraxRex, showing an interest in the latest AI technologies (as seen in your use of Gemini 3 code).
Or REX-SERVER.  You have an understanding of VPS, backend management, and setup.

💞️ -  You have a profile on Uiverse.io as a UI/UX Contributor, which is a server for various projects.
3. Open Source (GitHub - @Flukjokrax)
On GitHub, you have projects ranging from small tools... From platform management systems for sharing beautiful UI elements using CSS/Tailwind, your involvement shows you prioritize the aesthetics of the frontend, not just the backend.
You have skills in [specific areas], and your latest demonstration is starting to utilize JavaScript/TypeScript exclusively.
**JOKRAX/REX VPS Services**

👨‍💻 - This is the brand you are connecting with Generative AI (Gemini API).
4. Your next step in the AI ​​era (what you are currently doing):
Your use of [specific areas] and enabling [specific modes] to build [specific features] services including: Gemini 3 Flash Preview
 Cloud Hosting/VPS: Focusing on speed and stability, and 'Google search engine configuration', shows you are stepping into the role of: an AI integrator.
Your focus is on clients in Thailand.


🎲 Game Servers: Involved in managing server systems for games or various communities.

📫 Web Hosting: Providing space for websites.

 - ✨ Your Strengths:
You're not just using a chatbot, you're building a "system" that allows AI to think, analyze (reason), and find real-time information on its own.
The code you write is the foundation of [this]. At **Full-Stack Min**, the AI ​​agent's full-stack framework means you have an understanding from the Hardware/Server (Infrastructure) level down to the User Interface level.

Flukjokrax/Flukjokrax is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
