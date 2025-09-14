# Setup GitHub Kolaborasi MVC Project

## 1. Struktur Tugas Siswa (Metode MVC)
- **Siswa A (View):** Membuat tampilan login & register.
- **Siswa B (Model & Database):** Membuat model, validasi, dan struktur database.
- **Siswa C (Controller):** Membuat controller dengan method `login()`, `register()`, `logout()`.

## 2. Alur Pengerjaan
1. Buat repo di GitHub (misalnya: `project-login-register`).
2. Tambahkan kolaborator (A, B, C).
3. Buat branch terpisah:
   - `feature/view-login-register` (A)
   - `feature/model-validation-db` (B)
   - `feature/controller-auth` (C)
4. Gunakan Pull Request (PR) untuk merge ke branch `main`.
5. Review code sebelum merge agar tidak bentrok.

## 3. Skeleton Method Controller
```php
class AuthController extends BaseController {
    public function login() {
        // TODO: Handle login
    }

    public function register() {
        // TODO: Handle register
    }

    public function logout() {
        // TODO: Handle logout
    }
}
```

## 4. Setup GitHub Repo
### Inisialisasi Repo
```bash
git init
git remote add origin https://github.com/username/project-login-register.git
git branch -M main
git push -u origin main
```

### Buat Branch Sesuai Tugas
```bash
git checkout -b feature/view-login-register
git checkout -b feature/model-validation-db
git checkout -b feature/controller-auth
```

### Workflow
- Commit perubahan di branch masing-masing.
- Push ke GitHub.
- Buat Pull Request.
- Review & merge ke `main`.

## 5. Issue Template
```markdown
## Deskripsi
Tuliskan deskripsi singkat tentang apa yang dikerjakan.

## Task
- [ ] Task 1
- [ ] Task 2

## Catatan
Tambahkan catatan tambahan bila ada.
```
