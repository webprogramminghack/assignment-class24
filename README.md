# React Router Assignment

## Tujuan

Mengenal konsep dasar react-router-dom dan mempraktikkan penggunaan berbagai fitur seperti BrowserRouter, Routes, Route, useParams, halaman 404, nested routes, shared layouts, Outlet, Link, NavLink, Navigate, dan useNavigate. Anda juga akan mengimplementasikan axios dan react-query untuk melakukan fetching data dari server.

## Deskripsi

Pada assignment ini, kita akan membuat aplikasi sederhana yang terdiri dari berdasarkan desain Figma berikut [Figma Design](https://www.figma.com/design/pIxEWxvMT6czvHU7vHOZD4/Class-24?m=auto&t=ByVCTA1w83NcVFmC-1) dengan empat halaman utama:

1. Home: Halaman utama.
2. Users: Menampilkan semua pengguna yang diperoleh dari API.
3. User: Menampilkan detail dari seorang pengguna berdasarkan ID.
4. About: Halaman yang menampilkan tentang kita.

Data pengguna diambil dari API: [JSONPlaceholder](https://jsonplaceholder.typicode.com/users).

## Design Figma

Berikut adalah link desain Figma untuk tugas ini : [Link Design Figma](https://www.figma.com/design/pIxEWxvMT6czvHU7vHOZD4/Class-24?m=auto&t=ByVCTA1w83NcVFmC-1)

## JSONPlaceholder API Information

API terdiri dari endpoint berikut:

- GET /users - Mengembalikan semua user
- GET /users/:id - Mengembalikan sebuah user
- GET /users?name=Leanne%20Graham - Mengembalikan user berdasarkan query name **(NAME HARUS LENGKAP, TIDAK BISA HANYA "Leanne" SAJA)**

## Setup Project

1. Instal dependensi yang dibutuhkan:

```
npm install
```

## Task

Kalian diminta untuk membuat routing website dengan desain [Figma Design](https://www.figma.com/design/pIxEWxvMT6czvHU7vHOZD4/Class-24?m=auto&t=ByVCTA1w83NcVFmC-1) dan menggunakan data dari [JSONPlaceholder](https://jsonplaceholder.typicode.com/users).

1. Buatkan Nav Bar berdasarkan desain, yang berisi tautan ke halaman berikut:

   - Logo **(JIKA DI KLIK MENGARAH HALAMAN HOME)**
   - Home
   - User
   - About

2. Buatkan route index atau '/', yang menampilkan halaman Home berdasarkan desain
3. Buatkan route '/users', yang menampilkan halaman Users berdasarkan desain, dengan data users dari API berikut [JSONPlaceholder](https://jsonplaceholder.typicode.com/users), serta memiliki search berdasarkan nama **(WAJIB MENGGUNAKAN AXIOS DAN REACT QUERY)**
4. Buatkan route '/users/:id', yang menampilkan halaman User berdasarkan desain, dengan data user dari API berikut [JSONPlaceholder](https://jsonplaceholder.typicode.com/users) **(WAJIB MENGGUNAKAN AXIOS DAN REACT QUERY)**
5. Buatkan route '/about', yang menampilkan halaman About berdasarkan desain
6. Tangani halaman 404, saat membuka route yang tidak ada, buat berdasarkan desain

**Note: Untuk background dapat menggunakan gradient color dan khusus tabel all user tidak harus mirip dengan desain**
**Note: Jika mengalami kendala pada saat search, lihat [YOUTUBE](https://www.youtube.com/watch?v=oZZEI23Ri6E&t=45s) berikut.**
