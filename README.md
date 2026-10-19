# logisticsiq-org.github.io

LogisticsIQ'nun herkese açık panoları bu depodan yayımlanır. Adres: https://logisticsiq-org.github.io

## Yayımlamadan önce

Bu depodaki her dosya internette herkese açıktır ve arama motorlarında çıkabilir. Panolar tarayıcıda çalıştığı için sayfaya konan her veriyi de sayfayı açan herkes görebilir. Bu yüzden:

- Üyelere ait hiçbir bilgi koymayın. Ad, e-posta, telefon, profil, CRM kaydı ve WhatsApp mesajı bunlara dahildir.
- Bir kuruma ait rakamları ya da belgeleri, o kurum yazılı olarak izin vermedikçe yayımlamayın.
- Şifre, API anahtarı ya da erişim tokeni koymayın.
- Her panoda verinin kaynağını ve hangi tarihte alındığını yazın.

Bir kişi ya da kurum için özel hazırlanan panolar buraya konmaz. Onlar logisticsiq.org'un üye alanında ya da özel bir depoda tutulur.

## Yeni pano eklemek

1. Kök dizinde pano için kısa adlı bir klasör açın, örneğin `liman-yogunlugu/`, ve sayfayı o klasöre `index.html` olarak koyun.
2. Kök dizindeki `index.html` dosyasında işaretli listeye bir satır ekleyin. Satırda başlık, tek cümlelik açıklama, yayın tarihi ve veri kaynağı yer alır.
3. Değişikliği `main` dalına gönderin. GitHub Pages sayfayı genellikle bir iki dakika içinde yayımlar ve pano `https://logisticsiq-org.github.io/<klasör>/` adresinde açılır.

Dışarıdan bir kütüphane kullanacaksanız sürüm numarasını sabitleyin, örneğin `chart.js@4.4.1`.

## English

LogisticsIQ publishes its public dashboards from this repository at https://logisticsiq-org.github.io.

Everything here is public and can show up in search engines. A dashboard runs in the browser, so anyone who opens it can see the data inside it. Do not add member information of any kind, a company's figures or documents without its written permission, or any password, API key or token. Every dashboard states where its data came from and the date it was taken. A dashboard made for one person or one company does not go here. It belongs in the member area of logisticsiq.org or in a private repository.

To add a dashboard, create a short-named folder at the root with an `index.html`, add a line to the marked list in the root `index.html`, and push to `main`. The page appears at `https://logisticsiq-org.github.io/<folder>/`, usually within a minute or two.
