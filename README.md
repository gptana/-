<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>Happie BIRTH day to Meenney</title>
    <style>
        body {
            background-color: #ffc0cb; /* สีชมพูอ่อน */
            color: #333; /* สีตัวหนังสือ */
            font-family: Arial, Helvetica, sans-serif;
            text-align: center;
            padding: 20px;
            overflow-y: scroll; /* ทำให้สามารถเลื่อนลงได้ */
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px; /* ทำให้รูปมีขอบมน */
            box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.2); /* เพิ่มเงาให้รูป */
            margin: 20px auto; /* จัดรูปให้อยู่ตรงกลาง */
            display: block; /* ให้รูปเป็นบล็อกเพื่อให้ margin ทำงาน */
        }
        button {
            background-color: #ff69b4; /* สีชมพูสด */
            color: white;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px 2px;
            cursor: pointer;
            border-radius: 5px; /* ทำให้ปุ่มมีขอบมน */
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); /* เพิ่มเงาให้ปุ่ม */
        }
        button:hover {
            background-color: #ff1493; /* เปลี่ยนสีเมื่อเมาส์ชี้ */
        }
        input[type="text"] {
            padding: 10px;
            font-size: 16px;
            margin: 10px;
            border-radius: 5px; /* ทำให้ฟิลด์มีขอบมน */
            border: 1px solid #ddd;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); /* เพิ่มเงาให้ฟิลด์ */
        }
        #message {
            display: none; /* ซ่อนข้อความในตอนแรก */
            margin-top: 20px;
            font-size: 18px;
            color: #ff1493; /* สีชมพูสด */
        }
    </style>
    <script>
        function checkAnswer() {
            var answer = document.getElementById("answer").value;
            if (answer === "13 กุมภาพันธ์ 2568") { // ใช้วันคบรอบที่ถูกต้อง
                document.getElementById("message").style.display = "block"; // แสดงข้อความ
            } else {
                alert('คำตอบไม่ถูกต้อง!');
            }
        }
    </script>
</head>
<body>
    <h1>Happie BIRTH day to Meenney</h1>
    <p>ขอให้มีความสุขมาก ๆ นะ!</p>
    <img src="myphoto.jpg" alt="รูปของฉัน" width="200">
    <input type="text" id="answer" placeholder="วันคบรอบคือวันที่เท่าไหร่ เดือนอะไร พ.ศ.อะไร">
    <button onclick="checkAnswer()">กดเพื่ออวยพร</button>
    <div id="message">
        สุขสันต์วันเกิด! ขอให้มีความสุขมาก ๆ และสมหวังในทุกสิ่งที่ปรารถนา! 
        ขอให้มีสุขภาพแข็งแรง มีความสุขในทุก ๆ วัน ได้พบเจอแต่สิ่งดี ๆ 
        และมีความเจริญรุ่งเรืองในชีวิต ขอให้ความฝันทุกอย่างเป็นจริง 
        และขอให้ชีวิตมีแต่ความสุขและสนุกสนานตลอดไป!
    </div>
    <audio controls autoplay loop>
        <source src="https://www.example.com/your-audio-file.mp3" type="audio/mpeg">
        เบราว์เซอร์ของคุณไม่รองรับการเล่นไฟล์เสียง
    </audio>
</body>
</html>
