# 1 - Belajar Basic NestJS dengan Sequelize

Belajar API backend dengan NestJS dan sequelize untuk koneksi ke database. Sudah di sertakan untuk pembuatan migration dan seeder.

### Menjalankan aplikasi:

- Clone repo ini taruh di mana saja di komputer anda.

- Jalankan perintah ini:

```bash
$ npm install

# untuk membuat tabel baru dengan nama file `database-dev.sqlite`
$ npm run db:migrate

# untuk membuat user baru dari file seeder
$ npm run db:seed-dev

# memulai aplikasi: buka postman dengan url `http://localhost:3000`
$ npm run start:dev
```

- Done.

## Planing pengerjaan:

- [x] Koneksi ke database
- [x] Buat migration
- [x] Buat seeder
- [ ] Buat API untuk modules `/users`
- [ ] Buat authenticate dengan JWT
- [ ] Buat auth login
