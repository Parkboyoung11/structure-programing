# Structured programming in software project
# Lập trình cấu trúc trong dự án phần mềm  
## Nội dung đưọc đề cập  
* Tổng quan
* Cấu trúc của một chương trình
* Tách mối quan tâm

## Mục tiêu
* Sau bài học này, sinh viên có thể:  
	* Nhắc lại được những thuật ngữ về lập trình cấu trúc  
	* Tóm tắt đưọc mối quan hệ giữa chất lượng phần mềm, giải thuật và cấu trúc chương trình  
	* Xây dựng sự tách biệt giữa các mối quan tâm  
------
## Tổng quan  
1. Giới thiệu  
* Kĩ thuật phần mềm = các hoạt động giải quyết vấn đề  
	* Hiểu vấn đề  
	* Thiết kế giải thuật cho giải pháp  
	* Triển khai giải thuật trong chương trình máy tính  
* Giải thuật: Trình tự các bước từ đầu vào đến đầu ra để giải quyết vấn đề  
	* Sự chính xác: Cung cấp giải pháp đúng theo thông số kĩ thuật  
	* Tính hữu hạn: có sự kết thúc  
	* Tính chung: làm việc trong mọi trường hợp của vấn đề  
	* Tính hiệu quả: sử dụng ít tài nguyên (thời gian, bộ nhớ, băng thông, ...)  

-> Cần có một cách tiếp cận cấu trúc  

2. Lập trình cấu trúc  
### Lập trình cấu trúc là gì?  
* Ban đầu: lập trình mà không cần sư dụng câu lệnh GOTO  
* Sau đó: một phương pháp viết chương trình máy tính để giảm thiểu độ phức tạp của vấn đề  
	* phân tích từ trên xuống để giải quyết vấn đề  
	* module hóa cho cấu trúc chương trình và tổ chức  
	* mã có cấu trúc cho các module riêng lẻ  
* Hiện nay: một phương pháp thiết kế các thành phần phần mềm / yếu tố chương trình và mối quan hệ của chúng với:  
	* Giảm thiểu độ phức tạp  
	* Thích ứng với sự thay đổi (xác định các sửa đổi cho các chức năng bổ sung hoặc sửa lỗi)  
	* Cải thiện độ tin cậy và rõ ràng của các chương trình  
### Thiết kế có cấu trúc của phần mềm  
* Khái niệm hóa một vấn đề thành một số yếu tố được tổ chức tốt của giải pháp (chủ yếu dựa trên chiến lược “phân chia và chinh phục”)  
* Duy trì cấu trúc thống nhất ở các cấp độ khác nhau  
	* Giải quyết vấn đề: từ trên xuống, từ dưới lên, giữa chừng  
	* Tóm tắt và tổ chức chương trình: mô-đun, dịch vụ, chức năng, đối tượng, ...  
	* Yếu tố chương trình: mã có cấu trúc