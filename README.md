# Autospy-exercise---1203210107

# Cara Menggubakan Autospy
1. Mendowlod Autopsy 4.21.0/Latest
2. lalu membuat folder Cases.
3. Selanjutnya di dalam folder cases, membuat folder dengan nomor kasus 001 dan menambahkan semacam indikator jenis investigasi, dengan cara itu saya bisa melihat kasus saya yang mungkin tidak menegenali nomor kasusnya tetapi saya dapat mengenali tagnya jadi saya akan memberi tanda H,sedangkan jij ini yaitu tentang tag penyelidik dan XX ini adalah inisialnya anggota penyelidik.
4. Selanjutnya didalam folder 001-H-jij-XX ini akan membuat folder lagi yang terdiri Docs, Image, temp, Autopsy, Reports.
5. Selanjutnya masuk ke dokumen (docs) dan saya akan membuat dokumen teks baru yang berjudul 001-H-jij-XX-doc.txt, Selanjutnya membuat dokumentasi kasus yang dibuka di notepad. untuk memasukkan stempel waktu tekan f5, dan sebelum keluar jangan lupa untuk disimpan.
6. Membuat file di dalam folder image, jadi membuat data yang dicurigai yaitu Exhibit001. selanjutnya klik dua kali pada Exhibit001.
7. Kemudian memindahkan data ke diroktori yang berjudul SuspectData.dd dan selanjutnya menambahkan data SuspectData.ddhashes.txt.
8. Selanjutnya open aplikasi autopsy. lalu klik *new case, Isi case name : 001-H-jij-XX
9. Isi base directory : D:\CASES\001-H-jij-XX\Autopsy (agar siapa pun yang membaca catatan ini melihat bawa catatan itu selalu berada di direktotri yang sama.)
10. Pilih single User, lalu next
11. Selanjutnya isi number :001
    • Name : Indra
    • Phone : isi nomor hp (agar sistem management tau akan menghubungi kesiapa kasus ini )
    • Email : isi email
    • Pilih organization analysis is being done for : CIA
    • Klik finish
12. Pilih specify new host name : Exhibit001, selanjutnya klik next.
13. Klik disk image or VM file : ini itu berada di folder image.
14. Selanjutnya pilih path image : D:\CASES\001-H-jijXX\Image\SuspectData.dd
15. Pilih time zone wilayah sesuai posisi sekarang.
16. Isi hash value
    • md5 : efbf30672c4eb3713b7f639f16944fd3
    • SHA-256 : 6baed29520499d2d5c44c32a0f3a8a08cbe92c47b4e00101b1041d14f9a579e2
Ini ada di SuspectData.dd-hashes.txt
17. Selanjutnya klik file type identification adalah langkah yang memungkinkan pengguna untuk mengatur jenis file yang ingin dicocokkan dalam pengaturan global, sehingga Autopsy dapat mengenali dan mengklasifikasikan file dengan lebih akurat selama proses penyelidikan. Dengan mengatur jenis file yang ingin dicocokkan, pengguna dapat mempersempit atau memperluas ruang lingkup pencarian, meningkatkan efisiensi dalam menemukan bukti digital yang relevan.
18. Selanjutnya di exhibit001 kita dapat melihat gambar dan data mentah dimana dari gambar yang dapat kita lihat ditampilan hex (tampilan ascii). .Klik launch in Hxd untuk menginstall.
19. Penjelasan mengenai search misal kita ke suspectdata keyword lalu search CAT dia akan memunculkan beberapa pilihan cat.
20. Jika sudah kita pilih keyword hits lalu selanjutnya klik single literal keyword serch (disitu akan memunculkan kembali apa yang sudah kita search tadi) yang di suspectdata keyword search.
21. Selanjutnya pada keyword search di cat klik kanan klik add file tag yaitu untuk menambahkan tag file lalu klik bookmark. Pilih tags, selanjutnya pilih bookmark, klik file tags disitu akan muncul yang telah kita bookmark tadi
22. .Selanjutnya pada keyword search di cat klik kanan klik add result tag yaitu untuk menambahkan tag file lalu klik bookmark.
23. .Pilih tags, selanjutnya pilih bookmark, klik result tak disitu akan muncul yang telah kita bookmark tadi. lalu extract file
24. Klik generate report untuk membuat laporan dan apa yang dilakukan pada beberapa jenis laporan yang berbeda.
25. Selanjutnya klik html report kemudian akan memproses data yang dicurigai (suspectdata.dd).
26. Selanjutnya klik spesifik targged result untuk data yang dilaporkan yang dapat melakukan hasil yang diberi tags tertentu selanjutnya akan melakukan hasil yang diberi tags khusus lalu klik centang bookmark dan klik finish untuk mengakhiri.
27. Selanjutnya klik spesifik targged result untuk data yang dilaporkan yang dapat melakukan hasil yang diberi tags tertentu selanjutnya akan
melakukan hasil yang diberi tags.

# Kesimpulan
Autopsy adalah alat forensik digital sumber terbuka yang dirancang untuk membantu investigator forensik dalam menganalisis bukti digital dari perangkat penyimpanan, termasuk hard drive, memori, dan perangkat media lainnya. 






