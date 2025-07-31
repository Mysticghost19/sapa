<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cofre Temporal Digital</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', monospace;
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
            min-height: 100vh;
            color: #eee;
            padding: 20px;
            animation: backgroundShift 10s ease-in-out infinite alternate;
        }

        @keyframes backgroundShift {
            0% { background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%); }
            100% { background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); }
        }

        .system-header {
            background: linear-gradient(135deg, #2d3748 0%, #1a202c 100%);
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 25px;
            border-left: 5px solid #4299e1;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            color: #90cdf4;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            position: relative;
            overflow: hidden;
        }

        .system-header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #4299e1, #68d391, #4299e1);
            animation: loadingBar 3s ease-in-out infinite;
        }

        @keyframes loadingBar {
            0%, 100% { transform: translateX(-100%); }
            50% { transform: translateX(100%); }
        }

        .code-line {
            color: #68d391;
            margin: 5px 0;
            opacity: 0;
            animation: typeWriter 0.5s ease forwards;
        }

        .comment {
            color: #a0aec0;
        }

        @keyframes typeWriter {
            from { opacity: 0; transform: translateX(-10px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .container {
            background: rgba(45, 55, 72, 0.98);
            border-radius: 20px;
            padding: 35px;
            max-width: 700px;
            margin: 0 auto;
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4);
            border: 2px solid #4a5568;
            position: relative;
            backdrop-filter: blur(10px);
        }

        .container::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #4299e1, #68d391, #ed8936, #e53e3e);
            z-index: -1;
            border-radius: 20px;
            opacity: 0.6;
            animation: borderGlow 4s ease-in-out infinite;
        }

        @keyframes borderGlow {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 0.8; }
        }

        h1 {
            color: #90cdf4;
            margin-bottom: 15px;
            font-size: 2.5em;
            text-align: center;
            text-shadow: 0 0 20px rgba(144, 205, 244, 0.5);
            animation: titlePulse 2s ease-in-out infinite alternate;
        }

        @keyframes titlePulse {
            from { text-shadow: 0 0 20px rgba(144, 205, 244, 0.5); }
            to { text-shadow: 0 0 30px rgba(144, 205, 244, 0.8); }
        }

        .subtitle {
            color: #cbd5e0;
            margin-bottom: 30px;
            text-align: center;
            font-size: 1.1em;
            opacity: 0.8;
        }

        .status-bar {
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 25px;
            font-family: 'Courier New', monospace;
            font-size: 13px;
            color: #68d391;
            border: 2px solid #2d3748;
            position: relative;
            overflow: hidden;
        }

        .status-bar::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(104, 211, 145, 0.1), transparent);
            animation: scanLine 2s linear infinite;
        }

        @keyframes scanLine {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .form-group {
            margin-bottom: 25px;
        }

        label {
            display: block;
            margin-bottom: 10px;
            color: #e2e8f0;
            font-weight: bold;
            font-size: 1.1em;
        }

        input[type="file"], textarea, select {
            width: 100%;
            padding: 15px;
            border: 2px solid #4a5568;
            border-radius: 12px;
            font-size: 16px;
            background: linear-gradient(135deg, #2d3748 0%, #1a202c 100%);
            color: #e2e8f0;
            transition: all 0.3s ease;
            font-family: inherit;
        }

        input[type="file"]:focus, textarea:focus, select:focus {
            outline: none;
            border-color: #4299e1;
            box-shadow: 0 0 0 4px rgba(66, 153, 225, 0.2);
            transform: translateY(-2px);
        }

        textarea {
            min-height: 120px;
            resize: vertical;
            line-height: 1.6;
        }

        .time-selector {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        button {
            background: linear-gradient(135deg, #4299e1 0%, #3182ce 100%);
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 12px;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin: 10px 8px;
            font-family: 'Courier New', monospace;
            font-weight: bold;
            position: relative;
            overflow: hidden;
        }

        button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s;
        }

        button:hover::before {
            left: 100%;
        }

        button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(66, 153, 225, 0.4);
        }

        .clear-btn {
            background: linear-gradient(135deg, #e53e3e 0%, #c53030 100%);
        }

        .clear-btn:hover {
            box-shadow: 0 10px 25px rgba(229, 62, 62, 0.4);
        }

        .messages-section {
            margin-top: 35px;
            padding-top: 25px;
            border-top: 3px solid #4a5568;
        }

        .message-item {
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 20px;
            border-left: 5px solid #4299e1;
            position: relative;
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .message-item:hover {
            transform: translateX(5px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        .message-item img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .message-time {
            color: #a0aec0;
            font-size: 0.95em;
            margin-bottom: 8px;
        }

        .waiting-message {
            border-left-color: #ed8936;
            background: linear-gradient(135deg, #2d2016 0%, #3d2817 100%);
            animation: waitingPulse 3s ease-in-out infinite;
        }

        @keyframes waitingPulse {
            0%, 100% { opacity: 0.8; }
            50% { opacity: 1; }
        }

        .ready-message {
            border-left-color: #48bb78;
            background: linear-gradient(135deg, #1c2e1c 0%, #2d5a2d 100%);
            animation: readyGlow 2s ease-in-out;
        }

        @keyframes readyGlow {
            0% { box-shadow: 0 0 5px rgba(72, 187, 120, 0.3); }
            50% { box-shadow: 0 0 25px rgba(72, 187, 120, 0.7); }
            100% { box-shadow: 0 0 5px rgba(72, 187, 120, 0.3); }
        }

        .countdown {
            font-weight: bold;
            color: #ed8936;
            margin-top: 12px;
            font-size: 1.1em;
            text-shadow: 0 0 10px rgba(237, 137, 54, 0.5);
        }

        .terminal {
            background: linear-gradient(135deg, #000 0%, #1a1a1a 100%);
            color: #0f0;
            padding: 12px;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            font-size: 13px;
            margin: 15px 0;
            border: 2px solid #333;
            box-shadow: inset 0 0 10px rgba(0, 255, 0, 0.1);
            position: relative;
        }

        .terminal::before {
            content: '$';
            color: #0f0;
            margin-right: 5px;
            animation: blink 1s infinite;
        }

        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }

        .system-activity {
            position: fixed;
            top: 20px;
            right: 20px;
            background: rgba(0, 0, 0, 0.8);
            color: #0f0;
            padding: 10px;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            font-size: 12px;
            opacity: 0;
            transition: all 0.3s ease;
            pointer-events: none;
            z-index: 1000;
        }

        .system-activity.show {
            opacity: 1;
            transform: translateX(-10px);
        }

        @media (max-width: 768px) {
            .container {
                padding: 20px;
                margin: 10px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .time-selector {
                grid-template-columns: 1fr;
                gap: 10px;
            }
            
            button {
                margin: 5px 0;
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div id="systemActivity" class="system-activity"></div>

    <div class="system-header">
        <div class="comment"># cofre_temporal.js - Sistema de Cápsula do Tempo</div>
        <div class="code-line" style="animation-delay: 0.1s;">const crypto = require('crypto');</div>
        <div class="code-line" style="animation-delay: 0.2s;">const fs = require('fs');</div>
        <div class="code-line" style="animation-delay: 0.3s;">const express = require('express');</div>
        <div class="code-line" style="animation-delay: 0.4s;"></div>
        <div class="code-line" style="animation-delay: 0.5s;">let database = [];</div>
        <div class="code-line" style="animation-delay: 0.6s;">let activeTimers = new Map();</div>
        <div class="code-line" style="animation-delay: 0.7s;"></div>
        <div class="code-line" style="animation-delay: 0.8s;">function encryptData(data) {</div>
        <div class="code-line" style="animation-delay: 0.9s;">&nbsp;&nbsp;return Buffer.from(data).toString('base64');</div>
        <div class="code-line" style="animation-delay: 1.0s;">}</div>
        <div class="code-line" style="animation-delay: 1.1s;"></div>
        <div class="code-line" style="animation-delay: 1.2s;">function calculateUnlockTime(amount, unit) {</div>
        <div class="code-line" style="animation-delay: 1.3s;">&nbsp;&nbsp;const now = new Date();</div>
        <div class="code-line" style="animation-delay: 1.4s;">&nbsp;&nbsp;let multiplier = 1000;</div>
        <div class="code-line" style="animation-delay: 1.5s;">&nbsp;&nbsp;if (unit === 'minutes') multiplier *= 60;</div>
        <div class="code-line" style="animation-delay: 1.6s;">&nbsp;&nbsp;if (unit === 'hours') multiplier *= 3600;</div>
        <div class="code-line" style="animation-delay: 1.7s;">&nbsp;&nbsp;return new Date(now.getTime() + amount * multiplier);</div>
        <div class="code-line" style="animation-delay: 1.8s;">}</div>
    </div>

    <div class="container">
        <h1>🔒 Cofre Temporal</h1>
        <p class="subtitle">Cápsula do Tempo Digital - Sistema de Mensagens Criptografadas</p>

        <div class="status-bar">
            <div id="systemStatus">⚡ Sistema: <span style="color: #48bb78;">ATIVO</span> | Servidor: <span style="color: #4299e1;">Node.js</span> | Cofres: <span id="msgCount">0</span> | Runtime: <span id="uptime">0s</span></div>
        </div>

        <div class="form-group">
            <label for="messageText">💌 Mensagem para o Futuro:</label>
            <textarea id="messageText" placeholder="Escreva sua mensagem que será guardada até o momento escolhido..."></textarea>
        </div>

        <div class="form-group">
            <label for="imageUpload">📸 Anexar Imagem:</label>
            <input type="file" id="imageUpload" accept="image/*">
        </div>

        <div class="form-group">
            <label>⏰ Tempo de Bloqueio:</label>
            <div class="time-selector">
                <select id="timeAmount">
                    <option value="5">5</option>
                    <option value="10">10</option>
                    <option value="15">15</option>
                    <option value="30">30</option>
                    <option value="1">1</option>
                    <option value="2">2</option>
                    <option value="5">5</option>
                    <option value="10">10</option>
                    <option value="60">60</option>
                </select>
                <select id="timeUnit">
                    <option value="seconds">Segundos</option>
                    <option value="minutes">Minutos</option>
                    <option value="hours">Horas</option>
                    <option value="days">Dias</option>
                </select>
            </div>
        </div>

        <button onclick="createTimeCapsule()">🚀 Criar Cápsula</button>
        <button class="clear-btn" onclick="clearDatabase()">🗑️ Limpar Cofre</button>

        <div id="terminal" class="terminal" style="display: none;"></div>

        <div class="messages-section">
            <h3>📦 Cápsulas do Tempo Ativas</h3>
            <div id="messagesList"></div>
        </div>
    </div>

    <script>
        let database = [];
        let systemUptime = 0;
        let systemProcesses = [
            'checkTimers() -> checking locks',
            'for (timer of activeTimers) validate()',
            'if (now > unlockTime) decrypt(message)',
            'server.listen(3000)',
            'try { processQueue() } catch(e) {}',
            'setInterval(() => monitor(), 1000)',
            'database.length === 0',
            'crypto.randomBytes(16)',
            'fs.writeSync(logFile, data)',
            'const unlocked = findExpired()'
        ];

        const STORAGE_KEY = 'temporal_vault_db';

        document.addEventListener('DOMContentLoaded', function() {
            loadDatabase();
            startSystemDaemon();
            startUptimeCounter();
            startSystemActivity();
        });

        function startUptimeCounter() {
            setInterval(() => {
                systemUptime++;
                const hours = Math.floor(systemUptime / 3600);
                const minutes = Math.floor((systemUptime % 3600) / 60);
                const seconds = systemUptime % 60;
                
                let uptimeStr = '';
                if (hours > 0) uptimeStr += `${hours}h `;
                if (minutes > 0) uptimeStr += `${minutes}m `;
                uptimeStr += `${seconds}s`;
                
                document.getElementById('uptime').textContent = uptimeStr;
            }, 1000);
        }

        function startSystemActivity() {
            setInterval(() => {
                if (Math.random() < 0.12) {
                    showSystemActivity();
                }
            }, 4000);
        }

        function showSystemActivity() {
            const activity = systemProcesses[Math.floor(Math.random() * systemProcesses.length)];
            const activityDiv = document.getElementById('systemActivity');
            activityDiv.textContent = activity;
            activityDiv.classList.add('show');
            
            setTimeout(() => {
                activityDiv.classList.remove('show');
            }, 3000);
        }

        function showTerminal(message, delay = 0) {
            setTimeout(() => {
                const terminal = document.getElementById('terminal');
                terminal.style.display = 'block';
                const commands = [
                    'node app.js --production',
                    'npm run encrypt --silent',
                    'for i in {1..10}; do echo $i; done',
                    'if [ "$status" = "ok" ]; then continue; fi',
                    'while read line; do process $line; done',
                    'tail -f /var/log/system.log',
                    'ps aux | grep node',
                    'kill -9 $(pidof defunct)'
                ];
                const randomCmd = commands[Math.floor(Math.random() * commands.length)];
                terminal.innerHTML = `${message}<br><span style="color: #666; font-size: 11px;">${randomCmd}</span>`;
                
                setTimeout(() => {
                    terminal.style.display = 'none';
                }, 3500);
            }, delay);
        }

        function createTimeCapsule() {
            const messageText = document.getElementById('messageText').value.trim();
            const imageFile = document.getElementById('imageUpload').files[0];
            const timeAmount = parseInt(document.getElementById('timeAmount').value);
            const timeUnit = document.getElementById('timeUnit').value;

            if (!messageText && !imageFile) {
                showTerminal('ERROR: Dados insuficientes para criar cápsula');
                alert('Adicione pelo menos uma mensagem ou imagem!');
                return;
            }

            showTerminal('Iniciando processo de criptografia...', 0);
            showTerminal('Calculando timestamp de desbloqueio...', 800);
            showTerminal('Configurando timer automático...', 1600);

            const now = new Date();
            let unlockTime = new Date(now);
            
            switch(timeUnit) {
                case 'seconds':
                    unlockTime.setSeconds(unlockTime.getSeconds() + timeAmount);
                    break;
                case 'minutes':
                    unlockTime.setMinutes(unlockTime.getMinutes() + timeAmount);
                    break;
                case 'hours':
                    unlockTime.setHours(unlockTime.getHours() + timeAmount);
                    break;
                case 'days':
                    unlockTime.setDate(unlockTime.getDate() + timeAmount);
                    break;
            }

            const message = {
                id: Date.now(),
                text: messageText,
                image: null,
                unlockTime: unlockTime.getTime(),
                createdAt: now.getTime(),
                status: 'locked'
            };

            if (imageFile) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    message.image = e.target.result;
                    finalizeCapsule(message);
                };
                reader.readAsDataURL(imageFile);
            } else {
                finalizeCapsule(m
