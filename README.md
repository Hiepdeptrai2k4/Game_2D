


*   **Custom Game Engine (Java 2D):** Xây dựng Game Loop chuẩn xác bằng Thread và Runnable (60 FPS), quản lý vòng lặp tính toán và render độc lập.
*   **Pathfinding & AI (Thuật toán A*):** Triển khai thuật toán tìm đường A-Star (A*) cho NPC và quái vật để truy đuổi người chơi (Aggro), tự động tránh vật cản.
*   **State Management & UI:** Quản lý linh hoạt các trạng thái game (Game State) như Title Screen, Playing, Inventory, Map, Options, Cutscenes, và Game Over với kiến trúc UI tùy chỉnh.
*   **Entity & Collision System:** Thiết kế hệ thống thực thể hướng đối tượng (Player, NPC, Monster, Projectile). Viết logic xử lý va chạm pixel-perfect cực kỳ chính xác.
*   **Advanced Combat System:** Lập trình cơ chế chiến đấu phức tạp: Đỡ đòn (Guard), Phản đòn (Parry tính bằng mili-giây), dội ngược (Knockback) và chém vỡ đạn (Cutting projectiles).
*   **Environment & Dynamic Lighting:** Tích hợp chu kỳ Ngày/Đêm (Day/Night cycle) và hệ thống ánh sáng động (Lantern) khi trời tối.
*   **Data & Save/Load:** Sử dụng Java File I/O để tạo hệ thống Save/Load game, kết hợp hệ thống Hòm đồ (Inventory) có thể cộng dồn (Stackable) vật phẩm.
*   **Performance Optimization:** Tối ưu hóa hiệu năng bằng cách chỉ render các thành phần nằm trong khung hình camera của người chơi (Camera rendering).

