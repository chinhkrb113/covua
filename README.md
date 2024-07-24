1. Mô tả yêu cầu bài toán
Tóm tắt bài toán: Viết chương trình cho phép chơi cờ vua với máy tính
Yêu cầu:
- Các nước đi trong bàn cờ đúng với các luật trong cờ vua
- Chương trình có đồ họa
- Máy tính phải phản ứng các nước cờ nhanh (~3s)
Thách thức:
- Hệ số phân nhánh lớn
- Quản lý các nước đi của một trạng thái
- Làm quen với Python
Lợi thế:
- Thư viện hỗ trợ xây dựng đồ họa: PySimpleGUI
- Thư viện hỗ trợ kiểm soát các trạng thái của bàn cờ: chess
2. Các thư viện hỗ trợ
- Thư viện PySimpleGUI: giúp xây dựng đồ họa cho chương trình.
- Thư viện python-chess: giúp chương trình dễ dàng quản lý trạng thái các nước cờ, cung cấp các chức năng hữu ích như:
  + Hiển thị trạng thái bàn cờ
  + Sinh ra các nước đi hợp lệ cho một trạng thái
  + Cập nhật trạng thái sau các nước đi
3. Thuật toán sử dụng:
- Minimax
- Alpha-Beta Pruning
- Zobrist hashing
- Bảng chuyển vị (Tranposition table)
- Principal Variation Search (PV-search)
- Đào sâu lặp lại (Iterative deepening)
