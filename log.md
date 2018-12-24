# 100 Days Of Code - Log
## Python - Javascript backend focus 

### Day 0: 2018-11-17T03:31:49.006Z

**Today's Progress**: Belajar tentang scraping memakai BeautifulSoup4 dan request 

**Thoughts:** sebenernya bisa dibikin lebih cepat dan tidak harus mengunjungi semua 48 website untuk di scrape satu persatu dengan pagination. cuman ya kok males ya *hehe* 

**Link to work:** [Calculator App](https://github.com/svmihar/scraper-matematika-its)


### Day 1: 2018-11-18T06:52:01.698Z
**Today's Progress**: belajar tentang scraping img dan save ke local directory memakai selenium webdriver

**Thoughts**: di tutorial ada video yang hilang, sempat kehilangan geckodriver nya karena ternyata harus di install dulu ke $PATH, setelah ada lancar semua ke save ke dalam folder local. sayangnya hanya bisa digunakan di mac. bisa di improve buat scraping semua gambar yagn ada di dalam website matematika, cuman sek mager buat bikinnya karena kelaperan. nasib mahasiswa.

**Link(s) to work**: [Scraper App](https://github.com/svmihar/scraper-matematika-its)


### Day 1: 2018-11-18T09:35:31.415Z
**Today's Progress**: belajar tentang scraping img dan save ke local directory, savenya pake Bytes.IO

**Thoughts**: berhasil ngesave seluruh image dosen ke local dan ngambilnya tinggal pake object. belajar pake PIllow buat mendeteksi dan ngambil filenya dari website. Dari source filenya src="/foto/dosen/nama.jpg" gak lengkap alamatnya, jadi tinggal ditambah string alamat websitenya aja. Ngesave nama filenya juga tinggal pake split, dari string "/" 

**Link(s) to work**: [Scraper App](https://github.com/svmihar/scraper-matematika-its)

### Day 3: Wed Nov 21 22:04:17 ICT 2018
**Today's Progress**: Python decorator

**Thoughts**: hanya konsep dalam memahami decorator, dan bagaimana penggunaan @decorator_function, @decorator_class. baru tau kalau di python bisa masukin banyak argumen(atau paramater di java) ke dalam function dengan (*args, **kwargs) disimpan dengan semacam dictionary yang bisa di loop kwargs nya. Inti dari dictionary ini adalah implementasi unik dari OOP untuk Python, dengan me return function dan bukan variable / data statis. Decorator banyak menggunakan wrapper. Lalu wrapper bisa dirapikan dengan functools import wraps, dan menggunakan syntax @wrapper(nama_fungsi yang di return) untuk mencegah si functionnya ngereturn nama dari argumen orig_function.__name__ nya. 

**bahan**: https://www.youtube.com/watch?v=FsAPt_9Bf3U


**Link(s) to work**: [ProjectFile ](https://github.com/svmihar/30-days-of-python/tree/master/python-decorator)

### Day 4: Wednesday 21-11-2018 19:23:29
**Today's Progress**: Atari Asteroid 1979 Javascript


**Thoughts**: Belajar tentang geometri yang dipake di html canvas. Seru njir nentuin hidup mati, collision, sama lives yang tersisa. Agak ruwet di bagian radian buat menentukan sudut rotasi, tembakan. Kebanyakan hanya if else if else doang. ingin dibuat agar ship nya bisa pinter terus nembak sendiri. 

**Link(s) to work**: [Atari Asteroid](https://github.com/svmihar/100-days-of-code.git)

### Day 5: Saturday 24-11-2018 22:23:22
**Today's Progress**: Python Auto GUI 


**Thoughts**: Enak nih buat bikin mechanical turk, jadi bisa key write apapun ke dalam python bahkan bikin command custom. senang saya ngeliatnya. Di contohnya dibuat ngetik pembukaan pancasila 1000 kali. cukup lama nge run nya. 

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/python-auto-gui)

### Day 6: Monday 26-11-2018 02:32:17
**Today's Progress**: Python Text Based RPG Game


**Thoughts**: Standard RPG, with HP, mp for special attacks and healing, then attacking enemies. Basic stuff to learn more about OOP in classes. Not so special. 

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/rpg-battle)



### Day 7: Thursday 29-11-2018 17:40:22
**Today's Progress**: WhatsApp Bot with Selenium


**Thoughts**: menyenangkan apalagi buat semacam mechanical turk yang mencari "nama" dari xpath element si web.whatsapp.com, sayangnya hanya satu command per session jadi kalau ada command baru harus update qr code dari whatsapp-nya. Implementasi ini bisa dipakai buat pengingat rapat, pengingat tugas follow up2 tanpa harus mengetik dengan jari. so much things it can do .

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/whatsapp-spam-bot)




### Day 8: Monday 03-12-2018 21:30:28
**Today's Progress**: Classification from Breast Cancer Dataset with k-NN Python using scikit-learn 


**Thoughts**: ternyata salah satu aplikasi jarak euclidean adalah mencari tetangga. Banyak belajar untuk preproses data, dari pc kernel, ngebuat target class, nentuin predictor sampe selesai. Terus baru ngeh tentang f1 scoring. 

**Link(s) to work**: [Project File](https://github.com/svmihar/tubes-data-mining/tree/master/classification)

### Day 9: Sunday 09-12-2018 21:42:30
**Today's Progress**: Unzipping Files 


**Thoughts**: banyak donwload driver dan semuanya zip file, terlalu males untuk ngeklik satu2 buat extract akhirnya mempelajari buat make zipfile library python. tinggal sekali ngetik.

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/unzip)

### Day 10: Friday 21-12-2018 13:03:19
**Today's Progress**: Pong Neural Network with pygame, tensorflow, opencv


**Thoughts**: whew. cukup banyak sih, tensorflow gak bisa run di python 3.6++ jadinya harus install enviroment baru yang pake python 3.6.7, tadinya pake ubuntu bash + pyenv-virtualenv ternyata ruwet dan gak bisa keinstall terus python-nya jadinya pake miniconda buat ngatur versi python dan virtualenv nya, pengerjaan baru tau kayak pake canvas di javascript untuk pygame-nya, lalu ngajarin paddle nya pake tf.session() nya juga lucu karena tiap epoch jadi makin pinter what a day. 

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/pong-neural-network)

### Day 11: Friday 21-12-2018 20:43:21
**Today's Progress**: Manual Pong with turtle

**Thoughts**: nah ini baru berasa canvas-nya si html, bener2 di map per pixel dari deteksi collision bola dan paddle sampe check border pun semua manual (di map by pixel)

**Link(s) to work**: [Project File](https://github.com/svmihar/30-days-of-python/tree/master/pong-neural-network)

