OM1 - Hệ điều hành AI mô-đun cho Robot
​English | Tiếng Việt
​OM1 là một AI runtime (môi trường thực thi) mô-đun được thiết kế để phát triển robot dễ dàng như phát triển phần mềm hiện đại.
​🚀 BrainPack - Bắt đầu nhanh
​Chúng tôi đang chuẩn bị phát hành BOM (danh mục linh kiện) và hướng dẫn tự làm (DIY) cho phần cứng. Hiện tại, bạn có thể thiết lập phần mềm.
​1. Tải mã nguồn (Clone Repositories)
​git clone https://github.com/OpenMind/OM1.git
git clone https://github.com/OpenMind/unitree-sdk.git
git clone https://github.com/OpenMind/OM1-avatar.git
git clone https://github.com/OpenMind/OM1-video-processor.git
​2. Thiết lập Biến môi trường
​export OM_API_KEY="your_api_key_here"
​3. Chạy với Docker
​docker compose up -d --build
​🛠 Tính năng chính
​Modular AI Runtime: Hỗ trợ đa dạng robot (Humanoids, TurtleBot 4...).
​Đa mô hình: Tích hợp LLM và simulator hàng đầu.
​Hardware Plugins: Kết nối qua ROS2 hoặc Zenoh.
