# Arsitektur Backend - SIM Sidang API

Pola: MVC (tanpa View, respons berupa JSON).

Alur request: Client -> .htaccess -> index.php -> routes/api.php -> Controller -> Model -> MySQL -> JSON Response

- config/      : koneksi database
- controllers/ : logika endpoint
- models/      : akses data (PDO/Eloquent)
- routes/      : definisi endpoint
- utils/       : helper response JSON dan JWT
