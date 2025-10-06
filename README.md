<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tinh Thủy Trà</title>
<style>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background-color: #ffe6f2; /* Nền hồng nhạt */
  color: #3cb371; /* Toàn bộ chữ màu xanh lá cây */
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 1000;
}

.logo {
  height: 70px;
}

nav a {
  text-decoration: none;
  color: #3cb371;
  margin: 0 20px;
  font-weight: bold;
  transition: color 0.3s;
}
nav a:hover {
  color: #2e8b57;
}

/* Hero section */
.hero {
  text-align: center;
  padding: 150px 20px;
  background-image: url("file_0000000013e861f6b6ebb2df6dfdfe4f.png");
  background-size: cover;
  background-position: center;
  background-attachment: fixed; /* Parallax effect */
  color: #3cb371;
  animation: fadeIn 2s ease-in;
}
.hero h1 {
  font-size: 2.8em;
}
.hero p {
  font-size: 1.2em;
  max-width: 800px;
  margin: 20px auto;
  line-height: 1.6;
}

/* Sections */
.section {
  padding: 80px 20px;
  text-align: center;
  background-color: #fff0f5; /* Giữ nền hồng nhẹ */
  border-radius: 20px;
  margin: 60px auto;
  width: 85%;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  opacity: 0;
  transform: translateY(40px);
  transition: all 1s ease;
}
.section.visible {
  opacity: 1;
  transform: translateY(0);
}
.section h2 {
  color: #2e8b57;
  margin-bottom: 20px;
}

/* Cards */
.features {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 30px;
}
.card {
  width: 300px;
  background: #ffffff;
  border-radius: 16px;
  padding: 20px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  transition: transform 0.3s, box-shadow 0.3s;
}
.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.3);
}
.card img {
  width: 100%;
  border-radius: 12px;
  margin-bottom: 15px;
}
.card h3 {
  color: #3cb371;
}

/* Contact */
.social-icons a {
  color: #3cb371;
  margin: 0 8px;
  text-decoration: none;
  font-weight: bold;
}
.social-icons a:hover {
  color: #228b22;
}

/* Footer */
footer {
  background: #ffd6e8;
  text-align: center;
  padding: 20px;
  color: #3cb371;
  font-weight: 600;
  box-shadow: 0 -2px 10px rgba(0,0,0,0.1);
}

/* Chatbox */
.chatbox {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #3cb371;
  color: white;
  padding: 14px 20px;
  border-radius: 50px;
  font-weight: bold;
  cursor: pointer;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  transition: background 0.3s;
}
.chatbox:hover {
  background-color: #2e8b57;
}

/* Animation */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
</head>

<body>
<header>
  <img src="A_logo_design_for_\"Tinh_Thủy_Trà\"_is_displayed_in_.png" alt="Tinh Thủy Trà Logo" class="logo">
  <nav>
    <a href="#gioithieu">Giới thiệu</a>
    <a href="#sanpham">Sản phẩm</a>
    <a href="#congnghe">Công nghệ</a>
    <a href="#lienhe">Liên hệ</a>
  </nav>
</header>

<section class="hero">
  <h1>Tinh Thủy Trà – Gói trọn tinh túy đất trời trong từng lá trà</h1>
  <p>Tinh Thủy Trà mang đến sự giao hòa giữa thiên nhiên thuần khiết và công nghệ hiện đại, nơi mỗi tách trà không chỉ chứa đựng tinh túy từ đất trời, mà còn là biểu tượng của lối sống xanh, thông minh và kết nối toàn cầu.</p>
</section>

<section id="gioithieu" class="section">
  <h2>Lý do ra đời</h2>
  <p>Tinh Thủy Trà là dòng trà sấy khô cao cấp, được phát triển theo hướng “trà thông minh – sản xuất xanh”, kết hợp tinh hoa trà truyền thống với công nghệ hiện đại, đáp ứng xu hướng tiêu dùng đồ uống lành mạnh và tự nhiên.</p>
  <img src="https://cdn.pixabay.com/photo/2017/06/28/09/45/tea-2457560_1280.jpg" alt="Trà túi lọc" width="50%">
</section>

<section id="sanpham" class="section">
  <h2>Sản phẩm nổi bật</h2>
  <div class="features">
    <div class="card">
      <img src="https://cdn.pixabay.com/photo/2018/05/07/22/25/tea-3388567_1280.jpg" alt="Trà sấy khô">
      <h3>Trà sấy khô</h3>
      <p>Trà sấy khô từ lá trà, hoa, thảo mộc – giữ trọn hương vị tự nhiên nhờ công nghệ sấy thăng hoa.</p>
    </div>
    <div class="card">
      <img src="https://cdn.pixabay.com/photo/2020/04/20/17/22/tea-5066980_1280.jpg" alt="Trà viên nén">
      <h3>Trà viên nén (Tea Pods)</h3>
      <p>Tiện lợi pha nhanh, phù hợp nhịp sống hiện đại – chỉ cần vài giây là có tách trà hoàn hảo.</p>
    </div>
    <div class="card">
      <img src="https://cdn.pixabay.com/photo/2015/09/09/18/54/tea-931254_1280.jpg" alt="Trà thiên nhiên">
      <h3>Trà thiên nhiên</h3>
      <p>Nguyên liệu sạch, không phẩm màu, không hương liệu nhân tạo – tốt cho sức khỏe.</p>
    </div>
  </div>
</section>

<section id="congnghe" class="section">
  <h2>Công nghệ & Sáng tạo</h2>
  <p>Ứng dụng công nghệ sấy thăng hoa có giám sát IoT, kết hợp AI và Blockchain giúp truy xuất nguồn gốc sản phẩm, cá nhân hóa trải nghiệm thưởng trà cho từng khách hàng.</p>
  <img src="https://cdn.pixabay.com/photo/2018/04/11/08/17/tea-3312290_1280.jpg" alt="Công nghệ trà" width="50%">
</section>

<section id="lienhe" class="section">
  <h2>Liên hệ</h2>
  <p>📞 SĐT: 0363963329 | 📧 Email: tinhthuytra@gmail.com</p>
  <div class="social-icons">
    <a href="https://facebook.com" target="_blank">Facebook</a> |
    <a href="https://tiktok.com" target="_blank">TikTok</a> |
    <a href="https://shopee.vn" target="_blank">Shopee</a>
  </div>
</section>

<footer>
  <p>© 2025 Tinh Thủy Trà – Gói trọn tinh túy đất trời trong từng lá trà</p>
</footer>

<div class="chatbox" onclick="alert('Xin chào! Tinh Thủy Trà sẵn sàng hỗ trợ bạn 🌿')">
  💬 Chat với chúng tôi
</div>

<script>
const sections = document.querySelectorAll('.section');
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.2 });
sections.forEach(section => observer.observe(section));
</script>

</body>
</html>
