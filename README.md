<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>T4-FC | THPT Nguyễn Văn Hai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #2b0000, #4b0000, #7a1a00);
            color: #ffd580;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth; /* Cuộn mượt khi nhấn mục lục */
        }

        header {
            background: linear-gradient(90deg, #ff6600, #cc3300);
            color: #fff;
            text-align: center;
            padding: 20px;
            box-shadow: 0 0 20px #ff9933;
        }

        header img {
            width: 100px;
            vertical-align: middle;
            border-radius: 50%;
            border: 2px solid #ffcc66;
            box-shadow: 0 0 15px #ff9933;
            transition: 0.3s;
        }

        header img:hover {
            transform: scale(1.1);
        }

        header h1 {
            display: inline-block;
            margin-left: 15px;
            font-size: 2em;
            vertical-align: middle;
            color: #ffcc33;
            text-shadow: 0 0 15px #ff6600;
        }

        /* 🔸 Thanh mục lục */
        nav#toc {
            background: rgba(255, 213, 128, 0.08);
            box-shadow: 0 0 10px #ff9933;
            border-radius: 10px;
            margin: 20px auto;
            padding: 12px;
            max-width: 800px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 999;
            backdrop-filter: blur(6px);
        }

        nav#toc a {
            color: #ffcc66;
            font-weight: bold;
            text-decoration: none;
            margin: 0 12px;
            transition: 0.3s;
        }

        nav#toc a:hover {
            color: #fff;
            text-shadow: 0 0 10px #ffcc66;
        }

        section {
            padding: 20px;
            line-height: 1.6;
        }

        h2 {
            color: #ff9933;
            border-bottom: 2px solid #ffcc66;
            padding-bottom: 5px;
            text-shadow: 0 0 10px #ff6600;
        }
        /* Ảnh áo thi đấu */
        .uniforms {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            margin-top: 15px;
        }

        .uniforms div {
            text-align: center;
        }

        .uniforms img {
            width: 280px;
            border-radius: 15px;
            box-shadow: 0 0 15px #ff9933;
            transition: 0.3s;
        }

        .uniforms img:hover {
            transform: scale(1.05);
            box-shadow: 0 0 25px #ffcc33;
        }

        .uniforms p {
            margin-top: 8px;
            color: #ffcc66;
            font-weight: bold;
        }

        /* Bảng cầu thủ */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 30px;
            background-color: #ffd580;
            box-shadow: 0 0 15px #ff9933;
            font-size: 1.3em;
            font-weight: bold;
            table-layout: fixed;
            border-radius: 10px;
            overflow: hidden;
        }

        th, td {
            padding: 15px 12px;
            text-align: center;
            color: #000;
            word-wrap: break-word;
        }

        th {
            background: #ffcc66;
            font-size: 1.4em;
            position: sticky;
            top: 0;
            z-index: 2;
        }

        tr:nth-child(even) {
            background-color: #ffe0a3;
        }

        tr:hover {
            background-color: #ffd27f;
            transition: 0.3s;
        }

        footer {
            background: linear-gradient(90deg, #ff6600, #cc3300);
            color: #fff;
            text-align: center;
            padding: 10px;
            margin-top: 30px;
            box-shadow: 0 -3px 15px #ff9933;
        }

        /* Responsive cho điện thoại */
        @media (max-width: 600px) {
            header h1 {
                display: block;
                margin-top: 10px;
                font-size: 1.6em;
            }
            .uniforms img {
                width: 90%;
            }
            table {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="z5976717039808_f650e9c78d80460fcbb049c210a54470.jpg" alt="Logo T4-FC">
        <h1>T4-FC | THPT Nguyễn Văn Hai</h1>
    </header>

    <section>
        <h2>🔥 T4-FC – Tinh thần thể thao của THPT Nguyễn Văn Hai! 🔥</h2>
        <p>
            Thành lập ngày <strong>24/10/2024</strong>, <strong>T4-FC</strong> không chỉ là một đội bóng, mà còn là biểu tượng của tinh thần đoàn kết, khát khao chinh phục và đam mê sân cỏ.
            Dưới sự dẫn dắt của <strong>Huấn luyện viên Trần Văn Anh Khoa</strong>, các cầu thủ trẻ đã không ngừng rèn luyện, chiến đấu với trái tim rực lửa và niềm tin chiến thắng.
        </p>
        <p>
            Trên sân <strong>SÂN BÓNG - KHU LIÊN HỢP THỂ THAO CHÍ HÙNG</strong>, nơi mà chúng tôi gọi là “ngôi nhà thứ hai”, tiếng hô vang <strong>“THE FOURCE!”</strong> luôn là nguồn động lực mạnh mẽ, kết nối tất cả thành một tập thể bất khả chiến bại.
        </p>
        <p><strong>💪 T4-FC – Chiến đấu hết mình, vì danh dự, vì đam mê, vì tinh thần Nguyễn Văn Hai bất diệt!</strong></p>
    </section>
    <section id="history">
  <h2>🏆 Lịch sử hình thành và phát triển</h2>
  <p>
    Vào những ngày đầu của năm lớp 10(23-24), trên sân <strong>Học Đường</strong> chỉ có vài học sinh yêu bóng đá thường xuyên tụ tập để cùng nhau đá vui sau giờ học. 
    Trong số đó, một vài người đã từng được thi đấu ở các cấp dưới, có kinh nghiệm và niềm đam mê mãnh liệt với trái bóng tròn. 
    Chính từ những buổi tập đầy tiếng cười và tinh thần đồng đội ấy, ý tưởng thành lập một đội bóng chính thức của lớp dần được nhen nhóm.
  </p>

  <p>
    Cuối năm lớp 10(23-24), khi sự gắn kết giữa các thành viên ngày càng mạnh mẽ hơn, ý tưởng ấy được hiện thực hóa. 
    Đến đầu năm lớp 11, khoảng cuối tháng 9, số lượng thành viên tham gia các buổi đá bóng đã vượt con số 10. 
    Sau nhiều cuộc trò chuyện, chia sẻ và rủ rê, vào ngày <strong>24/10/2024</strong>, nhóm Zalo <strong>T4-FC</strong> chính thức được thành lập với 17 thành viên — đánh dấu cột mốc ra đời của đội bóng mang tinh thần trẻ trung, đoàn kết và khát vọng cháy bỏng.
  </p>

  <p>
    Dưới sự dẫn dắt của <strong>Coach-Trần Văn Anh Khoa</strong>, T4-FC bước vào những ngày đầu hoạt động đầy hứng khởi. 
    Tuy sở hữu lợi thế về số lượng nhưng đội vẫn còn non kinh nghiệm, lối chơi chưa đồng đều. 
    Trận đấu chính thức đầu tiên — cuộc đối đầu với A3 — tuy kết thúc bằng một thất bại, nhưng đó cũng chính là “bước ngoặt vàng”, mở ra hành trình rèn luyện, trưởng thành và hoàn thiện của từng thành viên. 
    Ngày hôm ấy không chỉ là đá giao hữu, mà còn là trận đấu ra mắt <strong>bộ áo đấu đầu tiên</strong> – biểu tượng cho tinh thần và niềm tự hào của T4-FC.
  </p>

  <p>
    Trong suốt năm lớp 11(24-25), đội không ngừng tập luyện và thi đấu. 
    Dù là giữa trưa nắng gắt, khi mưa rơi nặng hạt, hay lúc bóng tối dần phủ kín sân, <strong>T4-FC</strong> vẫn luôn hiện diện – mồ hôi thấm áo, ý chí không bao giờ tắt. 
    Từ những thất bại đầu tiên, đội đã xây dựng nên bản sắc riêng: thi đấu có chiến thuật, phối hợp nhuần nhuyễn, và trên hết là tinh thần “chiến đấu vì nhau”.
  </p>

  <p>
    Thành quả của những tháng ngày khổ luyện chính là việc <strong>T4-FC</strong> dần đánh bại những đối thủ mạnh trong trường, khẳng định vị thế của mình như một đội bóng đáng gờm. 
    Dù hiện tại, khi đã bước vào năm cuối cấp, áp lực học tập ngày một lớn, phong độ đôi lúc sa sút – nhưng ngọn lửa đam mê sân cỏ trong tim từng thành viên vẫn luôn cháy rực. 
    T4-FC không chỉ là một đội bóng, mà còn là một gia đình, nơi tình bạn, nhiệt huyết và khát vọng chiến thắng luôn song hành cùng năm tháng học trò.
  </p>
</section>

<style>
  #history {
    padding: 40px 25px;
    margin: 50px auto;
    background: rgba(255, 213, 128, 0.08);
    border-radius: 15px;
    box-shadow: 0 0 15px #ff9933;
  }

  #history h2 {
    color: #ff9933;
    text-shadow: 0 0 12px #ff6600;
    border-bottom: 2px solid #ffcc66;
    display: inline-block;
    padding-bottom: 6px;
    margin-bottom: 20px;
  }

  #history p {
    color: #ffcc66;
    line-height: 1.8;
    font-size: 1.1em;
    margin-bottom: 18px;
    text-align: justify;
  }

  #history strong {
    color: #ffd580;
  }
