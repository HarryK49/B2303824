<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang chủ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #1E90FF;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .schedule {
            margin-bottom: 30px;
            text-align: center;
        }
        table {
            border-collapse: collapse;
            margin: 0 auto;
        }
        table, th, td {
            border: 1px solid black;
            padding: 10px;
        }
        .poem {
            font-style: italic;
            margin-top: 30px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Trang chủ</h1>
    </header>

    <main>
        <div class="schedule">
            <h2>Thời khóa biểu</h2>
            <table>
                <thead>
                    <tr>
                        <th>Thứ</th>
                        <th>Môn học</th>
                        <th>Giờ học</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Thứ 2</td>
                        <td>Toán</td>
                        <td>8:00 - 9:30</td>
                    </tr>
                    <tr>
                        <td>Thứ 3</td>
                        <td>Văn</td>
                        <td>10:00 - 11:30</td>
                    </tr>
                    <tr>
                        <td>Thứ 4</td>
                        <td>Lý</td>
                        <td>13:30 - 15:00</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="poem">
            <h2>Một bài thơ:</h2>
            <p>
                Bài thơ: "Cảnh khuya" - Hồ Chí Minh<br>
                Tiếng suối trong như tiếng hát xa,<br>
                Trăng lồng cổ thụ bóng lồng hoa.<br>
                Cảnh khuya như vẽ người chưa ngủ,<br>
                Chưa ngủ vì lo nỗi nước nhà.
            </p>
        </div>
    </main>

    <footer>
        <p>Web của Trương Tuấn Kiệt - B2303824  </p>
    </footer>
</body>
</html>
