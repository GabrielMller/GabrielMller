<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil | Gabriel Muller</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');

        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: white;
        }

        /* Container do Ícone (Badges Quadradas) */
        .tech-badge {
            width: 48px;
            height: 48px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 4px;
            transition: transform 0.2s;
            background-color: #161b22;
            padding: 8px;
        }

        .tech-badge:hover {
            transform: translateY(-5px);
        }

        .tech-badge img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }

        /* Badge de Certificação Especial */
        .cert-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background-color: #f4f6f9;
            color: #00A1E0;
            padding: 6px 12px;
            border-radius: 4px;
            font-weight: bold;
            font-size: 12px;
            margin-bottom: 20px;
        }

        /* Botões de Redes Sociais */
        .social-button {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px 20px;
            color: white;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 14px;
            letter-spacing: 1px;
            transition: opacity 0.2s;
            border-radius: 2px;
        }

        .social-button:hover {
            opacity: 0.8;
        }

        .btn-gmail { background-color: #333333; }
        .btn-linkedin { background-color: #0077B5; }

        hr {
            border: 0;
            border-top: 1px solid #30363d;
            margin: 40px 0;
        }
    </style>
</head>
<body class="p-6 md:p-20">

    <div class="max-w-4xl mx-auto">
        
        <!-- Badge de Certificação em Destaque -->
        <div class="cert-badge">
            <img src="https://images.icon-icons.com/2699/PNG/512/mulesoft_logo_icon_170933.png" alt="MuleSoft Icon" class="w-5 h-5">
            MuleSoft Certified Developer - Salesforce
        </div>

        <!-- Saudação -->
        <h1 class="text-3xl md:text-5xl font-bold mb-8">
            Olá, eu sou o Gabriel Muller, Desenvolvedor Fullstack.
        </h1>

        <p class="text-gray-400 text-lg mb-6 leading-relaxed">
            Especialista em ecossistemas de alta disponibilidade. Atuo no desenho e implementação de **APIs escaláveis** e fluxos de integração complexos utilizando **MuleSoft**, **C#**, **Java** e **Kafka**.
        </p>
        
        <p class="text-gray-400 text-lg mb-10">
            Domínio completo do ciclo de vida de APIs (API-led connectivity), do design ao deploy, integrando frontends modernos em **Next.js** a backends resilientes.
        </p>

        <!-- Ícones de Tecnologias -->
        <div class="flex flex-wrap gap-4 mb-12">
            
            <div class="tech-badge" title="MuleSoft" style="background-color: #ffffff;">
                <img src="https://images.icon-icons.com/2699/PNG/512/mulesoft_logo_icon_170933.png" alt="MuleSoft">
            </div>

            <div class="tech-badge" title="C#">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#">
            </div>

            <div class="tech-badge" title="Java">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java">
            </div>

            <div class="tech-badge" title="Kafka" style="background-color: #eeeeee; padding: 4px;">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" alt="Kafka">
            </div>

            <div class="tech-badge" title="JavaScript">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" alt="JS">
            </div>

            <div class="tech-badge" title="TypeScript">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" alt="TS">
            </div>

            <div class="tech-badge" title="Next.js" style="background-color: #fff;">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="Next.js">
            </div>

        </div>

        <hr>

        <!-- Botões de Redes Sociais -->
        <div class="flex flex-wrap gap-2">
            <a href="mailto:seuemail@gmail.com" class="social-button btn-gmail">
                <i class="fas fa-envelope text-lg"></i> GMAIL
            </a>
            <a href="#" class="social-button btn-linkedin">
                <i class="fab fa-linkedin text-lg"></i> LINKEDIN
            </a>
        </div>
    </div>

</body>
</html>
