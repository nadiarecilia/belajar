# kalo udah ada si folder belajar lanjut:
- ls
- cd belajar
- 1s
- cd pert2
- code.
- 1s buat munculin Readme.md
- cd ..
- 1s
- code ke vscode

## TAHAPAN FILE 
- di terminal ubuntu ketikkan apt install g++ gcc -y buat file samplearray.cpp di folder pert1 dan file python.py di folder pert1 isi file samplearray.cpp seperti dibawah ini #include using namespace std;
- int main(){
    int a [5] = {1,2,3,4,5};

    cout << a[0];
    cout << a[1];
    cout << a[2];
    cout << a[3];
    cout << a[4];
    cout << a[5];
    cout << a;
    return 0;
}
- isi file python.py seperti dibawah ini a = 1 b = 2 c = a+b print(c)
- balik ke terminal ubuntu lakukan perintah gcc samplearray.cpp -o samplearray ketikkan ./samplearray (untuk running samplearray.cpp)
- buka terminal ubuntunya ketikkan cd belajar/pert1
- lakukan perintah git add . git commit -m "belajar" git push -u origin main

## FUNGSI DASAR COMMAND LINUX:
- ls			    :Mencantumkan konten direktori
- pwd			    :Menampilkan path direktori kerja saat ini
- cd			    :Mengubah direktori kerja
- mkdir			    :Membuat direktori baru
- rm			    :Menghapus file
- cp			    :Menyalin file dan direktori, termasuk isinya
- mv			    :Memindahkan atau mengganti nama file dan direktori
- touch			    :Membuat file kosong baru
- file			    :Memeriksa jenis file
- zip and unzip	    :Membuat dan mengekstrak arsip ZIP
- tar			    :Mengarsipkan file tanpa kompresi dalam format TAR
- nano, vi, and jed	:Mengedit file dengan editor teks
- cat			    :Mencantumkan, menggabungkan, dan menulis isi file sebagai output standar
- grep			    :Mencari string di dalam file
- sed			    :Menemukan, mengganti, atau menghapus pola dalam file
- head			    :Menampilkan sepuluh baris pertama file
- tail			    :Menampilkan sepuluh baris terakhir file
- awk			    :Menemukan dan memanipulasi pola dalam file
- sort			    :Mengurutkan ulang isi file
- cut			    :Membagi dan menampilkan baris dari sebuah file
- diff			    :Membandingkan isi dari dua file dan perbedaannya
- tee			    :Menampilkan output perintah di Terminal dan file
- locate		    :Menemukan file dalam database sistem
- chmod			    :Memodifikasi izin baca, tulis, dan eksekusi file
- useradd and userdel	:Membuat dan menghapus akun user
- df			:Menampilkan penggunaan ruang disk sistem secara keseluruhan
- du			:Memeriksa penggunaan penyimpanan file atau direktori
- ps			:Membuat snapshot dari semua proses yang berjalan
- ping			:Memeriksa konektivitas jaringan sistem
- wget			:Mendownload file dari URL
- lfconfig		:Menampilkan antarmuka jaringan sistem dan konfigurasinya
