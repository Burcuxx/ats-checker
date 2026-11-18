# ATS CV Kontrol / ATS CV Checker

CV'nizin başvuru takip sistemlerinde (ATS) doğru okunup okunmadığını kontrol eden, tamamen tarayıcıda çalışan ücretsiz bir araç. Dosyanız hiçbir sunucuya gönderilmez.

A free, fully client-side tool that checks whether your CV is ATS-friendly. Your file never leaves your browser.

## Özellikler / Features
- PDF, DOCX ve TXT okuma (iki sütunlu düzen algılama dahil)
- Format, yapı ve içerik alt puanlarıyla ATS puanı
- Öncelik sırasına göre düzeltme listesi
- Güçlendirilmesi gereken CV maddeleri (sayı, eylem fiili, uzunluk)
- İş ilanıyla anahtar kelime eşleşmesi ve gereksinim karşılaştırması (deneyim yılı, eğitim, dil, ehliyet)
- Türkçe / English arayüz

## Teknoloji / Tech
Tek dosya: `index.html` — saf HTML, CSS ve JavaScript. PDF için [pdf.js](https://mozilla.github.io/pdf.js/), DOCX için [mammoth.js](https://github.com/mwilliamson/mammoth.js).

## Yerelde çalıştırma / Run locally
`index.html` dosyasını tarayıcıda açın. / Open `index.html` in a browser.

`samples/` klasöründe test için örnek (kurgusal) CV'ler var. / `samples/` contains fictional test CVs.
