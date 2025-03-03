# **haftaningolu.com Web Projesi**

## **Projenin Amacı**
**haftaningolu.com** web sitesi, futbol dünyasında haftanın en iyi golünü atan futbolcuları seçmek amacıyla geliştirilmiştir. Kullanıcılar, futbolcuların performans bilgilerini, kişisel bilgilerini ve geçmiş performanslßarını görüntüleyebilir. Ayrıca iletişim sayfası üzerinden site sahipleriyle iletişime geçilebilir.

## **Kullanılan HTML Etiketleri**

Bu projede, web sayfasının yapısını ve içeriklerini düzenlemek için aşağıdaki HTML etiketleri kullanılmıştır:

- **`<header>`**: Sayfa başlığı ve menü gibi üst kısımlar için kullanılmıştır.
- **`<nav>`**: Sayfa içi gezintiyi sağlayan bağlantıları barındıran etiketlerdir. Kullanıcıların farklı sayfalara geçiş yapmasını sağlar.
- **`<section>`**: Sayfanın içeriğini belirli bölümlere ayırmak için kullanılmıştır. Her sayfa bölümü için ayrı bir `section` kullanılmıştır.
- **`<div>`**: İçerik bloklarını gruplamak için kullanılan genel bir konteynerdir.
- **`<a>`**: Bağlantılar oluşturmak için kullanılır. Kullanıcıları farklı sayfalara yönlendirir.
- **`<form>`**: Kullanıcıdan veri almak için kullanılan form etiketidir. İletişim sayfasında yer alan formda kullanılmıştır.
- **`<input>`**: Form elemanları (ad, soyad, e-posta gibi) için kullanılmıştır.
- **`<textarea>`**: Kullanıcının daha uzun metinler girebilmesi için kullanılan etiket. Mesaj kısmında yer alır.
- **`<button>`**: Formu göndermek için kullanılan buton etiketi.(Başka amaçlar için de  (örn. Tüm form elemanlarını temizlemek gibi)kullanılır ancak bu projede sadece göndermek için kullanılmıştır.)
- **`<table>`**: Performans bilgileri ve oyuncu detayları gibi verilerin düzenli bir şekilde görüntülenmesi için kullanılmıştır.
- **`<th>` ve `<td>`**: Tablo başlıkları (`<th>`) ve veri hücreleri (`<td>`) etiketleridir. İstatistiksel bilgilerin görüntülenmesinde kullanılmıştır.
- **`<h1>`** - **`<h6>`**: Sayfa veya bölüm başlığı için kullanılmıştır. Genellikle sayfanın ana başlığıdır.
- **`<p>`**: Paragraf etiketi, metni bir paragraf olarak gruplamak için kullanılmıştır. İçeriklerin daha okunabilir ve düzenli görünmesini sağlar.
- **`<a>`**: Bağlantı etiketi, sayfalar arası geçiş yapmak için kullanılır. `href` özelliği ile bağlantının hedefi belirtilir..
- **`<img>`**: Sayfada resim göstermek için kullanılmıştır. Resmin kaynağı `src` ile belirtilir ve resmin alt yazısı için `alt` kullanılır.  `alt` yazısı ayrıca resimin yüklenmesinde bir sorun olduğunda da gösterilen texttir.
- **`<ul>`**: Sırasız liste oluşturmak için kullanılmıştır. Liste elemanları **`<li>`** etiketi ile belirtilir.
- **`<ol>`**: Sıralı liste oluşturmak için kullanılmıştır. Bu liste numaralı bir sıra ile görünür. Liste elemanları **`<li>`** etiketi ile belirtilir.

**NOT:** Bazı etiketler kullanılacak kısım bulunmadığı için kullanılmamıştır.

## **Proje Özellikleri**

1. **Ana Sayfa (index.html)**:
   - Haftanın golününe aday olan futbolculara ait bilgiler ve attıkları gollerin videosu yer alır.
   - Kullanıcılar, her futbolcunun detaylarına "Kimdir?" bağlantısıyla ulaşabilirler.
   - Site tasarımında çim yeşili ve siyah renkler ağırlıklı olarak kullanılmıştır.

2. **Futbolcu Detay Sayfası(futbolcuismi.html)**:
   - Her futbolcu için performans bilgileri ve kişisel bilgiler yer alır.
   - Futbolcuların takım bilgisi, oynadıkları maçlar, attıkları goller ve asist sayıları gibi istatistikler tablo formatında sunulur.
   - Futbolcunun resmi, futbolcu bilgileriyle birlikte gösterilir.

3. **İletişim Sayfası (contact.html)**:
   - Kullanıcılar, iletişim formu aracılığıyla site sahipleriyle iletişime geçebilir.
   - Form, ad soyad, e-posta ve mesaj gibi alanlardan oluşur.

4. **Hakkımızda Sayfası (about.html)**
   - Sitenin ne iş yaptığı, ne amaçla korulduğuna dair bilgiler yer almaktadır.

5. **Oy Kullanma Klavuz Sayfası (howcanvote)**
   - Oyun nereden, nasıl kullanılabileceğine dair bilgiler içeren, adım adım ne yapılacağına yer verilmiştir.

## **Kullanıcı Deneyimi**

- Web sitesi basit ve kullanıcı dostu bir arayüze sahiptir.
- Sayfalar arasında geçiş yapmak kolaydır.
- Formlar, kullanıcıların rahatça veri girmesini sağlar.
- Hangi ögenin ne işe yaradığı ve nasıl kullanılacağı açıkla belirtilmiştir.

**SON OLARAK:** Bu proje benim için html kullanımı olarak bir pratik oldu. Ancak sadece html ile oluşturulan siteler göze hoş gelmemektedir. Bu yüzden temel seviyede css kullanmak zorunda kaldım. Böylece ilk websitesi oluşturma deneyimimi tamamladım. Öğrenme ve oluşturma yaklaşık olarak 7 saat civarında sürmüştür. Bu noktada html docs ve chatgptden faydalanılmıştır.
