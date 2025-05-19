# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


// Các bước cài đặt đầu tiên
- npm create vite

Cài đặt thư viện
npm i

# Todo
- format code: thống nhất một dạng format cho code
- Khởi tạo git
- deploy lên server
- library cần dùng trong dự án

# Khởi tạo git
git init 
- tạo repositories trên git hub
# format code
- sử dụng thư viện prettier

``` bash
npm i prettier
```
- tạo file .prettierrc
- lên  prettier playground để lấy thông tin cấu hình cho prettier. 
[prettier playground](https://prettier.io/playground/)

## deploy lên server
- câu lệnh gì để có thể cài lên thư viện
``` bash
npm install
```
- câu lệnh gì để build được dự án 
``` bash
npm run build
```

## Tổ chức thư mục
1. Components
2. Templates
3. Pages
4. Router
5. Store
6. Hooks - (Hiện tại ít sử dụng)
7. Common
    7.1 Utils 
    7.2 Helpers
    7.3 Constants
8. Services (Dùng để call api)
9.
# Library cần dùng trong dự án 
- react router
- tailwindcss
- redux
- formix
- lucide-react(Icon)
- library UI chưa sử dụng
- axios (call api - đỡ cực khi sử dụng so với)
# Kiểm tra thư viện nào bị outdate

``` bash
npm outdate
```

``` bash
npx npm-check-updates -i
```

# chọn thì nhấn space -> nhấn enter để tiếp tục
// lưu ý eslint để ý dễ bị lỗi nên hạn chế update phần này