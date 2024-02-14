Cơ bản
i: Chuyển sang chế độ chèn (Insert mode).
Esc: Trở về chế độ bình thường (Normal mode) từ bất kỳ chế độ nào khác.
:w: Lưu file.
:q: Thoát NeoVim.
:wq hoặc :x: Lưu và thoát.
:q!: Thoát mà không lưu.
dd: Xóa (cut) dòng hiện tại.
yy: Sao chép (copy) dòng hiện tại.
p: Dán (paste) nội dung đã sao chép hoặc xóa.
Di chuyển trong tập tin
h, j, k, l: Di chuyển trái, xuống, lên, phải (tương ứng).
0: Di chuyển đến đầu dòng.
^: Di chuyển đến ký tự đầu tiên không phải khoảng trắng của dòng.
$: Di chuyển đến cuối dòng.
gg: Di chuyển đến đầu tập tin.
G: Di chuyển đến cuối tập tin.
:n: Di chuyển đến dòng thứ n, với n là số.
Tìm kiếm và thay thế
/từ_khóa: Tìm từ khóa trong tập tin (nhấn n để tìm tiếp theo, N để tìm ngược lại).
:%s/từ_cũ/từ_mới/g: Thay thế tất cả các lần xuất hiện của từ_cũ bằng từ_mới trong tập tin.
Làm việc với cửa sổ và tab
:split hoặc :sp: Chia đôi cửa sổ ngang.
:vsplit hoặc :vsp: Chia đôi cửa sổ dọc.
Ctrl+w w: Chuyển đổi giữa các cửa sổ.
:tabnew: Mở một tab mới.
gt: Chuyển đến tab tiếp theo.
gT: Chuyển đến tab trước đó.
Cấu hình và Plugin
:PlugInstall: Cài đặt plugin (nếu bạn sử dụng Vim-Plug làm quản lý plugin).
:checkhealth: Kiểm tra trạng thái sức khỏe của NeoVim.
