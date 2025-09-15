# Kolaborasi CI4 Login & Register

Proyek ini dibuat sebagai latihan kolaborasi tim dalam membangun aplikasi **Login & Register** menggunakan **CodeIgniter 4 (CI4)** dengan metode **MVC**.

---

## 👥 Struktur Tim (Metode MVC)
- **Dev1 (View)** → Membuat tampilan login & register.
- **Dev2 (Model & Database)** → Membuat model, validasi, dan struktur database.
- **Dev3 (Controller)** → Membuat controller dengan method `login()`, `register()`, `logout()`.
- **Semua Dev** → Menangani `Routes` bila diperlukan.

---

## 🛠️ Setup Project

### 1. Clone Repo
```bash
git clone https://github.com/LaOdeSukri/Kolaborasi-ci4-login-register.git
cd Kolaborasi-ci4-login-register
```

### 2. Install Dependencies
```bash
composer install
```

### 3. Copy & Konfigurasi `.env`
```bash
cp env .env
```
Atur:
- `app.baseURL`
- `database.default.*`

### 4. Jalankan Server
```bash
php spark serve
```
Akses di: [http://localhost:8080](http://localhost:8080)

---

## 🌿 Workflow Git

### Buat branch sesuai tugas:
```bash
git checkout -b Dev1-(view-login-register)
git checkout -b Dev2-(model-validation-db)
git checkout -b Dev3-(controller-auth)
```

### Workflow kerja:
1. **Commit** perubahan di branch masing-masing.
2. **Push** ke GitHub.
3. Buat **Pull Request (PR)** ke branch `main`.
4. Lakukan **Code Review** sebelum merge.

---

## 📌 Skeleton Method Controller
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

---

## 📂 Struktur Folder CI4 (Ringkas)
```
app/
 ├── Controllers/
 ├── Models/
 ├── Views/
 └── Config/
public/
writable/
.env
```

---

## ✅ Aturan Kontribusi
- Selalu kerja di **branch masing-masing**.
- Jangan langsung commit ke `main`.
- Gunakan **commit message jelas** (contoh: `feat: tambah validasi email di register`).
- Gunakan **PR** untuk merge.

---

## 📝 Issue Template
```markdown
## Deskripsi
Tuliskan deskripsi singkat tentang apa yang dikerjakan.

## Task
- [ ] Task 1
- [ ] Task 2

## Catatan
Catatan tambahan.
```

---

🚀 **Happy coding & happy collaboration!**
