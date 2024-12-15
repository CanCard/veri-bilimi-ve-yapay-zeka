# Teknofest Projem

<br>

2024 yılında gerçekleştirilen Teknofest yarışmasının, "Doğal Dil İşleme Senaryosu" kısmı için tasarlamış olduğum Aspect Based Sentiment Analysis (yorum tabanlı duygu analizi) projemi çok yakında buraya yeniden yükleyeceğim. 

<br>

Projem kısaca, verilen bir metin içerisinde çeşitli firmalara gelen talep, öneri ve şikayetlerin hangi kategoride, bu kategorideki hangi spesifik konuda, hangi duygu durumuyla ve düşünceyle alakalı olduğunu doğru olarak tespit etmeye yöneliktir. Türkiye'deki çeşitli firmalara gelen şikayet ve talepler gerekli kaynaklardan web scraping yöntemiyle elde edilmiştir. 

<br>

---
### Bir Örnek:
<br>

>_"X firmasının internet hızı daha iyi fakat Y firmasının fiyatı daha uygun. Fiyatlar biraz pahalı lütfen makul seviyeye getirin."_

<br>

<br>

|Entity|Aspect|Polarity|Opinion|Category|
|---|---|---|---|---|
|X firması|İnternet|Positive|daha iyi|İnternet#Kalite|

<br>

|Entity|Aspect|Polarity|Opinion|Category|
|---|---|---|---|---|
|X firması|fiyatlar|Negative|biraz pahalı|Paket_Fiyatı#Fiyat|

<br>

|Entity|Aspect|Polarity|Opinion|Category|
|---|---|---|---|---|
|Y firması|fiyat|Positive|daha uygun|Paket_Fiyatı#Fiyat|

<br>


---

<br>
Yaptığım değişikliklerin projemi daha güzel hale getirdiğini gördüğüm için üzerine çalıştığım projeyi geçici olarak kaldırdım. Ayrıca bu süreçte projemi oldukça büyük bir Türkçe kaynak haline getirmek istiyorum. 

<br>

Projem PyABSA kütüphanesinden büyük ölçüde faydalanmaktadır. Buraya yükleyeceğim projenin neye benzeyeceğini görmek için [Huggingface/PyABSA](https://huggingface.co/spaces/yangheng/PyABSA) bağlantısını;

[PyABSA_Kütüphanesi](https://github.com/yangheng95/PyABSA/tree/v2) ve kaynak kodlarını incelemek için  ilgili bağlantıyı ve;

Teknofest yarışmasının mantığını ve amacını anlamak için de [Teknofest Doğal Dil İşleme Yarışması](https://teknofest.org/tr/yarismalar/turkce-dogal-dil-isleme-yarismasi/) bağlantısını ziyaret edebilirsiniz.

<br>

```Değişiklikler uygulanıyor... ⚙️🔧```