<template>
  <div class="min-h-screen flex flex-col items-center justify-center px-4 relative overflow-hidden mt-8">
    <!-- Lace background di bawah navbar -->
    <div class="absolute lace-border w-full h-12 top-2"></div>

    <!-- Hero Section -->
    <section class="w-full max-w-6xl text-center pt-16 px-4">
      <h1 class="text-xl md:text-4xl font-extrabold text-[#6a4c46] mb-4">Tips & Inspirasi</h1>
      <p class="text-lg md:text-xl text-pink-600">Tips dan Inspirasi seputar kesehatan perempuan.</p>
    </section>
    
    <section class="w-full max-w-6xl py-12 px-4 mb-6">

    <!-- Section: Tips -->
    <div class="mb-16">
      <h2 class="text-2xl font-bold text-yellow-700 mb-5 text-center">💡 Tips</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        
        <!-- 8 Tips Cards -->
        <div class="note-card yellow">Minum minimal 8 gelas air putih setiap hari untuk menjaga hidrasi tubuh.</div>
        <div class="note-card yellow">Cukupi tidur 7–9 jam per malam untuk menjaga keseimbangan hormon.</div>
        <div class="note-card yellow">Lakukan olahraga ringan minimal 30 menit setiap hari.</div>
        <div class="note-card yellow">Konsumsi buah dan sayur setiap hari untuk mendukung sistem imun.</div>
        <div class="note-card yellow">Batasi konsumsi makanan tinggi gula dan lemak jenuh.</div>
        <div class="note-card yellow">Jaga kesehatan mental dengan rutin meditasi atau journaling.</div>
        <div class="note-card yellow">Cek kesehatan reproduksi secara rutin ke dokter kandungan.</div>
        <div class="note-card yellow">Gunakan sunscreen setiap hari untuk lindungi kulit dari sinar UV.</div>

      </div>
    </div>

    <!-- Section: Inspirasi -->
    <div class="mb-16">
      <h2 class="text-2xl font-bold text-pink-700 mb-5 text-center">🌸 Inspirasi</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- 8 Inspirasi Cards -->
        <div class="note-card pink">"Kesehatan adalah anugerah, rawatlah dengan penuh cinta."</div>
        <div class="note-card pink">"Perempuan sehat adalah perempuan yang percaya diri dan bahagia."</div>
        <div class="note-card pink">"Rawat tubuhmu seperti merawat sahabat terbaikmu."</div>
        <div class="note-card pink">"Langkah kecil menuju sehat, berarti besar untuk masa depan."</div>
        <div class="note-card pink">"Tubuh yang sehat adalah rumah bagi jiwa yang kuat."</div>
        <div class="note-card pink">"Jaga tubuh, jaga pikiran, jaga hati."</div>
        <div class="note-card pink">"Kebaikan dimulai dari diri sendiri — termasuk merawat kesehatan."</div>
        <div class="note-card pink">"Jangan lupa tersenyum, itu vitamin gratis."</div>

      </div>
    </div>

    <!-- Section: Mitos & Fakta -->
    <div class="mb-16">
      <h2 class="text-2xl font-bold text-green-700 mb-5 text-center">🔍 Mitos & Fakta</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- Mitos & Fakta Cards -->
        <div class="note-card green"><strong>Mitos:</strong> Haid tidak teratur = mandul ❌<br><strong>Fakta:</strong> Tidak selalu. Haid tidak teratur bisa disebabkan oleh stres, gangguan hormon, PCOS, atau faktor lain yang tidak selalu berhubungan dengan kemandulan. Konsultasikan ke dokter untuk mengetahui penyebab pastinya ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Menyusui jadi kontrasepsi alami ❌<br><strong>Fakta:</strong> Tidak sepenuhnya efektif. Menyusui memang bisa menekan ovulasi, tetapi tidak bisa dijadikan metode kontrasepsi yang sepenuhnya aman tanpa risiko kehamilan. Tetap gunakan kontrasepsi tambahan jika tidak ingin hamil ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Sering pakai bra bikin kanker ❌<br><strong>Fakta:</strong> Tidak ada bukti ilmiah yang menunjukkan bahwa pemakaian bra, baik siang maupun malam, dapat menyebabkan kanker payudara. Faktor risiko kanker lebih berkaitan dengan genetik, gaya hidup, dan hormon ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Hamil selalu makan dua porsi ❌<br><strong>Fakta:</strong> Saat hamil, ibu memang membutuhkan lebih banyak nutrisi, tetapi bukan berarti makan dalam porsi dua kali lipat. Fokuslah pada kualitas nutrisi, bukan pada jumlah makanan yang dikonsumsi ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Keputihan selalu tanda penyakit ❌<br><strong>Fakta:</strong> Tidak selalu. Keputihan bisa normal jika berwarna bening atau putih susu, tidak berbau menyengat, dan tidak disertai gatal atau nyeri. Jika muncul perubahan warna, bau, atau keluhan lain, baru perlu diperiksakan ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Tidak haid pasti hamil ❌<br><strong>Fakta:</strong> Tidak haid belum tentu hamil. Siklus haid bisa terganggu akibat stres, pola makan, olahraga berlebihan, gangguan hormon, atau kondisi medis tertentu. Sebaiknya cek ke dokter jika haid tidak datang lebih dari 3 bulan ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Cukur bulu kemaluan bikin tumbuh lebih tebal ❌<br><strong>Fakta:</strong> Cukur bulu kemaluan tidak membuat rambut tumbuh lebih tebal atau lebat. Rambut baru hanya tampak lebih kasar atau kaku saat tumbuh kembali karena ujung rambut yang tumpul akibat dicukur ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Haid berhenti saat berenang ❌<br><strong>Fakta:</strong> Tekanan air saat berenang memang bisa memperlambat keluarnya darah haid, tetapi tidak menghentikannya sepenuhnya. Darah tetap keluar meski jumlahnya sangat sedikit. Penggunaan tampon atau menstrual cup bisa membantu ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Olahraga saat haid berbahaya ❌<br><strong>Fakta:</strong> Olahraga saat haid tidak akan menyebabkan masalah kesehatan atau gangguan siklus haid. Justru, aktivitas fisik ringan hingga sedang bisa membantu meredakan nyeri haid, memperbaiki mood, dan melancarkan aliran darah. Sesuaikan intensitas olahraga dengan kondisi tubuh ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Darah haid adalah darah kotor ❌<br><strong>Fakta:</strong> Darah haid adalah bagian dari siklus menstruasi wanita dan tidak kotor atau berbahaya. Itu adalah campuran darah, jaringan rahim, dan lendir yang keluar secara alami karena tidak terjadi kehamilan. Tidak ada kandungan racun atau zat berbahaya di dalamnya ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Ngemil di malam hari bikin gemuk ❌<br><strong>Fakta:</strong> Tidak ada perbedaan antara ngemil di malam hari, pagi hari maupun siang hari. Ketiganya sama-sama bisa menambah berat badan jika makanan yang dikonsumsi mengandung banyak gula dan berlemak ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Kontrasepsi hormonal menyebabkan kegemukan ❌<br><strong>Fakta:</strong> Kontrasepsi hormonal tidak selalu menyebabkan kegemukan, tetapi dapat mempengaruhi nafsu makan dan metabolisme ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Vagina perlu dibersihkan dengan sabun khusus atau douching ❌<br><strong>Fakta:</strong> Vagina memiliki mekanisme pembersihan alami. Penggunaan sabun khusus atau douching justru bisa mengganggu keseimbangan bakteri baik dan pH vagina, yang berisiko menyebabkan infeksi. Membersihkan bagian luar (vulva) cukup dengan air bersih ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Pap smear hanya diperlukan jika ada gejala ❌<br><strong>Fakta:</strong> Pap smear adalah pemeriksaan skrining untuk mendeteksi perubahan sel serviks sebelum menjadi kanker. Tes ini penting dilakukan secara rutin, meski tidak ada gejala, untuk deteksi dini kanker serviks ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Hanya perempuan tua yang berisiko kanker payudara ❌<br><strong>Fakta:</strong> Meski risikonya meningkat seiring usia, perempuan muda juga bisa terkena kanker payudara. Karena itu, penting membiasakan periksa payudara sendiri (SADARI) dan rutin cek ke dokter ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Endometriosis hanya nyeri haid biasa ❌<br><strong>Fakta:</strong> Endometriosis adalah kondisi medis serius di mana jaringan seperti lapisan rahim tumbuh di luar rahim. Gejalanya bisa berupa nyeri hebat saat haid, nyeri saat berhubungan, dan infertilitas. Perlu diagnosis dan penanganan dokter ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Infeksi saluran kemih hanya terjadi karena kurang minum ❌<br><strong>Fakta:</strong> Infeksi saluran kemih (ISK) bisa disebabkan oleh bakteri yang masuk ke saluran kemih, bukan hanya karena kurang minum. Faktor risiko lainnya termasuk hubungan seksual, kebersihan yang kurang tepat, dan penggunaan alat kontrasepsi tertentu ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Semua benjolan di payudara berarti kanker ❌<br><strong>Fakta:</strong> Tidak semua benjolan di payudara adalah kanker. Sebagian besar benjolan bersifat jinak seperti kista atau fibroadenoma. Namun, tetap penting memeriksakan benjolan ke dokter untuk memastikan diagnosis ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Perempuan tidak butuh zat besi sebanyak laki-laki ❌<br><strong>Fakta:</strong> Justru perempuan usia subur sering butuh lebih banyak zat besi karena kehilangan darah saat menstruasi. Kekurangan zat besi bisa menyebabkan anemia yang berdampak pada energi, konsentrasi, dan daya tahan tubuh ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Kanker serviks hanya terjadi pada perempuan yang aktif secara seksual ❌<br><strong>Fakta:</strong> Kanker serviks memang berkaitan dengan infeksi HPV (Human Papillomavirus) yang ditularkan lewat kontak seksual. Namun, perempuan yang jarang atau tidak aktif secara seksual tetap berisiko, walau lebih kecil. Vaksinasi HPV dan pemeriksaan rutin sangat dianjurkan ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Kehamilan bisa terjadi hanya jika ada orgasme ❌<br><strong>Fakta:</strong> Kehamilan terjadi saat sel sperma membuahi sel telur, tidak tergantung ada atau tidaknya orgasme. Orgasme perempuan tidak berpengaruh langsung terhadap kemungkinan hamil ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> PCOS artinya pasti tidak bisa hamil ❌<br><strong>Fakta:</strong> Polycystic Ovary Syndrome (PCOS) memang bisa mempersulit kehamilan, tetapi bukan berarti tidak bisa hamil sama sekali. Dengan pengobatan dan manajemen yang tepat, banyak perempuan dengan PCOS yang berhasil hamil ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Kalau tidak haid, berarti menopause sudah selesai ❌<br><strong>Fakta:</strong> Tidak haid selama beberapa bulan belum tentu berarti menopause sudah pasti terjadi. Menopause dikatakan terjadi jika tidak haid selama 12 bulan berturut-turut. Sebelumnya ada fase perimenopause yang gejalanya bisa naik turun ✅</div>
        <div class="note-card green"><strong>Mitos:</strong> Semua perempuan pasti mengalami nyeri haid ❌<br><strong>Fakta:</strong> Tidak semua perempuan mengalami nyeri haid. Tingkat nyeri bisa bervariasi, dan nyeri hebat bukan hal yang harus dianggap normal. Jika nyeri mengganggu aktivitas, bisa jadi ada kondisi medis seperti endometriosis atau adenomiosis yang perlu ditangani dokter ✅</div>

      </div>
    </div>

    <!-- Section: Fun Fact -->
    <div>
      <h2 class="text-2xl font-bold text-blue-700 mb-5 text-center">🎀 Fun Fact</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- Fun Fact Cards -->
        <div class="note-card blue">Perempuan punya indra penciuman lebih tajam dibanding pria.</div>
        <div class="note-card blue">Sel telur perempuan adalah sel terbesar di tubuh manusia.</div>
        <div class="note-card blue">Selama kehamilan, jantung memompa darah 30–50% lebih banyak.</div>
        <div class="note-card blue">Rata-rata siklus menstruasi normal adalah 28 hari, tapi rentang 21–35 hari masih normal.</div>
        <div class="note-card blue">Perempuan memiliki lemak tubuh lebih tinggi secara alami, untuk perlindungan hormonal.</div>
        <div class="note-card blue">Rasa nyeri saat haid dipengaruhi oleh hormon prostaglandin.</div>
        <div class="note-card blue">Selama masa subur, indra penciuman dan daya tarik visual perempuan meningkat.</div>
        <div class="note-card blue">Wanita hidup rata-rata lebih lama dibanding pria di hampir semua negara.</div>
        <div class="note-card blue">Perempuan memiliki otak yang lebih besar dibandingkan pria, meskipun perbedaan ukuran otak tidak berarti perbedaan kecerdasan.</div>
        <div class="note-card blue">Kehamilan bisa mempengaruhi gigi dan gusi, meningkatkan risiko penyakit gusi pada ibu hamil.</div>
        <div class="note-card blue">Kebanyakan perempuan lebih cenderung mengalami migrain dibandingkan pria, terutama di usia reproduktif.</div>
        <div class="note-card blue">Tingkat stress perempuan cenderung meningkat pada fase menstruasi dan kehamilan karena perubahan hormon.</div>
        <div class="note-card blue">Perempuan lebih cenderung mendeteksi rasa manis dibandingkan pria karena perbedaan jumlah sel pengecap di lidah.</div>
        <div class="note-card blue">Pada usia 30-an, kadar estrogen dalam tubuh perempuan mulai menurun, mempengaruhi kualitas tidur dan kulit.</div>
        <div class="note-card blue">Perempuan memiliki sistem kekebalan tubuh yang lebih kuat, tetapi juga lebih rentan terhadap beberapa penyakit autoimun.</div>
        <div class="note-card blue">Tingkat metabolisme perempuan cenderung lebih rendah dibandingkan pria, yang mempengaruhi laju pembakaran kalori.</div>
        <div class="note-card blue">Perempuan memiliki lebih banyak kelenjar keringat di tubuhnya, tetapi keringatnya cenderung lebih sedikit dibandingkan pria.</div>
        <div class="note-card blue">Perempuan memiliki lebih banyak koneksi saraf di otak, yang mempengaruhi kemampuan multitasking.</div>
        <div class="note-card blue">Perempuan lebih cenderung mengalami gangguan kecemasan dibandingkan pria, terutama pada masa remaja dan dewasa muda.</div>
        <div class="note-card blue">Perempuan memiliki lebih banyak sel otot di bagian bawah tubuh, yang mempengaruhi kekuatan dan daya tahan saat berlari.</div>

      </div>
    </div>

    </section>

</div>

</template>

<style scoped>
.lace-border {
  background-image: url('/images/lace-2.png');
  background-repeat: repeat-x;
  background-position: top center;
  background-size: auto 100%;
}

.note-card {
    border-radius: 0.5rem;
    padding: 1rem;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    border-width: 2px;
    transition: transform 0.2s;
    font-size: 0.9rem;
}
.note-card:hover { 
    transform: rotate(0deg) scale(1.05);
}

.note-card.yellow {
    background-color: #FEF9C3;
    border-color: #FACC15;
    color: #78350F;
}

.note-card.pink {
    background-color: #FCE7F3;
    border-color: #F472B6;
    color: #831843;
}

.note-card.green {
    background-color: #DCFCE7;
    border-color: #34D399;
    color: #064E3B;
}

.note-card.blue {
    background-color: #DBEAFE;
    border-color: #3B82F6;
    color: #1E3A8A;
}
</style>