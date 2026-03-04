# Bách khoa toàn thư RAG (Retrieval-Augmented Generation)

## Mục tiêu bộ tài liệu
Bộ tài liệu này được thiết kế để làm **nguồn tri thức chuẩn hóa** cho hệ thống RAG, giúp:
- Đồng nhất định nghĩa, thuật ngữ và thực hành tốt.
- Hỗ trợ truy hồi chính xác khi người dùng đặt câu hỏi kỹ thuật.
- Dễ chunking, embedding và trích dẫn nguồn trong câu trả lời.

## Cấu trúc thư mục theo lĩnh vực kiến thức

### 1) Nền tảng
- `nen-tang/`: Kiến thức cốt lõi về kiến trúc và luồng RAG.
  - [01-kien-truc-rag.md](./nen-tang/01-kien-truc-rag.md)

### 2) Dữ liệu & chỉ mục
- `du-lieu/`: Chuẩn hóa dữ liệu đầu vào, chunking, embedding và index.
  - [02-du-lieu-va-chia-nho.md](./du-lieu/02-du-lieu-va-chia-nho.md)
  - [03-embedding-va-index.md](./du-lieu/03-embedding-va-index.md)

### 3) Retrieval & Generation
- `retrieval-generation/`: Chiến lược truy hồi, reranking và sinh câu trả lời có grounding.
  - [04-chien-luoc-retrieval.md](./retrieval-generation/04-chien-luoc-retrieval.md)
  - [05-sinh-cau-tra-loi.md](./retrieval-generation/05-sinh-cau-tra-loi.md)

### 4) Đánh giá
- `danh-gia/`: Đánh giá retrieval, generation và end-to-end RAG.
  - [06-danh-gia-rag.md](./danh-gia/06-danh-gia-rag.md)

### 5) Vận hành & bảo mật
- `van-hanh-bao-mat/`: Vận hành production, giám sát, tối ưu và tuân thủ bảo mật.
  - [07-van-hanh-va-giam-sat.md](./van-hanh-bao-mat/07-van-hanh-va-giam-sat.md)
  - [08-bao-mat-va-tuan-thu.md](./van-hanh-bao-mat/08-bao-mat-va-tuan-thu.md)

### 6) Kiến trúc mẫu & xử lý sự cố
- `kien-truc-su-co/`: Mẫu thiết kế hệ thống và playbook sự cố.
  - [09-mau-thiet-ke-he-thong.md](./kien-truc-su-co/09-mau-thiet-ke-he-thong.md)
  - [10-playbook-su-co.md](./kien-truc-su-co/10-playbook-su-co.md)

### 7) Tối ưu truy vấn
- `truy-van-toi-uu/`: Nhóm tài liệu nâng cao chất lượng retrieval trước bước generation.
  - [11-query-transformation.md](./truy-van-toi-uu/11-query-transformation.md)
  - [12-hybrid-search-va-reranking.md](./truy-van-toi-uu/12-hybrid-search-va-reranking.md)

### 8) Use cases triển khai
- `use-cases/`: Nhóm tài liệu theo bối cảnh ứng dụng thực tế.
  - [13-rag-cho-tai-lieu-noi-bo.md](./use-cases/13-rag-cho-tai-lieu-noi-bo.md)

## Gom nhóm tài liệu theo mục tiêu sử dụng
Ngoài việc chia theo thư mục, có thể “ôm nhóm” tài liệu theo hành trình triển khai để dễ tra cứu:

- **Nhóm khởi tạo hệ thống**: 01, 02, 03.
- **Nhóm nâng chất lượng trả lời**: 04, 05, 11, 12.
- **Nhóm đo lường và vận hành**: 06, 07, 08, 10.
- **Nhóm thiết kế và ứng dụng thực tế**: 09, 13.

## Quy ước biên soạn cho RAG
1. Mỗi mục nên có tiêu đề rõ ràng, tập trung một chủ đề.
2. Ưu tiên đoạn văn ngắn + danh sách gạch đầu dòng để dễ chunk.
3. Tối ưu cho truy hồi: lặp lại từ khóa quan trọng có chủ đích.
4. Tránh nội dung mơ hồ, luôn nêu điều kiện áp dụng và đánh đổi.
5. Với khuyến nghị kỹ thuật, ghi rõ “khi nào nên dùng / không nên dùng”.

## Từ khóa cốt lõi
`RAG`, `retrieval`, `embedding`, `vector database`, `reranker`, `grounding`, `hallucination`, `evaluation`, `latency`, `cost optimization`, `security`, `PII`.
