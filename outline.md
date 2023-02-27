#Tính năng nổi bật của Tailwind

Xây dựng giao diện chỉ cần khai báo class trên file html
Chỉ xuất ra những file css chứa những class đã sử dụng trong giao diện.
Dễ dàng thiết lập Responsive ngay trên file html
Hỗ trợ tương tác hover, focus… ngay trên class html
Tối ưu những cấu trúc html css có tính lặp lại
Định nghĩa thêm class mới được phối hợp bởi các class có sẵn trong tailwind
Hỗ trợ chế độ tối Dark Mode
Dễ dàng mở rộng, chỉnh sửa và biến đổi
Tăng tốc độ code với Extension thông minh trên VS Code.

#Chuẩn bị
Bạn chuẩn bị những thứ bên dưới để phục vụ cho quá trình cài đặt và sử dụng tailwind css trong dự án.

nodejs
VSCode + Extensiton Tailwind CSS IntelliSense, PostCSS Language Support

#Các bước cài đặt tailwind Css vào website
Để cài đặt Tailwind Css vào website bạn thực hành từng bước theo video và phần ghi chú các câu lệnh đã sử dụng ở bên dưới.

1. Install Tailwind CSS

   > npm install -D tailwindcss
   > npx tailwindcss init

2. Configure your template paths

> "./public/\*_/_.{html,js}"

3. Add the Tailwind directives to your CSS

File: src/tailwind.css

> @tailwind base;
> @tailwind components;
> @tailwind utilities;

4. Start the Tailwind CLI build process

> npx tailwindcss -i ./src/tailwind.css -o ./public/css/tailwind.css --watch

5. Start using Tailwind in your HTML

> <link href="./css/tailwind.css" rel="stylesheet">
