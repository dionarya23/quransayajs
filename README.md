# QuranSaya.JS
QuranSaya.Js merupakan sebuah plugin jQuery, yang dapat menampilkan terjemahan ayat-ayat suci Al-Quran pada sebuah website

Untuk demo dan contoh pemakaian anda bisa dilihat di https://dionarya6661.github.io/quransayajs

### Instalasi
Pertama anda perlu file jquery dan quransaya.js dan kemudian letakan kedua file tersebut seperti ini:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="quransaya.js"></script>
```

### Cara Penggunaan
untuk pegunaan sangat mudah sekali perhatikan kode berikut:

```html
<div id="selector">
</div>

<script>
//kode berikut ini nanti nya akan menampilkan ayat dari Surat Al-Baqarah ayat 255
$('#selector').quransaya({
  surat: 2, //dapat diisi dengan angka 1 sampai 114
  ayat: 255
  });
</script>
```

Catatan: untuk parameter surat anda dapat mengisi nya dengan no 1 sampai 114 sesuai dengan jumlah surat yang ada pada Al-Qur'an.

### Mempercantik Tampilan
Untuk mempercantik tampilan anda bisa menambahkan file quransaya.css pada web anda dan anda juga bisa mengatur warna background pada tampilan text seperti ini:
```html
<link rel="stylesheet" href="quransaya.css">

<div id="selector"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="quransaya.js"></script>
<script>
$('#selector').quransaya({
  surat: 2, //dapat diisi dengan angka 1 sampai 114
  ayat: 255,
  warna: 'green' //untuk warna anda dapat memilih, ada 19 warna yang sudah disediakan
  });
</script>
```

### Daftar Warna

* amber
* aqua
* light-blue
* brown
* cyan
* blue-gray
* green
* light-green
* indigo
* khaki
* lime
* orange
* deep-orange
* pink
* purple
* red
* sand
* teal
* yellow

### PERHATIAN
Semua data berasal dari website https://quransaya.id, Insyaallah semua data akurat namun jika anda mememukan kesalahan data anda dapat menghubungi di email quransaya.id@gmail.com
