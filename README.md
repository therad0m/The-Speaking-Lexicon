# 📘 THE SPEAKING LEXICON - ADVANCED VOCABULARY & COLLOCATIONS

## Giới thiệu

Dự án này nhằm số hóa và biên soạn cuốn sách **"Từ vựng chuyên Anh dành cho kỹ năng nói"**, với mục tiêu:  

- Hệ thống từ vựng nâng cao cho kỹ năng **Speaking (IELTS/Academic English)**.  

- Giải thích chi tiết: **định nghĩa, ví dụ, collocation, synonym**.  

- Trình bày bằng **LaTeX** để tạo ra một cuốn sách học thuật chuẩn chỉnh.  

> Đây là project cá nhân được phát triển bởi **Nguyễn Thái Bảo**, đồng thời cũng là hành trình học tập và nghiên cứu.

---

## 📂 Cấu trúc thư mục

- glossaries: Chứa các glossary (từ vựng theo từng test/chủ đề) để build LaTeX.

- raw_vobs: File gốc (raw vocabulary list dạng 3 dòng: EN/EN def/VI def). Dùng để phục vụ cho việc tạo macro ExplainCard và VocabHighlights.

- Intro.tex: File LaTeX cho Chương Giới thiệu.

- Book_cover: Bìa thiết kế bằng Adobe Illustrator, import vào LaTeX.

- Preface.tex: File LaTeX cho Lời nói đầu.

- main.tex: File LaTeX chính, nơi include tất cả các chương/part.

- .gitignore: Bỏ qua các file phụ khi compile (.aux, .log, .toc…).

## 🛠️ Cách biên dịch

Yêu cầu: **TeX Live** hoặc **MikTeX** + `latexmk`.  

Chạy lệnh:

```bash
latexmk -pdf main.tex
