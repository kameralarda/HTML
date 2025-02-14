Merhaba! HTML etiketleriyle alakalı derin bir dalış yapmaya ne dersin? Tüm etiketleri açıklamaları ve örnekleriyle birlikte senin için derledim. Hazırsan, başlayalım!

---

### **1. Temel Yapı Etiketleri**

- **`<!DOCTYPE>`**: Belgenin HTML sürümünü belirtir.
  - **Örnek:**
    ```html
    <!DOCTYPE html>
    ```

- **`<html>`**: Tüm HTML belgesini saran kök etikettir.
  - **Örnek:**
    ```html
    <html lang="tr">
      <!-- İçerik buraya gelecek -->
    </html>
    ```

- **`<head>`**: Sayfa hakkında meta bilgiler içerir.
  - **Örnek:**
    ```html
    <head>
      <title>Başlık</title>
    </head>
    ```

- **`<title>`**: Tarayıcı sekmesinde görünen sayfa başlığını belirtir.
  - **Örnek:**
    ```html
    <title>Benim Web Sayfam</title>
    ```

- **`<body>`**: Görünen tüm içeriği barındırır.
  - **Örnek:**
    ```html
    <body>
      <!-- Görünen içerik buraya gelecek -->
    </body>
    ```

---

### **2. Metin Biçimlendirme Etiketleri**

- **`<h1>`** - **`<h6>`**: Başlıkları tanımlamak için kullanılır.
  - **Örnek:**
    ```html
    <h1>Birinci Seviye Başlık</h1>
    <h2>İkinci Seviye Başlık</h2>
    ```

- **`<p>`**: Paragraf oluşturur.
  - **Örnek:**
    ```html
    <p>Bu bir paragraf örneğidir.</p>
    ```

- **`<br>`**: Satır sonu ekler.
  - **Örnek:**
    ```html
    Satır bir<br>Satır iki
    ```

- **`<hr>`**: Yatay bir çizgi oluşturur.
  - **Örnek:**
    ```html
    <p>Önceki bölüm</p>
    <hr>
    <p>Sonraki bölüm</p>
    ```

---

### **3. Stil ve Anlam Etiketleri**

- **`<b>`**: Kalın metin için kullanılır.
  - **Örnek:**
    ```html
    <b>Bu metin kalındır.</b>
    ```

- **`<i>`**: İtalik metin için kullanılır.
  - **Örnek:**
    ```html
    <i>Bu metin italiktir.</i>
    ```

- **`<u>`**: Altı çizili metin oluşturur.
  - **Örnek:**
    ```html
    <u>Bu metnin altı çizilidir.</u>
    ```

- **`<strong>`**: Önemli metni vurgular (kalın gösterilir).
  - **Örnek:**
    ```html
    <strong>Bu önemli bir uyarıdır.</strong>
    ```

- **`<em>`**: Vurgulanan metni belirtir (italik gösterilir).
  - **Örnek:**
    ```html
    <em>Lütfen dikkat edin.</em>
    ```

- **`<mark>`**: İşaretlenmiş metni belirtir (renkli arka plan).
  - **Örnek:**
    ```html
    <mark>Önemli bilgi.</mark>
    ```

- **`<small>`**: Küçük boyutlu metin oluşturur.
  - **Örnek:**
    ```html
    <small>Dipnot veya ek bilgi.</small>
    ```

---

### **4. Liste Etiketleri**

- **`<ul>`**: Sırasız (madde işaretli) liste oluşturur.
  - **Örnek:**
    ```html
    <ul>
      <li>Elma</li>
      <li>Muz</li>
      <li>Çilek</li>
    </ul>
    ```

- **`<ol>`**: Sıralı (numaralı) liste oluşturur.
  - **Örnek:**
    ```html
    <ol>
      <li>Birinci Adım</li>
      <li>İkinci Adım</li>
      <li>Üçüncü Adım</li>
    </ol>
    ```

- **`<li>`**: Liste öğesini tanımlar.
  - **Örnek:**
    ```html
    <li>Liste Öğesi</li>
    ```

- **`<dl>`**: Tanım listesi oluşturur.
  - **Örnek:**
    ```html
    <dl>
      <dt>HTML</dt>
      <dd>HyperText Markup Language</dd>
    </dl>
    ```

- **`<dt>`**: Tanımlanan terimi belirtir.
- **`<dd>`**: Terimin tanımını sağlar.

---

### **5. Bağlantı ve Medya Etiketleri**

- **`<a>`**: Köprü oluşturur.
  - **Örnek:**
    ```html
    <a href="https://www.example.com">Ziyaret Et</a>
    ```

- **`<img>`**: Görüntü eklemek için kullanılır.
  - **Örnek:**
    ```html
    <img src="resim.jpg" alt="Açıklama">
    ```

