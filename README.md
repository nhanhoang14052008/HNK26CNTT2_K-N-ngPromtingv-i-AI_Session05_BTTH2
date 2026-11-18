# QUY TRÌNH PROMPT CHAINING GỒM 3 BƯỚC

## PROMPT 1: NGHIÊN CỨU KHÁCH HÀNG MỤC TIÊU

**Vai trò:** Bạn là chuyên gia nghiên cứu thị trường và Marketing.

**Nhiệm vụ:** Nghiên cứu đối tượng khách hàng mục tiêu cho sản phẩm AI Chatbot dành cho doanh nghiệp.

**Yêu cầu:**
- Xác định nhóm khách hàng mục tiêu.
- Phân tích nhu cầu và mong muốn của khách hàng.
- Liệt kê các nỗi đau (Pain Points) mà khách hàng đang gặp phải.
- Đề xuất cách AI Chatbot giải quyết từng vấn đề.
- Xác định thông điệp Marketing phù hợp.

**Đầu ra:**

CONTEXT_1:
- TARGET_CUSTOMERS: Khách hàng mục tiêu.
- CUSTOMER_NEEDS: Nhu cầu khách hàng.
- PAIN_POINTS: Các nỗi đau.
- SOLUTIONS: Giải pháp của AI Chatbot.
- KEY_MESSAGES: Thông điệp chính.

Lưu kết quả vào CONTEXT_1 để chuyển sang Prompt 2.

---

## PROMPT 2: XÂY DỰNG DÀN Ý BÀI PR

**Vai trò:** Bạn là chuyên gia Content Marketing và SEO.

**Đầu vào:** Sử dụng toàn bộ CONTEXT_1 từ Prompt 1.

**Nhiệm vụ:**
- Xây dựng dàn ý chi tiết cho bài PR dài 1000–1500 từ.
- Đề xuất tiêu đề thu hút (Headline).
- Viết ý tưởng đoạn mở đầu (Lead).
- Xây dựng các tiêu đề H2, H3 logic.
- Sắp xếp nội dung theo trình tự: vấn đề → giải pháp → lợi ích → kêu gọi hành động.
- Đề xuất từ khóa SEO chính và từ khóa phụ.

**Đầu ra:**

CONTEXT_2:
- HEADLINE: Tiêu đề bài viết.
- LEAD: Ý tưởng mở đầu.
- SEO_KEYWORDS: Từ khóa SEO.
- OUTLINE: Dàn ý H2, H3.
- CTA: Lời kêu gọi hành động.

Lưu kết quả vào CONTEXT_2 để chuyển sang Prompt 3.

---

## PROMPT 3: TRIỂN KHAI BÀI PR VÀ TỐI ƯU SEO

**Vai trò:** Bạn là chuyên gia viết bài PR và tối ưu hóa SEO.

**Đầu vào bắt buộc:**
- CONTEXT_1: Kết quả nghiên cứu khách hàng từ Prompt 1.
- CONTEXT_2: Dàn ý chi tiết từ Prompt 2.

**Nhiệm vụ:**
- Viết bài PR hoàn chỉnh dài 1000–1500 từ.
- Triển khai đầy đủ các nội dung theo dàn ý H2, H3.
- Tập trung giải quyết Pain Points của khách hàng.
- Sử dụng từ khóa SEO chính và từ khóa phụ tự nhiên.
- Làm nổi bật lợi ích của AI Chatbot.
- Kết thúc bằng CTA rõ ràng.

**Yêu cầu:**
- Giữ giọng văn chuyên nghiệp, đáng tin cậy.
- Không bỏ sót nội dung trong dàn ý.
- Không lặp ý hoặc tự tạo thông tin chưa được xác minh.
- Đảm bảo bài viết có cấu trúc chuẩn SEO.

**Đầu ra:** Bài PR hoàn chỉnh ở định dạng Markdown.

---

## SƠ ĐỒ QUY TRÌNH

Prompt 1 → CONTEXT_1 → Prompt 2 → CONTEXT_2 → Prompt 3 → Bài PR hoàn chỉnh. thành.
