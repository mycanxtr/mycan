# mycan
MYCAN v6.66 KULLANIMI

MyCan ilk kez çalıştırıldığında gerekli çalışma klasörlerini otomatik olarak oluşturur. Bu klasörlere yerleştirilen Ana Oyun PKG, Update / Backport PKG ve yama arşivleri otomatik olarak algılanır. Dosyalar başka bir konumdaysa MyCan arayüzündeki seçim düğmeleri kullanılarak farklı klasörlerden de seçilebilir.İngilizce dili yapay zeka çevirisidir. 

PROGRAMIN TEMEL AMAÇLARI

- Ana oyun paketini açmak, düzenlemek, Türkçe yama, mod veya dosya eklemek ve yeniden paketlemek.
- Update / Backport paketlerini doğru ana oyunla eşleştirmek, senkron sorunlarını gidermek, düzenlemek, yama eklemek ve yeniden paketlemek.
- Ana oyun ile Update içeriğini birleştirerek Remastered paket hazırlamak.
- Yamaları kolay ve güvenli biçimde paylaşmak; gerektiğinde yamayı veya hazır bir Update paketini oyuna özel MyCan uygulamasının içine eklemek.

YAMA VE PAYLAŞIM ARAÇLARI

Yama Arşivi: ZIP, RAR, 7Z veya .mycan biçimindeki yama ve düzenlemelerin Ana Oyun ya da Update paketine doğrudan ve kolay biçimde uygulanmasını sağlar.

Arşiv Oluştur: ZIP veya RAR içindeki yamaları MyCan'a özel .mycan arşivine dönüştürür. Oluşturulan arşiv yalnız MyCan ile uygulanabilir; böylece yamanın bütünlüğü daha kontrollü korunur ve sonradan değiştirilme riski azalır.

Arşivi Kilitle: ZIP, RAR, 7Z veya .mycan içindeki yamayı seçilen Ana Oyun ya da Update için hazırlanmış özel bir MyCan EXE dosyasına ekler. Oluşan uygulama yalnız hedef oyun ve seçilen işlem türüyle çalışır. Son kullanıcı gerekli Ana Oyun veya Update paketini seçerek hazır yamayı kolayca uygular.

Doğrudan Update PKG Kilitle: Hazır bir Update / Backport PKG dosyasını seçilen ana oyuna özel MyCan EXE dosyasına ekler. Son kullanıcı yalnız doğru Ana Oyun PKG dosyasını seçer; MyCan gömülü Update paketini ana oyunla eşleştirerek kullanıma hazır hâle getirir.


1. HANGİ İŞLEMİ SEÇMELİYİM?

- Ana oyuna Türkçe yama, mod veya dosya eklemek: Ana Oyun Yaması
- Mevcut Update veya Backport paketini ana oyunla eşleştirmek ya da yamalamak: Update Yaması
- Ana oyun ile Update içeriğini tek oyun paketi hâline getirmek: Remastered
- ZIP, RAR, 7Z veya .mycan yamasını uygulamak: Yama Arşivi alanını kullanın
- Yamayı belirli bir oyuna özel MyCan olarak hazırlamak: Arşivi Kilitle
- Hazır bir Update PKG’yi belirli bir ana oyuna özel MyCan yapmak: Doğrudan Update PKG Kilitle

2. BAŞLAMADAN ÖNCE

- Ana oyun ve Update dosyalarının aynı CUSA / TITLE_ID değerine ait olduğundan emin olun.
- Çıktı için diskte yeterli boş alan bırakın.
- İşlem devam ederken MyCan’ı veya paketleme araçlarını kapatmayın.
- Yama arşivinin hangi oyun ve hangi sürüm için hazırlandığını kontrol edin.
- 7Z arşivi kullanacaksanız güncel 7-Zip sürümünün kurulu olması gerekir.

MyCan paketlerin türünü ve oyun kimliğini kontrol eder. Yanlış ana oyun veya yanlış Update seçilirse işlem devam etmez.

3. ANA OYUN YAMASI

1. Ana Oyun PKG alanından oyun paketini seçin.
2. İşlem Türü olarak Ana Oyun Yaması seçin.
3. Yama arşiviniz varsa Yama Arşivi alanından seçin.
4. İsterseniz Oyun Adı Eki alanına TR, Türkçe veya TR Yama yazın.
5. İşlemi başlatın.
6. Yeni ana oyun paketini repack klasöründe kontrol edin.

Ana Oyun Yaması işleminde Patch / Update PKG alanı boş bırakılır.

4. UPDATE YAMASI VE SENKRON

1. Ana Oyun PKG alanından ana oyun paketini seçin.
2. Patch / Update PKG alanından Update veya Backport paketini seçin.
3. İşlem Türü olarak Update Yaması seçin.
4. Yama arşivi kullanacaksanız seçin.
5. İsterseniz Oyun Adı Eki girin.
6. İşlemi başlatın. MyCan ana oyun ile Update uyumunu kontrol eder ve Update’i ana oyunla eşleştirir.
7. Yeni Update paketini repack klasöründe kontrol edin.

