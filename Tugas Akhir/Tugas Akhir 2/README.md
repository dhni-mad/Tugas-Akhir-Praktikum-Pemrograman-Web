# Penjelasan Tugas Akhir 2

Alur Kerja (Workflow) dari tugas akhir ini sebagai berikut:
1. Commit Awal
   Pada Tahap ini Saya menambahkan file-file utama dari proyek Portofolio yaitu: index.html dan style.css
   
2. Melakukan Commit Bertahap (Feature Commits)
   Kemudian proyek portfolio dilanjutkan di branch main. Setiap penambahan section disimpan sebagai commit terpisah yang mana:
   a. Pertama, penambahan "section tentang saya".
   b. Kedua, penambahan "section proyek".
   c. Ketiga, penambahan "section keahlian dan kontak".

3. Pembuatan Branch untuk Melakukan Perubahan
   Untuk melakukan modifikasi tanpa mengganggu kode utama yang stabil, branch baru dibuat dengan nama "perubahan". Alur kerja kemudian dipindahkan ke branch perubahan ini.

4. Pengerjaan di Branch Terpisah
   Pada branch perubahan, saya melakukan perubahan pada "Tugas Akhir 2/index.html" untuk "ubah info kontak". Perubahan ini kemudian disimpan sebagai commit baru hanya di dalam branch perubahan.

5. Penggabungan Branch (Merge)
   Setelah saya selesai, maka pindah ke branch main. Kemudian melakukan perintah merge untuk menggabungkan semua riwayat commit dari branch perubahan ke main.

6. Push ke GitHub
   Terakhir, repository lokal yang sudah terbarui di branch main (termasuk semua commit bertahap dan hasil merge) dikirim (push) ke GitHub, sehingga antara kode lokal dan di gitbuh sudah tersinkron atau sama. 

Berikut Hasil ScreenShot dari perintah git log --graph --oneline:

<img width="960" height="778" alt="Screenshot 2025-11-05 200552" src="https://github.com/user-attachments/assets/d441df33-34c7-40cb-99a7-378eab444367" />

<img width="956" height="438" alt="Screenshot 2025-11-05 200603" src="https://github.com/user-attachments/assets/54671747-05fd-4179-aeb0-2deea2d7f9d6" />

<img width="952" height="465" alt="Screenshot 2025-11-05 200612" src="https://github.com/user-attachments/assets/16b36df8-f755-4dc4-8573-590293108279" />

<img width="965" height="458" alt="Screenshot 2025-11-05 200621" src="https://github.com/user-attachments/assets/5279d33b-1118-4d1c-b93e-4b290394a300" />

<img width="937" height="465" alt="Screenshot 2025-11-05 200630" src="https://github.com/user-attachments/assets/4082b0e1-db63-4008-a58b-5cc9cda86e0e" />
