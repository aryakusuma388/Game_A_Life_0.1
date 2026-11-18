A Life: aturan dan mekanisme permainan

Informasi ini saya susun dari membaca kode versi terbaru, termasuk perubahan yang kita buat tadi. Angka-angkanya sesuai kode, tetapi keseimbangan permainannya belum diuji main panjang.

1. Konsep dan tujuan

A Life adalah simulasi peradaban yang berjalan sendiri. Anda memulai dengan 2–3 manusia purba di peta 160×160 dan mengantar mereka melewati 10 zaman sampai Modern & Digital. Warga dikendalikan AI, jadi Anda tidak memerintah mereka langsung. Anda mengarahkan lewat wilayah, cetak biru bangunan, dan hasil musyawarah mereka.

Menang berarti mencapai zaman ke-10, lalu muncul layar kemenangan dan Anda boleh lanjut bermain. Tidak ada kondisi kalah resmi, tetapi peradaban bisa punah kalau semua warga mati.

2. Waktu dan lingkungan
Kecepatan: x1, x3, x8, atau jeda.
Tahun usia: 1 tahun = 40 detik permainan.
Hari: 120 detik per hari, dan sekitar 45% di antaranya malam.
Musim: Semi, Panas, Gugur, Dingin, masing-masing 30 detik. Di musim dingin warga yang tidak dekat api unggun atau tidak punya rumah kedinginan: energi dan kebahagiaan turun, dan di zaman awal nyawa ikut turun.
Medan: laut, pantai, rumput, gurun, gunung, dan salju. Rumput punya pohon dan semak beri, gurun punya kaktus, gunung punya batu.
Kabut: peta tertutup kabut dan terbuka lewat penjelajahan warga.
3. Warga
Tahap usia: anak (di bawah 13), remaja (13–17), dewasa (18–54), lansia (55 ke atas). Kekuatan dan kelincahan anak tumbuh bertahap, dan lansia melemah tetapi lebih pintar. Peluang meninggal karena usia naik setelah 62 tahun, dan batas mutlaknya 90 tahun.
Atribut: kecerdasan, kekuatan, kelincahan, dan keinginan bersosialisasi. Anak mewarisi rata-rata sifat orang tuanya dengan sedikit variasi.
Kebutuhan: nyawa, kenyang, energi, senang, marah, dan takut.
Kelaparan: kenyang 0 selama 40 detik berarti meninggal.
Aktivitas: setiap warga memilih sendiri aktivitas dengan skala prioritas. Pilihannya: makan, istirahat, cari makan, tebang kayu, tambang batu, berburu, bangun, bertani, memperbarui bangunan, belajar, menempa, menjinakkan hewan, menjelajah, diplomasi, latihan militer, bersosialisasi, berkeliling, berlindung di balai, dan merajuk. Prioritasnya mengikuti kebutuhan, persediaan koloni, syarat zaman yang belum terpenuhi, dan fokus hasil musyawarah.
Emosi: warga yang marah bisa bertengkar, dan yang takut berlindung di balai. Kebahagiaan rendah memperlambat kerja.
Kelahiran: terjadi bila ada pasangan dewasa yang bahagia, pangan melimpah (lebih dari 2 kali populasi), dan kapasitas rumah cukup (4 orang per rumah, plus 4 tempat bebas). Maksimal populasi 320.
4. Sumber daya
Pangan (🍖): dari semak beri, perburuan, ladang, dan ternak.
Kayu (🪵) dan batu (🪨): dipakai untuk bangunan.
Bijih (⛏️): muncul sesekali saat menambang batu di zaman Megalitikum ke atas, dipakai menempa perkakas dan senjata logam.
Koin (🪙): dari pajak, dagang, dan ternak unta. Bisa menutup kekurangan bahan saat memasang cetak biru.
Teknologi (💡): bertambah dari belajar dan penemuan.
Pulih: semak beri tumbuh lagi, sedangkan pohon dan batu habis lalu hilang.
5. Syarat naik zaman (tombol 📜)
Menuju	Syarat utama
Mesolitikum	Riset api, kapak, serpih, penusuk, tombak; populasi ≥15; bertahan 120 detik tanpa kelaparan
Neolitikum	Tempat berlindung (2 rumah atau wilayah tetap); jinakkan 1 hewan; panen pertama; riset batu asah dan gerabah
Megalitikum	Populasi ≥50; surplus pangan stabil; pemimpin adat terpilih; kebahagiaan >70%; monumen menhir
Zaman Logam	Temukan bijih; bengkel peleburan; pandai besi; cetak perkakas tani dan senjata logam
Peradaban Kuno	Aksara, hitung, hukum, pajak; irigasi, jalan, tembok; populasi ≥250
Abad Pertengahan	Aliansi ≥2 suku; barak; pasukan permanen ≥8; riset dagang dan feodal; lumbung; istana
Modern Awal	Mesin cetak, kompas, mesiu, uang; galangan; bank; peta terbuka ≥30%
Revolusi Industri	Riset baja dan mesin uap; tambang batu bara; pabrik; stasiun kereta
Modern & Digital	Pembangkit listrik; 3 menara telekomunikasi; riset komputer, semikonduktor, energi terbarukan; sekolah; literasi >80%; pusat riset

