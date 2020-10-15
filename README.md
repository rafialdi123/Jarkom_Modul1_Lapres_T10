# Christian Andrew 05311840000017 dan M Rafi Aldi 05311840000018
## Modul 1 
## Jawaban no 1

Pada soal nomor 1, kita disuruh menyebutkan webserver yang digunakan pada ```testing.mekanis.me``` yang tedapat pada file wireshark yang sudah diberikan. 
Disini, . Cara untuk mendapatkan nya pertama kita harus melakukan ping terhadap ```testing.mekanis.me``` dimana didapat ip nya adalah ```“157.245.50.224”``` dan setelah itu kita bisa melakukan pencarian ip pada wireshark dan kita pilih protocol HTTP untuk mendapatkan informasi mengenai webserver yang digunakan. Filter yang digunakan ```“ip.src == 157.245.50.224”``` Dan kami menemukan bahwa jawaban untuk webserver yang digunakan adalah nginx/1.14

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765910611740590080/unknown.png)

## Jawaban no 2 

Soal no 2 mengharuskan kita menyimpan gambar dengan nama file ```"Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"``` Pertama tama yang harus kita lakukan ialah Lakukan filter ```“http.response”``` untuk mendapatkan response dari server dan langsung cari yang mempunyai kata (PNG) dimana memuat gambar, setelah itu langsung export dan kita pilih nama file yang sesuai.

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765920266307764274/unknown.png)

Dan didapat hasil export nya adalah gambar berikut

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765920589856374814/unknown.png)

## Jawaban no 3

Pada Soal no 3, soalnya meminta untuk kita mencari tahu username beserta password untuk login ke website ```ppid.dpr.go.id``` Yang harus kita lakukan adalah pertama tama kita harus filter kata kata yang mengandung login menggunakan filter ```“http.request.uri contains "login"”``` dan kita bisa langsung mencari yang bertuliskan ```POST``` dan scroll maka kita akan mendapatkan username dan passwordnya dimana username nya adalah ```“10pemuda”``` dan password nya ```“guncangdunia”.```

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765922221771456532/unknown.png)

## Jawaban no 4

Kita diminta untuk menemukan paket dari web web yang menggunakan basic authentication method, disini kita tinggal masukkan perintah pada filter ```ip.src == 157.245.50.224``` dan langsung kita menemukan paketnya. 

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765928067759341589/unknown.png)

## Jawaban no 5

Kita diminta untuk melakukan perintah pada web ```aku.pengen.pw``` namun sebelum itu kita harus mempunyai username dan password untuk masuk pada web tersebut. Langkah yang kita gunakan untuk menemukan itu adalah pertama tama yaitu masukkan perintah pada filte ```ip.src == 157.245.50.224 || ip.dst == 157.245.50.224``` lalu pada bagian ```Credentials``` akan tertera username dan password nya 

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765949066013704232/unknown.png)

Dan lalu anda bisa masuk pada web nya 

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/765949797219041300/unknown.png)

## Jawaban no 9

No 9 meminta kita untuk menemukan username dan password untuk login FTP pada localhost, disini kami menemukan bahwa ...

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/766188124685860874/unknown.png)

saat membuka FTP ada tertera disitu ```username:dhana pass:dhana123``` 

## Jawaban no 10

Pada nomor 10 kita diminta untuk mencari file pdf dengan lokasi tersembunyi dan mendonwnloadnya dan pada soal kita diberi clue yaitu ```25 50 44 46```
Kita pertama tama masukkan ```tcp.stream eq 15``` pada filter dan pindah ke filter hex value dan masukkan kode 25 50 44 46 dan nanti akan ketemu file yang diinginkan tinggal di export lalu buka file pdf nya

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/766189145449562142/unknown.png)

Dan nanti file yang dicari akan berbentuk seperti ini, VOILAA

![Imagedescription](https://cdn.discordapp.com/attachments/691256969876471811/766189174251847700/unknown.png)

## Jawaban no 11

