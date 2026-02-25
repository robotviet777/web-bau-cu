<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Tra cứu bầu cử - Phường Tân Thuận</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#c40000;
    background-image:url("trongdong.png");
    background-repeat:no-repeat;
    background-position:center;
    background-size:80%;
}

/* HEADER */
.header{
    background:#d60000;
    color:white;
    text-align:center;
    padding:30px 10px;
}

.header h1{margin:0;font-size:28px;}
.header p{margin-top:10px;}

/* CONTAINER */
.container{
    width:80%;
    margin:40px auto;
    background:#111;
    border:2px solid gold;
    border-radius:15px;
    padding:30px;
    color:white;
    text-align:center;
}

/* INPUT */
input{
    width:80%;
    padding:12px;
    border-radius:5px;
    border:none;
    margin-bottom:15px;
}

button{
    padding:10px 25px;
    background:#d60000;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
    margin:5px;
}

.title{
    color:#ffcc00;
    font-size:22px;
    margin-bottom:20px;
}

/* MAP */
.map-box{
    width:100%;
    height:400px;
    margin-bottom:30px;
}

iframe{
    width:100%;
    height:100%;
    border-radius:10px;
}

/* IMAGE */
.image-box img{
    width:100%;
    border-radius:10px;
    border:3px solid gold;
}

/* ẨN TRANG */
.page{
    display:none;
}
</style>
</head>

<body>

<div class="header">
    <h1>ỦY BAN BẦU CỬ PHƯỜNG TÂN THUẬN</h1>
    <p>Tra cứu danh sách cử tri và khu vực bỏ phiếu</p>
</div>

<!-- ================= TRANG 1 ================= -->
<div class="container page" id="page1">

    <div class="title">TRA CỨU ĐỊA ĐIỂM BỎ PHIẾU</div>

    <input type="text" placeholder="Vui lòng nhập khu phố của cử tri...">
    <br>
    <button onclick="goPage(2)">TÌM KIẾM</button>

    <br><br>
    <img src="anh.jpg" style="width:100%;border-radius:10px;border:3px solid gold;">

</div>

<!-- ================= TRANG 2 ================= -->
<div class="container page" id="page2">

    <div class="title">THÔNG TIN KHU VỰC BỎ PHIẾU</div>

    <p><b>Khu vực bỏ phiếu:</b> 27</p>
    <p><b>Đơn vị bầu cử:</b> 09</p>
    <p><b>Địa điểm:</b> VP Khu phố 52 - 56, số 18B đường 11N, P Tân Thuận, TP.HCM</p>

    <br>
    <button onclick="goPage(3)">XEM BẢN ĐỒ</button>
    <button onclick="goPage(1)">QUAY LẠI</button>

</div>

<!-- ================= TRANG 3 ================= -->
<div class="container page" id="page3">

    <div class="title">BẢN ĐỒ GOOGLE MAP</div>

    <div class="map-box">
        <iframe 
        src="https://maps.app.goo.gl/Dy7FcJwDwi3Fvsvg8">
        </iframe>
    </div>

    <div class="title">HÌNH ẢNH VĂN PHÒNG KHU PHỐ</div>

    <div class="image-box">
        <img src="kp56.jpg">
    </div>

    <br>
    <button onclick="goPage(2)">QUAY LẠI</button>

</div>

<script>
function goPage(pageNumber){
    document.querySelectorAll(".page").forEach(p => p.style.display="none");
    document.getElementById("page"+pageNumber).style.display="block";
}

/* Mặc định mở trang 1 */
goPage(1);
</script>

</body>
</html>
