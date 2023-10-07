<style> 
body{ 
    background-color: #24292e; 
    color: #fff;
} 
</style> 


[back](./index.md)

# Pengertian HTML
Elemen HTML ditentukan oleh tag awal, beberapa konten, dan tag akhir:
```html
<tagname> Content goes here... </tagname>
```

Elemen HTML adalah segalanya mulai dari tag awal hingga tag akhir:
```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

# Struktur Dokumen HTML
Dokumen HTML dimulai dengan tag `<html>` dan diakhiri dengan tag `</html>`. Dokumen HTML dibagi dalam dua bagian `head` yang ada didalam tag `<head>` dan `</head>`, dan bagian `body` yang ada di dalam tag `<body>` dan `</body>`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

1. `<!DOCTYPE html>`
    Tag untuk memberitahu broser bahwa dokumen ada lah dokumen HTML
1. `<html lang="en">`
    tag awal html, attribute `lang="en"` artinya bahasa yang di pakai adalah English.
1. `<head>`
    tag yang menunjukkan bagian *kepala* dari dokumen HTML. Bagian kepala tidak akan dimunculkan di broser.  
    Dibagian kepala kalian bisa memasukkan tag meta seperti `<meta charset="UTF-8">` untuk mendifinisikan karakter yang dipakai yaitu format UTF-8 , `<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk mendifinikan tampilan konten yaitu lebar selebar device dengan sekala 1x, dan lain-lain.  
    Di Sana kita juga bisa memasukkan tag `<title>` untuk mendifinisikan judul halaman, `<link>` biasanya dipakai untuk mendifinisikan link CSS, dan `<script>` untuk mendifinisikan link JS.
1. `<body>`
    tag yang menunjukkan bagian *badan* dari dokumen HTML. Bagian ini yang akan ditampilkan di broser. Dibagian ini kita menuliskan tag-tag html yang akan ditampilkan.  
    Di Body juga bisa di masukkan tag `<script>` untuk mendifinisikan link JS.

[back](./index.md)
