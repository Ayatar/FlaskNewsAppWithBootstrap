# Insta-News

## 🇹🇷 Proje Özeti
Insta-News, Flask ve Bootstrap kullanarak NewsAPI üzerinden güncel haberlere hızlı erişim sağlayan basit bir web uygulamasıdır. Kullanıcı anahtar kelimeyle arama yapabilir ve sonuçlar kart görünümlü bir arayüzde listelenir.

### Özellikler
- Haberleri anahtar kelimeye göre arama
- Bootstrap kart tasarımı ve duyarlı arayüz
- Geçersiz veya istenmeyen kaynakların filtrelenmesi ("Yahoo" ve "removed" içerikleri)

### Kullanılan Teknolojiler
- Python 3
- Flask
- Bootstrap 5
- Requests
- NewsAPI (harici servis)

### Kurulum ve Çalıştırma
1. Depoyu yerel bilgisayarınıza klonlayın.
2. (Opsiyonel) Sanal ortam oluşturun ve etkinleştirin:
   ```powershell
   python -m venv env
   env\Scripts\Activate.ps1
   ```
3. Bağımlılıkları kurun:
   ```powershell
   pip install -r requirements.txt
   ```
4. Kök dizinde `config.py` dosyası oluşturup NewsAPI anahtarınızı ekleyin:
   ```python
   NEWS_API_KEY = "YOUR_NEWSAPI_KEY"
   ```
5. Uygulamayı çalıştırın:
   ```powershell
   flask --app app run --debug
   ```

## 🇺🇸 Project Summary
Insta-News is a lightweight Flask + Bootstrap web app that fetches the latest headlines from NewsAPI. Users can search by keyword and see the matching results in responsive cards.

### Features
- Keyword-based news search
- Responsive Bootstrap card layout
- Filters out unwanted sources ("Yahoo" and titles containing "removed")

### Tech Stack
- Python 3
- Flask
- Bootstrap 5
- Requests
- NewsAPI (external service)

### Setup & Run
1. Clone the repository to your machine.
2. (Optional) Create and activate a virtual environment:
   ```powershell
   python -m venv env
   env\Scripts\Activate.ps1
   ```
3. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
4. Add a `config.py` file in the project root with your NewsAPI key:
   ```python
   NEWS_API_KEY = "YOUR_NEWSAPI_KEY"
   ```
5. Start the app:
   ```powershell
   flask --app app run --debug
   ```

## Lisans / License
Bu proje için lisans belirtilmemiştir. / No license specified for this project.
