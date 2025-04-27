
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AcademeForge Scholars Test (AST) - FAQs</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .faq-container {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            padding: 20px;
            max-width: 800px;
        }
        .faq-item {
            background-color: #fafafa;
            margin-bottom: 10px;
            border-radius: 5px;
            transition: all 0.3s ease;
            padding: 15px;
            cursor: pointer;
            border: 2px solid #ddd;
        }
        .faq-item:hover {
            background-color: #f0f0f0;
            transform: translateX(5px);
        }
        .faq-item h3 {
            margin: 0;
            font-size: 18px;
            color: #333;
            font-weight: bold;
        }
        .answer {
            display: none;
            padding: 10px;
            margin-top: 10px;
            color: #555;
            background-color: #fff;
            border-top: 1px solid #ddd;
            border-radius: 5px;
            transition: opacity 0.5s ease;
        }
        .faq-item.open .answer {
            display: block;
            animation: slideDown 0.5s ease-in-out;
        }
        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <h1>Frequently Asked Questions (FAQs) - AcademeForge Scholars Test (AST)</h1>

    <div class="faq-container">
        <div class="faq-item">
            <h3>1. What is the AcademeForge Scholars Test (AST)?</h3>
            <div class="answer">
                <p>The AST is a competitive exam organized by AcademeForge to identify and reward talented students from Classes 1 to 10 across India.</p>
            </div>
        </div>
        <div class="faq-item">
            <h3>2. Who can participate in AST?</h3>
            <div class="answer">
                <p>Students currently studying in Classes 1 to 10 in any recognized school in India can participate.</p>
            </div>
        </div>
        <div class="faq-item">
            <h3>3. How many rounds are there in AST?</h3>
            <div class="answer">
                <p>There are <strong>three rounds</strong>:  
                    <ul>
                        <li>Round 1: Screening Test</li>
                        <li>Round 2: Advanced Test</li>
                        <li>Round 3: Final Round (Scholarship Round)</li>
                    </ul>
                </p>
            </div>
        </div>
        <div class="faq-item">
            <h3>4. What is the registration fee for AST?</h3>
            <div class="answer">
                <p>
                    <ul>
                        <li><strong>Round 1</strong>: ₹10</li>
                        <li><strong>Round 2</strong>: ₹40 (only for those who qualify from Round 1)</li>
                        <li><strong>Round 3</strong>: Free (for qualifiers from Round 2)</li>
                    </ul>
                </p>
            </div>
        </div>
        <div class="faq-item">
            <h3>5. What are the rewards and certificates given?</h3>
            <div class="answer">
                <p>
                    <ul>
                        <li><strong>Round 1</strong>: Digital Certificate</li>
                        <li><strong>Round 2</strong>: Printed Certificate + Social Media Recognition</li>
                        <li><strong>Round 3</strong>: Printed Certificate + Medal + Scholarships up to ₹5000 for top 3 students.</li>
                    </ul>
                </p>
            </div>
        </div>
        <div class="faq-item">
            <h3>6. How many students qualify for each round?</h3>
            <div class="answer">
                <p>About <strong>450 students</strong> will qualify from Round 1 to Round 2.  
                   About <strong>45 students</strong> will qualify from Round 2 to Round 3.</p>
            </div>
        </div>
        <div class="faq-item">
            <h3>7. What is the syllabus for AST?</h3>
            <div class="answer">
                <p>The syllabus is based on your current class topics (CBSE/ICSE/State boards) and focuses on logical reasoning, aptitude, and core subject knowledge.</p>
            </div>
        </div>
        <!-- Add more FAQ items here -->

    </div>

    <script>
        // JavaScript for toggling the answer visibility
        document.querySelectorAll('.faq-item').forEach(item => {
            item.addEventListener('click', () => {
                item.classList.toggle('open');
            });
        });
    </script>

</body>
</html>