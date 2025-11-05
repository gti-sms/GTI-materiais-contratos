<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Controle de Materiais de Limpeza - SMS</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #1a5276;
            --primary-dark: #13405c;
            --primary-light: #2e86c1;
            --secondary: #28a745;
            --accent: #17a2b8;
            --light: #f8f9fa;
            --dark: #343a40;
            --gray: #6c757d;
            --light-gray: #e9ecef;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
        }
        
        header {
            background: linear-gradient(to right, var(--primary), var(--primary-dark));
            color: white;
            padding: 1.5rem 2rem;
            box-shadow: var(--shadow);
            position: relative;
            overflow: hidden;
        }
        
        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 1200px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }
        
        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .logo {
            font-size: 2.5rem;
            color: white;
        }
        
        .header-text h1 {
            font-size: 1.8rem;
            margin-bottom: 0.25rem;
            font-weight: 600;
        }
        
        .header-text p {
            opacity: 0.9;
            font-size: 1rem;
        }
        
        .header-decoration {
            position: absolute;
            top: -20px;
            right: -20px;
            width: 150px;
            height: 150px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            z-index: 1;
        }
        
        .header-decoration::after {
            content: '';
            position: absolute;
            top: 30px;
            right: 30px;
            width: 90px;
            height: 90px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .dashboard {
            background: white;
            border-radius: 10px;
            box-shadow: var(--shadow);
            padding: 2rem;
            margin-bottom: 2rem;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .stat-card {
            background: var(--light);
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            transition: var(--transition);
        }
        
        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .stat-card i {
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        
        .stat-card h3 {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
            color: var(--primary);
        }
        
        .stat-card p {
            color: var(--gray);
            font-size: 0.9rem;
        }
        
        .search-box {
            display: flex;
            gap: 1rem;
            margin-bottom: 2rem;
        }
        
        .search-box input {
            flex: 1;
            padding: 0.75rem 1rem;
            border: 1px solid var(--light-gray);
            border-radius: 8px;
            font-size: 1rem;
            transition: var(--transition);
        }
        
        .search-box input:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(26, 82, 118, 0.2);
        }
        
        .search-box button {
            background: var(--primary);
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1rem;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .search-box button:hover {
            background: var(--primary-dark);
        }
        
        .units-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        
        .unit-card {
            background: white;
            border-radius: 10px;
            box-shadow: var(--shadow);
            padding: 1.5rem;
            transition: var(--transition);
            border-left: 4px solid var(--primary);
            position: relative;
            overflow: hidden;
        }
        
        .unit-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .unit-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(to right, var(--primary), var(--accent));
        }
        
        .unit-name {
            font-weight: 600;
            margin-bottom: 1rem;
            color: var(--primary);
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .unit-name i {
            color: var(--accent);
        }
        
        .unit-link {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            background: var(--primary);
            color: white;
            text-decoration: none;
            padding: 0.6rem 1.2rem;
            border-radius: 6px;
            font-weight: 500;
            transition: var(--transition);
            margin-top: 0.5rem;
            font-size: 0.9rem;
        }
        
        .unit-link:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
        }
        
        .confirmation-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            backdrop-filter: blur(5px);
        }
        
        .modal-content {
            background-color: white;
            padding: 2.5rem;
            border-radius: 12px;
            max-width: 500px;
            width: 90%;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            text-align: center;
            position: relative;
            animation: modalAppear 0.3s ease-out;
        }
        
        @keyframes modalAppear {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .modal-icon {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .modal-content h2 {
            margin-bottom: 1rem;
            color: var(--primary);
        }
        
        .modal-content p {
            margin-bottom: 1.5rem;
            color: var(--gray);
        }
        
        .modal-buttons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1.5rem;
        }
        
        .btn {
            padding: 0.7rem 1.8rem;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 500;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .btn-confirm {
            background: var(--secondary);
            color: white;
        }
        
        .btn-confirm:hover {
            background: #218838;
            transform: translateY(-2px);
        }
        
        .btn-cancel {
            background: var(--light-gray);
            color: var(--dark);
        }
        
        .btn-cancel:hover {
            background: #d6d8db;
            transform: translateY(-2px);
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
            color: var(--gray);
            border-top: 1px solid var(--light-gray);
            font-size: 0.9rem;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 1rem;
        }
        
        .footer-links a {
            color: var(--primary);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .footer-links a:hover {
            color: var(--primary-dark);
            text-decoration: underline;
            transform: translateY(-2px);
        }
        
        .whatsapp-link {
            background: #25D366;
            color: white !important;
            padding: 0.5rem 1rem;
            border-radius: 25px;
            font-weight: 600;
        }
        
        .whatsapp-link:hover {
            background: #128C7E;
            text-decoration: none !important;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
            
            .units-grid {
                grid-template-columns: 1fr;
            }
            
            .search-box {
                flex-direction: column;
            }
            
            .stats {
                grid-template-columns: 1fr;
            }
            
            .modal-buttons {
                flex-direction: column;
            }
            
            .footer-links {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-decoration"></div>
        <div class="header-content">
            <div class="logo-container">
                <i class="fas fa-hand-holding-medical logo"></i>
                <div class="header-text">
                    <h1>Secretaria Municipal de Saúde - SMS</h1>
                    <p>Controle de Materiais de Limpeza - Unidades de Saúde</p>
                </div>
            </div>
            <div class="header-stats">
                <div style="display: flex; gap: 1rem;">
                    <div style="text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold;">48</div>
                        <div style="font-size: 0.8rem;">Unidades</div>
                    </div>
                    <div style="width: 1px; background: rgba(255,255,255,0.3);"></div>
                    <div style="text-align: center;">
                        <div style="font-size: 1.5rem; font-weight: bold;">100%</div>
                        <div style="font-size: 0.8rem;">Ativas</div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    
    <div class="container">
        <div class="dashboard">
            <div class="stats">
                <div class="stat-card">
                    <i class="fas fa-clipboard-check"></i>
                    <h3>48</h3>
                    <p>Formulários Disponíveis</p>
                </div>
                <div class="stat-card">
                    <i class="fas fa-sync-alt"></i>
                    <h3>Atualizado</h3>
                    <p>Dados em Tempo Real</p>
                </div>
                <div class="stat-card">
                    <i class="fas fa-shield-alt"></i>
                    <h3>Seguro</h3>
                    <p>Acesso Controlado</p>
                </div>
                <div class="stat-card">
                    <i class="fas fa-headset"></i>
                    <h3>Suporte</h3>
                    <p>Assistência Técnica</p>
                </div>
            </div>
            
            <div class="search-box">
                <input type="text" id="searchInput" placeholder="Digite o nome da unidade para filtrar...">
                <button id="searchButton">
                    <i class="fas fa-search"></i> Buscar
                </button>
            </div>
            
            <div class="units-grid" id="unitsGrid">
                <!-- As unidades serão carregadas aqui via JavaScript -->
            </div>
        </div>
    </div>
    
    <div class="confirmation-modal" id="confirmationModal">
        <div class="modal-content">
            <i class="fas fa-clipboard-list modal-icon"></i>
            <h2>Confirmação de Acesso</h2>
            <p>Você está prestes a acessar o formulário de materiais de limpeza para a unidade:</p>
            <p><strong id="modalUnitName"></strong></p>
            <p>Acesso para o gerente realizar o preenchimento - E-mail da sua Unidade</p>
            <div class="modal-buttons">
                <button class="btn btn-cancel" id="cancelButton">
                    <i class="fas fa-times"></i> Cancelar
                </button>
                <button class="btn btn-confirm" id="confirmButton">
                    <i class="fas fa-external-link-alt"></i> Acessar Formulário
                </button>
            </div>
        </div>
    </div>
    
    <footer>
        <div class="footer-content">
            <p>Secretaria Municipal de Saúde - Sistema de Controle de Materiais de Limpeza</p>
            <p>© 2025 - Todos os direitos reservados</p>
            <div class="footer-links">
                <a href="#"><i class="fas fa-question-circle"></i> Ajuda</a>
                <a href="https://wa.me/555499771610?text=Olá!%20Preciso%20de%20suporte%20técnico%20para%20o%20Sistema%20de%20Controle%20de%20Materiais%20de%20Limpeza%20da%20SMS" class="whatsapp-link">
                    <i class="fab fa-whatsapp"></i> Suporte GTI - (54) 9977-1610
                </a>
                <a href="#"><i class="fas fa-shield-alt"></i> Privacidade</a>
                <a href="#"><i class="fas fa-file-alt"></i> Termos de Uso</a>
            </div>
        </div>
    </footer>
    
    <script>
        // Dados das unidades
        const units = [
            { name: "Ambulatório Bela Vista", url: "https://docs.google.com/spreadsheets/d/1Isxox5JM_9Vx0GXkC3ZbIO2tBoTWdD1FA5zDHDYFXWQ/edit?usp=sharing" },
            { name: "Ambulatório Capinzal", url: "https://docs.google.com/spreadsheets/d/1pkHbzsGgZ_veNC6ZrrjF-ToXiT3ui9KIkYo5r8br4m4/edit?usp=sharing" },
            { name: "Ambulatório Especialidades", url: "https://docs.google.com/spreadsheets/d/1Gi62kirWVRvUf93TEvyMXO1D36cdZ-Fj-kr1NMnp4eQ/edit?usp=sharing" },
            { name: "Ambulatório Pulador", url: "https://docs.google.com/spreadsheets/d/1paw1nwQFb-MfOOmUydA3d3EIrS8XZWKjfjBiEWoGwIs/edit?usp=sharing" },
            { name: "Ambulatório São Valentin/São Roque", url: "https://docs.google.com/spreadsheets/d/1pBd0NII9lkCs4AjEgBetLw-eVLc9Rz3ZEQLhi-E1NgY/edit?usp=sharing" },
            { name: "Cais Dr. Antônio Marinho Albuquerque – Vila Luíza", url: "https://docs.google.com/spreadsheets/d/1vmGatR4fnWFjsbVK9zEo5J1hcYFQQlnP1v8wHk2w_mE/edit?usp=sharing" },
            { name: "Cais Dr. Cyrio Nacul – Petrópolis", url: "https://docs.google.com/spreadsheets/d/1LWEq2oQopnvV-CwMPaTuJ4q-CnHB02b6nBdZEF85aZE/edit?usp=sharing" },
            { name: "Cais Dr. Erwin Crussius – Hípica", url: "https://docs.google.com/spreadsheets/d/1zgoDmusVt1xzzTD2Mac_JOZbE-LHPUwrl83yWi5MOjs/edit?usp=sharing" },
            { name: "Cais Dr. Luís Augusto Hexsel – Boqueirão", url: "https://docs.google.com/spreadsheets/d/1zgoDmusVt1xzzTD2Mac_JOZbE-LHPUwrl83yWi5MOjs/edit?usp=sharing" },
            { name: "Cais Dr. Luís Fragomeni – São Cristóvão", url: "https://docs.google.com/spreadsheets/d/1K4V0xWRXA0TV17ABkAW1pRMKCq_8vutLdZP1iYic1s8/edit?usp=sharing" },
            { name: "Caps Ad", url: "https://docs.google.com/spreadsheets/d/1aVUAMx5PT2JdBSp7vlTVth1a03Fca2ZxBDCUdHmbId0/edit?usp=sharing" },
            { name: "Caps I", url: "https://docs.google.com/spreadsheets/d/12WO4BAAAon-_bKTcR6LHkLn42H-sQrN7-6refW8lk7M/edit?usp=sharing" },
            { name: "Caps II", url: "https://docs.google.com/spreadsheets/d/12WO4BAAAon-_bKTcR6LHkLn42H-sQrN7-6refW8lk7M/edit?usp=sharing" },
            { name: "Central de Vacinas", url: "https://docs.google.com/spreadsheets/d/1c1npV4dk1du1cJ3ZYnJS1f9oLfsbFoEgJ517bbjMQ6o/edit?usp=sharing" },
            { name: "Centro de Referência de Saúde da Mulher", url: "https://docs.google.com/spreadsheets/d/1ha6k11NHABlQVPIsy8vJK65bBvc4WWc60-DB7OjrUzM/edit?usp=sharing" },
            { name: "Centro de Referência de Saúde do Idoso", url: "https://docs.google.com/spreadsheets/d/1cCSmcp9xQcp6Ax1r3xEuAhNkEY39DiRxDohwxLYza_E/edit?usp=sharing" },
            { name: "Capne", url: "https://docs.google.com/spreadsheets/d/160Q72HacnruMRiJIKZg3qJwT-D8w7mb5NbadYbtYu3A/edit?usp=sharing" },
            { name: "Coordenadoria de Vigilância em Saúde", url: "https://docs.google.com/spreadsheets/d/1N0m5qMOtYr_Rw6gHV57Jj2uz37GjjnZyVZf6VBbleM0/edit?usp=sharing" },
            { name: "ESF 1º Centenário", url: "https://docs.google.com/spreadsheets/d/1DOue-0t2_2PapvEYAwwu7SGo2BCMAcgDtcAt2BaymUc/edit?usp=sharing" },
            { name: "ESF Adirbal Corralo", url: "https://docs.google.com/spreadsheets/d/1B-X93vNUYnhJP2-cwWLpJLkBxL-HrCzOE_0Gn_aUGik/edit?usp=sharing" },
            { name: "ESF Adolfo Groth", url: "https://docs.google.com/spreadsheets/d/18iF9CErM8EfPEA6Or6N8f5CPs2TejSLtf1IMfKgArds/edit?usp=sharing" },
            { name: "ESF Adriana Lirio – Operária", url: "https://docs.google.com/spreadsheets/d/14pN1vwHWoc_HFY3MpcwWq-_u4ccFDBa4EnrqHsRA0G8/edit?usp=sharing" },
            { name: "ESF Edu Villa de Azambuja (Caic)", url: "https://docs.google.com/spreadsheets/d/1pxbyMDEA0RwwIQR8-erBfrvE_JMHFF6scnP6vAFrwsg/edit?usp=sharing" },
            { name: "ESF Jaboticabal", url: "https://docs.google.com/spreadsheets/d/1iPrOdXGlOFQmdKGMZgxB-gxrSkIFbR4twp8L9i2mjyY/edit?usp=sharing" },
            { name: "ESF Jerônimo Coelho", url: "https://docs.google.com/spreadsheets/d/1papQ1EzyA7864xdkMrl2BTAd8G7LOaKmQ1jghqih4yM/edit?usp=sharing" },
            { name: "ESF Planaltina", url: "https://docs.google.com/spreadsheets/d/1Gg-RP403UQSCuQcoerdxId1U04syTb5QjNoKc3gBasQ/edit?usp=sharing" },
            { name: "ESF Ricci", url: "https://docs.google.com/spreadsheets/d/1U4X1DX1T3zxiEkxYCGiRAR3jPTiJLCJBTPHvr43De-M/edit?usp=sharing" },
            { name: "ESF Santa Marta / ESF Donária", url: "https://docs.google.com/spreadsheets/d/1g7jnkYWwpUVoq0xK9zDK5j8yJOy422FpjgAaP_sOmMM/edit?usp=sharing" },
            { name: "ESF São Cristóvão", url: "https://docs.google.com/spreadsheets/d/1ZJsQXxMmJm9Pu5b8oko-n22oFcGu-mhw7FNiAvJl4WM/edit?usp=sharing" },
            { name: "ESF São Luiz Gonzaga", url: "https://docs.google.com/spreadsheets/d/12jfjhw8rLdvbjjXmaLA7F8Zmsm831Y63-T9we4SkOgI/edit?usp=sharing" },
            { name: "Farmácia Central", url: "https://docs.google.com/spreadsheets/d/1BbGbyRoCM9p8wdNcN5JSb5M07PrTfpP-RLy1Dy6NAps/edit?usp=sharing" },
            { name: "SAMU", url: "https://docs.google.com/spreadsheets/d/1_HZj4YfbqVo8JaQwo5NX4IWcRtQYg00EwEy89kXn8kM/edit?usp=sharing" },
            { name: "Secretaria Municipal De Saúde", url: "https://docs.google.com/spreadsheets/d/1tO1i-BPC6OoGZWLFup-me4aFeyeXI7bDdTqcOUX7XYM/edit?usp=sharing" },
            { name: "Serviço de Atendimento Especializado – SAE", url: "https://docs.google.com/spreadsheets/d/1nNQN5mdBCRb8VMy_Hr56ZeDd1wl8ezXuMqefSVNon1w/edit?usp=sharing" },
            { name: "UBS Annes", url: "https://docs.google.com/spreadsheets/d/1Ky8frymYfZqsdmdzMY1cEpNMYQhElTeum-x3ZPsFkeY/edit?usp=sharing" },
            { name: "UBS Bom Recreio", url: "https://docs.google.com/spreadsheets/d/1e7zz5sghpbdQM_on2R2aLYwoKj8F52B1seSlLLTRUSw/edit?usp=sharing" },
            { name: "UBS Entre Rios", url: "https://docs.google.com/spreadsheets/d/1Fkw7OunZw2HigxtH16soT115hw8JkhU1J_TxhcUC5oA/edit?usp=sharing" },
            { name: "UBS Independente", url: "https://docs.google.com/spreadsheets/d/1z25XuIqkKYbrJO1Lf2TU1SNr68UbakRU_Z3Zsw84Qhg/edit?usp=sharing" },
            { name: "UBS Ivo Ferreira", url: "https://docs.google.com/spreadsheets/d/1gKaJUFDy3mVQNiPNeq3BUzUKPaiVcZKo5H49-RvV8zY/edit?usp=sharing" },
            { name: "UBS Nossa Senhora Aparecida", url: "https://docs.google.com/spreadsheets/d/15oZdBErm5wMdZHaenmUxl6YZ-ExgHH6rqKrcZe07W1Q/edit?usp=sharing" },
            { name: "UBS Parque Farroupilha", url: "https://docs.google.com/spreadsheets/d/1X1IUnCGgXk8NmLkK7Sh5o3bQQTF7vpepOhkJGGAmU9A/edit?usp=sharing" },
            { name: "UBS Petrópolis", url: "https://docs.google.com/spreadsheets/d/16ipxtGe9rZbWlawfjTkBxxD0pPPog8QyW6ZjO9TbyoA/edit?usp=sharing" },
            { name: "UBS Santa Rita", url: "https://docs.google.com/spreadsheets/d/1INRxMpgcLhueL_uBwd4cEqCTc47u2AuiNc8SK_Cv-8I/edit?usp=sharing" },
            { name: "UBS Santo Antônio Da Pedreira", url: "https://docs.google.com/spreadsheets/d/1cRDWNIaRSVbBquafLatYmW4SS_r9RWJr2yZoYhz8nyU/edit?usp=sharing" },
            { name: "UBS Vila Nova", url: "https://docs.google.com/spreadsheets/d/1P2tVpszvSF9AFOGiA5o6C_GpipsCjxrF3-_JCVllVYs/edit?usp=sharing" }
        ];

        // Elementos DOM
        const unitsGrid = document.getElementById('unitsGrid');
        const searchInput = document.getElementById('searchInput');
        const searchButton = document.getElementById('searchButton');
        const confirmationModal = document.getElementById('confirmationModal');
        const modalUnitName = document.getElementById('modalUnitName');
        const cancelButton = document.getElementById('cancelButton');
        const confirmButton = document.getElementById('confirmButton');
        
        let selectedUnitUrl = '';
        
        // Função para renderizar as unidades
        function renderUnits(unitsToRender) {
            unitsGrid.innerHTML = '';
            
            if (unitsToRender.length === 0) {
                unitsGrid.innerHTML = '<p style="grid-column: 1 / -1; text-align: center; padding: 2rem; color: var(--gray);">Nenhuma unidade encontrada com o termo pesquisado.</p>';
                return;
            }
            
            unitsToRender.forEach(unit => {
                const unitCard = document.createElement('div');
                unitCard.className = 'unit-card';
                
                unitCard.innerHTML = `
                    <div class="unit-name">
                        <i class="fas fa-clinic-medical"></i>
                        ${unit.name}
                    </div>
                    <a href="#" class="unit-link" data-url="${unit.url}" data-name="${unit.name}">
                        <i class="fas fa-external-link-alt"></i> Acessar Formulário
                    </a>
                `;
                
                unitsGrid.appendChild(unitCard);
            });
            
            // Adicionar event listeners aos links
            document.querySelectorAll('.unit-link').forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const url = this.getAttribute('data-url');
                    const name = this.getAttribute('data-name');
                    showConfirmationModal(name, url);
                });
            });
        }
        
        // Função para mostrar o modal de confirmação
        function showConfirmationModal(unitName, unitUrl) {
            modalUnitName.textContent = unitName;
            selectedUnitUrl = unitUrl;
            confirmationModal.style.display = 'flex';
        }
        
        // Função para filtrar unidades
        function filterUnits() {
            const searchTerm = searchInput.value.toLowerCase();
            const filteredUnits = units.filter(unit => 
                unit.name.toLowerCase().includes(searchTerm)
            );
            renderUnits(filteredUnits);
        }
        
        // Event Listeners
        searchButton.addEventListener('click', filterUnits);
        searchInput.addEventListener('keyup', function(e) {
            if (e.key === 'Enter') {
                filterUnits();
            }
        });
        
        cancelButton.addEventListener('click', function() {
            confirmationModal.style.display = 'none';
        });
        
        confirmButton.addEventListener('click', function() {
            window.open(selectedUnitUrl, '_blank');
            confirmationModal.style.display = 'none';
        });
        
        // Fechar modal ao clicar fora dele
        confirmationModal.addEventListener('click', function(e) {
            if (e.target === confirmationModal) {
                confirmationModal.style.display = 'none';
            }
        });
        
        // Inicializar a página
        renderUnits(units);
    </script>
</body>
</html>
