<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multilingual Lessons</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        section {
            max-width: 800px;
            width: 100%;
            margin-bottom: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            text-align: center;
        }

        .button:hover {
            background-color: #0056b3;
        }
    </style>
    <script>
        function showSection(sectionId) {
            document.querySelectorAll('section').forEach(section => {
                section.style.display = 'none';
            });
            document.getElementById(sectionId).style.display = 'block';
        }

        function openTestPage() {
            const testContent = `<html><head><title>Test</title></head><body><h1>Test</h1><p>1. What is the meaning of the word "tradition" in Korean?<br>a) 실수<br>b) 전통<br>c) 직원<br>d) 분위기<br><strong>Answer:</strong> b) 전통</p><p>2. What is the meaning of the word "advertisement" in Korean?<br>a) 신문<br>b) 광고<br>c) 전화번호<br>d) 공군<br><strong>Answer:</strong> b) 광고</p><p>3. What is the meaning of the word "office" in Korean?<br>a) 사무실<br>b) 동료들<br>c) 행동하다<br>d) 공<br><strong>Answer:</strong> a) 사무실</p><p>...</p></body></html>`;
            const testWindow = window.open('about:blank', '_blank');
            testWindow.document.write(testContent);
            testWindow.document.close();
        }
    </script>
</head>
<body>
    <section id="english-lesson">
        <h2>English Lesson</h2>
        <p>Sears was a major department store chain in the United States. In 1955, they published an advertisement in a newspaper. The advertisement included a phone number, telling children they could speak directly to Santa Claus by calling that number.</p>
        <p>However, due to a mistake, the wrong number was printed. When children dialed the number, it was answered by a U.S. Air Force officer.</p>
        <p>When the children said, "I want to talk to Santa Claus," the officer was a bit surprised but didn’t want to disappoint the children. So, he said, "I am Santa Claus." The children were very happy to hear that.</p>
        <p>Calls kept coming in, and the officer, along with his colleagues, acted as Santa Claus and answered all the calls.</p>
        <p>Thanks to this, the atmosphere in the office became very cheerful. Even today, this tradition continues. The credit for starting this tradition goes to Officer Harry Shoup.</p>
        <a href="#" class="button" onclick="showSection('korean-lesson')">한국어/Korean</a>
    </section>

    <section id="korean-lesson" style="display: none;">
        <h2>Korean Lesson</h2>
        <p>Sears는 미국의 한 대형 마트 체인이었습니다. 그들은 1955년에 신문에 광고를 하나 냈습니다. 광고에서는 전화번호를 주면서 아이들이 그 번호로 산타클로스와 직접 이야기할 수 있다고 했습니다.</p>
        <p>하지만 실수로 잘못된 번호가 인쇄되었습니다. 아이들이 그 번호로 전화를 걸었을 때, 미국 공군의 한 직원이 전화를 받았습니다.</p>
        <p>아이들이 "산타클로스와 이야기하고 싶어요"라고 하자, 직원은 조금 놀랐지만, 아이들의 마음을 실망시키고 싶지 않았습니다. 그래서 그는 "내가 바로 산타클로스야"라고 대답했습니다. 아이는 그 말을 듣고 매우 행복해했습니다.</p>
        <p>그 후에도 계속 전화가 왔고, 직원은 동료들과 함께 산타클로스처럼 행동하며 모든 전화를 받았습니다.</p>
        <p>그 덕분에 사무실의 분위기는 매우 밝아졌습니다. 오늘날까지도 이 전통은 계속되고 있습니다. 이 전통을 시작한 공은 해리 숍(Harry Shoup) 직원에게 돌아갑니다.</p>
        <a href="#" class="button" onclick="showSection('english-lesson')">영어/English</a>
    </section>

    <section id="important-words">
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
            <!-- Add remaining words -->
        </ul>
        <a href="#" class="button" onclick="openTestPage()">Test</a>
    </section>
</body>
</html>
