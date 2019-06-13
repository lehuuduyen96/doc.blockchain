# Cài đặt Hyperledger Fabric

Bạn có thể xem hướng dẫn gốc [tại đây](https://developer.ibm.com/tutorials/ibm-blockchain-platform-vscode-smart-contract/)
## Yêu cầu hệ thống
Để cài đặt môi trường phát triển Hyperledger Fabric, cần có các thành phần sau:

- [Node v8.x or greater and npm v5.x or greater](https://nodejs.org/en/download/)
- [Yeoman (yo) v2.x](http://yeoman.io/)
- [Docker version v17.06.2-ce or greater](https://www.docker.com/get-started)
- [Docker Compose v1.14.0 or greater](https://docs.docker.com/compose/install/)
- [VSCode 1.28.2 or higher](https://code.visualstudio.com/download)

Đối với Windows:

- Windows 10 Enterprise, Pro, or Education with 1607 Anniversary Update or later
- Docker for Windows chạy Linux containers (đây là thiết lập mặc định)
- C++ Build Tools for Windows from [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools#windows-build-tools)
* OpenSSL v1.0.2 from [Win32 OpenSSL](http://slproweb.com/products/Win32OpenSSL.html)
    * Cài đặt version bình thường, không phải "light" version
    * Cài đặt Win32 version vào C:\OpenSSL-Win32 trên máy 32-bit
    * Cài đặt Win64 version vào C:\OpenSSL-Win64 trên máy 64-bit

Sau khi cài đặt tất cả các thành phần, bạn có thể kiểm tra lại bằng cách chạy những lệnh sau trong terminal:

- `node --version`
- `npm --version`
- `yo --version`
- `docker --version`
- `docker-compose --version`
