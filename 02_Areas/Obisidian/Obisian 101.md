Dưới đây là **cheat sheet Markdown thông dụng trong Obsidian**, được sắp xếp theo mức độ phổ biến giảm dần để bạn tiện tra cứu và sử dụng hiệu quả:

---

## 📄 Văn bản Cơ bản

Đây là những định dạng bạn sẽ dùng thường xuyên nhất khi ghi chú:

|Chức năng|Markdown|Hiển thị|
|:--|:--|:--|
|**In đậm**|`**đậm**`|**đậm**|
|**In nghiêng**|`*nghiêng*`|_nghiêng_|
|**Gạch ngang**|`~~gạch~~`|&lt;del>gạch&lt;/del>|
|**Gạch nổi bật**|`==nổi bật==`|==nổi bật== (cần plugin)|

---

## 🧭 Tiêu đề (Heading)

Giúp cấu trúc nội dung và tạo mục lục dễ dàng. Sử dụng dấu `#` tương ứng với cấp độ tiêu đề:

|Cấp độ|Markdown ví dụ|Kết quả hiển thị|
|:--|:--|:--|
|**H1**|`# Tiêu đề 1`|# Tiêu đề 1|
|**H2**|`## Tiêu đề 2`|## Tiêu đề 2|
|**H3**|`### Tiêu đề 3`|### Tiêu đề 3|
|...|`####`, `#####`|Các cấp nhỏ hơn|

---

## 📌 Danh sách (List)

Để tổ chức thông tin dưới dạng danh sách, cả danh sách có dấu đầu dòng và danh sách số:

|Loại|Markdown ví dụ|Kết quả hiển thị|
|:--|:--|:--|
|**Danh sách chấm**|`- mục 1`|• mục 1|
|**Danh sách số**|`1. mục 1`|1. mục 1|
|**Danh sách lồng**|`- mục con`|▪ mục con|


---

## ✅ Checkbox (Nhiệm vụ)

Lý tưởng để theo dõi các việc cần làm hoặc trạng thái nhiệm vụ:

|Loại|Markdown ví dụ|Hiển thị|
|:--|:--|:--|
|**Chưa làm**|`- [ ] Việc 1`|- [ ] Việc 1|
|**Đã làm**|`- [x] Việc 2`|- [x] Việc 2|


---

## 🔗 Liên kết và Gắn thẻ

Liên kết các ghi chú trong Obsidian hoặc với nguồn bên ngoài, cùng với việc sử dụng hashtag để dễ dàng tìm kiếm và phân loại:

|Loại|Markdown ví dụ|Kết quả & Ghi chú|
|:--|:--|:--|
|**Liên kết nội bộ**|`[[Tên note]]`|Link đến file khác trong vault|
|**Gắn thẻ**|`#từ_khóa`|Hashtag (dễ lọc tìm kiếm)|
|**Liên kết ngoài**|`[Tên](https://link.com)`|[Tên](https://link.com)|


---

## 🧱 Code và Mã nguồn

Để hiển thị các đoạn mã hoặc cú pháp đặc biệt, bạn có thể định dạng code trong dòng hoặc cả một khối:

| Loại            | Markdown ví dụ | Hiển thị & Ghi chú                          |
| :-------------- | :------------- | :------------------------------------------ |
| **Inline code** | `` `code` ``   | `code` — đoạn mã nhỏ nằm trong dòng văn bản |
| **Code block**  | ```bash<br>    | ```bash (xuống hàng) có thể copy được       |