</style>


    <section>
        <h2>👕 Áo thi đấu chính thức của T4-FC</h2>
        <div class="uniforms">
            <div>
                <img src="z5973258455951_4d6dd257bc16403fc1cabbf1fc3bf7ab.jpg" alt="Áo thi đấu T4-FC">
                <p>Áo thi đấu</p>
            </div>
            <div>
                <img src="z6675838432936_81ae87965a74c971cca2df0014a03a89.jpg" alt="Áo thi đấu T4-FC">
                <p>Áo thi đấu</p>
            </div>
        </div>

        <h2 style="margin-top: 40px;">👥 Danh sách cầu thủ</h2>
        <table>
            <tr>
                <th>STT</th>
                <th>Tên cầu thủ</th>
                <th>Số áo</th>
                <th>Vị trí</th>
                <th>Ghi chú</th>
            </tr>
            <tr><td>1</td><td>Anh Oblak</td><td>1</td><td>GK</td><td>Thủ thành thép giữ vững niềm tin nơi khung gỗ</td></tr>
            <tr><td>2</td><td>Daniel Bảo</td><td>2</td><td>LB</td><td>Bức tường cánh trái, cản phá hàng công</td></tr>
            <tr><td>3</td><td>Thịnh Mbappe</td><td>4</td><td>RW</td><td>Tốc độ như tên bắn, những pha bức tốc khó tin</td></tr>
            <tr><td>4</td><td>Ngọc Tài</td><td>7</td><td>ST</td><td>Sát thủ vòng cấm, xuất hiện đúng lúc săn bàn chủ lực</td></tr>
            <tr><td>5</td><td>Triều Liều</td><td>8</td><td>CDM</td><td>Lá chắn vững chắc, chiến đấu không biết mệt mỏi</td></tr>
            <tr><td>6</td><td>Hào Milk</td><td>9</td><td>LW</td><td>Kỹ thuật tinh tế, át chủ bài trên hàng công</td></tr>
            <tr><td>7</td><td>Qui Musiala</td><td>10</td><td>AM</td><td>Khéo léo, sáng tạo và có tư duy chiến thuật</td></tr>
            <tr><td>8</td><td>Hiền Gullit</td><td>11</td><td>AM/FW</td><td>Cân bằng tuyến giữa tạo đột phá trong mọi tình huống</td></tr>
            <tr><td>9</td><td>Toàn Rivaldo</td><td>17</td><td>AM</td><td>Tốc độ biết cách đột biến ở những pha tấn công</td></tr>
            <tr><td>10</td><td>Khoa Kroos</td><td>18</td><td>CM</td><td>Chuyên gia chuyền dài, lên công, về thủ nhịp nhàng</td></tr>
            <tr><td>11</td><td>Lamine GiaHuy</td><td>19</td><td>RW</td><td>Khả năng bứt tốc và tạt bóng chuẩn xác</td></tr>
            <tr><td>12</td><td>Quí Gea</td><td>20</td><td>GK</td><td>Phòng thủ chắc chắn, tập trung sẵn sàng cứu thua </td></tr>
            <tr><td>13</td><td>Nhân Pirlo</td><td>21</td><td>CM</td><td>Kiểm soát trận đấu bằng những đường chuyền đẳng cấp</td></tr>
            <tr><td>14</td><td>Trường Tân</td><td>22</td><td>RW</td><td>Mũi khoan cánh phải ghi bàn chuẩn xác</td></tr>
            <tr><td>15</td><td>Phong Kumalala</td><td>24</td><td>LW</td><td>Cơn lốc cánh trái kỹ thuật và tốc độ bùng nổ</td></tr>
            <tr><td>16</td><td>Kha Boiz</td><td>28</td><td>CDM</td><td>Đa năng, luôn biết cách tạo sự khác biệt</td></tr>
            <tr><td>17</td><td>Kha Kaka</td><td>29</td><td>AM</td><td>Bậc thầy kiến tạo linh hồn sáng tạo nơi tuyến giữa</td></tr>
        </table>
    </section>
    <section id="contact">
  <h2 class="contact-title">📩 Liên hệ với T4-FC</h2>
  <p class="contact-desc">
    Nếu các đội bóng khác muốn <strong>giao lưu, tổ chức trận đấu hữu nghị</strong> hoặc 
    <strong>liên hệ hợp tác</strong> cùng T4-FC, hãy gửi thông tin cho chúng tôi tại đây:
  </p>

  <form id="contactForm" action="https://formspree.io/f/mkgwojqy" method="POST"
        class="contact-form">
    
    <label for="name" class="label"><strong>Tên đội bóng hoặc người liên hệ</strong></label><br>
    <input type="text" id="name" name="name" required class="input"><br>

    <label for="email" class="label"><strong>Email hoặc số điện thoại</strong></label><br>
    <input type="text" id="email" name="email" required class="input"><br>

    <label for="message" class="label"><strong>Nội dung liên hệ</strong></label><br>
    <textarea id="message" name="message" rows="4" required class="textarea"></textarea><br>

    <button type="submit" id="submitBtn" class="btn">
      Gửi liên hệ
    </button>

    <p id="statusMsg" class="status"></p>
  </form>
