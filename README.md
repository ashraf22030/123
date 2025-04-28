<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>تسجيل الدخول - مشروع تدريبي</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f0f0f0; text-align: center; padding-top: 100px; }
    .login-container { background: white; padding: 20px; border-radius: 8px; display: inline-block; }
    input { display: block; width: 250px; margin: 10px auto; padding: 10px; }
    button { padding: 10px 20px; margin-top: 10px; }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>تسجيل الدخول</h2>
    <form>
      <input type="text" id="username" placeholder="اسم المستخدم" required>
      <input type="password" id="password" placeholder="كلمة المرور" required>
      <button type="submit">دخول</button>
    </form>
  </div>

  <script>
    window.onload = function() {
      document.getElementById('username').value = 'Username123';
      document.getElementById('password').value = 'Password123';
    };
  </script>
</body>
</html>
