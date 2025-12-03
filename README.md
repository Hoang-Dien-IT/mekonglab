# Mekong Lab - Chuyển đổi số & AI ĐBSCL

Trang web giới thiệu trung tâm nghiên cứu Mekong Lab chuyên về chuyển đổi số và trí tuệ nhân tạo cho Đồng bằng Sông Cửu Long.

## 📋 Tổng quan

Mekong Lab là trung tâm nghiên cứu chuyên sâu, tập hợp các nhà khoa học, kỹ sư và chuyên gia hàng đầu từ khắp vùng ĐBSCL. Website này giới thiệu về:

- **Sứ mệnh**: Nghiên cứu khoa học và phát triển ứng dụng thực tiễn
- **Lĩnh vực**: AI, Chuyển đổi số cho Nông nghiệp, Môi trường, Y tế
- **Sản phẩm**: DTDrugs, SahiKid, WikiCrop
- **Đội ngũ**: Các chuyên gia và nghiên cứu viên

## 🚀 Công nghệ sử dụng

### Frontend
- **HTML5** - Cấu trúc trang web với ngôn ngữ tiếng Việt
- **Tailwind CSS** - Framework CSS utility-first từ CDN
- **Google Fonts** - Font Inter (100-900)
- **CSS tùy chỉnh** - Gradient và animations
- **SVG Icons** - Icons inline cho UI

### Cấu hình Tailwind
```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        "mekong-blue": "#167683",
        "mekong-light": "#E0F7FA", 
        "mekong-green": "#38B2AC"
      },
      fontFamily: {
        sans: ["Inter", "sans-serif"]
      }
    }
  }
};