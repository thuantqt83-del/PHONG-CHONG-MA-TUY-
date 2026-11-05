# Ứng dụng học tập với AI phòng chống ma túy

Ứng dụng học tập tương tác giúp học sinh hiểu đúng về ma túy, tác hại và pháp luật, đồng thời luyện kĩ năng nói KHÔNG theo nguyên tắc **3T**: **Tỉnh táo – Từ chối – Thoát ra & Thông báo**.

## Nội dung chính

- **6 bài học:** Ma túy là gì? · Ma túy trá hình · Tác hại · Pháp luật · Kĩ năng 3T · Trách nhiệm, mỗi bài kèm trò chơi tương ứng.
- **Đấu trí Quiz:** chơi theo nhóm hoặc cá nhân, có bảng thống kê trực tiếp.
- **Tình huống và trò chơi:** Lá chắn 4 KHÔNG, Thám tử hoàn cảnh, Ngộ nhận, Cán cân pháp luật.
- **Hành động của em:** Tìm trợ giúp (111 · 113 · 115), Thẻ 3T gửi gia đình, Lời hứa 3T.
- **Hỏi AI:** trợ lý chỉ trả lời bằng nội dung có sẵn trong ứng dụng. Câu hỏi không gửi đi đâu cả.
- **Dành cho giáo viên:** bảng theo dõi, nhiệt kế tin cậy, phiếu in.

## Cách chạy

Ứng dụng là **một file `index.html`**, không cần máy chủ và không cần mạng. Tải file về rồi mở bằng trình duyệt như Chrome, Edge hoặc Firefox.

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub, nên chọn **Public**, ví dụ `phong-chong-ma-tuy`.
2. Tải các file trong thư mục này lên repository (**Add file → Upload files**), hoặc dùng git.
3. Vào **Settings → Pages**, phần **Build and deployment** chọn:
   - **Source:** Deploy from a branch
   - **Branch:** `main`, thư mục `/ (root)`
   - Bấm **Save**.
4. Sau vài phút, ứng dụng chạy tại địa chỉ:
   `https://<tên-tài-khoản>.github.io/phong-chong-ma-tuy/`

## Cấu trúc thư mục

| File | Mô tả |
| --- | --- |
| `index.html` | Toàn bộ ứng dụng: giao diện, mã lệnh và nội dung bài học trong một file |
| `README.md` | Tài liệu này |
| `.gitignore` | Bỏ qua các file rác của Windows và công cụ phát triển |
| `.nojekyll` | Báo GitHub Pages phục vụ file nguyên gốc, không xử lý qua Jekyll |

## Lưu ý

- Ứng dụng **không lưu tên học sinh** và không gửi dữ liệu đi. Kết quả chơi (nếu có) chỉ nằm trong trình duyệt của từng máy.
- Ảnh minh họa do giáo viên tạo bằng AI. Nhạc nền được tạo bằng Web Audio ngay trên trình duyệt.
- Nội dung đã được giáo viên duyệt trước khi đưa vào sử dụng.
