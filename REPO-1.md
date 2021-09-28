<h2> INSTALASI GIT </h2>
<ol>
  <li> Download GIT dengan mengakses "https://git-scm.com/downloads" tersedia GIT untuk Windows, Linux, dan macOS. </li> 
  <img src="https://user-images.githubusercontent.com/91447664/134845967-2d0d6a22-8290-4d4a-8297-b0171f0921cf.png" width="450px">
  <li> Setelah Download GIT berhasil, buka file tempat anda menyimpan GIT lalu double-click, maka akan muncul License dan klik "Next".
  <img src="https://user-images.githubusercontent.com/91447664/134846522-891e462c-368d-4c0a-a0e6-e81cb24ff5ce.png" width="450px">
  <li> Setelah itu, pilih lokasi dimana anda akan menyimpan GIT atau anda dapat menyimpan sesuai default yang disarankan.
  <img src="https://user-images.githubusercontent.com/91447664/134866738-5b39dce3-202e-4297-af03-87b0ad0b4ac4.png" width="450px">
  <li> Akan muncul Pilihan Komponen, klik "Next" untuk melanjutkan sesuai default.
  <img src="https://user-images.githubusercontent.com/91447664/134866922-a762e2ae-7c9c-4afd-8dff-46b9acf4d8c7.png" width="450px">
  <li> Selanjutnya, shortcut untuk menu Start, anda dapat mengubahnya atau bisa sesuai default. (Git)
  <img src="https://user-images.githubusercontent.com/91447664/134867448-76cf12fc-89a2-4d12-95a2-43263348fb3f.png" width="450px">
  <li> Lalu memilih Editor Software yang akan digunakan sebagai default penggunaan GIT. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134867818-1bd678ad-77a7-4a23-b1b8-2645001bf885.png" width="450px">
  <li> Next, sesuai default. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134868241-de3cb1c9-3425-4ae3-944f-7d6087bbd388.png" width=450px">
  <li> Pilih sesuai yang direkomendasikan, lalu klik "Next". </li>
  <img src="https://user-images.githubusercontent.com/91447664/134868357-5a0ae75b-28f7-4e1f-a9d9-1321f41c0cd5.png" width="450px">
  <li> Pilih Client program untuk GIT lalu klik "Next". </li>
  <img src="https://user-images.githubusercontent.com/91447664/134869716-fb0ab8fd-789d-4c49-9498-9a26ef5059e8.png" width="450px">
  <li> Pilih yang akan digunakan GIT untuk koneksi HTTPS. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134869871-9ba8e62d-233f-4ff6-9812-6991cd1a03cd.png" width="450px">
  <li> Pilih opsi pertama untuk konversi akhir baris (CR-LF). </li>
  <img src="https://user-images.githubusercontent.com/91447664/134870061-19bb8fd1-d416-45b0-95a0-2a36447d2b42.png" width="450px">
  <li> Pilih MinTTY untuk terminal yang digunakan untuk mengakses Git Bash. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134870259-78866053-38da-455f-9859-7152b23a5921.png" width="450px">
  <li> Pilih default </li>
  <img src="https://user-images.githubusercontent.com/91447664/134870942-acf6c1bd-47d8-4162-b78f-b520fa328624.png" width="450px">
  <li> Next, sesuai default. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134871106-e5cad55a-5e8a-4ac5-b7da-2e9bde42c6f2.png" width="450px">
  <li> Pilih update terbaru "Credential Manager Core" lalu klik "Next". </li>
  <img src="https://user-images.githubusercontent.com/91447664/134871106-e5cad55a-5e8a-4ac5-b7da-2e9bde42c6f2.png" width="450px">
  <li> Untuk opsi ekstra, pilih serta aktifkan enable file system caching. </li>
  <img src="https://user-images.githubusercontent.com/91447664/134871289-a5ee41c1-64c3-4aeb-b4f8-2719d32d6b01.png" width="450px">
  <li> Lalu, klik Install dan Finish </li>
  <img src="https://user-images.githubusercontent.com/91447664/134871733-3943b7f4-a176-4ad9-8f77-3f7abe615e8b.png" width="450px">
  <li> Untuk melihat apa GIT sudah terinstall atau belum, pergi ke CMD lalu masukan <b>git --version</b> jika sudah terinstall maka tampilannya sbb </li>
  <img alt="Screenshot 2021-09-28 202755" src="https://user-images.githubusercontent.com/91532628/135096108-11cc68f2-532d-4dd0-b066-31b2145a00ce.png">
</ol>

<br><br>
  
<h2> KONFIGURASI GIT </h2>
Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. 
Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Linux atau sejanis (UNIX), 
konfigurasi ini nantinya akan disimpan di $HOME/.gitconfig. Untuk sistem operasi Windows, konfigurasi ini akan disimpan di 
C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email.
<img width="450" alt="Screenshot 2021-09-28 203855" src="https://user-images.githubusercontent.com/91532628/135098001-63d65da7-6681-4261-89a5-81780a39127b.png">

<br><br>

<h2> MENGELOLA REPO SENDIRI </h2>
  <ul>
    <li> Membuat File Repository (Proyek Baru) </li>
      <ol>
        1. Pergi ke Halaman Github, lalu Klik "Start a Project" untuk memulai membuat Proyek Baru.<br>
           <img src="https://user-images.githubusercontent.com/91532628/135106587-47a55557-71bd-44f8-93e9-ad5695386396.png" width="450px"><br>
        2. Setelah itu, akan muncul tampilan dimana anda akan membuat Proyek baru, Lalu Klik "Create Repo".<br>
           <img src="https://user-images.githubusercontent.com/91532628/135107365-135ab664-6db2-4fe3-b063-47b3fa6a86e0.png" width="450px"><br>
        3. Lalu, untuk membuat File maka klik "Creating a new file" berwarna biru.<br>
           <img src="https://user-images.githubusercontent.com/91532628/135108003-f7c28169-f881-4f10-8a20-4b3565ea9a88.png" width="450px"> <br>
        4. Setelah itu anda diberikan keleluasaan untuk membuat proyek yang diinginkan, jika sudah selesai maka klik "Commit new file".<br>
           <img src="https://user-images.githubusercontent.com/91532628/135109111-ce85115d-8615-4c53-9380-645d99cb11c6.png" width="450px"><br>
        5. Anda telah membuat satu Commit<br>
      </ol>
    </li>
  </ul>
Kita dapat mengubah, membuat cabang (branch), menyatukan cabang (merge), dan banyak hal lainnya. Github sendiri memiliki kemampuan untuk
melakukan itu, dan kita dapat melihat siapa, kapan, dan apa saja yang diupdate dalam Repository.
