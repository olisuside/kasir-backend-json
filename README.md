# Kasir Backend JSON

Backend JSON untuk aplikasi kasir menggunakan JSON Server sebagai Fake API.

## Frontend Aplikasi
Gunakan frontend berikut untuk aplikasi kasir:  
🔗 **[Kasir App](https://github.com/olisuside/kasir-app)**  

## Cara Menjalankan JSON Server
1. Clone repository ini:
   ```sh
   git clone https://github.com/olisuside/kasir-backend-json.git
   cd kasir-backend-json
2. Install dependencies:
   ```sh
   npm install

3. Jalankan json
   ```sh
   npx json-server --watch db.json --port 3000

4. JSON Server akan berjalan di http://localhost:3000/.

## Endpoint API
- Produk: http://localhost:3000/products 
- Kategori: http://localhost:3000/categories
- Keranjang: http://localhost:3000/keranjangs
- Pesanan: http://localhost:3000/pesanans
- Pastikan frontend aplikasi kasir sudah berjalan dan menggunakan backend ini dengan benar.
