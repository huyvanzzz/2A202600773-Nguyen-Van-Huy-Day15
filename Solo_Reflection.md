# BỘ CÂU HỎI 1 – NHÌN LẠI CÁ NHÂN (SOLO)

* **Họ tên:** Nguyễn Văn Huy  
* **Mã học viên:** 2A202600773  

---

### 1. Trong 15 ngày, mình thực sự làm được điều gì mà trước đó chưa làm được?
15 ngày trước, mình chưa nắm rõ cách thức hoạt động thực tế của LLM hay cách kết nối chúng vào hệ thống. Đến hôm nay, mình đã tự tay thiết lập và triển khai (deploy) thành công ứng dụng **RAG tra cứu Luật** và **Chatbot Y tế**, nắm vững cơ chế Tool Calling, xây dựng Multi-agent phối hợp và tích hợp Guardrails bảo vệ an toàn cho sản phẩm.

### 2. Khoảnh khắc “à, ra là vậy” rõ nhất là khi nào – một hiểu lầm được sửa lại?
Đó là lúc mình nhận ra RAG không chỉ đơn giản là đọc dữ liệu thô và ném vào prompt của LLM. Mình đã hiểu ra tầm quan trọng của việc chunking dữ liệu, embedding tối ưu và đặc biệt là cơ chế **groundedness** (đối chiếu nguồn gốc dữ liệu) để ngăn chặn ảo tưởng (hallucination) của mô hình.

### 3. Phần nào mình kẹt lâu nhất? Nhìn lại, gốc rễ thật sự là gì (kiến thức / công cụ / cách làm / quy trình)?
* Mình kẹt lâu nhất ở phần thiết kế giao diện UI cho sản phẩm và phần theo dõi luồng hoạt động (logs/trace) của Agent khi hệ thống bị chậm hoặc trả về kết quả lỗi.  
* **Gốc rễ thực sự:** Do nền tảng Frontend/UI của mình còn mỏng và mình chưa quen sử dụng các công cụ quan sát chuyên biệt (như Langfuse/LangSmith) mà chủ yếu debug thủ công bằng console logs.

### 4. Sản phẩm hay artifact nào mình tự hào nhất, và vì sao?
Ứng dụng **RAG Luật**. Hệ thống văn bản luật pháp có cấu trúc quan hệ rất phức tạp. Việc ứng dụng trả về chính xác điều khoản kèm nguồn trích dẫn rõ ràng làm mình cảm thấy sản phẩm này thực sự có giá trị thực tiễn.

### 5. Loại công việc nào khiến mình muốn làm tiếp? Loại nào khiến mình mệt hoặc muốn né?
* **Muốn làm tiếp:** Thiết kế hệ thống backend, tối ưu hóa các giải thuật prompt, thiết kế agent thông minh và nghiên cứu các kỹ thuật mới (AI Assistant Research).  
* **Muốn né:** Thiết kế giao diện CSS từ đầu hoặc căn chỉnh bố cục giao diện phức tạp.

### 6. Nếu thành thật, kỹ năng nào của mình còn mỏng?
Kỹ năng xử lý Latent UX (trải nghiệm người dùng khi hệ thống AI có độ trễ) và kỹ năng thiết lập **Structured Logging & Tracing** chuyên nghiệp cho Agent.

### 7. Câu hỏi nào về AI mình vẫn chưa trả lời được và muốn đào sâu ở Phase 2?
Làm thế nào để đánh giá và benchmark tự động độ chính xác của AI Agent trong môi trường production thực tế với hàng nghìn request mỗi ngày bằng RAGAS hay các công cụ tương đương mà tối ưu chi phí nhất? Làm sao để tối ưu chi phí token (chiếm 40-60% chi phí vận hành) bằng Model Routing và Semantic Caching hiệu quả?