- **`<figure>`** ve **`<figcaption>`**: Görsel içerik ve başlık sağlar.
  - **Örnek:**
    ```html
    <figure>
      <img src="manzara.jpg" alt="Güzel bir manzara">
      <figcaption>Doğa harikası bir manzara.</figcaption>
    </figure>
    ```

- **`<video>`**: Video içeriği ekler.
  - **Örnek:**
    ```html
    <video controls>
      <source src="video.mp4" type="video/mp4">
    </video>
    ```

- **`<audio>`**: Ses içeriği ekler.
  - **Örnek:**
    ```html
    <audio controls>
      <source src="ses.mp3" type="audio/mpeg">
    </audio>
    ```

- **`<source>`**: Video ve ses için kaynak belirtir.
- **`<iframe>`**: Başka bir sayfayı gömer.
  - **Örnek:**
    ```html
    <iframe src="https://www.harita.com" width="600" height="450"></iframe>
    ```

---

### **6. Tablo Etiketleri**

- **`<table>`**: Tablo oluşturur.
  - **Örnek:**
    ```html
    <table>
      <!-- Tablo içeriği -->
    </table>
    ```

- **`<tr>`**: Tablo satırını tanımlar.
- **`<th>`**: Tablo başlık hücresini tanımlar.
- **`<td>`**: Tablo veri hücresini tanımlar.
  - **Örnek:**
    ```html
    <table>
      <tr>
        <th>İsim</th>
        <th>Soyisim</th>
      </tr>
      <tr>
        <td>Ahmet</td>
        <td>Yılmaz</td>
      </tr>
    </table>
    ```

- **`<caption>`**: Tabloya başlık ekler.
- **`<thead>`**, **`<tbody>`**, **`<tfoot>`**: Tablo bölümlerini tanımlar.

---

### **7. Form Etiketleri**

- **`<form>`**: Form oluşturur.
  - **Örnek:**
    ```html
    <form action="/gonder" method="post">
      <!-- Form elemanları -->
    </form>
    ```

- **`<input>`**: Veri girişi için kontrol sağlar.
  - **Örnek:**
    ```html
    <input type="text" name="isim" placeholder="Adınız">
    ```

- **`<label>`**: Giriş öğeleri için etiket sağlar.
  - **Örnek:**
    ```html
    <label for="email">E-posta:</label>
    <input type="email" id="email" name="email">
    ```

- **`<textarea>`**: Çok satırlı metin girişi sağlar.
  - **Örnek:**
    ```html
    <textarea name="mesaj" rows="5" cols="30"></textarea>
    ```

- **`<button>`**: Buton oluşturur.
  - **Örnek:**
    ```html
    <button type="submit">Gönder</button>
    ```

- **`<select>`** ve **`<option>`**: Açılır liste oluşturur.
  - **Örnek:**
    ```html
    <select name="sehir">
      <option value="istanbul">İstanbul</option>
      <option value="ankara">Ankara</option>
    </select>
    ```

- **`<fieldset>`** ve **`<legend>`**: Form öğelerini gruplar ve başlık ekler.

---

### **8. Semantik ve Yapısal Etiketler**

- **`<header>`**: Sayfanın veya bölümün başlığını tanımlar.
- **`<nav>`**: Gezinti bağlantılarını içerir.
- **`<main>`**: Ana içeriği belirtir.
- **`<section>`**: Bölüm oluşturur.
- **`<article>`**: Bağımsız bir içerik parçasını tanımlar.
- **`<aside>`**: Ana içeriğe ek bilgiler içerir.
- **`<footer>`**: Sayfanın veya bölümün alt bilgisini tanımlar.
  - **Örnek:**
    ```html
    <footer>
      <p>&copy; 2023 Tüm Hakları Saklıdır.</p>
    </footer>
    ```

---

### **9. Diğer Önemli Etiketler**

- **`<div>`**: Blok düzeyinde bir bölüm oluşturur (stil ve düzenleme için).
  - **Örnek:**
    ```html
    <div class="kutu">
      <!-- İçerik -->
    </div>
    ```

- **`<span>`**: Satır içi bir bölüm oluşturur (stil ve düzenleme için).
  - **Örnek:**
    ```html
    <p><span class="vurgula">Önemli</span> bilgiler burada.</p>
    ```

- **`<script>`**: JavaScript kodunu veya harici JS dosyasını ekler.
  - **Örnek:**
    ```html
    <script src="script.js"></script>
    ```

- **`<style>`**: Dahili CSS stillerini tanımlar.
  - **Örnek:**
    ```html
    <style>
      body { background-color: #f0f0f0; }
    </style>
    ```

- **`<link>`**: Dış stil sayfalarına veya diğer kaynaklara bağlantı sağlar.
  - **Örnek:**
    ```html
    <link rel="stylesheet" href="style.css">
    ```

