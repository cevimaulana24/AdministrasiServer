1. unduh dan Instal Putty di https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
![alt text](image.png)

2. Konversi ekstensi Private Key dari .pem menjadi .ppk
Buka Putty Gen
Muat Kunci Pribadi .pem
Klik Save Private Key ekstensi menjadi File .ppk
![alt text](image-1.png)

3. Cara Mengatur SSH Jarak Jauh dengan Putty
isi alamat IPv4 Data publik berasal dari instance masing2
port SSH (22)
muat kunci pribadi .ppk di menu Koneksi->SSH->Otorisasi->Kredensial
pengguna dari instance masing-masing (ubuntu)
![alt text](image-2.png)

4. Setiap awal Remote kita melakukan Patching OS
sudo apt-get update && sudo apt-get upgrade

5. coba instalasi melakukan Web Server dalam keadaan Kosong
![alt text](image-3.png)

instal salah satu web server sudo apt install nginx
![alt text](image-4.png)