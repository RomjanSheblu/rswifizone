<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RS Wifi Zone</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
  font-family:'Segoe UI',sans-serif;
  background:linear-gradient(135deg,#0f0c29,#302b63,#24243e);
  color:white;
}

/* Navbar */
.navbar{
  background:rgba(0,0,0,0.6);
  backdrop-filter:blur(10px);
  padding:18px;
  text-align:center;
  font-size:24px;
  font-weight:bold;
  color:#00f5ff;
  letter-spacing:1px;
  box-shadow:0 0 15px rgba(0,255,255,0.3);
}

/* Hero */
.hero{
  height:420px;
  background:url('banner.jpg') no-repeat center center;
  background-size:cover;
  display:flex;
  align-items:center;
  justify-content:center;
}
.hero h1{
  background:rgba(0,0,0,0.6);
  padding:20px 35px;
  border-radius:15px;
  color:#00f5ff;
  font-size:32px;
  box-shadow:0 0 20px rgba(0,255,255,0.5);
}

/* Notice */
.notice-bar{
  display:flex;
  background:linear-gradient(90deg,#ff416c,#ff4b2b);
  overflow:hidden;
  align-items:center;
}

.notice-label{
  background:#8b0000;
  padding:12px 18px;
  font-weight:bold;
  font-size:18px;
}

.notice-text{
  flex:1;
  white-space:nowrap;
  overflow:hidden;
}

.notice-scroll{
  display:inline-block;
  padding-left:100%;
  font-size:20px;   /* 🔥 ফন্ট বড় করা হয়েছে */
  font-weight:600;
  animation:scroll 20s linear infinite;
}

@keyframes scroll{
  0%{transform:translateX(0);}
  100%{transform:translateX(-100%);}
}

/* Section */
.section{
  padding:60px 20px;
  text-align:center;
}

/* Packages */
.packages{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:25px;
}

.card{
  background:rgba(255,255,255,0.08);
  backdrop-filter:blur(15px);
  padding:25px;
  width:260px;
  border-radius:20px;
  transition:0.4s;
  box-shadow:0 0 25px rgba(0,255,255,0.2);
}

.card:hover{
  transform:translateY(-10px) scale(1.03);
  box-shadow:0 0 35px rgba(0,255,255,0.5);
}

.card h3{
  color:#00f5ff;
  margin-bottom:10px;
}

.price{
  margin:12px 0;
  font-size:20px;
  font-weight:bold;
}

.btn{
  background:linear-gradient(45deg,#00f5ff,#00c3ff);
  border:none;
  padding:10px 18px;
  border-radius:8px;
  cursor:pointer;
  font-weight:bold;
  transition:0.3s;
}

.btn:hover{
  opacity:0.8;
}

/* Payment */
.payment-box{
  background:rgba(255,255,255,0.08);
  padding:25px;
  border-radius:15px;
  max-width:450px;
  margin:25px auto;
  box-shadow:0 0 25px rgba(255,75,43,0.3);
}

/* Contact */
.contact-container{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:25px;
}

.contact-card{
  background:rgba(255,255,255,0.08);
  padding:25px;
  width:260px;
  border-radius:20px;
  transition:0.4s;
  box-shadow:0 0 25px rgba(0,255,255,0.2);
}

.contact-card:hover{
  transform:translateY(-8px);
  box-shadow:0 0 30px rgba(255,0,150,0.6);
}

.contact-card a{
  color:#00f5ff;
  text-decoration:none;
  font-size:18px;
}

.footer{
  background:#111827;
  padding:20px;
  text-align:center;
  margin-top:40px;
  font-size:14px;
}
</style>
</head>

<body>

<div class="navbar">RS Wifi Zone</div>

<div class="hero">
  <h1></h1>
</div>

<div class="notice-bar">
  <div class="notice-label">📢 নোটিশ</div>
  <div class="notice-text">
    <div class="notice-scroll">
      প্রতি মাসের ইন্টারনেট বিল 10 তারিকের মধ্যে প্রেমেন্ট করুন; অন্যথায় সংযোগ বিচ্ছিন্ন করা হবে - আদেশক্রমে কর্তৃপক্ষ ******  RS WIFI Zone সংযুক্ত থাকুন এগিয়ে চলুন, আপনার সেবাই আমাদের কাম্য*******
    </div>
  </div>
</div>

<div class="section">
  <h2>আমাদের প্যাকেজ</h2>
  <div class="packages">
    <div class="card">
      <h3>Basic</h3>
      <p>আনলিমিটেড ইন্টারনেট</p>
      <p>সারা মাস (১ ডিভাইস)</p>
      <div class="price">১০০ টাকা</div>
      <button class="btn">Subscribe</button>
    </div>
    <div class="card">
      <h3>Standard</h3>
      <p>৩০ দিন WIFI+IPTV</p>
      <div class="price">২০০ টাকা</div>
      <button class="btn">Subscribe</button>
    </div>
    <div class="card">
      <h3>Premium</h3>
      <p>WIFI+IPTV+IP PHONE</p>
      <div class="price">৩০০ টাকা</div>
      <button class="btn">Subscribe</button>
    </div>
  </div>
</div><div class="section">
  <h2>অনলাইন পেমেন্ট</h2>
  <div class="payment-box">
    <p>রকেট: <strong>01982528055</strong></p>
    <p>Nagad: <strong>01700628666</strong></p>
    <p>পেমেন্ট করার পর ট্রানজেকশন আইডি</p>
    <p>WhatsAppএ মেসেজ করুন</p>
  </div>
</div>

<div class="section">
  <h2>যোগাযোগ করুন</h2>
  <div class="contact-container">
    <div class="contact-card">
      <h3>📞 কল করুন</h3>
      <a href="tel:8801700628666">8801700628666</a>
    </div>
    <div class="contact-card">
      <h3>💬 WhatsApp</h3>
      <a href="https://wa.me/8801700628666">মেসেজ করুন</a>
    </div>
    <div class="contact-card">
      <h3>📍 ঠিকানা</h3>
      <p>শহির উদ্দিন মিয়ার বাড়ী,</p>
      <p>বুড়ির বাজার রোড</p>
      <p>উত্তর গাজীরচট, ধামসোনা</p>
      <p>আশুলিয়া, সাভার, ঢাকা-১৩৪৯</p>
    </div>
  </div>
</div>

<div class="footer">
© 2026 RS Wifi Zone | সর্বস্বত্ব সংরক্ষিত
</div>

</body>
</html>
