# 🚀 ThanhDev Hub AI

**ThanhDev Hub AI** là ứng dụng web trợ lý trí tuệ nhân tạo giao diện tối (Dark Mode) hiện đại, kết nối trực tiếp với **Google Gemini API (`gemini-3-flash-preview`)** ngay trên trình duyệt mà không cần máy chủ trung gian (Backend).

![ThanhDev Hub AI Logo](./logo.jpg)

---

## ✨ Tính năng nổi bật

- **Kết nối API trực tiếp & Bảo mật:** API Key được lưu cục bộ trên trình duyệt của người dùng (`localStorage`), đảm bảo quyền riêng tư tuyệt đối.
- **Hiển thị Markdown & Code chuyên nghiệp:** Tích hợp `Marked.js` và `Highlight.js` giúp định dạng văn bản, bảng biểu và tô màu cú pháp (Syntax Highlighting) cho nhiều ngôn ngữ lập trình.
- **Sao chép nhanh (1-Click Copy):** Nút sao chép riêng cho từng đoạn mã nguồn (Code Block) và toàn bộ câu trả lời.
- **Lưu trữ lịch sử hội thoại:** Tự động lưu lịch sử trò chuyện trên trình duyệt và hỗ trợ xóa nhanh khi cần.
- **Tự động thử lại (Auto-Retry):** Cơ chế Exponential Backoff tự động gọi lại API nếu gặp lỗi mạng tạm thời.
- **Hiệu ứng âm thanh tương tác:** Tích hợp Web Audio API tạo âm thanh phản hồi nhẹ nhàng khi gửi và nhận tin nhắn.
- **Giao diện Responsive:** Tối ưu hiển thị mượt mà trên cả máy tính và điện thoại nhờ `Tailwind CSS`.

---

## 📂 Cấu trúc thư mục

Để ứng dụng hiển thị đầy đủ logo và hoạt động chính xác, hãy giữ cấu trúc thư mục như sau:

```text
ThanhDev-Hub-AI/
├── index.html      # Mã nguồn chính của ứng dụng (HTML, CSS, JS)
├── logo.jpg        # Logo thương hiệu & Favicon của ThanhDev Hub AI
└── README.md       # Tài liệu hướng dẫn dự án
