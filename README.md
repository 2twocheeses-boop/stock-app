# stock-app
[index.html.html](https://github.com/user-attachments/files/25817580/index.html.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مخزوني الذكي</title>
    <script src="https://cdnjs.cloudflare.com"></script>
    <style>
        :root { --bg: #121212; --card: #1e1e1e; --primary: #bb86fc; --text: #ffffff; }
        body { background: var(--bg); color: var(--text); font-family: sans-serif; margin: 0; padding: 20px; text-align: center; }
        .nav { position: fixed; bottom: 0; width: 100%; background: #1f1f1f; display: flex; justify-content: space-around; padding: 15px 0; left:0; }
        button { background: var(--primary); border: none; padding: 15px; border-radius: 10px; width: 100%; font-weight: bold; margin-top: 10px; }
        .card { background: var(--card); padding: 15px; border-radius: 12px; margin-top: 20px; border-right: 5px solid #03dac6; }
    </style>
</head>
<body>
    <h2 style="color: var(--primary)">مخزوني الذكي 📦</h2>
    <div class="card">
        <strong>حليب طازج</strong><br><small>ينتهي غداً - 15 ريال</small>
    </div>
    <button onclick="alert('سيتم فتح الكاميرا قريباً')">➕ إضافة منتج جديد</button>
    <div class="nav">
        <div>🏠 الرئيسية</div>
        <div>💬 المحادثة</div>
    </div>
</body>
</html>
