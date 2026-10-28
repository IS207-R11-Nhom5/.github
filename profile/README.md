# Thông tin nhóm

**Tên nhóm:** PHP Is Awesome  
**Môn học:** Phát triển ứng dụng Web — IS207.R11  
**Trường:** Trường Đại học Công nghệ Thông tin, ĐHQG-HCM  
**Giảng viên hướng dẫn:** ThS. Tạ Việt Phương

Đây là trang tổng quan của nhóm cho **Mini Project uitplans** và **đồ án chính TravelGo**. Các repository lưu mã nguồn; tài liệu sản phẩm, phân công và minh chứng được liên kết bên dưới.

## Danh sách thành viên

| STT | MSSV | Họ và tên | Phần việc chính trong Mini Project | GitHub |
| :---: | --- | --- | --- | --- |
| 1 | 24520442 | Phạm Tuấn Hải | Kiến trúc, UI, tích hợp Google/cloud và triển khai | [haiphamt](https://github.com/haiphamt) |
| 2 | 24520013 | Nguyễn Thị Quỳnh Hân | Explore, Path detail và nội dung hướng học | [QuynhHan486](https://github.com/QuynhHan486) |
| 3 | 24520306 | Phạm Công Định | My roadmap, planner và QA | [Dingglebell](https://github.com/Dingglebell) |
| 4 | 24520486 | Chung Minh Hiếu | My plan, tiến độ và tuần học | [chungminhhieu2311-collab](https://github.com/chungminhhieu2311-collab) |
| 5 | 24520495 | Lê Nguyễn Hữu Hiếu | Profile, nhịp học và nội dung hướng học | [lihanhutiu](https://github.com/lihanhutiu) |
| 6 | 24520708 | Triệu Quang Huy | Lưu trữ, sao lưu, nhập dữ liệu, migration và QA | [1can5ez](https://github.com/1can5ez) |

Phân công chi tiết và trách nhiệm kiểm thử theo module được ghi tại [Project Hub](https://github.com/haiphamt/is207-project-hub#phân-công-và-kiểm-thử-theo-module). Mức “Nỗ lực 100%” trong slides giữ theo khai báo của nhóm, kèm sản phẩm và minh chứng tương ứng.

# Quy trình làm việc nhóm

## Các liên kết truy cập nhanh

| Nội dung | Liên kết |
| --- | --- |
| Tài liệu và minh chứng chung | [Project Hub](https://github.com/haiphamt/is207-project-hub) |
| Mini Project | [Mã nguồn uitplans](https://github.com/haiphamt/uitplans) · [Website](https://uitplans.netlify.app/) |
| Product Brief của Mini Project | [Notion uitplans](https://app.notion.com/p/3ee533490aed81f7ab5eee549942f2c3) |
| Đồ án chính | [Mã nguồn TravelGo](https://github.com/haiphamt/TravelGo) · [Figma](https://www.figma.com/design/QYzdMjHKiquZjUAvHUdXhq/TravelGo?node-id=43-2) |
| Sơ đồ uitplans | [Activity, Sequence và Flowchart](https://uitplans.netlify.app/events.html) |
| Video kiểm soát AI và so sánh công cụ AI | [Google Drive](https://drive.google.com/drive/folders/1nuZU3G-NEcOPM4UF4fP5bB-GgAus5R40?usp=drive_link) |

Nhóm trao đổi nhanh qua Zalo, quản lý mã nguồn bằng GitHub và tổng hợp tài liệu Mini Project trên Notion. Antigravity là công cụ AI nhóm sử dụng chủ yếu; AI Development Log ghi đúng công cụ trong từng tương tác thực tế.

## Quy ước phối hợp đề xuất

Các quy ước dưới đây là bản đề xuất để nhóm thống nhất áp dụng; lịch họp và hạn công việc được chốt riêng theo từng giai đoạn.

- **Minh bạch công việc:** mỗi việc có dự án, nội dung, người thực hiện, đầu ra, người rà soát và hạn hoàn thành.
- **Cập nhật tiến độ:** dùng các trạng thái Chưa bắt đầu → Đang làm → Chờ kiểm tra → Hoàn thành. Khi gặp vướng mắc hoặc có nguy cơ trễ, báo sớm để nhóm hỗ trợ.
- **Review trước khi gộp:** tạo nhánh theo việc, gửi Pull Request kèm mô tả và kết quả kiểm tra. Người rà soát đối chiếu yêu cầu và chạy luồng liên quan trước khi gộp vào nhánh chính.
- **Có minh chứng hoàn thành:** dùng commit/PR, ảnh, test case hoặc tài liệu để ghi nhận kết quả. Phân biệt phần đã chạy thật với phần mô phỏng bằng fixture.
- **Bảo vệ cấu hình:** không đưa mật khẩu, token, OAuth secret hoặc service role key vào repository. Chỉ công khai cấu hình mẫu phù hợp.
- **Kiểm soát AI:** thành viên giải thích được đầu ra đưa vào sản phẩm, ghi các tương tác có ý nghĩa vào AI Log và kiểm chứng lại bằng chạy thử, test hoặc review.

## Kiểm tra và triển khai

Repository uitplans hiện có GitHub Actions chạy các bước:

```sh
npm ci
npm run check
npm run check:features
npm run build
```

Sau build, nhóm kiểm tra các luồng liên quan trên desktop/mobile và bản online. Hướng dẫn cài đặt, cấu hình và triển khai nằm trong README của từng dự án.

# Các dự án

| Dự án | Nội dung | Trạng thái được ghi nhận |
| --- | --- | --- |
| **uitplans — Mini Project** | Khám phá hướng học CNTT, chọn kỹ năng/nguồn học, lập kế hoạch tuần và theo dõi tiến độ; Guest lưu cục bộ, Google lưu qua Supabase | Đã có website online và đã demo trực tiếp. Product Brief, AI Log, test case và minh chứng nằm trên Notion. Hai video AI đang chờ bổ sung vào Drive. |
| **TravelGo — Đồ án chính** | Khám phá địa điểm và lập lịch trình du lịch; phạm vi ban đầu TP.HCM, Đà Lạt và Góc Địa Phương tại TP.HCM | Đang phát triển. Phạm vi và tiến độ mới nhất được cập nhật trong repository TravelGo. |

**Công nghệ uitplans:** React, TypeScript, Vite, CSS, IndexedDB, Supabase Auth/PostgreSQL và Netlify.  
**Công nghệ đã chốt của TravelGo:** Angular/TypeScript, PHP/Laravel REST API, MySQL, Laravel Sanctum và Leaflet/OpenStreetMap.

# Tài liệu và minh chứng

- [Product Brief uitplans: thành viên, bài toán, phạm vi, user stories, kiến trúc, UI/UX, AI Log và test case](https://app.notion.com/p/3ee533490aed81f7ab5eee549942f2c3).
- [Slides Mini Project đã nộp](https://github.com/haiphamt/is207-project-hub/blob/main/minh-chung/uitplans/Slides_Mini_Project.pptx).
- [Báo cáo kiểm thử gốc của Công Định](https://github.com/haiphamt/is207-project-hub/blob/main/minh-chung/uitplans/Kiem_thu_Cong_Dinh.docx).
- [Đối chiếu lỗi và kiểm thử My Plan ngày 11/10/2026](https://github.com/haiphamt/is207-project-hub/blob/main/minh-chung/uitplans/QA_bo_sung_20261011.md).
- [Kiến trúc và vòng đời dữ liệu uitplans](https://github.com/haiphamt/uitplans/blob/main/docs/architecture.md).
- [Hướng dẫn triển khai uitplans](https://github.com/haiphamt/uitplans/blob/main/docs/deployment.md).

Cập nhật trang tổng quan ngày **28/10/2026**. Các minh chứng kiểm thử giữ ngày thực hiện riêng.
