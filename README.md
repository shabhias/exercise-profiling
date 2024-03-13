<h1>First Profiling</h1>
<a href="https://ibb.co/C5S9yVm"><img src="https://i.ibb.co/27pMrcW/test-plan1.png" alt="test-plan1" border="0"></a>
<a href="https://ibb.co/SQWTrLZ"><img src="https://i.ibb.co/Q8zBd5x/all-student-names.png" alt="all-student-names" border="0"></a>
<a href="https://ibb.co/SxS30mR"><img src="https://i.ibb.co/N3RypNZ/highest-gpa.png" alt="highest-gpa" border="0"></a>
<a href="https://ibb.co/HNkkJ4f"><img src="https://i.ibb.co/8zSShsL/testresult1.png" alt="testresult1" border="0"></a>
<a href="https://ibb.co/DCktGLJ"><img src="https://i.ibb.co/MVps89v/testresult2.png" alt="testresult2" border="0"></a>
<a href="https://ibb.co/LNymZfG"><img src="https://i.ibb.co/wcqVz1v/testresult3.png" alt="testresult3" border="0"></a>


<h1>Execution Time Before Refactoring</h1>

<a href="https://ibb.co/wJytWMq"><img src="https://i.ibb.co/ZHd98Wr/before-refactoring1.png" alt="before-refactoring1" border="0"></a>
<a href="https://ibb.co/Jk53WHr"><img src="https://i.ibb.co/PCwDsg1/before-refactoring2.png" alt="before-refactoring2" border="0"></a>
<a href="https://ibb.co/nBYYLjW"><img src="https://i.ibb.co/G9885Rh/before-refactoring3.png" alt="before-refactoring3" border="0"></a>


<h1>Execution Time After Refactoring</h1>

<a href="https://ibb.co/8KBKNN7"><img src="https://i.ibb.co/K0G0bbr/after-refactoring1.png" alt="after-refactoring1" border="0"></a>
<a href="https://ibb.co/51xszCv"><img src="https://i.ibb.co/Gd3C1Gk/after-refactoring2.png" alt="after-refactoring2" border="0"></a>
<a href="https://ibb.co/db2xC3t"><img src="https://i.ibb.co/8z5tvRb/after-refactoring3.png" alt="after-refactoring3" border="0"></a>


<h1>Second Polling</h1>

<a href="https://ibb.co/sQW48KN"><img src="https://i.ibb.co/ftDWjky/testresult1-after.png" alt="testresult1-after" border="0"></a>
<a href="https://ibb.co/0mx5HRw"><img src="https://i.ibb.co/9c7PQkM/testresult2-after.png" alt="testresult2-after" border="0"></a>
<a href="https://ibb.co/PGQGdFZ"><img src="https://i.ibb.co/8gcgHND/tesresult3-after.png" alt="tesresult3-after" border="0"></a>


<h1>REFLECTION</h1>

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
    -  JMeter menggunakan simulasi tindakan pengguna untuk menilai respons aplikasi, fokus pada aspek seperti waktu respons, throughput, dan penggunaan sumber daya. Ini membantu dalam mengidentifikasi area yang perlu perbaikan, meskipun hanya memperhatikan respons secara umum tanpa memahami detail operasi aplikasi. Di sisi lain, dengan IntelliJ Profiler, profil aplikasi secara rinci dianalisis, memungkinkan identifikasi bagian kode yang memakan waktu dan pemahaman lebih mendalam tentang kinerja aplikasi, termasuk pola penggunaan memori dan beban kerja CPU. Informasi yang diperoleh dari profiling memungkinkan optimisasi pada bagian kode yang berdampak signifikan terhadap kinerja aplikasi.

2. How does the profiling process help you in identifying and understanding the weak points in your application?
    - Profiling membantu dalam mengetahui dan memahami alur kode dalam aplikasi dengan memonitor runtime, termasuk penggunaan CPU, alokasi memori, pemanggilan metode, dan aktivitas thread. Dengan menganalisis data ini, kita dapat menunjukkan ketidakefisienan, bottlenecks, atau konsumsi sumber daya yang berlebihan. Alat-alat profiling menawarkan representasi visual dari alur runtime aplikasi, memfasilitasi identifikasi jalur kode yang bermasalah dan memungkinkan pengoptimalan yang ditargetkan.
   
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
    - Ya, IntelliJ Profiler dapat membantu pengembang dalam menganalisis dan mengenali masalah kinerja dalam kode aplikasi mereka. Sebagai contoh, dalam tutorial dan latihan pada modul 5 ini, kita dapat memperhatikan bahwa beberapa metode memiliki kinerja yang lebih lambat. Dengan kemampuan Profiler untuk menampilkan durasi setiap baris kode, kita dapat dengan mudah mengidentifikasi bagian program yang menjadi penyebab kemacetan atau bottlenecks.
   
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
    - Salah satu tantangannya adalah membaca hasil output dan membandingkannya dengan output sebelumnya. Dalam profil, informasi yang ditampilkan bisa sangat banyak, sehingga memerlukan kesabaran dan kecermatan. Rekaman hasil sebelumnya, seperti screenshot atau snapshot, dapat membantu dalam membandingkan hasil. Untuk mengatasi tantangan ini, diperlukan kesabaran, ketelitian, dan keterampilan menggunakan alat-alat tersebut.
   
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
    - Dengan menggunakan IntelliJ Profiller ini, proses profiling sudah terintegrasi langsung dengan keseluruhan lingkungan pengembangan (IDE). Ini membuat kita lebih mudah dalam mengidentifikasi bagian kode yang menjadi penyebab bottlenecks.
   
6. How do you handle situations where the results from profiling with Inte	lliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
    - langkah utama adalah memeriksa kembali metode pengujian dan skenario yang digunakan dalam kedua alat tersebut. Selain itu, kita perlu membandingkan metrik yang diukur oleh kedua alat untuk mengidentifikasi penyebab perbedaan.
   
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
    - Setelah menganalisis, kita juga harus memeriksa durasi program menggunakan JMeter. Jika saya menemukan waktu eksekusi yang berlebihan, saya akan mengidentifikasi bagian kode yang bertanggung jawab dan melakukan optimalisasi. Penting bagi saya untuk memastikan bahwa perubahan yang saya lakukan tidak mengganggu fungsionalitas aplikasi dengan melakukan perbandingan antara output sebelum dan setelah modifikasi.
