# GHI CHÉP VỀ DOCKER
## CÁC THUẬT NGỮ
* IMAGE: là khuôn mẫu, lớp chứa các file cần thiết để tạo nên một container, chứa những tài nguyên có sẵn, không được tiếp cận vào CPU, RAM, Storage
* Container: Tồn tại trên host với một địa chỉ IP, được deploy, run và xóa bỏ thông qua remote client
* Docker engine: tạo, run container. Chạy lệnh trong chế độ daemon (chạy ngầm), nằm trên layer OS và dưới các ứng dụng và thư viện
* Docker daemon: Tiến trình chạy ngầm quản lý các container
* Docker client: Kiểm soát hầu hết các workflow của docker, giao tiếp với các máy chủ docker thông qua daemon
* Docker Hub: chứa các component Docker. Cho phép lưu, sử dụng, tìm kiếm các image. Thực hiện các vai trò ship trong "Build, Ship, Deploy"
### Docker có kiến trúc client-server và có 3 thành phần chính: Docker client, Docker Host và Docker Registry(Hub)
## CÁC TIẾN TRÌNH TRONG CONTAINER
* DOCKER RUN
  * Docker container có tiền trình chính, khi tiến trình này thoát thì container cũng sẽ dừng. Container được đặt tên và nếu không được đặt tên nó sẽ tự sinh ra cái tên ngẫu nhiên
* lệnh docker run:
  * -ti: truyền vào tiến trình chính
  * --rm: chạy container sẽ tự động xóa khi container này dừng
* docker run -d tạo container và cho nó chạy nền trong hệ thống
* docker attach  dùng để truy cấp vào một container đang chạy thông qua ID hoặc tên. Có thể truy cập vào cùng một contaniner từ nhiều nơi tại cùng một thời điểm
* docker exec: khởi tạo một process khác bên trong một container đã có, tiện cho việc debuy và quản lý database, không thể thêm port, volume
## Một số lện thông dụng trong docker container
* Docker create
  * Tạo ra một container với các config tương tự như docker run nhưng container này sẽ không chạy ngay từ đầu mà phải dùng lệnh docker start để khởi chạy container




 
