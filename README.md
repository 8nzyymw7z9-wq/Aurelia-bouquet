<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Aurelia | ออกแบบช่อดอกไม้ของคุณ</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f6fbfa;
  color: #40554b;
}

header {
  text-align: center;
  padding: 35px 20px;
  background: linear-gradient(135deg, #dceff5, #e0f1e5);
}

header h1 {
  margin: 0;
  font-family: Georgia, serif;
  letter-spacing: 6px;
  font-size: 38px;
}

header p {
  margin: 10px 0 0;
  color: #668075;
}

.container {
  max-width: 900px;
  margin: auto;
  padding: 25px 15px 50px;
}

.section-title {
  text-align: center;
  margin-bottom: 8px;
}

.section-description {
  text-align: center;
  color: #71847a;
  margin-bottom: 25px;
}

.flower-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
}

.flower-card {
  background: white;
  border-radius: 18px;
  padding: 15px;
  border: 1px solid #dce9e3;
  box-shadow: 0 3px 10px rgba(0,0,0,0.03);
}

.flower-name {
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 6px;
}

.price {
  color: #739182;
  margin-bottom: 12px;
}

label {
  font-size: 13px;
  display: block;
  margin-bottom: 5px;
}

input {
  width: 100%;
  padding: 9px;
  border-radius: 10px;
  border: 1px solid #cfded7;
  margin-bottom: 8px;
}

.color-note {
  font-size: 11px;
  color: #8a9b92;
}

@media (max-width: 600px) {
  .flower-grid {
    grid-template-columns: 1fr;
  }
}
</style>

</head>

<body>

<header>
  <h1>AURELIA</h1>
  <p>ออกแบบช่อดอกไม้ของคุณ</p>
</header>

<div class="container">

<h2 class="section-title">เลือกดอกไม้</h2>

<p class="section-description">
เลือกดอกไม้และระบุสีที่คุณต้องการ
</p>

<div class="flower-grid">

<div class="flower-card">
<div class="flower-name">กุหลาบใหญ่</div>
<div class="price">50 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="เช่น สีแดง สีขาว สีชมพู">
</div>

<div class="flower-card">
<div class="flower-name">กุหลาบเล็ก</div>
<div class="price">30 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ลิลลี่บาน</div>
<div class="price">40 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ลิลลี่หุบ</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ทานตะวัน</div>
<div class="price">35 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ทานตะวันรีดกลีบ</div>
<div class="price">40 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกระฆัง 6 ดอก</div>
<div class="price">49 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกระฆัง 8 ดอก</div>
<div class="price">69 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกคาร์เนชั่น</div>
<div class="price">30 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกลิลลี่แห่งหุบเขา 7 ดอก</div>
<div class="price">49 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกทิวลิป</div>
<div class="price">30 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกเดซี่</div>
<div class="price">5 บาท / ดอก</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกเยอบีร่า</div>
<div class="price">25 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกไฮเดรนเยียเล็ก</div>
<div class="price">45 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ลาเวนเดอร์เล็ก</div>
<div class="price">5 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกกล้วยไม้</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกคาลล่าลิลลี่</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกป๊อบปี้</div>
<div class="price">30 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกไฮยาซินธ์</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกทิวลิปเกลียว</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกลิลลี่บานน้อย</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกลิลลี่กลีบโค้ง</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

<div class="flower-card">
<div class="flower-name">ดอกเยอบีร่า</div>
<div class="price">20 บาท</div>
<label>สีที่ต้องการ</label>
<input type="text" placeholder="ระบุสีที่ต้องการ">
</div>

</div>

</div>

</body>
</html>