Riset berjalan lewat warga yang belajar di balai. Kecerdasan, pusat riset, dan lansia mempercepatnya. Perubahan zaman merambat pelan, karena tiap warga “menyusul” zaman lewat aktivitasnya.

6. Wilayah dan bangunan
Wilayah (🏴): Anda menetapkan lokasinya, dan balai dipindah ke sana. Warga hanya bekerja di dalam radius.
Radius: min(16, 5 + 0,18 × populasi + 0,75 × zaman + perluasan). Perluasan +2 setiap musyawarah memilih “Perluas wilayah”.
Bangunan: rumah, ladang, dan balai ada sejak awal. Bangunan khusus terbuka sesuai zaman: monumen dan bengkel peleburan mulai zaman ke-3 atau 4, lalu barak, istana, galangan, bank, pabrik, sampai pusat riset di zaman terakhir.
Cara membangun: ketuk 🏗️ (Bangun), pilih bangunan, lalu ketuk tanah kosong di dalam wilayah. Warga membangunnya sendiri. Bangunan lama bisa dihapus dengan 🗑️.
Peningkatan: bangunan ditingkatkan otomatis oleh warga saat zaman naik.
7. Musyawarah dan keputusan bersama
Waktu: rapat rutin tiap sekitar 40–60 detik. Rapat juga terjadi saat krisis pangan atau rata-rata amarah warga tinggi.
Durasi: semua warga berkumpul di balai selama sekitar 11 detik, lalu memilih.
Lima pilihan fokus: pangan, hunian, kayu dan batu, belajar dan inovasi, perluasan wilayah. Fokus terpilih mengarahkan aktivitas warga selama kurang lebih 90 detik.
Pemimpin adat: dipilih saat populasi ≥10, berdasarkan kecerdasan, usia, dan kebahagiaan.
Jaga malam: tiap musyawarah, dewasa memilih tingkat jaga 0–3 menurut rasa takut dan ancaman. Suara terbanyak menang dan hasilnya tampil di log.
8. Malam hari
Anak-anak: masuk rumah dan tidur. Remaja dan dewasa yang tidak berjaga juga tidur, kecuali sangat lapar.
Penjaga: dewasa 18–60 tahun bergiliran tiap 15 detik. Jumlahnya 10%, 20%, 30%, atau 40% dari dewasa menurut tingkat yang dipilih, minimal 1 dan selalu menyisakan satu dewasa yang tidur.
Tugas jaga: mereka berpatroli dan menghadang predator. Penjaga yang energinya di bawah 20 diganti.
Pemulihan: yang sudah berjaga pulang tidur di rumah sampai energinya pulih, lalu bekerja lagi.
Dampak: penjaga mengurangi kerugian akibat penjarahan perampok sekitar 40%.
9. Hewan dan ancaman
Buruan: kelinci, rusa, babi hutan (melawan balik), dan unta.
Ternak: hewan yang dijinakkan (mulai Neolitikum) menambah pangan, bisa beranak, dan unta menghasilkan koin.
Predator: serigala menyerang warga yang sendirian. Mereka takut api unggun dan menjauhi wilayah. Warga kuat melawan, sementara yang lemah lari ke balai.
Perampok: mulai Zaman Logam, suku tetangga yang bukan sekutu mengirim 2 sampai 7 perampok tiap 110–170 detik. Mereka menjarah pangan dan kayu. Tembok kota mengurangi kerugian sekitar 60%.
Kejadian acak: tiap 70–130 detik terjadi salah satu dari kemarau (pangan −35%), panen raya, badai (kayu −30%), wabah, ilham penemuan, atau pedagang keliling.
10. Suku tetangga dan perang
Empat suku: Rimba, Pesisir, Gunung, dan Padang, masing-masing di titik tertentu peta.
Diplomasi: mulai Peradaban Kuno ke atas, warga yang menjelajah mengunjungi suku yang sudah terlihat dan menambah hubungan. Pada 100 terbentuk aliansi.
Aliansi: menghasilkan koin dan sumber daya secara berkala.
Serangan: ketuk suku lalu ⚔️ Serang. Butuh barak dan minimal 4 prajurit. Kekuatan pasukan dibandingkan dengan pertahanan suku (40–70). Menang berarti jarahan dan suku itu jadi sekutu bawahan. Kalah berarti beberapa prajurit gugur dan pertahanan suku naik.
11. Koloni mandiri
Syarat mendirikan: dua dewasa atau lebih berkumpul (jarak di bawah 3 petak) dan berada lebih dari 16 petak dari balai mana pun. Koloni induk minimal 8 warga dan harus menyisakan minimal 4. Maksimal 4 koloni, dan rombongan pendiri maksimal 6 orang. Tombol 🏴 Dirikan koloni muncul bila syaratnya terpenuhi.
Yang dibawa: pangan, kayu, dan batu dari persediaan induk. Zaman, riset, dan 40% teknologi diwariskan.
Mandiri: tiap koloni punya balai, wilayah, persediaan, dan musyawarah sendiri.
Berpindah koloni: tombol 🔁.
Hubungan antarkoloni: dicek tiap 20 detik, nilainya −100 sampai +100. Wilayah tumpang tindih membuat hubungan turun (di bawah −40 muncul sengketa dan kebahagiaan turun). Wilayah terpisah membuat hubungan naik pelan sampai 25. Di atas 25, koloni yang surplus pangan membantu yang kekurangan. Tombol 🎁 mengirim hadiah 10 pangan dan 6 kayu ke koloni terdekat dan menambah hubungan +15.
12. Kontrol dan antarmuka
Peta: geser satu jari, cubit dua jari untuk zoom, ketuk minimap untuk memperbesar lalu ketuk lagi untuk berpindah.
Ketuk objek: warga, hewan, suku, atau bangunan untuk melihat info dan aksi. Warga bisa dipindahkan dengan 📍.
Tombol bawah: − + (zoom), kecepatan, 🏗️ Bangun, tombol Dirikan koloni (saat muncul), dan ☰.
Isi ☰: Wilayah, Syarat, Koloni, Hadiah, Simpan, Ekspor, mode Hemat, dan Menu.
13. Penyimpanan
Slot: ada 3 slot di browser. Game menyimpan otomatis tiap 20 detik dan juga lewat tombol 💾.
Ekspor dan impor: save bisa diunduh sebagai file .json dan dimuat kembali di menu utama.
Kompatibilitas: save dari peta lama (80×80) ditolak.
Mode Hemat: aktif otomatis di layar sentuh atau layar sempit dan bisa diatur dari ☰.
