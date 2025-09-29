**Konteks**

Dalam industri perfilman, kualitas data mengenai film sangat penting dan sangat diperlukan untuk menghasilkan analisis yang akurat, baik untuk pengambilan keputusan bisnis, analisis kesuksesan film, dan lainnya. Dataset yang berisi informasi film seperti genre, nama sutradara, durasi, dan skor IMDb, seringkali masih memiliki masalah berupa missing value, data duplikat, maupun format yang tidak konsisten. Pentingnya preprocessing yang baik sebelum melakukan suatu analisis, sehingga tidak menghasilkan kesimpulan yang keliru.

**Problem statement**

Perusahaan menghadapi tantangan dalam menyiapkan data film agar bersih dan siap digunakan untuk analisis lebih lanjut. Dataset yang dimiliki masih mengandung permasalahan seperti nilai yang hilang (missing values), duplikasi data, nilai negatif pada kolom numerik, serta keberadaan variabel kategorikal yang belum dapat langsung diproses oleh algoritma machine learning.
Dengan memahami permasalahan tersebut, divisi analisis data ditugaskan untuk melakukan tahapan preprocessing data yang meliputi penanganan missing values, koreksi data, standarisasi, normalisasi, serta transformasi variabel kategorikal menjadi dummy variables. Hal ini bertujuan agar dataset lebih konsisten, akurat, dan siap digunakan pada tahap analisis berikutnya.

**Tujuan**

Maka berdasarkan konteks dan permasalahan tersebut, perusahaan membutuhkan kemampuan untuk melakukan preprocessing data film sehingga dataset yang awalnya kotor dapat dibersihkan dan distandarisasi. Dengan preprocessing yang tepat, data akan lebih mudah dipahami, dianalisis, dan digunakan sebagai input model prediksi.
Selain itu, perusahaan juga ingin mengetahui variabel-variabel apa saja yang memerlukan perhatian khusus dalam tahap pembersihan data, sehingga kualitas data dapat terjaga dan hasil analisis yang dilakukan di tahap selanjutnya lebih dapat diandalkan.

**Dataset**

Berikut merupakan variabel yang terdapat dalam dataset.

•	Color: jenis film berwarna atau tidak

•	Director_name: nama sutradara

•	Duration: durasi film (menit)

•	Gross: pendapatan kotor (USD)

•	Genres: genre film

•	Movie_title: judul film

•	Title_year: tahun pembuatan film

•	Language: bahasa yang digunakan dalam film

•	Country: negara pembuatan film

•	Budget: biaya pembuatan film

•	Imdb_score: skor IMDb

•	Actors: nama aktor

•	Movie_facebook_likes: jumlah like di Facebook

Data yang dimiliki mencakup berbagai variabel yang berkaitan dengan karakteristik dan performa film. Setiap baris dalam dataset mewakili informasi tentang satu film, sementara setiap kolom merepresentasikan atribut atau fitur tertentu yang dapat digunakan untuk menganalisis atau memprediksi tingkat keberhasilan film. Dengan memahami data ini, dapat dilakukan preprocessing yang tepat untuk memastikan dataset bersih, konsisten, dan siap digunakan pada tahap analisis selanjutnya.

