# GHI CHÉP VỀ DOCKER
## CÁC THUẬT NGỮ
* IMAGE: là khuôn mẫu, lớp chứa các file cần thiết để tạo nên một container, chứa những tài nguyên có sẵn, không được tiếp cận vào CPU, RAM, Storage
* Container: Tồn tại trên host với một địa chỉ IP, được deploy, run và xóa bỏ thông qua remote client
* Docker engine: tạo, run container. Chạy lệnh trong chế độ daemon (chạy ngầm), nằm trên layer OS và dưới các ứng dụng và thư viện
* Docker daemon: Tiến trình chạy ngầm quản lý các container
* Docker client: Kiểm soát hầu hết các workflow của docker, giao tiếp với các máy chủ docker thông qua daemon
* Docker Hub: chứa các component Docker. Cho phép lưu, sử dụng, tìm kiếm các image. Thực hiện các vai trò ship trong "Build, Ship, Deploy"
### Docker có kiến trúc client-server và có 3 thành phần chính: Docker client, Docker Host và Docker Registry(Hub)

 
