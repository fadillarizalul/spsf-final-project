# spsf-final-project
this is a repository for one of uni course i've taken in 8th semester of my study. which about simulation of covid dynamic movement using agent based modelling for simulation and problem solving in physics

# Project Brief  
**Title** : Pemodelan Dinamika Penyebaran COVID-19 Menggunakan Euler dan RK4 dengan Pendekatan Model SIR  

**Sistem fisis** :  
Dalam hal ini, dapat dibuat model interaksi di antara orang-orang yang serupa dengan 
interaksi fisis dari dua atau lebih partikel atau molekul. Masing-masing mewakili faktor atau 
parameter tertentu yang dapat memberikan pengaruh terhadap keseluruhan model 
penyebaran COVID-19. Dalam pemodelan SIR, sistem seperti ini
dimodelkan sebagai kumpulan entitas pembuat keputusan yang memiliki parameter masing-masing. Model SIR menggunakan model deterministik yang dikembangkan oleh Kermack dan McKendrick pada tahun 1920. Model SIR bergantung pada tiga parameter, yaitu S: jumlah individu dalam populasi yang belum terinfeksi tetapi *susceptible* terhadap infeksi, I: jumlah individu dalam populasi yang terinfeksi, dan R: jumlah individu yang terjangkit penyakit tetapi pulih karena itu telah menjadi kebal terhadap virus serta parameter A: populasi awal dari daerah yang dimodelkan, r: tingkat penularan penyakit atau tingkat di mana seseorang rentan terinfeksi, a: tingkat pemulihan, dan μ: tingkat kematian keseluruhan. Tiap-tiap parameter secara individual menilai situasinya dan membuat keputusan berdasarkan seperangkat 
aturan.  

**Model** :  
Dalam membuat suatu model dinamika yang mempelajari kondisi dinamis di dalam urban, 
salah satunya digunakan simulasi berbasis agen atau disebut Agent-based Modelling (ABM). 
Agent-Based Modelling (ABM) dapat dipakai untuk memodelkan interaksi dalam suatu 
populasi sehingga pengambil keputusan dapat mempelajari bagaimana perubahan kecil 
dalam perilaku dan interaksi dapat mempengaruhi output dalam populasi (Currie et al., 
2020). Menurut Wilensky (1999) dan Yang (2011), salah satu simulasi dengan ABM yang 
dapat dilakukan adalah untuk simulasi penyebaran virus. Hal ini juga diperkuat oleh Currie 
dkk. (2020), bahwa ABM bersifat stokastik sehingga mampu melihat variabilitas perilaku 
manusia.  
Dari Bonabeau (2002), ABM merupakan suatu teknik pemodelan simulasi ketika sebuah 
sistem dimodelkan sebagai kumpulan agen dan terdapat hubungan di antara agen-agen 
tersebut terhadap sistem. ABM menggunakan pendekatan bottom-up untuk menggunakan 
simulasi komputasi untuk melihat bagaimana interaksi perilaku individu mempengaruhi 
perilaku sistem. Elemen utama dari pemodelan ABM adalah agen, dan setiap agen 
berperilaku dan berperilaku sesuai dengan aturan yang dibuat di lingkungan itu. Menurut 
Macal dan North (2010), ABM memiliki tiga komponen: Satu set agen, atribut dan 
perilakunya; Satu set relationship dan metode interaksi yaitu tipologi yang mendasari 
keterhubungan dan mendefinisikan bagaimana dan dengan siapa agen berinteraksi; dan 
Lingkungan (environment) agen. Agen berinteraksi dengan lingkungannya selain dengan 
agen-agen lain.  

**Rancangan Simulasi** :  
Berdasarkan uraian singkat mengenai model di atas, penelitian ini bertujuan untuk melihat
pengaruh parameter dinamika dengan simulasi berbasis agen dan melihat pengaruhnya 
pada hasil simulasi. Secara garis besar proses simulasi wabah COVID-19 dapat digambarkan 
sebagai berikut:  
1. Keadaan awal pathogen sehat (normal), memiliki riwayat penyakit penyerta, dan Orang 
Tanpa Gejala  
2. Di awal simulasi, terdapat agen yang terinfeksi  
3. Secara random, orang lain akan tertular, yang tergantung dari tingkat penularan  
4. Obat yang terinfeksi lebih lama dari masa inkubasi akan memperoleh kekebalan jika 
terdapat OTG, jika tidak maka akan sakit  
5. Agen yang sakit dengan periode sakit dari periode tertentu akan menjadi penderita 
berat. Tergantung pada tingkat keparahan dari yang ditentukan. Juga agen yang sakit 
dapat menjadi pulih dan kebal  
6. Jika ada agen sakit parah saat rumah sakit penuh, bisa meninggal. Namun, jika ada kursi 
kosong yang tersisa, ia akan dirawat di rumah sakit tergantung pada stadium 
penyakitnya, dan kondisi medis akan terjadi. Peluang acak agen parah untuk menjadi 
meninggal tergantung dari tingkat kematian yang ditentukan dan komorbid 12% lebih 
besar berpeluang untuk meninggal. Selain itu, agen yang sakit bisa sembuh dan 
mempunyai imun.  
7. Penguat kekebalan berlangsung selama waktu kekebalan tertentu.
Proses simulasi tersebut dilakukan dengan bantuan software NetLogo (Wilensky, 2020). 
Hasil simulasi dilakukan observasi dengan melihat persentase jumlah agen terdampak, 
persentase jumlah agen meninggal, dan waktu wabah berlangsung. Simulasi dilakukan
secara berulang-ulang agar dapat dilihat variasi-variasi yang ada.  

**Referensi** :  
[1] Bonabeau, E. (2002). *Agent-based modeling: Methods and techniques for simulating human 
systems*. Proceedings of the National Academy of Sciences, 99(suppl 3), 7280-7287. doi: 
10.1073/pnas.082080899  
[2] Currie, Christine S.M., John W. Fowler, Kathy Kotiadis, Thomas Monks, Bhakti Stephan 
Onggo, Duncan A. Robertson & Antuela A. Tako. (2020). *How simulation modelling can help 
reduce the impact of COVID-19*. Journal of Simulation, 14:2, 83-97, DOI: 
10.1080/17477778.2020.1751570  
[3] Yang, C. and Wilensky, U. (2011). *NetLogo epiDEM Travel and Control model*. 
http://ccl.northwestern.edu/netlogo/models/epiDEMTravelandControl. Center for 
Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.  
[4] Wilensky, U. (1999). *NetLogo*. http://ccl.northwestern.edu/netlogo/. Center for Connected 
Learning and Computer-Based Modeling, Northwestern University, Evanston, IL  
