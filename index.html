# pte-app-for-students
PTE Read Aloud Practice is a free, web-based tool designed to help students improve their speaking and reading skills for the Pearson Test of English (PTE). With a simple interface and smart functionality, this app allows users to paste any passage, read it aloud using their microphone, 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PTE Read Aloud Practice Tool</title>
    <style>
        :root {
            --primary-color: #4a6baf;
            --secondary-color: #f5f7fa;
            --accent-color: #ff7043;
            --text-color: #333;
            --light-text: #666;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            font-size: 16px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--secondary-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        h1 {
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        .subtitle {
            color: var(--light-text);
            font-size: 1.1rem;
        }

        .container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 30px;
            margin-bottom: 30px;
        }

        @media (min-width: 768px) {
            .container {
                grid-template-columns: 1fr 1fr;
            }
        }

        .panel {
            background-color: white;
            border-radius: var(--border-radius);
            padding: 25px;
            box-shadow: var(--box-shadow);
        }

        textarea {
            width: 100%;
            min-height: 200px;
            margin-bottom: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: var(--border-radius);
            font-size: 1rem;
            resize: vertical;
        }

        .button-group {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.2s;
            white-space: nowrap;
        }

        button:hover {
            background-color: #3a5a9f;
        }

        button.secondary {
            background-color: white;
            color: var(--primary-color);
            border: 1px solid var(--primary-color);
        }

        button.secondary:hover {
            background-color: var(--secondary-color);
        }

        button.accent {
            background-color: var(--accent-color);
        }

        button.accent:hover {
            background-color: #e64a19;
        }

        button:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }

        .timer {
            font-size: 1.3rem;
            font-weight: bold;
            text-align: center;
            margin: 20px 0;
            color: var(--primary-color);
        }

        .progress-container {
            width: 100%;
            height: 8px;
            background-color: #eee;
            border-radius: 4px;
            margin: 10px 0;
            overflow: hidden;
        }

        .progress-bar {
            height: 100%;
            background-color: var(--primary-color);
            width: 0%;
            transition: width 0.05s linear;
        }

        .result-panel {
            display: none;
        }

        .result-section {
            margin-bottom: 20px;
        }

        .result-title {
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 8px;
        }

        .highlight {
            background-color: rgba(255, 255, 0, 0.3);
            padding: 0 2px;
        }

        .correct {
            background-color: rgba(0, 255, 0, 0.2);
        }

        .incorrect {
            background-color: rgba(255, 0, 0, 0.2);
        }

        .pronunciation {
            background-color: rgba(0, 0, 255, 0.2);
        }

        .score-card {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .score-item {
            text-align: center;
            padding: 15px;
            border-radius: var(--border-radius);
            background-color: var(--secondary-color);
            min-width: 120px;
            margin: 10px;
        }

        .score-number {
            font-size: 2rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        .score-label {
            font-size: 0.9rem;
            color: var(--light-text);
        }

        .status-message {
            padding: 15px;
            border-radius: var(--border-radius);
            margin-bottom: 20px;
            text-align: center;
        }

        .error {
            background-color: rgba(255, 0, 0, 0.1);
            color: #d32f2f;
        }

        .success {
            background-color: rgba(0, 200, 83, 0.1);
            color: #008000;
        }

        .info {
            background-color: rgba(0, 176, 255, 0.1);
            color: #007bff;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            color: var(--light-text);
            font-size: 0.9rem;
        }

        .compare-container {
            margin-top: 20px;
            background-color: var(--secondary-color);
            padding: 15px;
            border-radius: var(--border-radius);
        }

        .compare-title {
            font-weight: bold;
            margin-bottom: 10px;
            color: var(--primary-color);
        }

        .compare-section {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>PTE Read Aloud Practice Tool</h1>
        <p class="subtitle">Improve your pronunciation, fluency, and content accuracy</p>
    </header>

    <div class="container">
        <div class="panel">
            <h2>Practice Passage</h2>
            <textarea id="passage-input" placeholder="Paste your passage here (or use our sample text)"></textarea>
            
            <div class="button-group">
                <button id="sample-btn">Load Sample Text</button>
                <button id="clear-btn" class="secondary">Clear Text</button>
            </div>

            <div class="timer" id="preparation-timer">Preparation time: 00:40</div>
            <div class="progress-container">
                <div class="progress-bar" id="preparation-progress"></div>
            </div>

            <div class="button-group">
                <button id="record-btn">Start Recording</button>
                <button id="stop-btn" class="secondary" disabled>Stop Recording</button>
                <button id="play-btn" class="secondary" disabled>Play Recording</button>
            </div>

            <div class="timer" id="recording-timer">Recording time: 00:00</div>
            <div class="progress-container">
                <div class="progress-bar" id="recording-progress"></div>
            </div>

            <div id="status-message" class="status-message info">Please paste a passage and click "Start Recording" when ready.</div>

            <button id="submit-btn" class="accent" disabled>Submit for Scoring</button>
        </div>

        <div class="panel result-panel" id="result-panel">
            <h2>Your Results</h2>
            
            <div class="score-card">
                <div class="score-item">
                    <div class="score-number" id="content-score">0</div>
                    <div class="score-label">Content</div>
                </div>
                <div class="score-item">
                    <div class="score-number" id="pronunciation-score">0</div>
                    <div class="score-label">Pronunciation</div>
                </div>
                <div class="score-item">
                    <div class="score-number" id="fluency-score">0</div>
                    <div class="score-label">Fluency</div>
                </div>
                <div class="score-item">
                    <div class="score-number" id="overall-score">0</div>
                    <div class="score-label">Overall</div>
                </div>
            </div>

            <div class="result-section">
                <div class="result-title">Fluency Analysis</div>
                <div id="fluency-analysis">No analysis available yet.</div>
            </div>

            <div class="result-section">
                <div class="result-title">Pronunciation Analysis</div>
                <div id="pronunciation-analysis">No analysis available yet.</div>
            </div>

            <div class="compare-container">
                <div class="compare-title">Original vs Recorded Text</div>
                <div class="compare-section">
                    <div class="result-title">Original Text:</div>
                    <div id="original-text-display"></div>
                </div>
                <div class="compare-section">
                    <div class="result-title">Recorded Text:</div>
                    <div id="recorded-text-display"></div>
                </div>
            </div>

            <button id="new-practice-btn" class="secondary">Practice Again</button>
        </div>
    </div>

    <footer>
        <p>Free PTE Read Aloud practice tool - Works on all devices</p>
    </footer>

    <script>
        // DOM Elements
        const passageInput = document.getElementById('passage-input');
        const sampleBtn = document.getElementById('sample-btn');
        const clearBtn = document.getElementById('clear-btn');
        const recordBtn = document.getElementById('record-btn');
        const stopBtn = document.getElementById('stop-btn');
        const playBtn = document.getElementById('play-btn');
        const submitBtn = document.getElementById('submit-btn');
        const newPracticeBtn = document.getElementById('new-practice-btn');
        const statusMessage = document.getElementById('status-message');
        const preparationTimer = document.getElementById('preparation-timer');
        const recordingTimer = document.getElementById('recording-timer');
        const preparationProgress = document.getElementById('preparation-progress');
        const recordingProgress = document.getElementById('recording-progress');
        const resultPanel = document.getElementById('result-panel');
        const originalTextDisplay = document.getElementById('original-text-display');
        const recordedTextDisplay = document.getElementById('recorded-text-display');
        const fluencyAnalysis = document.getElementById('fluency-analysis');
        const pronunciationAnalysis = document.getElementById('pronunciation-analysis');
        const contentScore = document.getElementById('content-score');
        const pronunciationScore = document.getElementById('pronunciation-score');
        const fluencyScore = document.getElementById('fluency-score');
        const overallScore = document.getElementById('overall-score');

        // Variables
        let mediaRecorder;
        let audioChunks = [];
        let audioBlob;
        let audioUrl;
        let audio;
        let isRecording = false;
        let isPlaying = false;
        let preparationStartTime;
        let recordingStartTime;
        let recordedText = '';
        let preparationInterval;
        let recordingInterval;

        // Sample PTE Reading Passage
        const samplePassage = `The Industrial Revolution was a period of major industrialization that took place during the late 1700s and early 1800s. The Industrial Revolution marked a shift from agrarian societies to industrialized ones, characterized by the development of new manufacturing processes and the introduction of machinery. This period saw significant advancements in technology, transportation, and communication, which ultimately transformed the economic and social structures of many countries. The effects of the Industrial Revolution continue to influence modern society in various ways.`;

        // Event Listeners
        sampleBtn.addEventListener('click', loadSampleText);
        clearBtn.addEventListener('click', clearText);
        recordBtn.addEventListener('click', startRecording);
        stopBtn.addEventListener('click', stopRecording);
        playBtn.addEventListener('click', playRecording);
        submitBtn.addEventListener('click', submitForScoring);
        newPracticeBtn.addEventListener('click', resetPractice);

        // Functions
        function loadSampleText() {
            passageInput.value = samplePassage;
            updateStatus('Sample text loaded. Click "Start Recording" when ready.', 'info');
        }

        function clearText() {
            passageInput.value = '';
            updateStatus('Text cleared. Paste your passage or use sample text.', 'info');
        }

        function updateStatus(message, type) {
            statusMessage.textContent = message;
            statusMessage.className = 'status-message ' + type;
        }

        function startCountdown() {
            let preparationTimeLeft = 40; // 40 seconds preparation time
            preparationStartTime = Date.now();
            
            clearInterval(preparationInterval);
            preparationInterval = setInterval(() => {
                preparationTimeLeft--;
                const minutes = Math.floor(preparationTimeLeft / 60);
                const seconds = preparationTimeLeft % 60;
                
                preparationTimer.textContent = `Preparation time: ${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
                preparationProgress.style.width = `${(preparationTimeLeft / 40) * 100}%`;
                
                if (preparationTimeLeft <= 0) {
                    clearInterval(preparationInterval);
                    preparationTimer.textContent = 'Preparation time: 00:00';
                    preparationProgress.style.width = '0%';
                    updateStatus('Preparation time ended. Click "Start Recording" to begin.', 'info');
                }
            }, 1000);
        }

        function startRecording() {
            if (!passageInput.value.trim()) {
                updateStatus('Please paste or enter a passage first.', 'error');
                return;
            }

            // Start preparation countdown if not already started
            if (!preparationStartTime) {
                startCountdown();
            }

            navigator.mediaDevices.getUserMedia({ audio: true })
                .then(stream => {
                    isRecording = true;
                    audioChunks = [];
                    
                    mediaRecorder = new MediaRecorder(stream);
                    
                    mediaRecorder.addEventListener('dataavailable', event => {
                        audioChunks.push(event.data);
                    });
                    
                    mediaRecorder.addEventListener('stop', () => {
                        audioBlob = new Blob(audioChunks, { type: 'audio/wav' });
                        audioUrl = URL.createObjectURL(audioBlob);
                        audio = new Audio(audioUrl);
                        
                        playBtn.disabled = false;
                        submitBtn.disabled = false;
                        updateStatus('Recording stopped. You can play it back or submit for scoring.', 'success');
                        simulateTranscription();
                    });
                    
                    recordBtn.disabled = true;
                    stopBtn.disabled = false;
                    
                    // Start recording timer
                    let recordingTime = 0;
                    recordingStartTime = Date.now();
                    clearInterval(recordingInterval);
                    recordingInterval = setInterval(() => {
                        recordingTime++;
                        const minutes = Math.floor(recordingTime / 60);
                        const seconds = recordingTime % 60;
                        
                        recordingTimer.textContent = `Recording time: ${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
                        recordingProgress.style.width = `${Math.min((recordingTime / 60) * 100, 100)}%`;
                        
                        if (recordingTime >= 60) {
                            stopRecording();
                        }
                    }, 1000);
                    
                    mediaRecorder.start();
                    updateStatus('Recording started. Click "Stop Recording" when finished.', 'info');
                })
                .catch(error => {
                    console.error('Error accessing microphone:', error);
                    updateStatus('Microphone access denied. Please allow microphone permissions.', 'error');
                });
        }

        function stopRecording() {
            if (!isRecording) return;
            
            clearInterval(recordingInterval);
            isRecording = false;
            
            if (mediaRecorder && mediaRecorder.state !== 'inactive') {
                mediaRecorder.stop();
                mediaRecorder.stream.getTracks().forEach(track => track.stop());
            }
            
            recordBtn.disabled = false;
            stopBtn.disabled = true;
        }

        function playRecording() {
            if (!audio) {
                updateStatus('No recording available to play.', 'error');
                return;
            }
            
            if (isPlaying) {
                audio.pause();
                audio.currentTime = 0;
                isPlaying = false;
                playBtn.textContent = 'Play Recording';
            } else {
                audio.play();
                isPlaying = true;
                playBtn.textContent = 'Stop Playback';
                
                audio.addEventListener('ended', () => {
                    isPlaying = false;
                    playBtn.textContent = 'Play Recording';
                });
            }
        }

        function simulateTranscription() {
            // In a real implementation, this would call an actual speech-to-text API
            // For this demo, we'll simulate a transcription with some variation
            const originalText = passageInput.value.trim();
            const words = originalText.split(/\s+/);
            
            // Simulate changes that might occur in speech recognition
            const possibleChanges = [
                { from: 'the', to: 'a' },
                { from: 'was', to: 'were' },
                { from: 'this', to: 'that' },
                { from: 'these', to: 'those' },
                { from: ',', to: '' },
                { from: '.', to: '' },
                { from: 'ing', to: 'in' },
            ];
            
            // Simulate partial matches and mistakes
            recordedText = originalText;
            
            // Add some random changes to simulate speech recognition errors
            for (let i = 0; i < Math.min(5, words.length); i++) {
                const word = words[i];
                const change = possibleChanges[Math.floor(Math.random() * possibleChanges.length)];
                
                recordedText = recordedText.replace(
                    new RegExp(`\\b${word}\\b`, 'i'),
                    Math.random() > 0.7 ? change.to : word
                );
                
                // Simulate missing words
                if (Math.random() > 0.9) {
                    recordedText = recordedText.replace(
                        new RegExp(`\\b${word}\\b`, 'i'),
                        ''
                    );
                }
                
                // Simulate extra words
                if (Math.random() > 0.9) {
                    const extraWords = ['um', 'ah', 'like', 'you know'];
                    recordedText = recordedText.replace(
                        new RegExp(`\\b${word}\\b`, 'i'),
                        `${word} ${extraWords[Math.floor(Math.random() * extraWords.length)]}`
                    );
                }
            }
            
            // Some pronunciation patterns that would trigger pronunciation errors
            const pronunciationIssues = [
                { pattern: /tion/g, replacement: 'shun'},
                { pattern: /th/g, replacement: 'd'},
                { pattern: /ing/g, replacement: 'een'},
                { pattern: /world/g, replacement: 'word'},
            ];
            
            pronunciationIssues.forEach(issue => {
                if (Math.random() > 0.5) {
                    recordedText = recordedText.replace(issue.pattern, issue.replacement);
                }
            });
        }

        function submitForScoring() {
            if (!audioBlob || !recordedText) {
                updateStatus('Please record your voice first.', 'error');
                return;
            }
            
            // Show loading state
            updateStatus('Analyzing your recording...', 'info');
            submitBtn.disabled = true;
            
            // Simulate API call delay
            setTimeout(() => {
                analyzePerformance();
                showResults();
            }, 2000);
        }

        function analyzePerformance() {
            const originalText = passageInput.value.trim();
            
            // Content score based on word matching
            const originalWords = originalText.split(/\s+/);
            const recordedWords = recordedText.split(/\s+/);
            
            let contentMatch = 0;
            let pronunciationErrors = 0;
            let fluencyIssues = [];
            
            // Calculate content match score
            const matchedWords = recordedWords.filter(word => 
                originalWords.includes(word)
            ).length;
            
            const contentScoreValue = Math.min(
                Math.floor((matchedWords / originalWords.length) * 90),
                90
            );
            
            // Simulate pronunciation analysis
            const pronunciationScoreValue = 85 - Math.floor(Math.random() * 15);
            
            // Simulate fluency analysis
            const fluencyScoreValue = 80 + Math.floor(Math.random() * 15);
            
            // Overall score
            const overallScoreValue = Math.floor(
                (contentScoreValue * 0.45) + 
                (pronunciationScoreValue * 0.3) + 
                (fluencyScoreValue * 0.25)
            );
            
            // Update scores
            contentScore.textContent = contentScoreValue;
            pronunciationScore.textContent = pronunciationScoreValue;
            fluencyScore.textContent = fluencyScoreValue;
            overallScore.textContent = overallScoreValue;
            
            // Prepare analysis text
            fluencyAnalysis.innerHTML = `
                <p>Your fluency is ${fluencyScoreValue >= 80 ? 'excellent' : fluencyScoreValue >= 60 ? 'good' : 'needs improvement'}.</p>
                <p>Fluency refers to the rhythm, phrasing, and pace of your speech. ${fluencyScoreValue >= 80 ? 'You maintained a natural pace with appropriate pauses.' : 'Try to maintain a more consistent pace and reduce hesitation sounds.'}</p>
            `;
            
            pronunciationAnalysis.innerHTML = `
                <p>Your pronunciation is ${pronunciationScoreValue >= 80 ? 'clear and understandable' : pronunciationScoreValue >= 60 ? 'mostly clear' : 'needs improvement'}.</p>
                <p>${pronunciationScoreValue >= 80 ? 'Most words were pronounced correctly.' : 'Pay attention to word endings and consonant clusters.'}</p>
                ${pronunciationScoreValue < 80 ? '<p>Common issues: "-tion" pronounced as "-shun", "th" sounds unclear</p>' : ''}
            `;
            
            // Format original and recorded text for comparison
            originalTextDisplay.innerHTML = highlightDifferences(originalText, recordedText);
            recordedTextDisplay.innerHTML = highlightDifferences(recordedText, originalText);
        }

        function highlightDifferences(text1, text2) {
            const words1 = text1.split(/\s+/);
            const words2 = text2.split(/\s+/);
            
            let highlighted = text1;
            
            // Find missing words
            words1.forEach(word => {
                if (!words2.includes(word) && word.length > 1) {
                    highlighted = highlighted.replace(
                        new RegExp(`\\b${word}\\b`, 'g'),
                        `<span class="highlight incorrect">${word}</span>`
                    );
                }
            });
            
            // Find correctly matched words
            words1.forEach(word => {
                if (words2.includes(word) && word.length > 1) {
                    highlighted = highlighted.replace(
                        new RegExp(`\\b${word}\\b`, 'g'),
                        `<span class="highlight correct">${word}</span>`
                    );
                }
            });
            
            return highlighted.split('\n').join('<br>');
        }

        function showResults() {
            document.querySelectorAll('.panel').forEach(panel => {
                panel.style.display = 'none';
            });
            
            resultPanel.style.display = 'block';
        }

        function resetPractice() {
            document.querySelectorAll('.panel').forEach(panel => {
                panel.style.display = 'block';
            });
            
            resultPanel.style.display = 'none';
            
            // Reset timers and progress bars
            preparationTimer.textContent = 'Preparation time: 00:40';
            preparationProgress.style.width = '100%';
            recordingTimer.textContent = 'Recording time: 00:00';
            recordingProgress.style.width = '0%';
            
            // Reset buttons
            recordBtn.disabled = false;
            stopBtn.disabled = true;
            playBtn.disabled = true;
            submitBtn.disabled = true;
            
            // Reset audio variables
            audioChunks = [];
            audioBlob = null;
            audioUrl = null;
            if (audio) {
                audio.pause();
                audio = null;
            }
            
            // Reset status message
            updateStatus('Ready for new practice. Paste your passage and click "Start Recording" when ready.', 'info');
            
            // Clear timers
            clearInterval(preparationInterval);
            clearInterval(recordingInterval);
            preparationStartTime = null;
            recordingStartTime = null;
        }
    </script>
</body>
</html>
