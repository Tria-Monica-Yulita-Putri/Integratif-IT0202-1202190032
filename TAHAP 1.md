# 				FINAL PROJECT LARAVEL 

**Tahap 1 Install Laravel** 

1. Sebelum install Laravel, hal pertama yang harus dilakukan adalah install Composer

   ![1](https://user-images.githubusercontent.com/92940432/172362219-bc39e7d3-86e2-43f1-b318-370cea0fef66.png)

   

2. Setelah dilakukan install Composer, maka langkah selanjutnya yaitu masuk Command Prompt dengan cara klik Win+R lalu ketik cmd dan klik **OK**

   ![2](https://user-images.githubusercontent.com/92940432/172362232-9c369137-8aff-40ad-9675-ff0b81ba9d26.png)

   

3. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau terminal menuju direktori file server. Lokasi file server pada XAMPP secara default berada pada direktori xampp/htdocs. Masukan perintah ini pada jendela Command Prompt untuk masuk ke direktori htdocs.

   ```markdown
   cd \xampp\htdocs
   ```

   

   ![3](https://user-images.githubusercontent.com/92940432/172362235-836f8e85-2825-4a36-af66-62fd651dcebf.png)

   

4. Setelah itu, membuat request untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori Github. 

   ```
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   

   ![4](https://user-images.githubusercontent.com/92940432/172362240-6d08d9ff-b4eb-4850-b6b1-c8fd9499a282.png)

   

   ![5](https://user-images.githubusercontent.com/92940432/172362244-49c2a94a-f289-42e2-af1a-30bc24732014.png)

   

5. Setelah proses download file Laravel selesai, nantinya akan ada folder baru pada direktori file server dengan nama sesuai nama project yang telah dibuat. 

   ![6](https://user-images.githubusercontent.com/92940432/172362246-ebcc6a5b-deed-4b72-8044-ea7efac446aa.png)

   

6. Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk digunakan, arahkan Command Prompt atau Terminal menuju direktori yang telah dibuat sebelumnya.

   ```markdown
   Php artisan serve
   ```

   

   ![7](https://user-images.githubusercontent.com/92940432/172362251-2409dae0-1e1b-46bf-8267-21c641d8d0a8.png)

   

7. Apabila sudah muncul tulisan ``Laravel development server started`` pada Command Prompt atau Terminal, maka langkah selanjutnya yaitu membuka link yang telah disediakan oleh Laravel.  Secara default, akan diarahkan menuju alamat server, yaitu 127.0.0.1:8000. Nantinya, akan muncul tampilan homepage dengan tulisan Laravel di bagian tengah seperti pada gambar di bawah ini

   ![8](https://user-images.githubusercontent.com/92940432/172362193-f8c4514c-e088-4f80-be19-3049b3fe5b96.png)

   

