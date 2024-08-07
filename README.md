<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <p>Josue Gabriel Morales</p>
    <p>Calculo Mercantil</p>
    <title>Explorador del Mercado Bursátil Guatemalteco</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #2c3e50;
            color: #ecf0f1;
            margin: 0;
            padding: 20px;
        }

        .quetzal-container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #34495e;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
        }

        h1 {
            background-color: #e67e22;
            color: #fff;
            padding: 20px;
            margin: 0;
            text-align: center;
            font-size: 2em;
        }

        .menu {
            display: flex;
            background-color: #d35400;
        }

        .menu-item {
            flex: 1;
            padding: 15px;
            text-align: center;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .menu-item:hover {
            background-color: #e67e22;
        }

        .content {
            padding: 20px;
            display: none;
        }

        .active {
            display: block;
        }

        .icon {
            font-size: 24px;
            margin-right: 10px;
        }

        .info-box {
            background-color: #2980b9;
            border-radius: 10px;
            padding: 15px;
            margin-top: 15px;
        }
    </style>
</head>

<body>
    <div class="quetzal-container">
        <h1>🦜 Mercado Bursátil de Guatemala</h1>
        <div class="menu">
            <div class="menu-item" onclick="showContent('base')">🏛️ Base</div>
            <div class="menu-item" onclick="showContent('participa')">🚀 Participa</div>
            <div class="menu-item" onclick="showContent('estrategias')">📊 Estrategias</div>
            <div class="menu-item" onclick="showContent('simulacion')">🎮 Simulación</div>
        </div>

        <div id="base" class="content active">
            <h2>🏛️ Base del Mercado</h2>
            <p>El mercado bursátil guatemalteco, aunque joven, es un pilar en crecimiento para la economía nacional.</p>
            <ul>
                <li>🏢 Bolsa de Valores Nacional (BVN): El corazón del mercado</li>
                <li>💼 Enfoque: Principalmente en instrumentos de deuda</li>
                <li>🌱 Desarrollo: Mercado en expansión con potencial</li>
                <li>👀 Supervisión: Bajo el ojo vigilante de la Superintendencia de Bancos</li>
            </ul>
            <div class="info-box">
                <p>💡 Dato curioso: El quetzal, ave nacional, también nombra la moneda guatemalteca, símbolo de la
                    fortaleza económica del país.</p>
            </div>
        </div>

        <div id="participa" class="content">
            <h2>🚀 Cómo Participar</h2>
            <ol>
                <li>🤝 Contacta un agente de bolsa certificado</li>
                <li>📄 Prepara tu documentación (ID, información financiera)</li>
                <li>💰 Abre tu cuenta de inversión</li>
                <li>🎓 Participa en sesiones de orientación</li>
                <li>🏁 ¡Comienza tu viaje de inversión!</li>
            </ol>
            <div class="info-box">
                <p>⚠️ Recuerda: Invertir conlleva riesgos. Siempre investiga antes de comprometer tu capital.</p>
            </div>
        </div>

        <div id="estrategias" class="content">
            <h2>📊 Estrategias de Inversión</h2>
            <ul>
                <li>🔍 Análisis profundo del mercado local</li>
                <li>🌿 Diversificación: La clave del éxito</li>
                <li>⏳ Inversión a largo plazo vs. trading activo</li>
                <li>📰 Mantente informado sobre noticias económicas</li>
                <li>🤖 Considera herramientas tecnológicas de análisis</li>
            </ul>
            <div class="info-box">
                <p>🌟 Pro-tip: El conocimiento del mercado local puede darte una ventaja competitiva.</p>
            </div>
        </div>

        <div id="simulacion" class="content">
            <h2>🎮 Simulador de Escenarios</h2>
            <p>Explora diferentes escenarios de inversión:</p>
            <ol>
                <li>🏆 "El Conservador": 70% bonos, 30% acciones blue-chip</li>
                <li>🚀 "El Arriesgado": 60% acciones growth, 40% bonos</li>
                <li>🌱 "El Verde": Enfoque en empresas sostenibles</li>
                <li>🔮 "El Visionario": Apuesta por tecnología e innovación</li>
            </ol>
            <div class="info-box">
                <p>🎯 Desafío: Crea tu propio portafolio simulado y sigue su rendimiento durante un mes.</p>
            </div>
        </div>
    </div>

    <script>
        function showContent(id) {
            document.querySelectorAll('.content').forEach(el => el.classList.remove('active'));
            document.getElementById(id).classList.add('active');
        }
    </script>
</body>

</html>
