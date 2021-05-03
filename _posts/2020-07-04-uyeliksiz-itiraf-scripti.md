---
title: Üyeliksiz İtiraf Scripti
date: 2020-07-04T02:39:15
author: Burak Dündar
layout: post
permalink: /uyeliksiz-itiraf-scripti/
published: true
categories:
  - Yazılım
  - PHP
tags:
  - Ücretsiz Script
  - Üyeliksiz İtiraf Scripti
---
Merhaba arkadaşlar, sizlere codeigniter ile yazmış olduğum üyeliksiz itiraf scriptini ücretsiz olarak veriyorum :)

**Yönetim paneli özellikleri**

  * İtiraf Sayfası (Düzenle - Sil)
  * Yöneticiler Sayfası (Ekle - Düzenle - Sil)
  * Yorumlar Sayfası (Düzenle - Sil)
  * İletişim Mesajları Sayfası (Görüntüle - Sil)
  * Genel Ayarlar (Düzenle)

**Açıklama**

İtiraf veya dedikodu sitesi açmak isteyenlere tamamen açık kaynak kodlu uygun bir scripttir. Anasayfa kısmında StartBootstrap tarafından ücretsiz yayınlanan "Blog Home" ve "Blog Post" kullanılmıştır. Admin paneli kısmında StartBootstrap tarafından ücretsiz yayınlanan "SB Admin" kullanılmıştır. Kullanımı son derece basit ve kolaydır. Anasayfada kullanıcılar itiraflarını ve rumuzlarını yazıp paylaştıklarında admin paneline onaysız olarak düşmektedir, eğer adminler uygun görürlerse onaylayıp yayına alabilirler veya uygunsuz ifade oluşturduğu için silebilirler. Anasayfada gösterilecek olan itiraf sayısını "Genel Ayarlar" kısmından "Anasayfada görünecek olan itiraf sayısı" bölümünü doldurmaları yeterlidir.

**Yönetim paneli bilgileri**

website.com/admin  
Kullanıcı adı: <a href="http://mailto:admin@admin.com/" target="_blank">admin@admin.com</a>  
Şifre: 123456789  
(Bu bilgileri daha sonra yönetim panelinden değiştirebilirsiniz.)

**Kurulum**

->application->config->config.php = bu dizindeki dosyanın içerisinde;  
$config['base_url'] = 'dizin buraya';  
bu alana scriptin kurulu olduğu dizini yazın.  
->application->config->database.php = bu dizindeki dosyanın içerisinde;  
'hostname' => 'buraya veritabanı sunucunuzun adı', 'username' => 'buraya veritabanı kullanıcı adınız', 'password' => 'buraya veritabanı şifreniz', 'database' => 'buraya veritabanı adınız',  
bu alanları kendinize göre doldurunuz.

**Güncelleme ile eklenen ve değiştirilen kısımlar**

  * Veritabanı yapısı değiştirildi
  * Veritabanı optimizasyonu yapıldı.
  * İtiraflar ve Yorumlar için onaylı ve onaysız seçeneği ayarlar paneline eklendi.
  * İtiraflar paylaşılırken isteğe bağlı olarak görsel ile itiraf paylaşılabilecek.

**Kurulum Videosu**

<iframe src="https://www.youtube.com/embed/vCHJIBJN6PY" width="100%" height="450"></iframe>

**Eğer kurulumda bir sorun çıkarsa veya yardımcı olabileceğim bir konu olursa bana sosyal medya adreslerimden ulaşabilirsiniz.**

**Not: Bu script tamamen açık kaynak ve ücretsizdir. Kendinize göre düzenleyebilirsiniz**

**Ekran Görüntüleri**

<img src="https://cdn.r10.net/editor/103319/d1549523d77c3b7975052df0da8daf42.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/eb4e584b571fd8eb81d992c945af9d20.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/2a9301d1ca0bd58be8d5fbfaba9b0708.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/02389ca468e3877d8fed5488ab7fe559.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/9713ced6dd137d4c0776a8fc123ffa8a.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/ebcd4f7708ce28b71d32ae0dea07e492.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/967759b525b54c37ff2d1768a3e919c1.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/2141632e85d06eb643f2fd5961c98673.png" class="img-fluid">

<img src="https://cdn.r10.net/editor/103319/24f9a959987091a193eb2b972bf194c2.png" class="img-fluid">

[Demo](https://demo.codetify.net/?theme=cy-itiraf) [İndir](https://demo.codetify.net/?theme=cy-itiraf)