# XÂY DỰNG CHUỖI PROMPT VIẾT BÀI PR SẢN PHẨM CÔNG NGHỆ

## 1. PROMPT 1: NGHIÊN CỨU KHÁCH HÀNG MỤC TIÊU

**Vai trò:** Bạn là chuyên gia nghiên cứu thị trường.

**Nhiệm vụ:** Nghiên cứu khách hàng mục tiêu của sản phẩm AI Chatbot dành cho doanh nghiệp.

**Yêu cầu:**
- Xác định nhóm khách hàng mục tiêu.
- Phân tích nhu cầu và hành vi khách hàng.
- Liệt kê ít nhất 5 nỗi đau (Pain Points).
- Đề xuất giải pháp tương ứng của AI Chatbot.

**Đầu ra:** Lưu kết quả theo cấu trúc CONTEXT_1 gồm:
- TARGET_CUSTOMERS
- CUSTOMER_NEEDS
- PAIN_POINTS
- SOLUTIONS

## 2. PROMPT 2: XÂY DỰNG DÀN Ý BÀI PR

**Vai trò:** Bạn là chuyên gia Content Marketing và SEO.

**Đầu vào:** Sử dụng toàn bộ CONTEXT_1 từ Prompt 1.

**Nhiệm vụ:** Xây dựng dàn ý chi tiết cho bài PR giới thiệu AI Chatbot.

**Yêu cầu:**
- Tạo tiêu đề hấp dẫn (Headline).
- Viết ý tưởng đoạn mở đầu (Lead).
- Xây dựng các tiêu đề H2, H3 logic.
- Làm rõ tính năng và lợi ích sản phẩm.
- Đề xuất từ khóa SEO chính và phụ.
- Xây dựng lời kêu gọi hành động (CTA).

**Đầu ra:** Lưu kết quả theo cấu trúc CONTEXT_2 gồm:
- HEADLINE
- LEAD
- KEYWORDS
- OUTLINE_H2_H3
- CTA

## 3. PROMPT 3: VIẾT BÀI PR HOÀN CHỈNH

**Vai trò:** Bạn là chuyên gia viết bài PR và SEO.

**Đầu vào:** Sử dụng CONTEXT_1 và CONTEXT_2 từ hai bước trước.

**Nhiệm vụ:** Viết bài PR chuyên sâu giới thiệu giải pháp AI Chatbot cho doanh nghiệp.

**Yêu cầu:**
- Độ dài 1000–1500 từ.
- Triển khai đầy đủ dàn ý H2, H3.
- Tối ưu từ khóa SEO tự nhiên.
- Nội dung chuyên nghiệp, tin cậy, không lặp ý.
- Giải quyết đúng các Pain Points của khách hàng.
- Có CTA rõ ràng ở cuối bài.
- Không tự ý thêm tính năng hoặc số liệu chưa được cung cấp.

**Đầu ra:** Bài PR hoàn chỉnh bằng Markdown.

## 4. XỬ LÝ KHI AI BỊ NGẮT QUÃNG (MAX TOKEN)

Sử dụng câu lệnh:

"Tiếp tục viết chính xác từ vị trí bị dừng. Nối tiếp ngay sau câu cuối cùng đã hoàn thành, không lặp lại nội dung cũ. Giữ nguyên giọng văn chuyên nghiệp, tin cậy, cấu trúc H2/H3, từ khóa SEO và toàn bộ CONTEXT_1, CONTEXT_2. Đảm bảo đoạn văn mới liên kết tự nhiên với đoạn trước và hoàn thành đủ 1000–1500 từ."

## 5. SƠ ĐỒ QUY TRÌNH PROMPT CHAINING

PROMPT 1: NGHIÊN CỨU KHÁCH HÀNG
↓
CONTEXT_1: Đối tượng + Nhu cầu + Pain Points
↓
PROMPT 2: XÂY DỰNG DÀN Ý SEO
↓
CONTEXT_2: Headline + Lead + H2/H3 + Keywords + CTA
↓
PROMPT 3: VIẾT BÀI PR
↓
BÀI PR HOÀN CHỈNH (1000–1500 TỪ)
↓
KIỂM TRA SEO VÀ TÍNH NHẤT QUÁN

## 6. NGUYÊN TẮC KIỂM SOÁT

- Không gộp 3 prompt thành một.
- Output của bước trước là đầu vào bắt buộc của bước sau.
- Giữ nguyên giọng văn chuyên nghiệp, tin cậy.
- Không tự ý thay đổi dữ liệu và dàn ý.
- Khi bị ngắt, phải nối đúng câu đang viết, không lặp nội dung.
- Kiểm tra độ dài, từ khóa SEO và cấu trúc trước khi hoàn thành.
