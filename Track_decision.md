# TRACK DECISION MEMO – Day 15

* **Họ tên:** Nguyễn Văn Huy  
* **Mã học viên:** 2A202600773  
* **Pathway:** C / D (Đưa AI vào tổ chức đang làm & Tự build sản phẩm)  

---

### ĐỊNH HƯỚNG
Vài job/role mình hướng tới + kỹ năng mỗi job đòi hỏi 

* **Job 1: AI Assistant Researcher / AI Agent Developer (Vị trí yêu thích nhất)**  
  * **Kỹ năng cần:** Nghiên cứu và thiết kế các cấu trúc Prompt nâng cao; thiết kế **Advanced Agent patterns** (ReAct, Planning, Memory); ứng dụng **GraphRAG & Knowledge Graphs** để xử lý dữ liệu phức tạp; thiết kế hệ thống **Production evaluation systems** để đo lường độ chính xác của Agent.
* **Job 2: AI Engineer / LLM Engineer (CP3 - AI Engineering)**  
  * **Kỹ năng cần:** Tích hợp và điều phối các mô hình qua LLM APIs; phát triển hệ thống RAG tối ưu; xây dựng multi-agent phối hợp thông qua MCP (Model Context Protocol); thiết lập cơ chế **Guardrails & Safety testing** để kiểm soát đầu ra của LLM.
* **Job 3: AI Solutions Developer (Phục vụ định hướng tự build sản phẩm)**  
  * **Kỹ năng cần:** Phát triển nhanh sản phẩm khả thi tối thiểu (MVP); thiết kế hệ thống **Hybrid AI** (sensitive data chạy on-premise qua **vLLM/Ollama** để đảm bảo an toàn dữ liệu/compliance, non-sensitive data chạy cloud API); tối ưu hóa chi phí hệ thống (**ROI Analysis**, FinOps).

---

### ĐỐI CHIẾU BẢN THÂN
Từ kết quả tích lũy ở Phase 1

* **Những việc mình đã làm được (liệt kê tự do, không giới hạn):**  
  * Hoàn thành 15 bài lab lập trình thực chiến về LLMs, Vector Stores và Agentic workflows.  
  * Xây dựng và deploy thành công ứng dụng tra cứu thông tin pháp lý bằng RAG cho ngành Luật (áp dụng grounded RAG để chống ảo tưởng).  
  * Xây dựng Chatbot tư vấn sức khỏe cho ngành Y tế (tích hợp prompt engineering an toàn).  
  * Có nền tảng vững về lập trình Backend và tích hợp mô hình AI qua API.  
  * Biết cách sử dụng Tool Calling, xây dựng Multi-agent và thiết lập Guardrails bảo vệ ứng dụng.  
  * Deploy ứng dụng lên nền tảng Cloud (Railway).  
* **Loại công việc cho mình năng lượng, muốn làm tiếp:**  
  * Lập trình backend cho hệ thống AI, thiết kế luồng xử lý thông tin và hành vi của AI Agents.  
  * Nghiên cứu các phương pháp Trợ lý AI mới (AI Assistant Research), tối ưu hóa RAG nâng cao và quản lý ngữ cảnh dài (long-term context).  

---

### KỸ NĂNG MÌNH ĐỊNH PHÁT TRIỂN TỚI
Danh sách kỹ năng dự định tập trung nâng cao sắp tới

1. **Advanced RAG & Agentic Workflows** (GraphRAG, Multi-agent phối hợp)  
2. **Structured Logging, Tracing & Monitoring** (Làm chủ Langfuse/LangSmith để kiểm soát lỗi Agent)  
3. **Cost Optimization & Scaling** (Model Routing, Semantic Caching, self-hosted LLM qua Ollama/vLLM)  

* **Gap lớn nhất + thứ mình sẽ build để cho thấy tiến bộ:**  
  * **Gap lớn nhất:** Khả năng debug, kiểm soát hoạt động của AI (chưa tốt phần tracing/logs) và kỹ năng thiết kế giao diện người dùng (UI) còn yếu khiến sản phẩm chưa hoàn thiện về mặt trải nghiệm đầu-cuối.  
  * **Thứ mình sẽ build:** Dự án **"AI Legal & Medical Research Assistant (Trợ lý Nghiên cứu Pháp lý/Y tế)"**. Ứng dụng này sẽ:  
    * Tích hợp cơ chế **Model Routing** (chia luồng GPT-4o-mini & GPT-4o) để tiết kiệm 40-60% chi phí token.  
    * Tích hợp **Structured Logging & Tracing** qua Langfuse để trace chi tiết các bước suy luận (reasoning chain) của AI.  
    * Sử dụng **Gradio/Streamlit** làm giao diện UI trực quan, mượt mà giúp người dùng dễ tương tác.  
    * Đánh giá chất lượng tự động bằng bộ chỉ số **RAGAS** (Faithfulness, Answer Relevance, Context Recall).  

---

### QUYẾT ĐỊNH TRACK
Lựa chọn hướng đi chuyên sâu cho Phase 2

* **Track chọn:** **T3 AI Engineering**  
  * **Vì:** Bổ trợ trực tiếp cho thế mạnh Backend và sở thích nghiên cứu ứng dụng AI của mình. Track này đi sâu vào lập trình AI thực chiến, xây dựng Agent và tối ưu RAG – những thành phần cốt lõi giúp mình tự build sản phẩm (Pathway D) cũng như mang giải pháp AI giá trị vào tổ chức (Pathway C).  
* **Track cân nhắc nhưng KHÔNG chọn + lý lẽ mạnh nhất cho nó:**  
  * *T1 AI Business & Product:* Rất quan trọng để làm PRD hay Go-to-market khi tự build sản phẩm, nhưng mình muốn làm chủ sâu phần kỹ thuật trước. Kỹ năng business có thể tự bồi dưỡng hoặc kết hợp với co-founder phù hợp sau.  
  * *T2 AI Infrastructure & Data:* Rất cần thiết cho LLMOps và deploy vLLM, nhưng mình đam mê tạo ra các trợ lý AI thông minh tương tác trực tiếp ở đầu cuối hơn là chỉ tập trung duy trì hạ tầng dữ liệu thô.  
* **Dấu hiệu sẽ khiến mình xem lại lựa chọn:**  
  * Khi nhận ra các lỗi của Agent/RAG không phải đến từ giải thuật hay prompt (T3) mà do chất lượng dữ liệu đầu vào hoặc hạ tầng dữ liệu bị thắt nút cổ chai (T2). Hoặc sản phẩm hoàn thiện tốt về kỹ thuật nhưng không thể áp dụng vào tổ chức do vướng mắc về bảo mật và compliance (T1/T2).  

---

### ĐỊNH HƯỚNG & CHUẨN BỊ
Các bước chuẩn bị hành động tiếp theo

* **Định hướng tiếp theo:** Hoàn thành bài tập lớn cuối Phase 1 với đầy đủ Deployed URL, Monitoring Dashboard và báo cáo đánh giá điểm RAGAS.  
* **Những thứ cần chuẩn bị:**  
  * Nghiên cứu sâu về các luật lệ bảo vệ dữ liệu (như nghị định PDPA Việt Nam) để lên phương án hybrid cloud/local hợp lý cho tổ chức.  
  * Thực hành setup local server với Ollama/vLLM trên máy cá nhân để sẵn sàng cho các bài toán chạy on-premise dữ liệu nhạy cảm.  
  * Tự thiết kế một Dashboard quản lý chi phí LLM API (đặc biệt là quản lý token) phục vụ cho sản phẩm indie.  
