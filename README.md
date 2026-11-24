# Mohamed-
Mohamed 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>دعوة شبكة | محمد ياسر ❤️ آلاء أشرف</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Cairo',sans-serif}
  body{background:#f5efe3;color:#4a2e1a;text-align:center}
  .hero{min-height:100vh;padding:30px 20px;display:flex;flex-direction:column;justify-content:center;align-items:center}
  .top{display:flex;gap:30px;align-items:center;justify-content:center;flex-wrap:wrap;margin-bottom:25px}
  .cal{font-size:14px;line-height:2}
  .cal b{color:#b08a4f}
  .heart{border:2px solid #b08a4f;border-radius:50%;padding:2px 6px}
  .line{width:2px;height:140px;background:#4a2e1a}
  h1{font-family:'Amiri',serif;font-size:42px;line-height:1.2}
  .names{font-family:'Amiri',serif;font-size:36px;margin:20px 0}
  .names span{background:#b08a4f;color:#fff;border-radius:50%;padding:5px 12px;font-size:22px}
  .card{background:#fffaf0;border:2px solid #d9c8a8;border-radius:25px;padding:25px;margin:20px auto;max-width:520px;width:95%;box-shadow:0 10px 30px rgba(0,0,0,.08)}
  .count{display:flex;justify-content:center;gap:10px;margin:20px 0}
  .count div{background:#4a2e1a;color:#fff;border-radius:15px;padding:12px 10px;min-width:70px}
  .count b{font-size:24px;display:block}
  .btn{display:inline-block;background:#4a2e1a;color:#fff;padding:14px 28px;border-radius:30px;font-weight:900;text-decoration:none;margin:8px 5px;font-size:17px}
  .btn2{background:#b08a4f}
  .info{display:flex;justify-content:center;gap:25px;margin-top:15px;font-weight:700;flex-wrap:wrap}
</style>
</head>
<body>
<div class="hero">
  <div class="top">
    <div class="cal">
      <b>Save the date</b><br>
      Su Mo Tu We Th Fr Sa<br>
      1 &nbsp; 2 &nbsp; 3 &nbsp; 4 &nbsp; 5 &nbsp; 6 &nbsp; 7<br>
      8 &nbsp; 9 &nbsp; 10 &nbsp; 11 &nbsp; 12 &nbsp; 13 &nbsp; 14<br>
      15 &nbsp; 16 &nbsp; 17 &nbsp; 18 &nbsp; 19 &nbsp; 20 &nbsp; 21<br>
      22 &nbsp; 23 &nbsp; 24 &nbsp; 25 &nbsp; <span class="heart">26</span> &nbsp; 27 &nbsp; 28<br>
      29 &nbsp; 30<br>
      <b style="font-size:18px">26.11.2026</b>
    </div>
    <div class="line"></div>
    <h1>Welcome to<br>our<br>Engagement</h1>
  </div>

  <p style="font-size:16px;max-width:600px;line-height:1.8">وَمِنْ آيَاتِهِ أَنْ خَلَقَ لَكُم مِّنْ أَنفُسِكُمْ أَزْوَاجًا لِّتَسْكُنُوا إِلَيْهَا وَجَعَلَ بَيْنَكُم مَّوَدَّةً وَرَحْمَةً</p>
  <div class="names">Mohamed <span>&</span> Alaa</div>
  <div style="font-size:26px;font-weight:900">المهندس / محمد ياسر ❤️ الدكتورة / آلاء أشرف</div>

  <div class="card">
    <p style="font-size:18px">We cordially invite you to our engagement celebration on Thursday</p>
    <div class="count">
      <div><b id="d">00</b>يوم</div>
      <div><b id="h">00</b>ساعة</div>
      <div><b id="m">00</b>دقيقة</div>
      <div><b id="s">00</b>ثانية</div>
    </div>
    <div class="info">
      <div>🕔 5:00 PM</div>
      <div>📍 أمام منزل أشرف أبوجبل</div>
      <div>📅 26 | 11 | 2026</div>
    </div>
    <br>
    <a class="btn" href="https://wa.me/201000000000?text=ألف%20مبروك%20🎉" target="_blank">أكد حضورك واتساب 💌</a>
    <a class="btn btn2" href="https://maps.app.goo.gl/bJC4a11cxRg8xxdcA" target="_blank">موقع الحفل 📍</a>
  </div>
</div>
<script>
  const target = new Date("2026-11-26T17:00:00").getTime();
  setInterval(()=>{
    const now = new Date().getTime();
    let diff = target - now; if(diff<0) diff=0;
    document.getElementById("d").innerText = Math.floor(diff/(1000*60*60*24));
    document.getElementById("h").innerText = Math.floor((diff%(1000*60*60*24))/(1000*60*60));
    document.getElementById("m").innerText = Math.floor((diff%(1000*60*60))/(1000*60));
    document.getElementById("s").innerText = Math.floor((diff%(1000*60))/1000);
  },1000);
</script>
</body>
</html>
