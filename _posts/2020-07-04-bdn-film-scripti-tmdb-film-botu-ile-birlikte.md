---
title: 'BDN Film Scripti [TMDb film botu ile birlikte]'
date: 2020-07-04T11:46:29
author: Burak Dündar
layout: post
permalink: /bdn-film-scripti-tmdb-film-botu-ile-birlikte/
categories:
  - CMS
  - PHP
  - Yazılım
tags:
  - Codeigniter
  - Film Scripti
  - Ücretsiz Film Scripti
---
Merhaba arkadaşlar, sizlere codeigniter ile yazmış olduğum film scriptini ücretsiz olarak veriyorum.

**Yönetim paneli özellikleri**

  * Filmler Sayfası (Ekle - Düzenle - Sil)
  * Film Kaynakları Sayfası (Ekle - Düzenle - Sil)
  * TMDb Film Botu Sayfası (ID ile veri çekme - Ekle)
  * Kategoriler Sayfası (Ekle - Düzenle - Sil)
  * Yöneticiler Sayfası (Ekle - Düzenle - Sil)
  * Sayfaların Yönetim Sayfası (Ekle - Düzenle - Sil)
  * Yorumlar Sayfası (Düzenle - Sil)
  * İletişim Mesajları Sayfası (Görüntüle - Sil)
  * Reklamlar Sayfası (Düzenle - Aktif/Pasif)
  * Genel Ayarlar (Düzenle)

**Açıklama**

Film sitesi açmak isteyenlere tamamen açık kaynak kodlu uygun bir scripttir. Anasayfa kısmında StartBootstrap tarafından ücretsiz yayınlanan "Blog Home" ve "Blog Post" kullanılmıştır. Admin paneli kısmında StartBootstrap tarafından ücretsiz yayınlanan "SB Admin" kullanılmıştır. Kullanımı son derece basit ve kolaydır. Anasayfada gösterilecek olan filmlerin sayısını "Genel Ayarlar" kısmından "Anasayfada görünecek olan film sayısı" bölümünü doldurmaları yeterlidir.

**TMDb Bot Kullanımı**

Script kurulumundan sonra menüden "Ayarlar" kısmına gidip burada "Film botu için TMDB API Anahtarı" yazan değeri bırakmış olduğum linkten aldığınız api anahtarı ile doldurunuz ve kaydediniz.  
Daha sonra TMDb sitesinden istediğiniz bir filmin idsini, menüden "Filmler-Film Botu" kısmına gidip "TMDb Film ID giriniz" yazan yere yazdıktan sonra "Film bilgilerini getir" butonuna basmanız yeterlidir. Bot girmiş olduğunuz idye ait olan filmin bilgilerini ve afişini sizin yerinize otomatik olarak getirecektir. Size kalan tek iş gelen sayfada "Kaydet" butonuna basmanız olacaktır.

**TMDb Film Botu Kullanımı**

<iframe src="https://www.youtube.com/embed/cmyuwzdkoqA" width="100%" height="450"></iframe>

**Yönetim paneli bilgileri**

website.com/admin  
Kullanıcı adı: admin@admin.com
Şifre: 123456789  
(Bu bilgileri daha sonra yönetim panelinden değiştirebilirsiniz.)

**Kurulum**

->application->config->config.php = bu dizindeki dosyanın içerisinde;  
$config['base_url'] = 'dizin buraya';  
bu alana scriptin kurulu olduğu dizini yazın.  
->application->config->database.php = bu dizindeki dosyanın içerisinde;  
'hostname' => 'buraya veritabanı sunucunuzun adı', 'username' => 'buraya veritabanı kullanıcı adınız', 'password' => 'buraya veritabanı şifreniz', 'database' => 'buraya veritabanı adınız',  
bu alanları kendinize göre doldurunuz.

**Kurulum Videosu (Kurulum adımları itiraf scripti ile aynı olduğu için ekstra olarak kurulum videosu çekmedim)**

<iframe src="https://www.youtube.com/embed/vCHJIBJN6PY" width="100%" height="450"></iframe>

**Notlar**

Not 1: Eğer kurulumda bir sorun çıkarsa veya yardımcı olabileceğim bir konu olursa bana sosyal medya adreslerimden ulaşabilirsiniz.(Script üzerinde düzenleme - ekleme vs. yapmamaktayım.)  
Not 2: Bu script tamamen açık kaynak ve ücretsizdir. Kendinize göre düzenleyebilirsiniz.  
Not 3: Scriptte hazır girilmiş kategoriler ve 24 adet film bulunmaktadır (Filmlerin kaynakları ekli değildir). Eğer hazır girilmiş kategoriler ve filmleri istiyorsanız "sql" klasöründe "bdnfilm_DOLU.sql" verilerini kullanmalısınız.  
Not 4: Script kurulumundan sonra admin paneli veya diğer sayfalarda 404 hatası alıyorsanız gizli dosyaları görünür yapıp .htaccess dosyalarını tekrar ftp programı ile sunucuya atmayı unutmayınız.

**Ekran Görüntüleri**

<img src="https://cdn.r10.net/editor/103319/81e949a3681aafb4fc295eb6515e93af.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/11c447424638cd4e5ede1ce217d4ac61.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/9ff93780192146ba12def39c24ee5028.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/d288fbbd78e89a45e4601332bfa19130.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/11f0271eaba3586ea50c20fe8599ed22.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/bee2086d8e9a1b217d398101facaf311.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/d552ca29f7807746bc5e5a6daf7f0f4d.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/9d6c68bee11c1822483803211f804d61.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/c4934f055267e7bba110512b464f5027.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/bfb42834ddfc94889e83eb72bb82fbc3.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/233ee0e9f0356d7868a6be28fa11709d.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/e60e551ed40e07dbafaad126daca6550.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/7b5f6363022e765b9c27b187eb9b2ce3.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/ed5fc50f0ca9affaea843510ba65790a.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/bc4db2ff6275434be21582e68a689474.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/f4dd4c1e373e0b26e67f4b60352d3046.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/aa34678dd8761070c7d5c53e973938aa.png" class="img-fluid">

[Demo](https://demo.codetify.net/?theme=cy-film) [İndir](https://demo.codetify.net/?theme=cy-film)