# Tugas-sistem-operasi-6
1.Eksekusi seluruh profile yang ada :
a.Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 08-58-11" src="https://github.com/user-attachments/assets/61325793-402a-4c68-95af-0b8f6ab68033" />
b.Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 09-14-16" src="https://github.com/user-attachments/assets/37370817-eecb-4644-aed4-ba513e55d0cf" />
c.Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai
berikut:
<img width="1214" height="768" alt="Screenshot from 2026-10-13 09-19-51" src="https://github.com/user-attachments/assets/f54fc104-4e18-4213-8ed9-971345b95925" />

2.Prompt String (PS)
a.Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan
dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal
oleh semua shell
<img width="1214" height="768" alt="Screenshot from 2026-10-13 09-24-58" src="https://github.com/user-attachments/assets/a45fa5ad-fcc6-4f15-9e69-4a7ed8f4a5c0" />
b.Eksperimen hasil PS1 :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 09-37-27" src="https://github.com/user-attachments/assets/5287c085-3735-42df-aaff-648499894dbc" />

3.Logout
Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi
logout
<img width="1214" height="768" alt="Screenshot from 2026-10-13 09-45-43" src="https://github.com/user-attachments/assets/71a25c0d-7a78-4571-aeef-290db0500148" />

4.Bash script

a.Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-10-46" src="https://github.com/user-attachments/assets/232d2927-6519-40a4-a920-ba6ce6de533e" />
b.Jalankan script tersebut sebagai berikut :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-11-40" src="https://github.com/user-attachments/assets/7f969e42-6f7f-4b61-bd34-bb85f0c21566" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-12-01" src="https://github.com/user-attachments/assets/dc722941-5bf7-44af-817b-645fcb2924b8" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-13-56" src="https://github.com/user-attachments/assets/6585bdf6-7d5a-43f2-8a84-3ff7935c140d" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-14-26" src="https://github.com/user-attachments/assets/2fa9fe01-7115-4be9-9dc8-ee2d9c1eaa13" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-15-58" src="https://github.com/user-attachments/assets/c2e77920-607d-412c-916b-4ab8052bf3f2" />

5.Jobs
 a.Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-21-38" src="https://github.com/user-attachments/assets/4be46ecf-32ca-4c27-9543-cb47dd5277fa" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-20-38" src="https://github.com/user-attachments/assets/1ad8a250-be72-4fd8-af96-4dda5ba68407" />
b.Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-24-08" src="https://github.com/user-attachments/assets/c95acadf-ab8e-4bdf-800a-0a79bf2fd386" />
c.Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-28-28" src="https://github.com/user-attachments/assets/48d6d438-5e6f-478b-b1e6-80eea7062645" />
d.Stop program background dengan utilitas kill
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-30-12" src="https://github.com/user-attachments/assets/5ef018b5-ab8d-45a0-b5d5-f5637e2c35b2" />
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-30-40" src="https://github.com/user-attachments/assets/33bafda0-29c9-47cd-97d4-4153709a8df4" />

6.History
 a.Ganti nilai HISTSIZE dari 1000 menjadi 20
 <img width="1214" height="768" alt="Screenshot from 2026-10-13 10-33-56" src="https://github.com/user-attachments/assets/2b740acf-1e98-434c-bb76-e83ab0812cb9" />
b.Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-37-12" src="https://github.com/user-attachments/assets/b69ba539-5e93-4ba7-a721-928c58ab3621" />
c.Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-40-27" src="https://github.com/user-attachments/assets/2ba9f681-041f-451f-836b-63f903d0e78c" />
d.Ulangi instruksi pada history bufer nomor 150
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-42-02" src="https://github.com/user-attachments/assets/f7348030-e3d3-4d9f-8692-593d46580bf0" />
e.Ulangi instruksi dengan prefix “ls”
<img width="1214" height="768" alt="Screenshot from 2026-10-13 10-43-12" src="https://github.com/user-attachments/assets/505e39aa-ae5b-4a06-9b56-10589beeae79" />

















