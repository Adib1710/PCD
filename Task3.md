# Grayscale

terdapat tiga macam metode algoritma untuk mengubah nilai R G B menjadi Grayscale. Baiklah, mari kita kupas satu per satu : 

## Lightness
Algoritmanya adalah mencari nilai tertinggi dan terendah dari nilai R G B, kemudian nilai tertinggi dan terendah tersebut dijumlahkan lantas dikalikan dengan 0.5. Secara matematis dapat dirumuskan :
Grayscale = (max(R,G,B)) + (min(R,G,B)) * 0.5

##Average
Algoritmanya adalah dengan menjumlahkan seluruh nilai R G B, kemudian dibagi 3, sehingga diperoleh nilai rata-rata dari R G B, nilai rata-rata itulah yang dapat dikatakan sebagai grayclase. Rumus matematisnya adalah :
Grayscale = (R + G + B) / 3

## Luminosity
Algoritmanya adalah dengan mengalikan setiap nilai R G B dengan konstanta tertentu yang sudah ditetapkan nilainya, kemudian hasil perkalian seluruh nilai R G B dijumlahkan satu sama lain. Rumus matematisnya adalah :
Grayscale = (0.21 * R) + (0.72 * G) + (0.07 * B)

# Halftoning

Digital halftoning adalah suatu proses untuk mengkonversi citra yang kontinu ke dalam suatu array berupa titik-titik. Jika dilihat oleh sistem visual manusia, pola tersebut akan menciptakan suatu ilusi sehingga citra tersebut tampak bukan seperti citra hitam putih, namun seperti citra abu-abu yang kontinu.

Halftoning bertujuan untuk memberikan kesan warna citra biner tampak seperti citra abu-abu meskipun hanya menggunakan piksel warna hitam dan putih saja.

# Dithering
Dithering adalah proses halftoning pixel dari dua warna untuk menciptakan ilusi bahwa warna ketiga hadir.
