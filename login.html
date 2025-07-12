<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login - Stock Manager</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Font: Prompt -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Prompt', sans-serif;
    }
  </style>
</head>
<body class="min-h-screen flex items-center justify-center bg-gradient-to-br from-teal-100 to-white">
  <div class="w-full max-w-sm bg-white rounded-xl shadow-lg p-8">
    <h2 class="text-2xl font-bold text-center text-teal-700 mb-6">🔐 เข้าสู่ระบบ</h2>

    <form id="loginForm" onsubmit="handleLogin(event)">
      <div class="mb-4">
        <label class="block text-sm font-medium text-gray-600">ชื่อผู้ใช้</label>
        <input type="text" id="username" required class="mt-1 w-full border rounded p-2 focus:outline-none focus:ring" />
      </div>

      <div class="mb-6">
        <label class="block text-sm font-medium text-gray-600">รหัสผ่าน</label>
        <input type="password" id="password" required class="mt-1 w-full border rounded p-2 focus:outline-none focus:ring" />
      </div>

      <button type="submit" class="w-full bg-teal-600 hover:bg-teal-700 text-white py-2 rounded-lg shadow">เข้าสู่ระบบ</button>

      <p id="errorMsg" class="text-center text-red-600 text-sm mt-4 hidden">❌ ชื่อผู้ใช้หรือรหัสผ่านไม่ถูกต้อง</p>
    </form>
  </div>

  <script>
    function handleLogin(e) {
      e.preventDefault();

      const user = username.value.trim();
      const pass = password.value.trim();

      google.script.run
        .withSuccessHandler(isOk => {
          if (isOk) {
            /*
             * เก็บชื่อผู้ใช้ให้หน้าอื่นดึงใช้ได้ (ทั้ง sessionStorage และ localStorage)
             * - sessionStorage: ลบเมื่อปิดแท็บ
             * - localStorage : อยู่ถาวรจนกว่าจะถูกลบ (ใช้ใน saveChange())
             */
            sessionStorage.setItem('loggedInUser', user);
            localStorage.setItem('currentUser', user);

            // ไปหน้า home
            google.script.run
              .withSuccessHandler(url => window.top.location.href = url)
              .getHomeUrl();
          } else {
            document.getElementById('errorMsg').classList.remove('hidden');
          }
        })
        .checkLogin(user, pass);
    }
  </script>
</body>
</html>
