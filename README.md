# Qua Đèo Ngang

Trang web tĩnh hiển thị hai câu thơ trong bài **Qua Đèo Ngang** trên nền ảnh Đèo Ngang.

## Chạy cục bộ

Mở `index.html` trực tiếp trong trình duyệt, hoặc chạy một static server bất kỳ:

```bash
python3 -m http.server 8000
```

Sau đó truy cập <http://localhost:8000>.

## GitHub Pages

Workflow tại `.github/workflows/deploy-pages.yml` sẽ tự deploy site mỗi khi có thay đổi trên branch `master`.

Trong repository GitHub:

1. Vào **Settings → Pages**.
2. Ở **Source**, chọn **GitHub Actions**.
3. Đẩy các file của project lên branch `master`.
4. Mở tab **Actions** để theo dõi workflow `Deploy to GitHub Pages`.
