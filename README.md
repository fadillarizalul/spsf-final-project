# spsf-final-project
this is a repository for one of uni course i've taken in 8th semester of my study. which about simulation of covid dynamic movement for simulation and problem solving in physics

# Project Brief  
**Title** : Pemodelan Dinamika Penyebaran COVID-19

**Sistem fisis** :  
Dalam hal ini, dapat dibuat model interaksi di antara orang-orang yang serupa dengan 
interaksi fisis dari dua atau lebih partikel atau molekul. Masing-masing mewakili faktor atau 
parameter tertentu yang dapat memberikan pengaruh terhadap keseluruhan model 
penyebaran COVID-19. Dalam pemodelan SIR, sistem seperti ini
dimodelkan sebagai kumpulan entitas pembuat keputusan yang memiliki parameter masing-masing. Model SIR menggunakan model deterministik yang dikembangkan oleh Kermack dan McKendrick pada tahun 1920. Model SIR bergantung pada tiga parameter, yaitu S: jumlah individu dalam populasi yang belum terinfeksi tetapi *susceptible* terhadap infeksi, I: jumlah individu dalam populasi yang terinfeksi, dan R: jumlah individu yang terjangkit penyakit tetapi pulih karena itu telah menjadi kebal terhadap virus serta parameter A: populasi awal dari daerah yang dimodelkan, r: tingkat penularan penyakit atau tingkat di mana seseorang rentan terinfeksi, a: tingkat pemulihan, dan μ: tingkat kematian keseluruhan. Tiap-tiap parameter secara individual menilai situasinya dan membuat keputusan berdasarkan seperangkat 
aturan.  

**Model** :  


**Rancangan Simulasi** :  


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

**UPDATES**  
[5] http://etheses.uin-malang.ac.id/4054/1/09610075.pdf  
[6] https://journal.unpak.ac.id/index.php/komputasi/article/download/3623/2422  
[7] https://repository.its.ac.id/329/3/1212100095-Undergraduate_Theses.pdf  
[8] https://core.ac.uk/download/pdf/154762681.pdf  

	Latar Belakang
	Rumusan Masalah
Berdasarkan latar belakang masalah tersebut, permasalahan yang dapat dirumuskan yaitu sebagai berikut
	Bagaimana membangun model SIR untuk dinamika Covid-19?
	Bagaimana analisis model SIR untuk dinamika Covid-19?
	Bagaimana penerapan simulasi model SIR untuk dinamika Covid-19 menggunakan bahasa pemrograman Python?
	Batasan Masalah
Berdasarkan rumusan masalah di atas, batasan yang dapat dirumuskan yaitu sebagai berikut
	Pada penelitian ini, akan diformulasikan model tanpa adanya pengaruh vaksinasi serta melakukan analisis kestabilan pada kasus Covid-19 dengan model SIR (Susceptible, Infected, Recovered). Lalu dilakukan simulasi untuk model tersebut.
	Angka kelahiran dan angka kematian diasumsikan sama.
	Data yang akan digunakan untuk simulasi model adalah data kasus Covid-19 tahun 2022 di provinsi Jawa Barat
	Tujuan Penelitian
Tujuan dari dilakukannya penelitian ini yaitu sebagai berikut
	Mengetahui cara membangun model SIR untuk dinamika Covid-19
	Mengetahui analisis model SIR untuk dinamika Covid-19
	Mengetahui implementasi hasil simulasi model SIR untuk dinamika Covid-19 menggunakan bahasa pemrograman Python
	Teori Covid-19
	Runge Kutta 4
Metode Runge Kutta 4 merupakan pengembangan dari metode Euler, yang mana perhitungan penyelesaian masalah matematis dilakukan Langkah demi Langkah. Dinyatakan dalam suatu persamaan diferensial berikut.
Type equation here.
Dengan titik pendekatan awal yaitu pada titik (x_0,y_0). Berdasarkan dari metode Euler, nilai fungsi penyelesaian diperoleh sebagai berikut
Type equation here.
