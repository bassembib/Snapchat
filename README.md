# Snapchat
موقع
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login-container">
        <h1>تسجيل الدخول</h1>
        <form id="login-form">
            <div class="input-group">
                <label for="username">اسم المستخدم أو البريد الإلكتروني أو الهاتف</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="input-group">
                <label for="password">كلمة المرور</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="options">
                <label>
                    <input type="checkbox" name="remember"> حفظ معلومات تسجيل الدخول على iCloud
                </label>
                <a href="#">هل نسيت كلمة المرور؟</a>
            </div>
            <button type="submit">تسجيل الدخول</button>
        </form>
        <div id="error-message" class="error-message"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>