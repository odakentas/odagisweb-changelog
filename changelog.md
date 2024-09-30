# Değişiklik Geçmişi

Bu projedeki tüm önemli değişiklikler bu dosyada belgelenecektir.

## [24.09.27]
- Admin paneldeki konum izleme sistemi webe entegre edildi.
- Artık alarmlar basıldığında tüm alarmlar değil sadece oto açık olan ayarlar açık olup diğerleri kapalı gelmesi ayarlandı.
## [24.09.24]
- Prime react güncellendi.(Webde eğer arayüzde bozulma yaşandıysa kullancıların cache temizlemesi gereklidir.)
- Artık bir cbs haritasında bir katmanın diğerlerinin üstünde gözükmesini isteyen kullanıcılar katmanı açıp kapatırsa artık o katman en üstte gözükecektir.
## [24.09.13]
- Dashboard filtreleme özelliği eklendi.
- Mobil info responsive yapıldı.Artık ekran dışına taşması engellendi.
## [24.07.22]
- 3d katmanları admin paneldeki yeni sisteme göre güncellendi.
## [24.07.16]
- Artık mobilde çizmiler harita sekmesinde gözükmesi ve oradan da kml olarak dışarı aktarılması eklendi.
- Grafiklerde dataların excel olarak dışarı aktarılması eklendi.
- Join tablo sistemi webe eklendi.
- Kayıt edilmiş özel harita güncellenirken eski çizmlerin korunması sağlandı ama kullanıcı isterse eski çizimlerin silebilir.
- Shp dosyaları artık webdeki güncel epsg göre dışarı aktarılıyor.
- Harita vektör haritalara eklenen kml katmanlarının özelleştirilmesi eklendi. 
## [24.05.20]
- Çıktı alırken Türkçe karakterlerin bozulması sorunu giderildi.
- Info foto galerideki hatalar düzeltildi.
- Rapor chart map ve grafik tipinde güncellemeler yapıldı.  
## [24.05.17]
- Alarma tıklanmama sorunu giderildi.
- Editör mobilde zoom yapınca nokta atma hatası düzeltildi.
- Info galeri artık oto açılması sağlandı.
- Tüm tablolara sütun genişletme özelliği eklendi.
- Tablolarda sütun isimlerinin sabit kalması eklendi.
- Tablete özel ayar eklendi.
- CSS hataları giderildi.
## [24.05.10]
- CBS Haritalarındaki treeview optimizasyonu yapıldı ve hataları giderildi.
## [24.05.07]
- Özelleştirebilir info dizaynın entegresi tamamlandı.
- Bu infonun responsive olması sağlandı.
## [24.04.26]
- Yeni dashboard sistemi webe entegre edildi.
- Özelleştirebilir info dizaynı sisteme entegresine başlanıldı.
## [24.04.08]
- Hazır sorgu ve dinamik sorgu tablo bilgi sonucuna filtre ve sort özelliği eklendi.Ayrıca istenmeyen sütunlar artık gizlenebiliyor.
- Aynı nokta bulunan alarmlara basıldığında artık info yerine bir tablo getirildi.Kullanıcı o noktadaki tüm alarmların bilgisini alabilir.
- Info fotoğraflar için galari entegre edildi.
  
## [24.04.02]
- CBS haritlarındaki lejant artık ilk açılışta yüklenmesi durduruldu.(Lejantların boyutundaki büyüklüklerden dolayı yavaşlığa sebep oluyordu)
- Lejant dosya yükleme boyutu getirildi. 
## [24.02.28]
- Nokta Editör import/export eklendi.
- Nokta Editörde bazı katmanların listeye atılmaması sorunu düzeltildi.
- Map -> Kurumsal Harita kısımına scroll eklendi.
- Hazır sorgu ve dinmaik sorgularda tablolara filtreleme özelliği eklendi.
- Geomesajda iyileştirme yapıldı.

## [24.02.23]
- Editor -> Data Table kayıtların sırası en yeniden en eskiye olarak güncellendi.
- Sağ alt kısımdaki buttonlara nokta editorü eklendi.
- Info card kısmında dialog büyütüldüğünde artık sadece sol tarafın büyümesi düzeltildi.
## [23.12.26]
- Editörde data table yeni kayıt ekleme ekranında ilk açılışta combolar arasında ilişkiye göre combo içersindeki datalar filtrelenir.
- Editör data table veri düzenleme eklendi.
- Editor data tabloda css değişklikleri yapıldı.
- Editor data tabloda filtreleme eklendi.Ayrıca kullanıcı isteği sütünları kaldırarak tabloyu sadeleştirebilir
- Kullanıcı panelinde kullanıcı listesini artık Ad soyad şeklinde ayarlandı ayrıca çevirim içi kullanıcı sayısındaki hata giderildi.
- İnfo data tablo kısmına filtreleme özelliği eklendi.

## [23.11.23]
- Editörde sütünların güncellenme hatası giderildi.Editör data tablolarında combo trigger sorunu düzeltildi.
- Raporda en son görüntülenen dashboardun hafaızda tutulması sağlandı.
- Info alınan objede data tablonun görüntülenme önceliği arttırıldı.
- Map kısmından export edilen çizimler düzeltildi.
- Özel haritada yen çizimler artık eski çizimler üzerine yazması düzeltildi.Oluşturulmuş özel haraitalarda çizimler güncellenebiliyor.
- Kml export ederken sembollerde notlar artık label olarak ayarlandı. 

## [23.10.20]
- Info Card kısmında tab değişimleri daha belirgin hale getirildi.
- Hazır sorgu kısmında indirilen tablo bilginden geometri kısmı çıkarıldı.
- Editör -> Sözel Bilgi Güncelle -> data tablo kısmında stil değişklikleri yapıldı.
- Ekranı böl kısmında artık katmanlar 2 haritada gösteriliyor. Ayrıca ekranı böl aktifken altık harita değişimi 2. haritayı etkiliyor. 

## [23.10.06]
- CBS treeview görünümde yeni eklenenen haritanın renderlanmama ve otomatik seçili gelmeme sorunu giderildi.

## [23.10.05]

- CBS haritalarındaki katmanlar artık kullanıcı bazlı özelleştirilebilir hale getirildi.Özelleştimek istenen katmana sağ tıklanarak bu işlem uygulanabilir.

## [23.09.29]

- Objeden info alırken çıkan data tablo ilgili stil değişklikleri yapıldı.
- İnfodaki data tablodaki dökümanlarda resim olmayanlar dosyalar için indirilme seçeneği eklendi.
- Pdf exporta artık sayfa boyutu seçme özelliği eklendi.Butona sağ tıklanarak istenilen boyutta dosya indirilebilir.
- Raporda dashboard listesi artık alfabetik sıralanıyor.
- Data tablolara ait alarmlarda artık alınan tablo ve normal info data tabloya ait bilgiler olarak değiştirildi.
- Boş altıkta oluşan hata giderildi.
- Harita treeview artık yapılan seçimleri hafızaya alındı.
