# Code Tour De Challenge FRONT END

> ### Xây dựng dựa trên cấu trúc của OnlineJudge 

## Hướng dẫn triển khai máy chủ

Cài đặt sẵn Node.JS **v12.16.1** hoặc mới hơn trước khi làm các bước tiếp theo

```
# Cài đặt các thư viện & môi trường
npm install
NODE_ENV=development npm run build:dll
cp node_modules/echarts/lib/langEN.js node_modules/echarts/lib/lang.js

# Gán IP:PORT của máy chủ API chấm điểm
TARGET=https://127.0.0.1:80 npm run dev

# Website hoạt động với localhost:7676
npm run dev
```

## LICENSE

[MIT](http://opensource.org/licenses/MIT)

## Dành cho Nhà phát triển

```
#Tùy chỉnh JavaScript/CSS
./src/styles

#Các trang
./src/pages

#Ngôn ngữ
./src/i18n
```
