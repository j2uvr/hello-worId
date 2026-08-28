<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالة خاصة لكِ ❤️</title>
    <style>
        * { box-sizing: border-box; }
        body {
            margin: 0; padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffe6e9;
            text-align: center;
            overflow-x: hidden;
            color: #333;
        }
        #overlay {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(135deg, #ff4d6d, #ff758f);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-size: 22px;
            cursor: pointer;
            z-index: 100;
            transition: opacity 0.8s ease;
            padding: 20px;
        }
        .main-content {
            padding: 40px 15px;
            display: none;
        }
        .card {
            background: white;
            padding: 22px;
            margin: 15px auto;
            max-width: 90%;
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.08);
            line-height: 1.8;
            font-size: 18px;
        }
        .sticker { font-size: 45px; margin: 10px 0; }
    </style>
</head>
<body>

    <div id="overlay" onclick="startExperience()">
        <p>✨ اضغطي هنا يا أجمل إنسانة ✨</p>
        <span style="font-size: 45px; margin-top: 15px;">👇❤️</span>
    </div>

    <div class="main-content" id="content">
        <div class="sticker">🥰🌹</div>
        <h2 style="color: #ff4d6d; font-size: 26px;">إلى روح روحي..</h2>
        
        <div class="card">
            أنتِ مو بس حبيبة، أنتِ راحة بعد التعب، أنتِ ضحكة تغير يومي كامل، وحضوركِ يمي ينسيني كلشي. أنتِ تستاهلين الاهتمام بدون طلب والوفاء بدون شروط.
        </div>
        
        <div class="sticker">💖✨💖</div>
        
        <div class="card">
            وگلب يختارج كل مرة وبدون تردد، أنتِ ماي عيني، أنتِ روح روحي وحب حياتي الأول والأخير. أنتِ عوضي الي الله عوضني بيه، وما هنت اعرف هلگد عوض الله حلو لحد ما عوضني بيج.
        </div>

        <div class="sticker">👑💎</div>

        <div class="card">
            عالمي الخاص، احبج يا اعز امل، ما احبج يا اعز شخص بحياتي.. احبج يا اول حب واخر حب بحياتي، احبج يا كل دنيتي احبج حبيبي تبارك و اتمنى تردين علي وما تزعلين علي بشي بعد لان اضوج بدونج ويومي كله يكون كئيب اذا ما حجيت وياج  ❤️
        </div>
    </div>

    <script>
        function startExperience() {
            let overlay = document.getElementById('overlay');
            let content = document.getElementById('content');
            overlay.style.opacity = '0';
            setTimeout(() => {
                overlay.style.display = 'none';
                content.style.display = 'block';
            }, 800);
        }
    </script>
</body>
</html>
