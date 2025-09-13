<!DOCTYPE html>
<html lang="vi">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nhập Code</title>
</head>

<body>
    <h2>Nhập Code để chuyển hướng</h2>
    <input type="text" id="codeInput" placeholder="Nhập code ở đây">
    <button onclick="checkCode()">Xác nhận</button>

    <script>
        function checkCode() {
            const code = document.getElementById('codeInput').value.trim();

            // Ví dụ: check các code
            if (code === "ongrom123") {
                window.location.href = "https://vlsexdam.net/";
            } else if (code === "123321") {
                window.location.href = "https://vlxx.bz/";
            } else {
                alert("Code không hợp lệ!");
            }
        }
    </script>
</body>

</html>
