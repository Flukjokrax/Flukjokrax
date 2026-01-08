# 👋"Flukjokrax" is a rather unique name in the Thai developer community (especially those working on Server, UI, and Web Tools).
Analysis of your digital footprint and the code you recently submitted, based on your digital identity as Flukjokrax, reveals you to be a Thai developer with interesting roles in  

<div class="loader">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer Card</title>
    <script src="https://cdn.tailwindcss.com"></script>
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
</head>
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