</section>

<style>
  /* Tiêu đề & mô tả */
  .contact-title {
    color: #ff9933;           /* màu da cam cho tiêu đề */
    text-shadow: 0 0 10px #ff6600;
    text-align: center;
    margin-bottom: 6px;
  }

  .contact-desc {
    color: #ffd580;           /* màu vàng sáng cho phần mô tả */
    text-align: center;
    margin: 0 0 18px 0;
  }

  /* Form */
  .contact-form {
    max-width: 450px;
    margin: 0 auto 30px;
    background: #fff3cd;
    padding: 24px;
    border-radius: 14px;
    box-shadow: 0 0 15px #ff9933;
    color: #000;              /* mặc định chữ trong form màu đen */
    font-weight: 500;
  }

  .label {
    color: #000;              /* nhãn ghi màu đen */
  }

  .input, .textarea {
    width: 100%;
    padding: 10px;
    margin: 8px 0 12px 0;
    border: 1px solid #d4c49a;
    border-radius: 8px;
    font-size: 1em;
    color: #000;              /* chữ nhập màu đen */
    background: #fff;
    box-sizing: border-box;
  }

  .textarea { min-height: 110px; }

  .btn {
    display: inline-block;
    background: linear-gradient(90deg,#ff6600,#cc3300);
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
    box-shadow: 0 0 10px #ff9933;
    transition: transform .15s, box-shadow .15s;
  }
  .btn:hover { transform: translateY(-2px); box-shadow: 0 0 18px #ffcc66; }

  .status {
    text-align: center;
    margin-top: 12px;
    color: #000;
    font-weight: 600;
  }

  /* Responsive */
  @media (max-width:600px) {
    .contact-form { padding: 18px; }
  }
</style>

<script>
  // Giữ lại behavior gửi và hiển thị trạng thái (như trước)
  const form = document.getElementById("contactForm");
  const btn = document.getElementById("submitBtn");
  const msg = document.getElementById("statusMsg");

  form.addEventListener("submit", (e) => {
    e.preventDefault();
    btn.disabled = true;
    btn.textContent = "⏳ Đang gửi...";
    msg.textContent = "";

    fetch(form.action, {
      method: "POST",
      body: new FormData(form),
      headers: { 'Accept': 'application/json' }
    }).then(response => {
      if (response.ok) {
        btn.textContent = "✅ Đã gửi thành công!";
        msg.textContent = "Cảm ơn bạn! T4-FC sẽ phản hồi sớm nhất.";
        form.reset();
      } else {
        btn.textContent = "⚠️ Lỗi gửi, thử lại!";
        msg.textContent = "Có lỗi xảy ra, vui lòng thử lại sau.";
      }
      setTimeout(() => {
        btn.disabled = false;
        btn.textContent = "Gửi liên hệ";
      }, 3500);
    }).catch(() => {
      btn.textContent = "⚠️ Lỗi kết nối!";
      msg.textContent = "Không thể gửi, vui lòng kiểm tra mạng.";
      btn.disabled = false;
    });
  });
</script>

<section id="map">
  <h2>📍 Sân thi đấu </h2>
  <p>Địa chỉ: <strong>W6FJ+M2H, Huyền Hội, Càng Long, Trà Vinh, Việt Nam</strong></p>

  <a href="https://www.google.com/maps/place/W6FJ%2BM2H,+Huy%E1%BB%81n+H%E1%BB%99i,+C%C3%A0ng+Long,+Tr%C3%A0+Vinh,+Vi%E1%BB%87t+Nam" 
     target="_blank" 
     class="map-btn">
     🔗 Xem vị trí trên Google Maps
  </a>
</section>

<style>
  #map {
    text-align: center;
    margin: 40px 0;
    background: rgba(255, 213, 128, 0.1);
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0 0 15px #ff9933;
  }

  #map h2 {
    color: #ff9933;
    text-shadow: 0 0 10px #ff6600;
    margin-bottom: 10px;
  }

  #map p {
    font-size: 1.2em;
    color: #ffcc66;
    margin-bottom: 15px;
  }

  .map-btn {
    display: inline-block;
    background: linear-gradient(90deg, #ff6600, #cc3300);
    color: #fff;
    padding: 12px 26px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 0 10px #ff9933;
    transition: 0.3s;
  }

  .map-btn:hover {
    background: linear-gradient(90deg, #ff9933, #ff6600);
    box-shadow: 0 0 20px #ffcc66;
    transform: scale(1.05);
  }
</style>

    <footer>
        <p>© 2025 T4-FC | THPT Nguyễn Văn Hai — Khẩu hiệu: <strong>THE FOURCE</strong></p>
    </footer>
<!-- Popup hiển thị thông tin cầu thủ -->
<div id="playerPopup" class="popup" style="display:none;">
  <div class="popup-content">
    <span class="close" onclick="closePopup()">&times;</span>
    <img id="playerImg" src="" alt="Ảnh cầu thủ">
    <h2 id="playerName"></h2>
    <p><strong>Ngày sinh:</strong> <span id="playerDob"></span></p>
    <p><strong>Nơi sinh:</strong> <span id="playerPlace"></span></p>
    <a id="playerFb" href="#" target="_blank" class="fb-link">Xem Facebook</a>
  </div>
</div>

<style>
/* --- Popup Style --- */
.popup {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.6);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 999;
}
.popup-content {
  background: #fff;
  border-radius: 15px;
  padding: 25px;
  width: 320px;
  text-align: center;
  position: relative;
  animation: fadeIn 0.3s ease-in-out;
}
.popup-content img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 10px;
}
.popup-content h2 { color: #b30000; margin: 10px 0; }
.popup-content p { margin: 5px 0; }
.popup-content .fb-link {
  display: inline-block;
  margin-top: 10px;
  background: #1877f2;
  color: #fff;
  padding: 8px 14px;
  border-radius: 8px;
  text-decoration: none;
}
.popup-content .close {
  position: absolute;
  top: 8px; right: 12px;
  font-size: 24px;
  cursor: pointer;
}
@keyframes fadeIn { from {opacity:0;} to {opacity:1;} }
</style>

<script>
// --- Dữ liệu 17 cầu thủ ---
const players = {
  "Nhân Pirlo": { name: "Huỳnh Ngọc Nhân", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/nhan", img: "default.jpg" },
  "Trường Tân": { name: "Nguyễn Trường Tân", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/truongtan", img: "default.jpg" },
  "Kha Boiz": { name: "Nguyễn Minh Kha", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/khaboiz", img: "default.jpg" },
  "Phát Tài": { name: "Trần Phát Tài", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/phattai", img: "default.jpg" },
  "Bảo Anh": { name: "Trần Bảo Anh", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/baoanh", img: "default.jpg" },
  "Lâm Sang": { name: "Lâm Hữu Sang", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/lamhuusang", img: "default.jpg" },
  "Tấn Đạt": { name: "Nguyễn Tấn Đạt", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/tandat", img: "default.jpg" },
  "Minh Khánh": { name: "Nguyễn Minh Khánh", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/minhkhanh", img: "default.jpg" },
  "Hoàng Phúc": { name: "Trần Hoàng Phúc", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/hoangphuc", img: "default.jpg" },
  "Nhật Nam": { name: "Nguyễn Nhật Nam", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/nhatnam", img: "default.jpg" },
  "Công Lý": { name: "Phạm Công Lý", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/congly", img: "default.jpg" },
  "Ngọc Tài": { name: "Nguyễn Ngọc Tài", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/ngoctai", img: "default.jpg" },
  "Hữu Tín": { name: "Nguyễn Hữu Tín", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/huutin", img: "default.jpg" },
  "Trường An": { name: "Nguyễn Trường An", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/truongan", img: "default.jpg" },
  "Tấn Khoa": { name: "Nguyễn Tấn Khoa", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/tankhoa", img: "default.jpg" },
  "Tuấn Kiệt": { name: "Trần Tuấn Kiệt", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/tuankiet", img: "default.jpg" },
  "Hữu Nghĩa": { name: "Nguyễn Hữu Nghĩa", dob: "2007", place: "Trà Vinh", fb: "https://facebook.com/huunghia", img: "default.jpg" }
};

// --- Hàm hiển thị popup ---
function showPlayerInfo(nickname) {
  const p = players[nickname];
  if (!p) return alert("Không tìm thấy thông tin cầu thủ này!");
  document.getElementById("playerImg").src = p.img;
  document.getElementById("playerName").textContent = p.name;
  document.getElementById("playerDob").textContent = p.dob;
  document.getElementById("playerPlace").textContent = p.place;
  document.getElementById("playerFb").href = p.fb;
  document.getElementById("playerPopup").style.display = "flex";
}

function closePopup() {
  document.getElementById("playerPopup").style.display = "none";
}
</script>

</body>
</html>
