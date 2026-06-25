# loop-daily

Proje adı:KİŞİSEL GELİŞİM GÜNLÜK MOTİVASYON MOBİL UYGULAMA 
Öğrenci adı:AYDANUR GÜN
Öğrenci numarası:24010509116
Projenin amacı ve kısa açıklaması:Bu uygulama insanların günlükrutinini oluşturma ve motivasyon hedeflerine ulaşmakta zorlanma problemini çözmek için kişiselgelişim ve günlük rutin motivasyon uygulamasıdır
Kullanılan teknolojiler / kütüphaneler: CHATGPT,GEMİNİ,STİTCH ,ANTİGRRAVİTY 

Proje klasör yapısı:
LoopDaily/
├── .expo/                  # Expo'nun çalışma zamanı (runtime) için otomatik ürettiği önbellek dosyaları
├── assets/                 # Uygulama içi görseller, logolar ve yazı tipleri (Fonts)
│   ├── adaptive-icon.png   # Android için uyarlanabilir uygulama ikonu
│   ├── favicon.png         # Web önizlemesi için tarayıcı ikonu
│   ├── icon.png            # Standart uygulama ikonu
│   └── splash.png          # Uygulama açılırken ekrana gelen yüklenme görseli (Splash Screen)
├── node_modules/           # Paket yöneticisi (npm) tarafından yüklenen tüm kütüphane ve bağımlılıklar
├── App.js                  # TÜM KAYNAK KODLARIN BULUNDUĞU ANA DOSYA (Tasarım, Fonksiyonlar ve Logic)
├── app.json                # Uygulamanın adı, versiyonu ve ikon ayarları gibi Expo yapılandırma dosyası
├── package.json            # Projenin bağımlılık listesi (AsyncStorage, Vector-Icons vb.) ve script komutları
└── package-lock.json       # Yüklenen paketlerin tam sürümlerini kilitleyen, npm tarafından yönetilen dosya

Kurulum adımları:# 1. Yeni bir Expo projesi oluşturun
npx create-expo-app LoopDaily --template blank

# 2. Oluşturulan proje klasörünün içine girin
cd LoopDaily
# 3. Gerekli bağımlılıkları yükleyin
npx expo install @react-native-async-storage/async-storage @expo/vector-icons

Çalıştırma / kullanım talimatları
Varsa ekran görüntüleri: Loop Daily - Çalıştırma ve Kullanım Kılavuzu
Bu kılavuz, kurulumu tamamlanmış olan Loop Daily uygulamasını mobil cihazınızda nasıl başlatacağınızı ve uygulamanın tüm fonksiyonlarını (Su takibi, BMI hesaplama, kronometre ve notlar) nasıl etkin bir şekilde kullanacağınızın adımlarını içerir.

🟢 1. Uygulamayı Başlatma (Çalıştırma)
Uygulamayı her test etmek veya kullanmak istediğinizde aşağıdaki adımları tekrarlamanız gerekir:

Terminali Açın: Projenizin kurulu olduğu ana klasörde (LoopDaily) terminalinizi veya komut satırını açın.

Projeyi Başlatın: Aşağıdaki komutu yazarak Expo sunucusunu ayağa kaldırın:

Bash
npx expo start
QR Kodu Taratın: * Android: Telefonunuzdan Expo Go uygulamasını açın ve "Scan QR Code" butonuna basarak terminaldeki kodu taratın.

iOS (iPhone): Telefonunuzun kendi Kamera uygulamasını açıp QR kodu gösterin ve gelen bildirime tıklayın.

Yükleme: JavaScript paketleri %100 olana kadar birkaç saniye bekleyin. Uygulama telefonunuzda açılacaktır.

⚙️ 2. Temel Kullanım Talimatları
Uygulama arayüzü tek bir ekrandan oluşur ve günlük rutinlerinizi yönetmenizi sağlayan 5 ana bölüm barındırır:

🧑‍াগ Profil ve Hedef Ayarları (İlk Kullanım)
Sağ üst köşede bulunan Ayar / Profil İkonuna (dişli çarklı hesap butonu) dokunun.

Açılan pencerede İsminizi ve Günlük Su Hedefinizi (Bardak cinsinden) girerek "Kaydet ve Kapat" butonuna basın. Uygulama artık size isminizle hitap edecektir.

💧 Su Takibi Paneli
Gün içinde su içtikçe "1 Bardak Ekle" butonuna basarak sayacı artırın.

İçtiğiniz miktar, belirlediğiniz günlük hedefe ulaştığında uygulama ekranda bir kutlama tebriki (Tebrikler! 🎉) gösterecektir.

Yeni bir güne başlarken sağ üstteki "Sıfırla" yazısına dokunarak su sayacını sıfırlayabilirsiniz.

😊 Mod Durumu Belirleme
"Bugün Nasıl Hissediyorsun?" başlığı altında yer alan mod butonlarından (Harika, Normal, Yorgun, Stresli) durumunuza uygun olanına dokunun. Seçtiğiniz mod renk değiştirerek aktif hale gelecektir.

⏱️ Egzersiz Süresi Kronometresi
Antrenmana veya aktiviteye başlarken "Başlat" butonuna basın.

Dinlenme aralarında veya egzersiz bittiğinde "Duraklat" yapabilirsiniz.

Süreyi tamamen sıfırlamak için "Sıfırla" butonunu kullanabilirsiniz.

🏃‍♂️ BMI (Vücut Kitle Endeksi) ve Egzersiz Önerisi
Boy (cm) ve Kilo (kg) alanlarına güncel bilgilerinizi yazın.

"Hesapla ve Öneri Al" butonuna dokunun.

Sistem anında vücut kitle endeksinizi hesaplayacak, Zayıf, Normal, Fazla Kilolu veya Obez kategorilerinden hangisinde olduğunuzu belirtecek ve durumunuza özel sağlıklı egzersiz tavsiyesini alt panelde listeleyecektir.

📝 Günlük Notlarım
"Notunuzu yazın..." alanına dokunarak o günkü spor, beslenme veya ruh halinizle ilgili notlar alın ve "Ekle" butonuna basın.

Notlarınız, eklendiği saat bilgisiyle birlikte alt alta listelenir.

Silmek istediğiniz notun sağ tarafında bulunan Kırmızı Çöp Kutusu ikonuna dokunarak notu kaldırabilirsiniz.

GitHub proje bağlantısı: https://github.com/aydanurgun1-netizen/loop-daily/blob/main/README.md

Kaynakça veya yararlanılan bağlantılar:https://gemini.google.com/app/f9275801027a7704?hl=tr
https://chatgpt.com/?utm_source=google&utm_medium=paid_search&utm_campaign=GOOG_C_SEM_GBR_Core_CHT_BAU_ACQ_PER_MIX_ALL_EMEA_TR_TR_020425&c_id=22200080104&c_agid=176486813978&c_kwid=kwd-1927227100722&c_ims=&c_pms=1012786&c_nw=g&c_dvc=c&gad_source=1&gad_campaignid=22200080104&gbraid=0AAAAA-I0E5fvcQP1Na9qKOTeCFa7pUxsJ&gclid=Cj0KCQjwo_PRBhDNARIsAEcVALUyN08WDKscpu5gDRt1ipXDo0nNy--G3xRIyZEn-4p-s5eHnCHkstcaAoOzEALw_wcB
https://stitch.withgoogle.com/
https://antigravity.google/
