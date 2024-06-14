# diffdrive_arduino

Nút này được thiết kế để cung cấp giao diện phần cứng ros2_control cho chương trình cơ sở chạy Arduino từ `ros_arduino_bridge`.
Nó được thiết kế để sử dụng với `diff_drive_controller` từ `ros2_control`.
Nó dự kiến ​​sẽ giao tiếp thông qua nối tiếp và có hai động cơ, mỗi động cơ có chức năng điều khiển vận tốc và phản hồi vị trí/vận tốc.

Vì một vài lý do mà bộ 2 encoder của tôi trả ra số tick/vòng là khác nhau mặc dù 2 motor có cùng thông số, cấp cùng điện áp.
Nên tôi sẽ tách 2 tham số encoder trái và encoder phải riêng biệt.



It is based on the diffbot example from [ros2_control demos](https://github.com/ros-controls/ros2_control_demos/tree/master/example_2).



