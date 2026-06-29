# Tạ Thùy Phương Vy_ 24110069
# Tri_Tue_Nhan_Tao
Dự án nghiên cứu và mô phỏng 6 nhóm thuật toán Trí tuệ nhân tạo áp dụng cho Robot hút bụi thông minh trong môi trường lưới (Grid Environment). Ứng dụng xây dựng trên nền tảng Python Tkinter, giúp trực quan hóa hành vi ra quyết định và so sánh hiệu suất giữa các trường phái AI khác nhau.

##  6 Groups of Algorithms Implemented

Dự án phân loại Robot hút bụi thành 6 nhóm tác nhân xử lý từ cơ bản đến nâng cao:

1. Simple Reflex Agent 
   * Quyết định hành động chỉ dựa trên trạng thái hiện tại (nếu ô hiện tại có Bụi -> Hút; nếu Sạch -> Rẽ ngẫu nhiên). Không có bộ nhớ lưu trữ lịch sử.
2. Model-Based Reflex Agent 
   * Cải tiến từ Reflex Agent nhưng có thêm bộ nhớ (Internal State) để lưu lại bản đồ các ô đã đi qua, tránh việc Robot bị lặp lại quãng đường hoặc đi vào góc chết.
3. Uninformed Search Agents 
   * Áp dụng các thuật toán tìm kiếm đồ thị cơ bản khi Robot chưa biết vị trí của bụi bẩn: **BFS (Breadth-First Search)** hoặc **DFS (Depth-First Search)** để quét sạch toàn bộ căn phòng.
4. Informed Search Agents 
   * Robot sử dụng hàm heuristic để ước lượng khoảng cách tới các ô có bụi nhằm tối ưu quãng đường: Cài đặt thuật toán **Greedy Best-First Search** và **A\* Search**.
5. Adversarial / Game Theory Search Agents 
   * Giả lập môi trường nâng cao khi có hai Robot cạnh tranh làm sạch hoặc có chướng ngại vật cản trở thông minh: Cài đặt **Minimax** kết hợp **Alpha-Beta Pruning** để tối ưu hóa quyết định từng bước.
6. Stochastic / Expectimax Agent 
   * Áp dụng trong môi trường có yếu tố ngẫu nhiên (bụi tự động xuất hiện theo thời gian hoặc chướng ngại vật di động): Sử dụng thuật toán **Expectimax** để tính toán giá trị kỳ vọng (Expected value).
