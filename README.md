<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>متجر إلكتروني</title>
  <style>
    body { font-family: sans-serif; direction: rtl; background-color: #f4f4f4; margin: 0; padding: 0; }
    header { background-color: #333; color: white; padding: 1rem; text-align: center; }
    .container { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 1rem; padding: 2rem; }
    .product { background: white; border-radius: 10px; padding: 1rem; box-shadow: 0 2px 4px rgba(0,0,0,0.1); text-align: center; }
    .product img { max-width: 100%; height: auto; border-radius: 8px; }
    .product h3 { margin: 0.5rem 0; font-size: 1.1rem; }
    .product p { color: green; font-weight: bold; }
    .checkout { text-align: center; margin: 2rem; }
    .checkout a { background-color: #28a745; color: white; padding: 1rem 2rem; border-radius: 8px; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>متجر إلكتروني - كل منتج بـ 15,000 دينار عراقي</h1>
  </header>

  <div class="container">
    <!-- منتج 1 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="سماعات بلوتوث">
      <h3>سماعات بلوتوث</h3>
      <p>15,000 دينار عراقي</p>
      <a href="https://api.whatsapp.com/send?phone=9627867226456&text=أرغب في شراء سماعات بلوتوث" target="_blank">طلب عبر واتساب</a>
    </div>
    <!-- منتج 2 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="كفر موبايل">
      <h3>كفر موبايل</h3>
      <p>15,000 دينار عراقي</p>
      <a href="https://api.whatsapp.com/send?phone=9627867226456&text=أرغب في شراء كفر موبايل" target="_blank">طلب عبر واتساب</a>
    </div>
    <!-- منتج 3 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="شاحن سريع">
      <h3>شاحن سريع</h3>
      <p>15,000 دينار عراقي</p>
      <a href="https://api.whatsapp.com/send?phone=9627867226456&text=أرغب في شراء شاحن سريع" target="_blank">طلب عبر واتساب</a>
    </div>
    <!-- منتج 4 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="حامل موبايل">
      <h3>حامل موبايل</h3>
      <p>15,000 دينار عراقي</p>
      <a href="https://api.whatsapp.com/send?phone=9627867226456&text=أرغب في شراء حامل موبايل" target="_blank">طلب عبر واتساب</a>
    </div>
    <!-- منتج 5 -->
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="كيبل USB">
      <h3>كيبل USB سريع</h3>
      <p>15,000 دينار عراقي</p>
      <a href="https://api.whatsapp.com/send?phone=9627867226456&text=أرغب في شراء كيبل USB" target="_blank">طلب عبر واتساب</a>
    </div>
  </div>

  <div class="checkout">
    <h2>لطلب المنتج، يرجى الدفع عبر زين كاش إلى الرقم: <span style="color:#d00">07867226456</span></h2>
    <a href="https://api.whatsapp.com/send?phone=9627867226456" target="_blank">تأكيد التحويل عبر واتساب</a>
  </div>
</body>
</html>
