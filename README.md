# Christian Andrew 05311840000017 dan M Rafi Aldi 05311840000018
## Modul 1 
## Jawaban no 1

Pada soal nomor 1, kita disuruh menyebutkan webserver yang digunakan pada ```testing.mekanis.me``` yang tedapat pada file wireshark yang sudah diberikan. 
Disini, . Cara untuk mendapatkan nya pertama kita harus melakukan ping terhadap ```testing.mekanis.me``` dimana didapat ip nya adalah ```“157.245.50.224”``` dan setelah itu kita bisa melakukan pencarian ip pada wireshark dan kita pilih protocol HTTP untuk mendapatkan informasi mengenai webserver yang digunakan. Filter yang digunakan ```“ip.src == 157.245.50.224”``` Dan kami menemukan bahwa jawaban untuk webserver yang digunakan adalah nginx/1.14

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765910611740590080/unknown.png)

## Jawaban no 2 

Soal no 2 mengharuskan kita menyimpan gambar dengan nama file ```"Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"``` Pertama tama yang harus kita lakukan ialah Lakukan filter ```“http.response”``` untuk mendapatkan response dari server dan langsung cari yang mempunyai kata (PNG) dimana memuat gambar, setelah itu langsung export dan kita pilih nama file yang sesuai.

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765920266307764274/unknown.png)

## Jawaban no 3
