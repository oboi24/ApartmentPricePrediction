Apartemen menjadi salah satu jawaban atas kebutuhan perumahan masyarakat modern karena keterbatasan lahan hunian dan padatnya aktivitas bisnis di kawasan perkotaan. Oleh karena itu, sangat menarik untuk mengkaji harga apartemen yang dipengaruhi oleh berbagai faktor internal dan eksternal.

Individu atau perusahaan biasanya membuat penawaran unit apartemen. Pihak yang menawarkan dapat menjual unit di platform dengan menentukan harga apartemen mereka. Cara tersebut cukup sulit bagi pemilik apartemen untuk menyesuaikan harga dengan harga pasar. Jika harga terlalu tinggi dibandingkan dengan harga pasar, tentu akan sulit untuk melakukan penjualan. Sebaliknya, jika terlalu rendah, pemilik akan kesulitan mendapatkan keuntungan maksimal.

Daegu merupakan salah satu kota terbesar dan termasuk kota metropolitan yang ada di Korea Selatan, bahkan menjadi kota ke-4 yang meiliki populasi tertinggi setelah Seoul, Busan, dan Incheon, dengan jumlah populasi sebesar 2,5 juta jiwa atau sebesar 4% dari total 51,7 juta jiwa penduduk Korea Selatan (source : Wikipedia). Dengan populasi yang tinggi, kebutuhan masyarakat kota Daegu akan hunian dalam hal ini apartement juga menjadi cukup tinggi, baik itu untuk dimiliki atau untuk disewa.

* *Problem Statement*

1. *Stakeholder* → Agen Properti / Pengembang kepada calon *customer* / pembeli.

2. *Problem* → Agen properti memiliki kesulitan dalam menentukan harga penjualan setiap unit. Penentuan harga berdasarkan tahun dan luas unit, akses serta lokasi strategis terhadap fasilitas kota, area kampus dan perkantoran.

3. *Problem Solving* → Penentuan harga jual yang kurang tepat akan menyebabkan kerugian kepada perusahaan dikarenakan unit tidak laku terjual konsumen tidak tertarik untuk membeli unit.

* *Goals*

1. Analisa dan identifikasi faktor-faktor apa saja yang mempengaruhi harga penjualan apartemen serta memberikan *insight* kepada *stakeholder* terkait penjualan di bidang *real estate*.

2. Analisa terukur dengan pemodelan prediktif Mean Absolute Error (MAE) sebagai acuan untuk akurasi harga yang akan dijadikan prediksi penjualan.

Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan.

Selain itu, kita juga bisa menggunakan nilai R-squared atau adj. R-squared jika model yang nanti terpilih sebagai final model adalah model linear. Nilai R-squared digunakan untuk mengetahui seberapa baik model dapat merepresentasikan varians keseluruhan data. Semakin mendekati 1, maka semakin fit pula modelnya terhadap data observasi. Namun, metrik ini tidak valid untuk model non-linear.