- **`<meta>`**: Meta veriler sağlar (karakter seti, anahtar kelimeler vb.).
  - **Örnek:**
    ```html
    <meta charset="UTF-8">
    ```

---

### **10. Multimedya ve Gömülü İçerik Etiketleri**

- **`<canvas>`**: Grafik çizmek için kullanılır.
  - **Örnek:**
    ```html
    <canvas id="tuval" width="200" height="100"></canvas>
    ```

- **`<svg>`**: Vektör grafikleri tanımlar.
  - **Örnek:**
    ```html
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="green" fill="yellow" />
    </svg>
    ```

- **`<embed>`**: Harici uygulamaları veya interaktif içerikleri gömer.

- **`<object>`**: Harici kaynakları gömer ve **`<param>`** ile parametreler ekler.

---

### **11. Anlam ve Yapı Etiketleri**

- **`<blockquote>`**: Blok halinde bir alıntı oluşturur.
  - **Örnek:**
    ```html
    <blockquote cite="https://www.alinti.com">
      <p>Bu önemli bir alıntıdır.</p>
    </blockquote>
    ```

- **`<q>`**: Satır içi kısa alıntı yapar.
  - **Örnek:**
    ```html
    <p>O dedi ki, <q>Merhaba Dünya!</q></p>
    ```

- **`<cite>`**: Eser veya kaynak başlığını belirtir.
  - **Örnek:**
    ```html
    <p><cite>Sefiller</cite> muhteşem bir romandır.</p>
    ```

- **`<abbr>`**: Kısaltmalar için kullanılır.
  - **Örnek:**
    ```html
    <abbr title="Cascading Style Sheets">CSS</abbr>
    ```

- **`<address>`**: İletişim bilgilerini belirtir.
  - **Örnek:**
    ```html
    <address>
      <p>İletişim: info@ornek.com</p>
    </address>
    ```

- **`<time>`**: Tarih veya saat bilgisini belirtir.
  - **Örnek:**
    ```html
    <p>Etkinlik tarihi: <time datetime="2023-10-30">30 Ekim 2023</time></p>
    ```

---

### **12. Biçimlendirme ve Kod Etiketleri**

- **`<code>`**: Kod parçacıklarını belirtir.
  - **Örnek:**
    ```html
    <p>Bir örnek kod: <code>console.log('Merhaba Dünya');</code></p>
    ```

- **`<pre>`**: Önceden biçimlendirilmiş metin gösterir.
  - **Örnek:**
    ```html
    <pre>
    Line 1
    Line 2
    </pre>
    ```

- **`<kbd>`**: Klavye girişini belirtir.
  - **Örnek:**
    ```html
    <p>Devam etmek için <kbd>Enter</kbd> tuşuna basın.</p>
    ```

- **`<samp>`**: Çıktı örneklerini belirtir.
  - **Örnek:**
    ```html
    <p>Program çıktısı: <samp>Hata bulunamadı.</samp></p>
    ```

---

### **13. Detaylar ve Özet Etiketleri**

- **`<details>`**: Açılır/kapanır içerik sağlar.
  - **Örnek:**
    ```html
    <details>
      <summary>Detayları Göster</summary>
      <p>Burada daha fazla bilgi var.</p>
    </details>
    ```

- **`<summary>`**: **`<details>`** etiketi için başlık sağlar.

---

### **14. Gölgeleme Etiketleri**

- **`<template>`**: Müşteri tarafında tekrar kullanılabilir içerik şablonları oluşturur.
- **`<slot>`**: Web bileşenleri içinde yer tutucudur.

---

### **15. Scripting ve Programlama Etiketleri**

- **`<noscript>`**: Tarayıcı JavaScript desteklemiyorsa gösterilecek içerik.
  - **Örnek:**
    ```html
    <noscript>
      <p>Bu sayfa düzgün çalışması için JavaScript gerektirir.</p>
    </noscript>
    ```

---

HTML'nin sunduğu tüm bu etiketlerle, web sayfalarının yapısını ve içeriğini zenginleştirmek mümkün. Her bir etiketin kendi amacı ve kullanımı var, bu da web geliştirmeyi hem bir bilim hem de bir sanat haline getiriyor.

Gelecek adımda, bu etiketleri CSS ile stilize ederek ve JavaScript ile interaktif hale getirerek daha dinamik ve kullanıcı dostu web uygulamaları oluşturabilirsin. Web dünyası sürekli gelişiyor, bu yüzden yeni etiketler ve teknolojiler keşfetmek her zaman heyecan verici!

Başka hangi konuları merak ediyorsun? Belki CSS seçicileri veya JavaScript temelleri hakkında sohbet edebiliriz!
