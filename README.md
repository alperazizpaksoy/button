# button

Kullanimi:
Kodu calistirdiginizda onunuze 4x4 bir buton paneli cikicak.Karsinizdaki butonlardan herhangi birine tikladiginizda siz de fark ediceksiniz ki rengi ve butonun merkezinde olan simge degisecek.Ve eger bir butona tikladiktan sonra baska bir butona tiklar iseniz ilk tikladiginiz buton eski haline donecektir.Eger koda GraphQL mutation islemini eklediyseniz tabii ki.Bu basit buton uygulamasi gelistirilerek mayin tarlasi gibi oyunlara donusebilir.

GraphQL:
Yukarida bahsettigim GraphQL'i biraz acikliyalim  , GraphQL bir sorgu dilidir.API lerle etkilesimde bulunmak icin kullanilir.RESTful API'lerin yerini alan GraphQL istemcilerin ihtiyac duydugu ozel verileri sorgulari ile talep etmemize olanak saglar ve bu ise yarar.Bu buton projemizde ise yukarda da dedigim gibi GraphQL mutation eklenmesi gerekti.Mutation dedigimiz ise veritabanindaki degisimleri ifade eder bu uygulamada ornek olarak butona tikladigimizda butonun degisimi icin buna ihtiyac duyduk.
Biraz daha detaya inersek : 

Test Etme Ve Gelistirme: 
Uygulamayi test etmek veya gelistirmek icin koddaki bolumleri duzenleyebilirsiniz.Zaten kod bolumunde elimdene geldigince acik olmaya calistim.Test etmek veya guncellemek istiyorsaniz cok zorluk cikarcagini dusunmuyorum.Ve Koddaki ButtonControlPanel class inin icinde renk ve simge bolumune bakarsaniz orda ki renk ve simgenin butonlarla uyusup uyusmadigina bakarak duzgun calisip calismadigini test edebilirsiniz.


