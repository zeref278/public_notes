- Thêm 1 file vào `gitignore`

Nếu muốn ignore 1 file đã có trên git trước đó thì ta thêm file đó vào `.gitignore` và chạy câu lệnh ở project:

```cmd
git update-index --skip-worktree <file>
```