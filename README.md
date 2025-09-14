# Setup GitHub Kolaborasi MVC Project
TIM DEVELOPMENT INI DAPAT BERUBAH POSISI

## 1. Struktur Tugas Siswa (Metode MVC)
- **Dev1 (View):** Membuat tampilan login & register.
- **Dev2 (Model & Database):** Membuat model, validasi, dan struktur database.
- **Dev3 (Controller):** Membuat controller dengan method `login()`, `register()`, `logout()`.
- **Dev1,Dev2,Dev3 (Routes):** Membuat atau cek routes Routes.
- 
## 2. Alur Pengerjaan
1. Kolaborator (Dev1, Dev2, Dev2).
2. branch terpisah:
   - `feature/view-login-register` (Dev1)
   - `feature/model-validation-db` (Dev2)
   - `feature/controller-auth` (Dev3)
3. Gunakan Pull Request (PR) untuk merge ke branch `main`.
4. Review code sebelum merge agar tidak bentrok.

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
git remote add origin https://github.com/LaOdeSukri/Kolaborasi-ci4-login-register.git
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
catatan tambahan.
```
