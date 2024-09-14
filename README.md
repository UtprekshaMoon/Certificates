# Certificates
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificate Generator</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #f7d3e2;
        }
        .certificate {
            border: 10px solid #000;
            padding: 50px;
            margin: 20px auto;
            width: 80%;
            background-color: #ca7e9c;
            max-width: 800px;
            position: relative;
        }
        h1 {
            font-size: 50px;
            margin-bottom: 20px;
        }
        .name {
            font-size: 30px;
            font-weight: bold;
            margin-top: 30px;
        }
        .course {
            font-size: 24px;
            margin-top: 20px;
        }
        .date {
            font-size: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <div class="certificate">
        <h1>Certificate of Completion</h1>
        <p>This certifies to</p>
        <p class="name" id="name">[Name]</p>
        <p>has successfully completed the</p>
        <p class="course" id="course">[Course Name]</p>
        <p class="date" id="date">[Date]</p>
    </div>

    <input type="text" id="inputName" placeholder="Enter Name" />
    <input type="text" id="inputCourse" placeholder="Enter Course" />
    <input type="text" id="inputDate" placeholder="Enter Date" /><br>
    <button onclick="generateCertificate()">Generate Certificate</button>

    <style>
       .button{
        text-align: center;
       }
    </style>
    <script src="script.js"></script>
</body>
</html>
