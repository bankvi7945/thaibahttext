<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>TrueMoney Gift Kiosk</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
    }
    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>

  <!--
    sandbox attribute:
      - allow-forms: ยอมให้กรอกและส่งฟอร์มภายใน iframe
      - allow-scripts: ยอมให้รัน JavaScript ภายใน iframe
      - allow-same-origin: รักษา origin เดิม (cookies, storage) สำหรับฟีเจอร์ในแอพ
    ไม่ได้ให้ allow-top-navigation หรือ allow-top-navigation-by-user-activation
    จึงจะบล็อกทุกการพยายามเปลี่ยนหน้าทั้งหมดของหน้าบนสุด
  -->
  <iframe
    sandbox="allow-forms allow-scripts allow-same-origin"
    src="https://gift.truemoney.com/campaign/?v=01964bbca584730cb23a9a21631158e3c9X"
    allowfullscreen
  ></iframe>

</body>
</html>