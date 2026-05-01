<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Fendi Menu</title>

<style>
body {
  margin: 0;
  background: #0e0e0e;
  color: #fff;
  font-family: Arial, sans-serif;
  padding: 40px 20px;
}

h1 {
  text-align: center;
  letter-spacing: 3px;
  margin-bottom: 10px;
}

.subtitle {
  text-align: center;
  color: #888;
  margin-bottom: 30px;
  font-size: 14px;
}

.section {
  margin-top: 30px;
  color: #f5c542;
  font-weight: bold;
  letter-spacing: 2px;
}

.item {
  border-bottom: 1px solid #222;
  padding: 15px 0;
}

.header {
  display: flex;
  justify-content: space-between;
  cursor: pointer;
}

.name {
  font-size: 16px;
}

.price {
  color: #f5c542;
  font-weight: bold;
}

.desc {
  font-size: 13px;
  color: #aaa;
  margin-top: 8px;
  display: none;
  line-height: 1.5;
}

.item.active .desc {
  display: block;
}
</style>
</head>

<body>

<h1>FENDI</h1>
<div class="subtitle">Violin Studio / Menu</div>

<!-- 課程 -->
<div class="section">COURSES</div>

<div class="item" onclick="toggle(this)">
  <div class="header">
    <div class="name">初級課程</div>
    <div class="price">$1199</div>
  </div>
  <div class="desc">
    適合零基礎學習者，建立正確持琴、運弓與基礎樂理。
  </div>
</div>

<div class="item" onclick="toggle(this)">
  <div class="header">
    <div class="name">中級課程</div>
    <div class="price">$1499</div>
  </div>
  <div class="desc">
    強化音色控制、換把技巧與基礎音樂表現力，進入音樂詮釋階段。
  </div>
</div>

<div class="item" onclick="toggle(this)">
  <div class="header">
    <div class="name">專業級課程</div>
    <div class="price">$1999</div>
  </div>
  <div class="desc">
    針對演奏者設計，深入曲目詮釋、舞台表現與音樂結構分析。
  </div>
</div>

<!-- 琴盒 -->
<div class="section">ACCESSORIES</div>

<div class="item" onclick="toggle(this)">
  <div class="header">
    <div class="name">牛皮琴盒</div>
    <div class="price">$38000</div>
  </div>
  <div class="desc">
    高級牛皮外層設計，兼具保護性與質感，適合專業演奏者使用。
  </div>
</div>

<script>
function toggle(el) {
  el.classList.toggle("active");
}
</script>

</body>
</html>
