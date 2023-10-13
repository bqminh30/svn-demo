# svn-demo
![image](https://github.com/bqminh30/svn-demo/assets/64219602/74f4066e-8789-4fa7-bc21-43ab22607b22)
1. In Apache Subversion, các lệnh được nhập thông qua một cửa sổ đầu cuối. Để mở cái này trong Windows, hãy nhấn 'Phím Windows' và 'r.' Thao tác này sẽ hiển thị hộp thoại 'Chạy'. Nhập 'cmd' và nhấn 'Ok.' Cửa sổ terminal bây giờ sẽ mở, sẵn sàng để bạn nhập lệnh
![image](https://github.com/bqminh30/svn-demo/assets/64219602/9ec9e247-54b2-4c79-86d7-5ec11c536d7f)
![image](https://github.com/bqminh30/svn-demo/assets/64219602/eea4c479-c298-43cf-9eb4-c2b82a01afa7)
2. Để tạo kho lưu trữ đầu tiên của bạn, hãy sử dụng lệnh 'svnadmin create', theo sau là đường dẫn mà bạn muốn tạo kho lưu trữ mới và tên của kho lưu trữ mới. Ví dụ: nếu bạn muốn tạo một kho lưu trữ mới có tên 'Dự án mới' trong thư mục 'Tài liệu', lệnh sẽ là: svnadmin create C:\Users\Jessica\Documents\New_Project
![image](https://github.com/bqminh30/svn-demo/assets/64219602/78f5f9c2-cee4-43ae-b906-a30d147856c8)
3. Kiểm tra thư mục 'Documents'. Bạn sẽ thấy một thư mục mới có tên 'New Project.'
![image](https://github.com/bqminh30/svn-demo/assets/64219602/24435def-0651-451a-b58f-bda3295f22e2)
4. Thư mục này chứa một số tập tin mới. Không xóa hoặc sửa đổi bất kỳ tập tin nào trong số này.
![image](https://github.com/bqminh30/svn-demo/assets/64219602/023cfafb-30e3-4822-b927-df37ba703674)
5. Bây giờ bạn đã tạo một kho lưu trữ, hãy kiểm tra một bản sao đang hoạt động. Việc này được thực hiện bằng cách sử dụng 'SVN Checkout' lệnh, theo sau là URL của kho lưu trữ của bạn và vị trí của kho lưu trữ bạn vừa tạo trên máy tính của mình. Trong ví dụ này, lệnh là: svn checkout http://127.0.0.1:9880/New-Project C:\Users\Jessica\Documents\New_Project Hit 'Enter.'
![image](https://github.com/bqminh30/svn-demo/assets/64219602/563f7327-0907-4cf1-9dff-123f8756ec72)
6. Khi kiểm tra bản sao làm việc của mình, bạn sẽ thấy bản sao của tất cả các tệp từ kho lưu trữ của mình.
![image](https://github.com/bqminh30/svn-demo/assets/64219602/d289accf-043b-4487-bf94-f163db63249b)
7. Bây giờ bạn có thể tự do thực hiện các thay đổi đối với bản sao làm việc của mình. Khi bạn sửa đổi xong các tệp của mình, bạn sẽ cần phải chuyển các thay đổi của mình trở lại kho lưu trữ. Để thực hiện một cam kết, hãy sử dụng lệnh 'svn commit' theo sau là “--message” và một thông báo tường trình thích hợp, và cuối cùng là vị trí của bản sao làm việc của bạn. Trong ví dụ này, lệnh sẽ là: svn commit --message “add Readme file”
C:\Users\Jessica\Documents\New_Project ấn 'Enter.'
Những thay đổi của bạn hiện đã được cam kết vào kho lưu trữ!