Yalnız Update PKG seçilip ana oyun seçilmezse Update inceleme amacıyla açılabilir; final Update paketi oluşturulmaz.

5. REMASTERED

1. Ana Oyun PKG alanından ana oyun paketini seçin.
2. Patch / Update PKG alanından eşleşen Update paketini seçin.
3. İşlem Türü olarak Remastered seçin.
4. İsterseniz yama arşivi ve Oyun Adı Eki seçin.
5. İşlemi başlatın.
6. Remastered ana oyun paketini repack klasöründe kontrol edin.

Ana oyun ile Update farklı CUSA değerlerine aitse Remastered işlemi yapılmaz.

6. YAMA ARŞİVİ

- ZIP, RAR, 7Z ve .mycan dosyaları Yama Arşivi alanından seçilebilir.
- 7Z kullanımı için güncel 7-Zip kurulu olmalıdır.
- Birden fazla arşiv bulunursa MyCan otomatik seçim yapmaz.

7. BEKLEME MODU

1. İşlem türünü ve PKG dosyalarını seçin.
2. Bekleme Modunu açın.
3. İşlemi başlatın.
4. MyCan dosyaları hazırladığında değişikliklerinizi tamamlayın.
5. Devam Et ve Paketle seçeneğini kullanın.

Elle değişiklik yapmayacaksanız Bekleme Modunu açmanız gerekmez.

8. ARŞİV OLUŞTUR

1. ZIP veya RAR dosyanızı Yama Arşivi alanından seçin.
2. Arşiv Oluştur düğmesine basın.
3. İstenen bilgileri girin.
4. Oluşturma işlemini başlatın.
5. Hazırlanan .mycan dosyasını saklayın veya dağıtın.

7Z yama olarak kullanılabilir ancak Arşiv Oluştur kaynağı olarak kullanılmaz.

9. ARŞİVİ KİLİTLE

Kilit türleri:
- Ana Oyun Yaması: Yama arşivi + referans ana oyun PKG
- Update Yaması: Yama arşivi + referans ana oyun PKG + referans Update PKG
- Doğrudan Update PKG Kilitle: Referans ana oyun PKG + kilitlenecek Update / Backport PKG

Adımlar:
1. Arşivi Kilitle düğmesine basın.
2. Kilit türünü seçin.
3. İstenen PKG ve yama dosyalarını seçin.
4. Yama adı ve sürüm bilgisini girin.
5. İsterseniz Oyun Adı Eki girin.
6. Update yalnız belirli bir sürümü destekliyorsa sürüm kilidini açık bırakın.
7. Kilitli MyCan dosyasını oluşturun ve test edin.

10. KİLİTLİ MYCAN KULLANIMI

- Ana Oyun Yaması: Yalnız doğru Ana Oyun PKG seçilir.
- Update Yaması: Doğru Ana Oyun PKG ile Update / Backport PKG seçilir.
- Doğrudan Update PKG Kilidi: Yalnız doğru Ana Oyun PKG seçilir. Update uygulamada hazırdır.

Kilitli MyCan yalnız hazırlandığı oyun ve işlem türü için çalışır. Yanlış oyun veya yanlış paket türü seçilirse işlem başlamaz.

11. SENKRON VE HATA UYARILARI

- Ana oyun ve Update eşleşmiyor: Aynı CUSA / TITLE_ID değerine ait paketleri seçin.
- Yanlış paket türü seçildi: Ana oyun ve Update alanlarındaki dosyaları kontrol edin.
- Update sürümü uygun değil: Yamanın desteklediği Update sürümünü kullanın.
- Disk alanı yetersiz: Yeterli boş alan oluşturup yeniden deneyin.
- Paketleme düzeltme seçeneği gösterildi: Ekrandaki açıklamayı okuyup önerilen güvenli seçeneği uygulayın.
- İşlem yarıda kaldı: MyCan’ı yeniden açın ve önceki işlem tamamlandıktan sonra tekrar deneyin.

12. ÇIKTI VE SON KONTROL

1. İşlem sonunda başarı mesajını bekleyin.
2. repack klasöründeki yeni PKG dosyasını bulun.
3. Dosya adını ve Oyun Adı Eki bilgisini kontrol edin.
4. Çıktıyı ayrı bir klasöre kopyalayın.
5. Sorun yaşarsanız son mesajı ve işlem logunu destek için paylaşın.

ÖNEMLİ: İşlem türünden emin değilseniz yamanın hazırlayıcısından ana oyun yaması mı yoksa Update yaması mı olduğunu öğrenin. Arşiv içeriğine bakarak her zaman kesin karar verilemez.
