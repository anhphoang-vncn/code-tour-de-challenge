# Coding Bug - Tour De Challenge | FRONT END

## Xây dựng dựa trên QDOJ của tác giả Harry-zklcdc 

### Hướng dẫn triển khai máy chủ

1. Cài đặt môi trường

    ```bash
    *** Cài đặt sẵn Node.JS **v12.16.1** hoặc mới hơn trước khi làm các bước tiếp theo
    ```
    ```bash
    npm install
    ```
    ```bash
    NODE_ENV=development npm run build:dll
    ```
    ```bash
    cp node_modules/echarts/lib/langEN.js node_modules/echarts/lib/lang.js
    ```

2. Gán IP:PORT của máy chủ API chấm điểm [BACK-END](https://github.com/anhphoang-vncn/code-tour-de-challenge-back-end), khởi động môi trường dev với cổng 7676 (http://localhost:7676)

    ```bash
    TARGET=http://127.0.0.1:80 npm run dev
    ```

### Ảnh chụp màn hình

![image](./static/img/screenshots/coding-bug-ss-001.png)
![image](./static/img/screenshots/coding-bug-ss-002.png)
![image](./static/img/screenshots/coding-bug-ss-003.png)
![image](./static/img/screenshots/coding-bug-ss-004.png)
![image](./static/img/screenshots/coding-bug-ss-005.png)

### Dành cho Nhà phát triển

```bash
# Tùy chỉnh JavaScript/CSS
./src/styles

# Các trang
./src/pages

# Ngôn ngữ
./src/i18n
```

## Contact

    EMAIL: anhph.skyone@gmail.com

## LICENSE

[MIT](http://opensource.org/licenses/MIT)