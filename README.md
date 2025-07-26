<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yash Siddhapura | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Roboto+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Custom CSS for styling */
        html, body {
            height: 100%;
            overflow: hidden; /* Prevents scrolling on the body */
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a192f;
            color: #ccd6f6;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .font-mono {
            font-family: 'Roboto Mono', monospace;
        }

        .main-container {
            background-color: #112240;
            border: 1px solid #1d2d50;
            box-shadow: 0 10px 30px -15px rgba(2,12,27,0.7);
        }
        
        .contact-icon {
            transition: transform 0.3s ease, color 0.3s ease;
        }

        .contact-icon:hover {
            transform: translateY(-3px);
            color: #64ffda;
        }

        .stats-card {
             background-color: #0a192f;
        }
    </style>
</head>
<body class="antialiased">

    <div class="main-container rounded-xl w-full max-w-6xl h-auto md:h-auto md:max-h-[90vh] flex flex-col md:flex-row overflow-hidden">
        
        <!-- Left Column: Personal Info -->
        <div class="w-full md:w-1/3 lg:w-2/5 p-8 md:p-12 flex flex-col justify-center">
            <div>
                <h1 class="text-4xl lg:text-5xl font-bold text-white">Yash Siddhapura</h1>
                <p class="mt-4 text-lg text-slate-400">
                    Electronics Engineering student passionate about RTL design and verification.
                </p>
                <div class="mt-8 flex items-center space-x-5">
                    <a href="mailto:siddhapurayash09@gmail.com" class="text-slate-400 contact-icon" aria-label="Email">
                        <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                    </a>
                    <a href="https://www.linkedin.com/in/yash-siddhapura/" target="_blank" rel="noopener noreferrer" class="text-slate-400 contact-icon" aria-label="LinkedIn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
                    </a>
                    <a href="https://github.com/Siddhapura-Yash" target="_blank" rel="noopener noreferrer" class="text-slate-400 contact-icon" aria-label="GitHub">
                        <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
                    </a>
                </div>
            </div>
        </div>

        <!-- Right Column: Skills, Tools & Stats -->
        <div class="w-full md:w-2/3 lg:w-3/5 p-8 md:p-12 bg-gray-900/20 overflow-y-auto">
            
            <!-- Skills Section -->
            <section class="mb-8">
                <h2 class="text-xl font-bold text-white mb-4">Skills</h2>
                <div class="flex flex-wrap gap-3">
                    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
                    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
                    <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"/>
                    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
                    <img src="https://img.shields.io/badge/Verilog-1C1C1C?style=for-the-badge&logo=verilog&logoColor=white" alt="Verilog"/>
                    <img src="https://img.shields.io/badge/VHDL-8EBF41?style=for-the-badge&logo=vhdl&logoColor=white" alt="VHDL"/>
                    <img src="https://img.shields.io/badge/SystemVerilog-0A5499?style=for-the-badge&logo=systemverilog&logoColor=white" alt="SystemVerilog"/>
                </div>
            </section>

            <!-- Tools Section -->
            <section class="mb-8">
                <h2 class="text-xl font-bold text-white mb-4">Tools</h2>
                <div class="flex flex-wrap gap-3">
                    <img src="https://img.shields.io/badge/Xilinx_Vivado-161616?style=for-the-badge&logo=xilinx&logoColor=white" alt="Vivado"/>
                    <img src="https://img.shields.io/badge/Quartus-00285A?style=for-the-badge&logo=intel&logoColor=white" alt="Quartus"/>
                    <img src="https://img.shields.io/badge/Modelsim-2496ED?style=for-the-badge&logo=siemens&logoColor=white" alt="Modelsim"/>
                    <img src="https://img.shields.io/badge/Proteus-00599C?style=for-the-badge&logoColor=white" alt="Proteus"/>
                    <img src="https://img.shields.io/badge/EDA%20Playground-555555?style=for-the-badge&logoColor=white" alt="EDA Playground"/>
                </div>
            </section>

            <!-- Most Used Languages Section -->
            <section>
                <h2 class="text-lg font-semibold text-slate-300 mb-4">Most Used Languages</h2>
                <div>
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Siddhapura-Yash&layout=compact&theme=dracula&hide_border=true&bg_color=0a192f&title_color=64ffda&text_color=ccd6f6" alt="Yash's Top Languages" class="stats-card rounded-lg w-full"/>
                </div>
            </section>

        </div>

    </div>

</body>
</html>
