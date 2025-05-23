A. Konfigurasi dari Sisi JumpCloud
1. Pengaturan Password Awal
Setelah user dibuat secara manual, atur initial password. Aktifkan opsi "User must change password at next login" melalui menu:
User Details → User Security Settings and Permissions → Password Settings
![image](https://github.com/user-attachments/assets/c6207dd9-2482-4365-a0a2-890291e5ace8)

Tujuannya agar user melakukan penggantian password saat pertama kali login ke JumpCloud User Portal.

3. Integrasi dengan Google Workspace
Lakukan binding user manual ke akun Google Workspace yang sesuai, seperti pada ilustrasi berikut (lampiran screenshot jika diperlukan).
![image](https://github.com/user-attachments/assets/c7b699b9-74b4-4735-9589-4d7f809db6d9)

4. Assign ke User Group SSO
Pastikan user yang dibuat manual ditambahkan ke dalam User Group SSO yang telah dikonfigurasi untuk akses ke Google Workspace.
![image](https://github.com/user-attachments/assets/78565c18-8fe3-4951-808f-c964694c4e7a)

5. Simpan Konfigurasi
Setelah seluruh konfigurasi selesai, klik Save.
Catatan: Nonaktifkan opsi pengiriman notifikasi email ke akun email kantor, karena pada tahap ini user belum dapat mengakses email tersebut.
![image](https://github.com/user-attachments/assets/663fa1f0-2588-470f-bba7-4cf3ad68a34a)

B. Konfigurasi dari Sisi Google Workspace (GWS)
Auto-Assign Lisensi
Pastikan lisensi Google Workspace secara otomatis ter-assign ke user baru.

Auto-Assign User Group
Pastikan Konfigurasi agar user baru secara otomatis tergabung dalam grup pengguna yang sesuai di GWS.

C. Langkah Selanjutnya untuk User
Setelah semua konfigurasi selesai, informasikan user untuk mengakses:

JumpCloud User Portal: https://console.jumpcloud.com
![image](https://github.com/user-attachments/assets/9daf6bfd-2f21-4c67-8694-64811e2b41b6)

Informasi akses awal dapat dikirim melalui email pribadi atau saluran komunikasi lain, karena email kantor belum dapat diakses.

User akan diminta untuk mengganti password saat pertama kali login ke portal.
![image](https://github.com/user-attachments/assets/b4d2af42-7d31-46ac-9ebc-49e503df6f8b)


Setelah password diganti, sistem akan melakukan sinkronisasi otomatis dengan akun GWS.
![image](https://github.com/user-attachments/assets/df8a820d-e9c0-4caa-a50c-6e71013d7210)

Dengan demikian, user sudah dapat menggunakan akun Google Workspace melalui SSO (Single Sign-On).









