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

