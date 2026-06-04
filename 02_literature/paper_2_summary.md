# Paper 17: Machine Learning-Enhanced Requirements Engineering: A Systematic Literature Review (2024)

## Thông tin bài báo

* **Tác giả:** A. G. Núñez và cộng sự
* **Năm:** 2024
* **Loại bài:** Systematic Literature Review (SLR)
* **Lĩnh vực:** Requirements Engineering, Machine Learning, NLP

## Mục tiêu nghiên cứu

Bài báo khảo sát việc ứng dụng Machine Learning (ML) và Natural Language Processing (NLP) trong Requirements Engineering (RE). Mục tiêu là tìm hiểu cách AI có thể hỗ trợ tự động hóa các hoạt động liên quan đến requirement trong phát triển phần mềm.

## Phạm vi nghiên cứu

Tác giả thu thập 1.219 bài báo từ các cơ sở dữ liệu học thuật lớn như IEEE, ACM, Scopus, Web of Science và ProQuest. Sau quá trình sàng lọc, 74 nghiên cứu chất lượng cao trong giai đoạn 2012–06/2023 được lựa chọn để phân tích.

## Nội dung chính

### Requirement Classification

Đây là hướng nghiên cứu phổ biến nhất. Machine Learning được sử dụng để phân loại:

* Functional Requirements (FR)
* Non-Functional Requirements (NFR)
* Security Requirements
* Performance Requirements

Các thuật toán phổ biến bao gồm SVM, Random Forest, Naive Bayes, Deep Learning và BERT.

### Requirement Smell và Ambiguity Detection

Nhiều nghiên cứu tập trung phát hiện các requirement:

* Mơ hồ
* Thiếu thông tin
* Khó kiểm thử
* Chứa từ ngữ không rõ nghĩa

Ví dụ:

> The system should be fast.

Từ "fast" không có tiêu chí đo lường cụ thể nên requirement này được xem là mơ hồ.

### Requirement Validation

Machine Learning được sử dụng để:

* Kiểm tra chất lượng requirement
* Phát hiện lỗi
* Tìm sự mâu thuẫn
* Xác định requirement không thể kiểm thử

### Requirement Prioritization

AI hỗ trợ:

* Xếp hạng độ ưu tiên requirement
* Hỗ trợ quản lý backlog
* Phân tích phản hồi người dùng

## Vai trò của NLP

NLP là nền tảng của hầu hết nghiên cứu trong bài báo.

Các kỹ thuật thường được sử dụng:

* Tokenization
* POS Tagging
* Semantic Similarity
* Word Embedding
* Transformer
* BERT

## Kết quả chính

* Số lượng nghiên cứu tăng mạnh sau năm 2018.
* Transformer và BERT thường cho kết quả tốt hơn các mô hình ML truyền thống.
* Thiếu dataset requirement chuẩn hóa.
* Nhiều nghiên cứu chưa được kiểm chứng ở quy mô công nghiệp.

## Kết luận

Machine Learning và NLP đang đóng vai trò quan trọng trong Requirements Engineering, đặc biệt ở các bài toán phân loại requirement, phát hiện requirement mơ hồ và kiểm tra chất lượng requirement. Tuy nhiên lĩnh vực này vẫn cần thêm dữ liệu chuẩn và các nghiên cứu thực tế trong doanh nghiệp.


# Paper 16: Large Language Models (LLMs) for Requirements Engineering (RE): A Systematic Literature Review (2025)

## Thông tin bài báo

* **Tác giả:** Mohammad Amin Zadenoori và cộng sự
* **Năm:** 2025
* **Loại bài:** Systematic Literature Review (SLR)
* **Lĩnh vực:** Requirements Engineering, Large Language Models, Generative AI

## Mục tiêu nghiên cứu

Bài báo khảo sát việc ứng dụng Large Language Models (LLMs) trong Requirements Engineering. Các nghiên cứu được phân tích nhằm đánh giá khả năng của LLM trong việc hỗ trợ phân tích, kiểm tra và sinh requirement.

## Phạm vi nghiên cứu

Bài báo tổng hợp 74 nghiên cứu chính được công bố trong giai đoạn 2023–2024, thời điểm Generative AI phát triển mạnh với sự xuất hiện của ChatGPT và các mô hình GPT-based.

## Nội dung chính

### Requirement Elicitation

LLM có thể hỗ trợ sinh requirement từ:

* Mô tả của khách hàng
* User Story
* Tài liệu đặc tả ban đầu

### Requirement Classification

LLM được sử dụng để:

* Phân loại Functional Requirement và Non-Functional Requirement
* Phát hiện Security Requirement
* Đánh giá chất lượng requirement

Ưu điểm của LLM là có thể thực hiện tốt ngay cả khi không cần huấn luyện thêm nhiều dữ liệu.

### Requirement Validation và Defect Detection

LLM có thể phát hiện:

* Requirement mơ hồ
* Requirement thiếu thông tin
* Requirement không nhất quán
* Requirement khó kiểm thử

Ví dụ:

> The system should be fast.

LLM có thể nhận diện rằng requirement này thiếu tiêu chí cụ thể để đánh giá hiệu năng.

### Use Case Generation và Test Case Generation

Đây là một trong những hướng nghiên cứu nổi bật nhất.

LLM có khả năng tự động sinh:

* Use Case
* User Story
* Acceptance Criteria
* Test Scenario
* Test Case

## Prompt Engineering

Bài báo nhấn mạnh tầm quan trọng của Prompt Engineering.

### Zero-shot Prompting

Mô hình thực hiện tác vụ mà không cần ví dụ minh họa.

### Few-shot Prompting

Cung cấp một số ví dụ trước khi yêu cầu mô hình dự đoán. Phương pháp này thường cho kết quả tốt hơn zero-shot.

### Chain-of-Thought Prompting

Yêu cầu mô hình giải thích từng bước suy luận trước khi đưa ra kết quả.

## Kết quả chính

* LLM cho hiệu quả cao trong nhiều tác vụ Requirements Engineering.
* Few-shot Prompting thường hoạt động tốt hơn Zero-shot Prompting.
* Kết quả phụ thuộc mạnh vào prompt và ngữ cảnh.
* Chưa có benchmark chuẩn để so sánh giữa các nghiên cứu.
* Con người vẫn cần tham gia vào quá trình review và validation requirement.

## Kết luận

Large Language Models đang mở ra hướng phát triển mới cho Requirements Engineering. Ngoài việc phân loại và kiểm tra requirement, LLM còn có khả năng sinh use case, test case và hỗ trợ analyst trong nhiều công việc khác. Tuy nhiên, LLM vẫn chưa đủ ổn định để thay thế hoàn toàn chuyên gia phân tích yêu cầu.

