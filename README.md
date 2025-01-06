# Calculator Project

## **1. Mô tả các thành phần của dự án**

### **Lớp `Calculator`**
- **Thuộc tính**: Không có (lớp này chỉ bao gồm các phương thức tính toán).
  
- **Phương thức:**
  - `add(int a, int b)`: Tính tổng hai số nguyên.
  - `subtract(int a, int b)`: Tính hiệu hai số nguyên.
  - `multiply(int a, int b)`: Tính tích hai số nguyên.
  - `divide(int a, int b)`: Tính thương hai số nguyên.
    - Nếu số chia bằng 0, ném ngoại lệ `IllegalArgumentException`.

---

### **Lớp kiểm thử `CalculatorTest`**
Lớp kiểm thử sử dụng **JUnit 5** để kiểm tra chức năng của lớp `Calculator`.

- **Kiểm tra phương thức `add()`**:
  - Đảm bảo kết quả trả về đúng khi tính tổng hai số nguyên.
  - Kiểm tra với các trường hợp đặc biệt như số âm hoặc số 0.

- **Kiểm tra phương thức `subtract()`**:
  - Đảm bảo kết quả trả về đúng khi tính hiệu hai số nguyên.
  - Kiểm tra với các trường hợp đặc biệt như số âm hoặc số 0.

- **Kiểm tra phương thức `multiply()`**:
  - Đảm bảo kết quả trả về đúng khi tính tích hai số nguyên.
  - Kiểm tra với các trường hợp đặc biệt như nhân với 0 hoặc số âm.

- **Kiểm tra phương thức `divide()`**:
  - Đảm bảo kết quả trả về đúng khi tính thương hai số nguyên.
  - Đảm bảo ném ngoại lệ `IllegalArgumentException` khi chia cho 0.

---

## **2. Kết quả kiểm thử**

- Tất cả các bài kiểm thử đều thành công.
- **Số lượng bài kiểm thử**: 4 (tương ứng với các phương thức `add`, `subtract`, `multiply`, và `divide`).
- **Kết quả kiểm thử trong console**:
  - **Tests run**: 4
  - **Failures**: 0
  - **Errors**: 0
  - **BUILD SUCCESS**

---

## **3. Cách thực hiện kiểm thử**

1. **Chạy kiểm thử trực tiếp trong IntelliJ IDEA**:
   - Nhấp chuột phải vào tệp kiểm thử `CalculatorTest` > Chọn **Run 'CalculatorTest'**.

2. **Sử dụng Maven**:
   - Trong terminal, chạy lệnh:
     ```bash
     mvn test
     ```

3. **Sử dụng Gradle**:
   - Trong terminal, chạy lệnh:
     ```bash
     gradle test
     ```

---

## **4. Kết luận**

Dự án bao gồm các thành phần chính:
- Lớp `Calculator` cung cấp các chức năng cơ bản: cộng, trừ, nhân và chia.
- Lớp kiểm thử `CalculatorTest` đảm bảo các chức năng của lớp `Calculator` hoạt động chính xác.

Tất cả bài kiểm thử đều thành công, chứng minh mã nguồn hoạt động ổn định và sẵn sàng sử dụng hoặc mở rộng thêm.


[Link ChatGPT!](https://chatgpt.com/share/677b5e55-c588-8007-8ece-f1f00b7eaf61)

![image](https://github.com/user-attachments/assets/e7b57c01-608f-4eb9-ac71-a275bd687433)
