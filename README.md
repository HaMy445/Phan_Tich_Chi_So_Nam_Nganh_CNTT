📄 Tóm tắt (Abstract)
Ngành Công nghệ Thông tin (CNTT) tiếp tục là động lực tăng trưởng kinh tế quan trọng tại Việt Nam, được thúc đẩy bởi chiến lược chuyển đổi số quốc gia. Bài báo này trình bày một phân tích định lượng toàn diện về các chỉ số phát triển của ngành CNTT trong 5 năm qua (2020-2024). Chúng tôi tập trung vào ba lĩnh vực chính: (1) quy mô và chất lượng đầu vào của đào tạo, (2) tỷ lệ tốt nghiệp, chất lượng đầu ra và khả năng có việc làm, và (3) nhu cầu nhân lực thực tế từ thị trường lao động. Bằng cách tổng hợp và phân tích dữ liệu từ báo cáo ba công khai của các trường đại học hàng đầu và dữ liệu tin đăng từ các nền tảng tuyển dụng lớn, chúng tôi xác định các xu hướng chính, các điểm nghẽn trong đào tạo và sự mất cân đối nghiêm trọng giữa cung và cầu nhân lực. Kết quả cho thấy mặc dù số lượng tuyển sinh tăng đều, tỷ lệ sinh viên tốt nghiệp có kỹ năng chuyên môn cao vẫn chưa đáp ứng đủ nhu cầu cấp thiết của doanh nghiệp, đặc biệt trong các lĩnh vực mới nổi như Trí tuệ Nhân tạo (AI), Khoa học Dữ liệu (Data Science) và Điện toán Đám mây (Cloud Computing).

💡 Các phát hiện chính (Key Findings)
Nghiên cứu chỉ ra một số xu hướng và thách thức chính:

📈 Tăng trưởng nóng về quy mô: Quy mô tuyển sinh ngành CNTT tại các trường hàng đầu tăng liên tục (tổng cộng ~47.7% trong 5 năm), thu hút nhóm sinh viên ưu tú với điểm chuẩn rất cao.

⚠️ Thách thức về chất lượng đầu ra: Chỉ khoảng 65% sinh viên tốt nghiệp đúng hạn. 35% còn lại tốt nghiệp muộn, chuyển ngành hoặc bỏ học, cho thấy chương trình học rất nặng và có tính đào thải cao.

❗ Mất cân đối Cung-Cầu nghiêm trọng:

Thị trường bão hòa ở các vị trí Web/Mobile cơ bản.

Thị trường thiếu hụt trầm trọng nhân lực có kỹ năng cao:

Kỹ sư Dữ liệu (Data Engineer) (Tỷ lệ thiếu hụt ước tính 4.2:1)

Kỹ sư AI/ML (AI/ML Engineer) (Tỷ lệ thiếu hụt ước tính 6:1)

Kỹ sư DevOps/Cloud (Tỷ lệ thiếu hụt ước tính 5:1)

☁️ Kỹ năng bắt buộc: Các kỹ năng về Cloud (AWS, Azure) và DevOps (CI/CD, Kubernetes) đã trở thành yêu cầu bắt buộc trong hơn 60% tin tuyển dụng, ngay cả với các vị trí Lập trình viên Web/Mobile.

🚀 Cách biên dịch (How to Compile)
1. Sử dụng Overleaf (Khuyến nghị)
Cách đơn giản nhất là sử dụng một trình biên dịch LaTeX trực tuyến như Overleaf:

Tạo một dự án mới trên Overleaf.

Tải (upload) toàn bộ các tệp trong kho chứa này (main.tex, IEEEtran.cls, và các hình ảnh) lên dự án.

Nhấn "Recompile" (Biên dịch lại).

2. Biên dịch trên máy tính cá nhân (Local Compilation)
Nếu bạn muốn biên dịch trên máy tính cá nhân:

Cài đặt một bản phân phối LaTeX (ví dụ: TeX Live hoặc MiKTeX).

Đảm bảo tệp IEEEtran.cls (lớp tài liệu của IEEE) nằm cùng thư mục với main.tex.

Mở Terminal hoặc Command Prompt, điều hướng đến thư mục dự án và chạy lệnh sau:

Bash

pdflatex main.tex
Bạn có thể cần chạy lệnh trên hai lần để đảm bảo tất cả các tham chiếu chéo (cross-references) như Bảng \ref{...} và Hình \ref{...} được cập nhật chính xác.

📁 Nội dung Kho chứa (Repository Contents)
main.tex: Tệp mã nguồn LaTeX chính của bài báo.

main.pdf: (Tùy chọn) Tệp PDF kết quả đã được biên dịch.

IEEEtran.cls: Tệp định dạng (class) bắt buộc của IEEE cho các bài báo hội thảo.

/images/ (hoặc các tệp .jpg/.png): Thư mục chứa các hình ảnh và biểu đồ được sử dụng trong bài báo.

🧑‍💻 Tác giả (Authors)
Đạt Nguyễn

Trường Đại học Đại Nam

Email: nguyendatablhp@gmail.com

Hà My Triệu

Trường Đại học Đại Nam

Email: hamy572002@gmail.com

📜 Trích dẫn (Citation)
Nếu bạn thấy công trình này hữu ích, vui lòng trích dẫn bài báo của chúng tôi. Dưới đây là mẫu BibTeX (bạn có thể điều chỉnh booktitle và year cho phù hợp):

Đoạn mã

@conference{NguyenTrieu2024CNTT,
    author    = {Nguyễn, Đạt and Triệu, Hà My},
    title     = {Phân tích các Chỉ số Tăng trưởng Cốt lõi và Thực trạng Nhân lực Ngành Công nghệ Thông tin tại Việt Nam},
    booktitle = {Kỷ yếu Hội thảo [TÊN HỘI THẢO] (hoặc Tên Tạp chí)},
    year      = {2024},
    pages     = {[số trang]},
    publisher = {[Nhà xuất bản]},
    address   = {Hà Nội, Việt Nam}
}
🤝 Đóng góp (Contributing)
Chúng tôi hoan nghênh mọi ý kiến đóng góp, báo cáo lỗi (issues), hoặc đề xuất cải tiến (pull requests) để làm cho nghiên cứu này trở nên hoàn thiện hơn.

📝 Giấy phép (License)
Dự án này được cấp phép theo Giấy phép [TÊN GIẤY PHÉP] - xem tệp LICENSE.md để biết chi tiết. (Ví dụ: MIT, Apache 2.0, hoặc CC BY-SA 4.0 cho các công trình học thuật).
