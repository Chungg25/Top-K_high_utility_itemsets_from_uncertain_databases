# Sử dụng 5 Thuật Toán trong Nghiên Cứu

## Danh sách các thuật toán

1. **Thuật toán 1: SKYFUP**
2. **Thuật toán 2: TUHUFP-Growth**
3. **Thuật toán 3: UHUOPM**
4. **Thuật toán 4: Bio-HUIF**
5. **Thuật toán 5: MOEA-HEUPM**

---
## Các thuật toán được nhóm biên chế để sự dụng tốt với bộ dữ liệu và đảm bảo tính chính xác từ phương pháp bài báo
## Chi tiết các thuật toán

### Thuật toán 1 và Thuật toán 2
- **Nguồn tham khảo**: Em đã tìm hiểu và tham khảo từ 2 anh khóa trên để hiện thực phương pháp bài báo
- **Hạn chế**: Cả hai thuật toán yêu cầu truyền vào ngưỡng (threshold). Tuy nhiên, việc xác định ngưỡng chính xác để khai phá các tập mục tốt rất khó.
- **Chiến lược**:
  - Sử dụng phương pháp **two-phase** để khai phá.

---

### Thuật toán 3: UHUOPM
- **Đề xuất của nhóm**: Đây là thuật toán do nhóm xây dựng, dựa trên các thuật toán hiện có.
- **Điểm nổi bật**:
  - **Không cần truyền ngưỡng**: Người dùng chỉ cần cung cấp số lượng top K mong muốn.
  - **Kết quả tốt hơn**: Hiệu quả khai phá vượt trội so với thuật toán 1 và 2.
  - **Thời gian chạy**: Gần tương đương với thuật toán 1 và 2.
  - **Bộ nhớ sử dụng**: Nhiều hơn thuật toán 1 và 2.
- **Chiến lược**:
  - Nhóm hiện thực chuyển phương pháp từ **two-phase** sang **one-phase** để tăng hiệu suất.
---

### Điểm chung của 3 thuật toán: đều sử dụng một cấu trúc dữ liệu để lưu trữ và áp dụng các chiến lược nâng ngưỡng để cải thiện hiệu năng
### Hạn chế chung của 3 thuật toán: Hiện tại, chưa có công thức toán học tối ưu hóa hiệu quả khai phá.
---

### Thuật toán 4: Bio-HUIF và Thuật toán 5: MOEA-HEUPM
- **Mục tiêu**: Giải quyết bài toán bằng các phương pháp dựa trên sinh học và tập tính động vật.
- **Phương pháp**:
  - Kết hợp các thuật toán tiến hóa như **GA** (Genetic Algorithm), **PSO** (Particle Swarm Optimization) và **BA** (Bat Algorithm).
- **Kế hoạch hiện thực**:
  - Sẽ hoàn thành trước ngày thuyết trình.

---

## Phần so sánh
- Sau khi hoàn thành thuật toán 4 và 5, em sẽ trình bày biểu đồ so sánh hiệu năng và hiệu quả.
- **Dữ liệu lưu trữ**:
  - Thời gian chạy và bộ nhớ sử dụng đã được lưu trong thư mục `out`.

---
