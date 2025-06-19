https://github.com/fesdinang/obisian.git

**Từ giờ trở đi, để đồng bộ giữa các thiết bị, bạn sẽ chỉ cần thực hiện:**

- **Để tải các thay đổi mới nhất từ GitHub về điện thoại:**
    
    - Mở Termux, `cd ~/storage/shared/Documents/ObsidianVaults/obisian/`
    - Chạy: `git pull`
    - Nhập passphrase nếu có.
- **Để đẩy các thay đổi từ điện thoại lên GitHub:**
    
    - Mở Termux, ``
    ```cd ~/storage/shared/Documents/ObsidianVaults/obisian/```
    - Chạy:
        
        Bash
        
        ```
        git add .
        git commit -m "Mô tả các thay đổi của bạn"
        git push
        ```
        
    - Nhập passphrase nếu có.