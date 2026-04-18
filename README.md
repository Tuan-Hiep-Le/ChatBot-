# 🤖 RAG Chatbot: Hệ thống Hỗ trợ Sinh viên

Dự án triển khai một hệ thống Chatbot thông minh dựa trên kỹ thuật **Retrieval-Augmented Generation (RAG)**. Hệ thống giúp giải đáp thắc mắc của sinh viên bằng cách truy xuất thông tin từ kho tài liệu nội bộ trước khi tạo câu trả lời.

---

## Tính năng nổi bật

* **Truy xuất thông minh (RAG):** Tìm kiếm ngữ cảnh từ cơ sở dữ liệu tri thức, giúp câu trả lời chính xác và đáng tin cậy.
* **Tương tác trực tiếp:** Giao diện hội thoại thân thiện thông qua hàm `simple_test_loop`.
* **Xử lý ngôn ngữ tự nhiên:** Sử dụng kiến trúc Transformer hiện đại để hiểu sâu câu hỏi của sinh viên.

## Công nghệ sử dụng

Hệ thống được xây dựng trên nền tảng Python với các thư viện chuyên dụng:

* **Sentence-Transformers**: Tạo vector embeddings cho văn bản.
* **Transformers**: Triển khai các mô hình ngôn ngữ lớn (LLM).
* **PyTorch**: Framework tính toán hiệu năng cao.
* **Ipywidgets**: Hiển thị tiến trình xử lý dữ liệu trực quan.

## Cấu trúc Notebook

1.  **Khởi tạo**: Thiết lập môi trường và cấu hình phần cứng (CPU/GPU).
2.  **Tải mô hình**: Nạp các trọng số và bộ từ điển (vocab, bpe) từ Hugging Face.
3.  **Xử lý dữ liệu**: Đánh chỉ mục kho tri thức để phục vụ truy xuất.
4.  **Triển khai**: Vòng lặp ` Sinh viên` <-> ` Chatbot` để test thực tế.


