<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Language Lessons</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .section {
            margin: 20px 0;
        }
        button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .hidden {
            display: none;
        }
    </style>
    <script>
        function toggleLesson(language) {
            const englishLesson = document.getElementById('english-lesson');
            const koreanLesson = document.getElementById('korean-lesson');

            if (language === 'Korean') {
                englishLesson.classList.add('hidden');
                koreanLesson.classList.remove('hidden');
            } else {
                koreanLesson.classList.add('hidden');
                englishLesson.classList.remove('hidden');
            }
        }

        function goToTest() {
            document.getElementById('home-page').classList.add('hidden');
            document.getElementById('test-sheet').classList.remove('hidden');
        }

        function goToHome() {
            document.getElementById('test-sheet').classList.add('hidden');
            document.getElementById('home-page').classList.remove('hidden');
        }

        function showAnswer(questionId, answer) {
            document.getElementById(questionId).innerText = `Answer: ${answer}`;
        }
    </script>
</head>
<body>
    <div class="container">
        <!-- Home Page -->
        <div id="home-page">
            <div id="english-lesson" class="section">
                <h1>English Lesson</h1>
                <p>Sears was a major department store chain in the United States. In 1955, they published an advertisement in a newspaper...</p>
                <button onclick="toggleLesson('Korean')">한국어/Korean</button>
            </div>

            <div id="korean-lesson" class="section hidden">
                <h1>Korean Lesson</h1>
                <p>Sears는 미국의 한 대형 마트 체인이었습니다. 그들은 1955년에 신문에 광고를 하나 냈습니다...</p>
                <button onclick="toggleLesson('English')">영어/English</button>
            </div>

            <div class="section">
                <h2>Important Words</h2>
                <ul>
                    <li>대형 마트 - Large department store</li>
                    <li>체인 - Chain (organization, network)</li>
                    <li>1955년 - The year 1955</li>
                    <li>신문 - Newspaper</li>
                    <li>광고 - Advertisement</li>
                    <li>전화번호 - Phone number</li>
                    <li>아이들 - Children</li>
                    <li>산타클로스 - Santa Claus</li>
                    <li>직접 - Directly, personally</li>
                    <li>이야기하다 - To talk, to converse</li>
                    <li>실수 - Mistake</li>
                    <li>잘못된 - Wrong, incorrect</li>
                    <li>인쇄되다 - To be printed</li>
                    <li>전화를 걸다 - To make a phone call</li>
                    <li>공군 - Air Force</li>
                    <li>직원 - Employee, staff</li>
                    <li>조금 - A little, slightly</li>
                    <li>놀라다 - To be surprised</li>
                    <li>마음 - Heart, feelings</li>
                    <li>실망시키다 - To disappoint</li>
                </ul>
            </div>

            <div class="section">
                <h2>Test/시험</h2>
                <button onclick="goToTest()">Go to Test Sheet</button>
            </div>
        </div>

        <!-- Test Sheet -->
        <div id="test-sheet" class="hidden">
            <h1>Test Sheet</h1>
            <div class="section">
                <p>1. What is the meaning of the word "tradition" in Korean?</p>
                <button onclick="showAnswer('q1', '전통')">Answer</button>
                <p id="q1"></p>
            </div>

            <div class="section">
                <p>2. What is the meaning of the word "advertisement" in Korean?</p>
                <button onclick="showAnswer('q2', '광고')">Answer</button>
                <p id="q2"></p>
            </div>

            <button onclick="goToHome()">Back to Home</button>
        </div>
    </div>
</body>
</html>
