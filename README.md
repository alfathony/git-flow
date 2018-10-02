# Git flow tutorial bahasa Indonesia

Baiq, gue akan coba share perihal git flow dengan bahasa Indonesia. Tapi ini tantangan berat sekali sebab gue gak bisa sepenuhnya pake bahasa Indonesia karna git flow aja flow nya itu dari bahasa Inggris. 🤔

Gue asumsikan kalian sudah terbiasa menggunakan Git untuk :
- init
- branch
- pull
- push
- merge
- remote

### Mengapa git flow?
Mungkin kalian pernah pake git tapi bingung gimana caranya menggunakan git yang baik dan rapih? nah git flow adalah salah satu caranya

### Memulai git flow
Ketika kita ingin menggunakan git flow di project kita pertama kita harus niat dulu, kemudian berunding dengan tim soalnya git flow ini secara umum berlaku individu jalankan

```git flow init```

Command tersebut untuk inisiasi bahwa kita akan menggunakan git flow pada working direktori kita. Git flow akan membantu kita membuatkan branch yang sesuai dengan apa yang sebetulnya kita perlukan. Git flow init akan menanyakan konfigurasi branch yang kita inginkan seperti ini :

1. Pengaturan untuk nama branch utama, biasanya itu untuk branch development dan production
- Branch name for production releases : defaultnya `master` namun dapat di ubah sesuai keinginan
- Branch name for "next release" development : defaultnya `develop` namun dapat di ubah sesuai keinginan
Saya sarankan gunakan default saja

2. Pengaturan untuk nama branch pendukung yaitu :
- Feature branches : Branch ini untuk setiap kali kita mengerjakan feature baru, defaultnya `feature/`
- Release branches : Branch ini untuk setiap kali development selesai dan sebelum rilis, defaultnya `release/`

