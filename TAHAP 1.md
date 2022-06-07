# 				FINAL PROJECT LARAVEL 

**Tahap 1 Install Laravel** 

1. Sebelum install Laravel, hal pertama yang harus dilakukan adalah install Composer

   ![](asset1/1.png)

   

2. Setelah dilakukan install Composer, maka langkah selanjutnya yaitu masuk Command Prompt dengan cara klik Win+R lalu ketik cmd dan klik **OK**

   ![](asset1/2.png)

   

3. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau terminal menuju direktori file server. Lokasi file server pada XAMPP secara default berada pada direktori xampp/htdocs. Masukan perintah ini pada jendela Command Prompt untuk masuk ke direktori htdocs.

   ```markdown
   cd \xampp\htdocs
   ```

   

   ![](asset1/3.png)

   

4. Setelah itu, membuat request untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori Github. 

   ```
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   

   ![](asset1/4.png)

   

   ![](asset1/5.png)

   

5. Setelah proses download file Laravel selesai, nantinya akan ada folder baru pada direktori file server dengan nama sesuai nama project yang telah dibuat. 

   ![](asset1/6.png)

   

6. Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk digunakan, arahkan Command Prompt atau Terminal menuju direktori yang telah dibuat sebelumnya.

   ```markdown
   Php artisan serve
   ```

   

   ![](asset1/7.png)

   

7. Apabila sudah muncul tulisan ``Laravel development server started`` pada Command Prompt atau Terminal, maka langkah selanjutnya yaitu membuka link yang telah disediakan oleh Laravel.  Secara default, akan diarahkan menuju alamat server, yaitu 127.0.0.1:8000. Nantinya, akan muncul tampilan homepage dengan tulisan Laravel di bagian tengah seperti pada gambar di bawah ini

   ![](asset1/8.png)

   

