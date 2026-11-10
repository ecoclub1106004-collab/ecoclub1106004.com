# ecoclub1106004.com
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eco Club 1106004 - Official Portal</title>
    <style>
        :root {
            --primary: #2e7d32;
            --primary-light: #e8f5e9;
            --text: #333;
            --white: #ffffff;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f4;
            color: var(--text);
        }
        header {
            background-color: var(--primary);
            color: var(--white);
            padding: 25px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        header h1 { margin: 0; font-size: 26px; }
        header p { margin: 8px 0 0 0; font-size: 15px; opacity: 0.9; }
        
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 15px;
        }
        .card {
            background: var(--white);
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        h2 { color: var(--primary); border-bottom: 2px solid var(--primary-light); padding-bottom: 5px; margin-top: 0; }
        
        .form-group {
            margin-bottom: 15px;
        }
        label { display: block; margin-bottom: 5px; font-weight: bold; }
        input, select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            font-size: 16px;
        }
        button {
            background-color: var(--primary);
            color: var(--white);
            border: none;
            padding: 14px 20px;
            font-size: 16px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
        }
        button:hover { background-color: #1b5e20; }
        
        .alert {
            display: none;
            padding: 15px;
            background-color: #d4edda;
            color: #155724;
            border-radius: 4px;
            margin-top: 15px;
            text-align: center;
            font-weight: bold;
        }
        .badge {
            background: var(--primary-light);
            color: var(--primary);
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 12px;
            display: inline-block;
            margin-left: 5px;
            font-weight: bold;
        }
        ul { padding-left: 20px; }
        li { margin-bottom: 10px; line-height: 1.5; }
    </style>
</head>
<body>

<header>
    <h1>🌱 इको क्लब (Eco Club) - स्कूल ID: 1106004</h1>
    <p>Govt. Boys Sr. Sec. School / Sarvodaya Bal Vidyalaya (Janta Flats, Nand Nagri)</p>
    <p style="margin-top: 10px; font-weight: bold; background: rgba(0,0,0,0.1); display: inline-block; padding: 5px 15px; border-radius: 20px;">👋 इको क्लब हेड डेस्क पर आपका स्वागत है!</p>
</header>

<div class="container">
    <!-- Notice Card -->
    <div class="card">
        <h2>📢 महत्वपूर्ण सूचना (Eco Club Notice)</h2>
        <p>सभी छात्रों को सूचित किया जाता है कि नए सत्र के लिए इको क्लब में एडमिशन्स शुरू हो चुके हैं। जो भी छात्र स्कूल को हरा-भरा और स्वच्छ बनाने में अपना योगदान देना चाहते हैं, वे नीचे दिए गए फॉर्म को भरकर अपना ऑनलाइन रजिस्ट्रेशन पूरा करें। शॉर्टलिस्ट होने वाले छात्रों के बेसिक टेस्ट की तारीख इसी वेबसाइट पर घोषित की जाएगी।</p>
    </div>

    <!-- Form Card -->
    <div class="card">
        <h2>✍️ ऑनलाइन रजिस्ट्रेशन फॉर्म (Registration Form)</h2>
        <form id="registrationForm" onsubmit="submitForm(event)">
            <div class="form-group">
                <label for="name">छात्र का नाम (Student Name):</label>
                <input type="text" id="name" required placeholder="अपना पूरा नाम लिखें">
            </div>
            <div class="form-group">
                <label for="class">कक्षा (Class):</label>
                <select id="class" required>
                    <option value="">अपनी कक्षा चुनें</option>
                    <option value="6">कक्षा 6वीं</option>
                    <option value="7">कक्षा 7वीं</option>
                    <option value="8">कक्षा 8वीं</option>
                    <option value="9">कक्षा 9वीं</option>
                    <option value="10">कक्षा 10वीं</option>
                    <option value="11">कक्षा 11वीं</option>
                    <option value="12">कक्षा 12वीं</option>
                </select>
            </div>
            <div class="form-group">
                <label for="roll">रोल नंबर (Roll No.):</label>
                <input type="number" id="roll" required placeholder="अपना क्लास रोल नंबर लिखें">
            </div>
            <div class="form-group">
                <label for="sid">स्टूडेंट आईडी (Student ID):</label>
                <input type="text" id="sid" required placeholder="अपनी 11 अंकों की स्टूडेंट आईडी डालें">
            </div>
            <div class="form-group">
                <label for="interest">आप किस गतिविधि में भाग लेना चाहते हैं?</label>
                <select id="interest" required>
                    <option value="Plantation">पौधारोपण अभियान (Tree Plantation)</option>
                    <option value="Cleanliness">स्कूल स्वच्छता ड्राइव (Cleanliness Drive)</option>
                    <option value="Poster">पोस्टर मेकिंग व स्लोगन राइटिंग (Art & Posters)</option>
                    <option value="Awareness">पर्यावरण जागरूकता रैलियां (Awareness Rallies)</option>
                </select>
            </div>
            <button type="submit">क्लब मेंबरशिप के लिए आवेदन करें</button>
        </form>
        <div id="successAlert" class="alert">
            🎉 बधाई हो! आपका रजिस्ट्रेशन फॉर्म इको क्लब हेड के पास सफलतापूर्वक सुरक्षित जमा हो गया है।
        </div>
    </div>

    <!-- Events Card -->
    <div class="card">
        <h2>🌱 हमारी आगामी गतिविधियाँ (Upcoming Events)</h2>
        <ul>
            <li><b>विश्व पर्यावरण दिवस:</b> स्कूल परिसर में विशेष पौधारोपण और वृक्ष वितरण अभियान। <span class="badge">आगामी</span></li>
            <li><b>हर शनिवार:</b> 'सिंगल-यूज़ प्लास्टिक मुक्त' स्कूल बनाने के लिए विशेष सफाई अभियान। <span class="badge">साप्ताहिक</span></li>
            <li><b>आगामी हफ़्ते:</b> नए आवेदकों के लिए एक बुनियादी पर्यावरण टेस्ट/इंटरव्यू का आयोजन। <span class="badge">जरूरी</span></li>
        </ul>
    </div>
</div>

<script>
    function submitForm(event) {
        event.preventDefault();
        document.getElementById('registrationForm').reset();
        var alertBox = document.getElementById('successAlert');
        alertBox.style.display = 'block';
        setTimeout(function() {
            alertBox.style.display = 'none';
        }, 5000);
    }
</script>

</body>
</html>
