    
<style>
  @keyframes slideDown {
  from {
    transform: translateY(-100%);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}

.notification.slide-down {
  animation: slideDown 0.8s ease forwards;
}

  @keyframes slideDownOut {
  from {
    transform: translateY(0);
    opacity: 1;
  }
  to {
    transform: translateY(100%);
    opacity: 0;
  }
}

.notification.slide-down-out {
  animation: slideDownOut 0.8s ease forwards;
}


  .notification {
    border-radius: 8px;
    border: 1px solid #00ffff; /* Đường viền cho khung thông báo */
    background-color: #f9f9f9; /* Màu nền cho khung thông báo */
    padding: 20px;
    width: 400px;
    text-align: center;
    position: fixed;
    top: 20%;
    left: 1.6%;
    transform: translate(-50%, -50%);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    z-index: 1000;
    display: none; /* Ẩn thông báo khi chưa được gọi */
    animation: slideDown 0.8s ease-in-out forwards; /* Thêm hiệu ứng fadeIn */
  }
  .close-btn {
    background-color: #000000;
    color: white;
    border: none;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 12px;
    animation:myfirst 0.1s;animation-iteration-count:infinite;-webkit-animation:myfirst 0.8s;-webkit-animation-iteration-count:infinite;font-family:Arial;font-weight:bold;text-decoration:none}@keyframes myfirst{0%{color:hsl(  10,90%,60% )}6%{color:hsl(  30,90%,60% )}12%{color:hsl(  50,90%,60% )}18%{color:hsl(  70,90%,60% )}24%{color:hsl(  90,90%,60% )}30%{color:hsl( 110,90%,60% )}36%{color:hsl( 130,90%,60% )}42%{color:hsl( 150,90%,60% )}48%{color:hsl( 170,90%,60% )}54%{color:hsl( 190,90%,60% )}60%{color:hsl( 210,90%,60% )}66%{color:hsl( 230,90%,60% )}72%{color:hsl( 250,90%,60% )}78%{color:hsl( 270,90%,60% )}84%{color:hsl( 290,90%,60% )}90%{color:hsl( 310,90%,60% )}96%{color:hsl( 330,90%,60% )}100%{color:hsl( 350,90%,60% )}}@-webkit-keyframes myfirst{0%{color:hsl(  10,90%,60% )}6%{color:hsl(  30,90%,60% )}12%{color:hsl(  50,90%,60% )}18%{color:hsl(  70,90%,60% )}24%{color:hsl(  90,90%,60% )}30%{color:hsl( 110,90%,60% )}36%{color:hsl( 130,90%,60% )}42%{color:hsl( 150,90%,60% )}48%{color:hsl( 170,90%,60% )}54%{color:hsl( 190,90%,60% )}60%{color:hsl( 210,90%,60% )}66%{color:hsl( 230,90%,60% )}72%{color:hsl( 250,90%,60% )}78%{color:hsl( 270,90%,60% )}84%{color:hsl( 290,90%,60% )}90%{color:hsl( 310,90%,60% )}96%{color:hsl( 330,90%,60% )}100%{color:hsl( 350,90%,60% )}
      }
.tenchina{color:black;animation:myfirst 0.8s;animation-iteration-count:infinite;-webkit-animation:myfirst 1.2s;-webkit-animation-iteration-count:infinite;font-family:Arial;font-weight:bold;font-size:15px;text-decoration:none;text-align:center}@keyframes myfirst{0%{color:hsl( 10,90%,60% )}6%{color:hsl( 30,90%,60% )}12%{color:hsl( 50,90%,60% )}18%{color:hsl( 70,90%,60% )}24%{color:hsl( 90,90%,60% )}30%{color:hsl( 110,90%,60% )}36%{color:hsl( 130,90%,60% )}42%{color:hsl( 150,90%,60% )}48%{color:hsl( 170,90%,60% )}54%{color:hsl( 190,90%,60% )}60%{color:hsl( 210,90%,60% )}66%{color:hsl( 230,90%,60% )}72%{color:hsl( 250,90%,60% )}78%{color:hsl( 270,90%,60% )}84%{color:hsl( 290,90%,60% )}90%{color:hsl( 310,90%,60% )}96%{color:hsl( 330,90%,60% )}100%{color:hsl( 350,90%,60% )}}@-webkit-keyframes myfirst{0%{color:hsl( 10,90%,60% )}6%{color:hsl( 30,90%,60% )}12%{color:hsl( 50,90%,60% )}18%{color:hsl( 70,90%,60% )}24%{color:hsl( 90,90%,60% )}30%{color:hsl( 110,90%,60% )}36%{color:hsl( 130,90%,60% )}42%{color:hsl( 150,90%,60% )}48%{color:hsl( 170,90%,60% )}54%{color:hsl( 190,90%,60% )}60%{color:hsl( 210,90%,60% )}66%{color:hsl( 230,90%,60% )}72%{color:hsl( 250,90%,60% )}78%{color:hsl( 270,90%,60% )}84%{color:hsl( 290,90%,60% )}90%{color:hsl( 310,90%,60% )}96%{color:hsl( 330,90%,60% )}100%{color:hsl( 350,90%,60% )}}</style>
</head>
<body>

<div id="notification" class="notification">
  <div class="tenchina"><span style="font-size:22px">Chào mừng bạn đến với website của chúng tôi!</div>
  <div class="tenchina">
        Hỗ trợ nhà mạng Viettel
    <br>Cung cấp các máy chủ VPN 4G giá rẻ
    <br>Thanh toán duyệt đơn tự động Banking
    <br>Thanh toán bằng Momo, Card liên hệ admin
    <br>Tham gia Groud Zalo để được hỗ trợ thêm nhé 
    
  </div>
  <button class="close-btn" onclick="document.getElementById('notification').style.display='none'">Đóng</button>
  <div class="tenchina"><span style="font-size:8">编辑 TenChina</div>
</div>

<script>
  // Hiển thị thông báo ngay khi trang web được tải
  window.onload = function() {
    document.getElementById('notification').style.display = 'block';
  };
  function closeNotification() {
  var notification = document.getElementById('notification');
  notification.classList.add('slide-down-out'); // Thêm class để kích hoạt hiệu ứng

  setTimeout(function() {
    notification.style.display = 'none';
  }, 800); // Đợi hiệu ứng hoàn tất rồi mới ẩn thông báo
}

// Gán hàm closeNotification vào sự kiện onclick của nút đóng
document.querySelector('.close-btn').onclick = closeNotification;

</script>
