# Giới thiệu về ngôn ngữ Java

## Java là gì?

Java là ngôn ngữ lập trình bậc cao, được phát triển bởi **Sun Microsystems**, do **James Gosling** khởi xướng và phát hành vào năm 1995 như là một thành phần cốt lõi của nền tảng Java của **Sun Microsystems (Java 1.0 [J2SE])**. Java chạy trên rất nhiều nền tảng khác nhau, như **Windows**, **Mac** và các phiên bản khác nhau của **UNIX**. 

Java được hiểu là một loại ngôn ngữ lập trình hướng đối tượng (OOP) và dựa trên các lớp. Không giống với những ngôn ngữ lập trình thông thường, thay vì việc biên dịch mã nguồn trở thành mã nguồn máy hoặc trực tiếp thông dịch mã nguồn khi chạy thì Java được thiết kế để biên dịch mã nguồn thành bytecode. Sau đó, bytecode sẽ được môi trường thực thi (runtime environment).

## Đặc điểm của Java

- **Hướng đối tượng**: Trong Java, mọi thứ đều là Object. Java có thể mở rộng vì nó dựa trên mô hình Object.
- **Nền tảng độc lập**: Không giống như nhiều ngôn ngữ lập trình khác (C, C++), khi Java được biên dịch, nó không biên dịch sang một máy tính cụ thể trên nền tảng nào, thay vào đó là những byte code độc lập với nền tảng. Byte code này được phân phối trên web và được thông dịch bằng Virtual Machine (JVM) trên bất cứ nền tảng nào mà nó đang chạy.
- **Đơn giản**: Java được thiết kế để dễ học. Nếu bạn hiểu cơ bản về khái niệm lập trình hướng đối tượng Java, thì có thể nắm bắt ngôn ngữ này rất nhanh.
- **Bảo mật**: Với tính năng an toàn của Java, nó cho phép phát triển những hệ thống không có virus, giả mạo. Các kỹ thuật xác thực dựa trên mã hóa công khai.
- **Kiến trúc trung lập**: Trình biên dịch của Java tạo ra một định dạng file object có kiến trúc trung lập, làm cho code sau khi biên dịch có thể chạy trên nhiều bộ vi xử lý, với sự hiện diện của Java runtime system.
- **Portable**: Là kiến trúc trung lập và không phụ thuộc vào việc thực hiện là những đặc điểm chính nhất khi nói về khía cạnh Portable của Java. Trình biên dịch trong Java được viết bằng ANSI C với một ranh giới portable gọn gàng, đó là một subset POSIX (giao diện hệ điều hành linh động). Bạn có thể mang byte code của Java lên bất cứ nền tảng nào.
- **Mạnh mẽ**: Java nỗ lực loại trừ những tình huống dễ bị lỗi bằng cách nhấn mạnh chủ yếu là kiểm tra lỗi thời gian biên dịch và kiểm tra runtime.
- **Đa luồng**: Với tính năng đa luồng của Java, bạn có thể viết các chương trình có thể thực hiện nhiều tác vụ đồng thời. Tính năng này cho phép các nhà phát triển xây dựng các ứng dụng tương tác có thể chạy trơn tru.
- **Thông dịch**: Byte code của Java được dịch trực tiếp tới các nền tảng gốc và nó không được lưu trữ ở bất cứ đâu. 
- **Hiệu suất cao**: Với việc sử dụng trình biên dịch Just-In-Time, Java cho phép thực thi với hiệu suất cao, nhanh chóng phát hiện, gỡ lỗi.
- **Phân tán**: Java được thiết kế cho môi trường phân tán của Internet.
- **Linh động**: Java được coi là năng động hơn C hay C++ vì nó được thiết kế để thích nghi với môi trường đang phát triển. Các chương trình Java có thể mang theo một lượng lớn thông tin run-time, được sử dụng để xác minh và giải quyết các truy cập đến đối tượng trong thời gian chạy.

## Ứng dụng của JAVA

Có 4 loại ứng dụng chính mà có thể được tạo bởi sử dụng ngôn ngữ lập trình Java:

- **Standalone App**  
Nó còn được biết đến với tên gọi khác là **Destop App** hoặc **Windows-based App**. Một ứng dụng mà chúng ta cần cài đặt trên mỗi thiết bị như media player, antivirus... **AWT** và **Swing** được sử dụng trong Java để tạo các **Standalone App**.
- **Web App**  
Một ứng dụng mà chạy trên **Server Side** và tạo **Dynamic Page**, được gọi là **Web App**. Hiện tại, các công nghệ Servlet, JSP, Struts, JSF... được sử dụng để tạo **Web App** trong Java.
- **Enterprise App**  
Một ứng dụng dạng như **Banking App**, có lợi thế là tính bảo mật cao, cân bằng tải (load balancing) và clustering. Trong java, **EJB** được sử dụng để tạo các **Enterprise App**.
- **Mobile App**  
Đây là loại ứng dụng được tạo cho thiết bị mobile. Hiện tại thì **Android** và **Java ME** được sử dụng để tạo loại ứng dụng này.

