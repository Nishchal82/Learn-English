<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Language Lessons</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div id="home">
        <h1>English Lesson</h1>
        <p id="english-text">
            Sears was a major department store chain in the United States. In 1955, they published an advertisement in a newspaper.
            The advertisement included a phone number, telling children they could speak directly to Santa Claus by calling that number.

            However, due to a mistake, the wrong number was printed.
            When children dialed the number, it was answered by a U.S. Air Force officer.

            When the children said, "I want to talk to Santa Claus," the officer was a bit surprised but didn’t want to disappoint the children.
            So, he said, "I am Santa Claus." The children were very happy to hear that.

            Calls kept coming in, and the officer, along with his colleagues, acted as Santa Claus and answered all the calls.

            Thanks to this, the atmosphere in the office became very cheerful.
            Even today, this tradition continues.
            The credit for starting this tradition goes to Officer Harry Shoup.
        </p>
        <button onclick="speakText('english-text')">🔊 Listen to English Text</button>
        <button onclick="stopSpeaking()">🛑 Stop</button>
        <button onclick="showSection('korean')">한국어/Korean</button>
        <div id="important-words">
            <h2>Important Words</h2>
            <p>
                대형 마트 - Large department store<br>
                체인 - Chain (organization, network)<br>
                1955년 - The year 1955<br>
                신문 - Newspaper<br>
                광고 - Advertisement<br>
                전화번호 - Phone number<br>
                아이들 - Children<br>
                산타클로스 - Santa Claus<br>
                직접 - Directly, personally<br>
                이야기하다 - To talk, to converse<br>
                실수 - Mistake<br>
                잘못된 - Wrong, incorrect<br>
                인쇄되다 - To be printed<br>
                전화를 걸다 - To make a phone call<br>
                공군 - Air Force<br>
                직원 - Employee, staff<br>
                조금 - A little, slightly<br>
                놀라다 - To be surprised<br>
                마음 - Heart, feelings<br>
                실망시키다 - To disappoint<br>
                대답하다 - To reply, to answer<br>
                행복하다 - To be happy<br>
                그 후에도 - Even after that<br>
                계속 - Continuously<br>
                동료들 - Colleagues, coworkers<br>
                행동하다 - To act, to behave<br>
                모든 - All, every<br>
                사무실 - Office<br>
                분위기 - Atmosphere, mood<br>
                밝아지다 - To brighten, to improve<br>
                오늘날까지도 - Even to this day<br>
                전통 - Tradition<br>
                시작하다 - To start, to begin<br>
                공 - Credit<br>
                돌아가다 - To return, to go back<br>
                해리 숍 - Harry Shoup
            </p>
        </div>
        <button onclick="showSection('test')">Test</button>
    </div>

    <div id="korean" class="hidden">
        <h1>Korean Lesson</h1>
        <p id="korean-text">
            Sears는 미국의 한 대형 마트 체인이었습니다. 그들은 1955년에 신문에 광고를 하나 냈습니다.
            광고에서는 전화번호를 주면서 아이들이 그 번호로 산타클로스와 직접 이야기할 수 있다고 했습니다.

            하지만 실수로 잘못된 번호가 인쇄되었습니다.
            아이들이 그 번호로 전화를 걸었을 때, 미국 공군의 한 직원이 전화를 받았습니다.

            아이들이 "산타클로스와 이야기하고 싶어요"라고 하자, 직원은 조금 놀랐지만, 아이들의 마음을 실망시키고 싶지 않았습니다.
            그래서 그는 "내가 바로 산타클로스야"라고 대답했습니다. 아이는 그 말을 듣고 매우 행복해했습니다.

            그 후에도 계속 전화가 왔고, 직원은 동료들과 함께 산타클로스처럼 행동하며 모든 전화를 받았습니다.

            그 덕분에 사무실의 분위기는 매우 밝아졌습니다.
            오늘날까지도 이 전통은 계속되고 있습니다.
            이 전통을 시작한 공은 해리 숍(Harry Shoup) 직원에게 돌아갑니다.
        </p>
        <button onclick="speakText('korean-text')">🔊 한국어 텍스트 듣기</button>
        <button onclick="stopSpeaking()">🛑 Stop</button>
        <button onclick="showSection('home')">영어/English</button>
    </div>

    <div id="test" class="hidden">
        <h1>Test</h1>
        <p>
            1. What is the meaning of the word "tradition" in Korean?<br>
            a) 실수<br>
            b) 전통<br>
            c) 직원<br>
            d) 분위기<br>
            Answer: b) 전통<br><br>

            2. What is the meaning of the word "advertisement" in Korean?<br>
            a) 신문<br>
            b) 광고<br>
            c) 전화번호<br>
            d) 공군<br>
            Answer: b) 광고<br><br>

            3. What is the meaning of the word "office" in Korean?<br>
            a) 사무실<br>
            b) 동료들<br>
            c) 행동하다<br>
            d) 공<br>
            Answer: a) 사무실<br><br>

            4. What is the meaning of the word "to make a phone call" in Korean?<br>
            a) 행복하다<br>
            b) 전화번호<br>
            c) 전화를 걸다<br>
            d) 대답하다<br>
            Answer: c) 전화를 걸다<br><br>

            5. What is the meaning of the word "employee" in Korean?<br>
            a) 직원<br>
            b) 아이들<br>
            c) 공군<br>
            d) 동료들<br>
            Answer: a) 직원<br><br>

            6. What is the meaning of the word "feelings" in Korean?<br>
            a) 실망시키다<br>
            b) 마음<br>
            c) 분위기<br>
            d) 대답하다<br>
            Answer: b) 마음<br><br>

            7. What is the meaning of the word "mistake" in Korean?<br>
            a) 잘못된<br>
            b) 실수<br>
            c) 행동하다<br>
            d) 공<br>
            Answer: b) 실수<br><br>

            8. What is the meaning of the word "directly" in Korean?<br>
            a) 조금<br>
            b) 직접<br>
            c) 대형<br>
            d) 시작하다<br>
            Answer: b) 직접<br><br>

            9. What is the meaning of the word "to reply" in Korean?<br>
            a) 대답하다<br>
            b) 실망시키다<br>
            c) 전화번호<br>
            d) 공군<br>
            Answer: a) 대답하다<br><br>

            10. What is the meaning of the word "newspaper" in Korean?<br>
            a) 전통<br>
            b) 신문<br>
            c) 분휘기<br>
            d) 사무실<br>
            Answer: b) 신문<br>
        </p>
        <button onclick="showSection('home')">Back to Home</button>
    </div>

    <script>
        let synthesis = window.speechSynthesis;

        function speakText(elementId) {
            const text = document.getElementById(elementId).innerText;
            const utterance = new SpeechSynthesisUtterance(text);

            if (elementId === 'korean-text') {
                utterance.lang = 'ko-KR';
            } else {
                utterance.lang = 'en-US';
            }

            synthesis.speak(utterance);
        }

        function stopSpeaking() {
            if (synthesis.speaking) {
                synthesis.cancel();
            }
        }

        function showSection(section) {
            document.getElementById('home').classList.add('hidden');
            document.getElementById('korean').classList.add('hidden');
            document.getElementById('test').classList.add('hidden');

            document.getElementById(section).classList.remove('hidden');
        }
    </script>
</body>
</html>
