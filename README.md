# German-English-Detector
This code detects whether the text input is in German or English.

<h1>TR</h1>
<p>Bigram ve trigramların frekansları, kullanıcıdan alınan metinde taranarak hesaplanır ve dillerin frekans değerleriyle karşılaştırılır. Elde edilen frekans değerleri hangi dilin frekanslarına daha yakınsa metnin o dille yazıldığı belirtilir.</p>

<b>filter_str:</b>
<p>- Kullanıcıdan alınan metindeki [A-Z], [a-z] ve boşluk karakterlerinin haricindeki karakterler, boşluk karakterine çevrilir. ASCII (decimal) tablosuna göre karakterin [a-z] aralığında olması için [97,122] aralığında olması, [A-Z] aralığında olması için [65-90] aralığında olması gerekir. Karakter, boşluk karakteri ise 32 değerine sahiptir.</p>

<b>tolower_str:</b>
<p>- Metinde bulunan bigram ve trigramların sayısının hesaplanması esnasında büyük - küçük harf uyumsuzluğu ile karşılaşmamak adına metindeki tüm harfler küçük harfe dönüştürülür.</p>

<b>harf_hesaplama:</b>
<p>- Metindeki harf sayısı hesaplanır.</p>

<b>calculate_frequencies_bi:</b>
<p>- Metinde geçen bigramların sayısı ve frekansları hesaplanır.</p>

<b>calculate_frequencies_tri:</b>
<p>- Metinde geçen trigramların sayısı ve frekansları hesaplanır.</p>

<b>calculate_distances</b>
<p>-Bigram ve trigram frekanslarının Ingilizce ve Almanca dillerinin frekans değerlerine öklit uzaklıkları hesaplanır.</p>

<b>detect_lang</b>
<p>Kullanıcıdan alınan metnin İngilizce mi yoksa Almanca mı olduğu kullanıcıya gösterilir.</p>
