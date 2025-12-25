    @page { size: 8.5in 11in; margin: 1in } p { margin-bottom: 0.1in; line-height: 115%; background: transparent }

_Yazılım Ekosistemi sunumu_

  
  

_3 Aralık 2025_ _Çarşamba_

  
  

_Yazılım Ekosistemi nedir?;_

_Yazılım denince aklınıza neler geliyor? Belkide hi__ç_ _bir şey gelimiyor ancak zaten gelmesinede gerek yok ._

_Bug__ü__n sizlere hem yazılımın ne olduğunu basit bir dille a__ç__ıklayacağım hemde yazılımın i__ç__indeki ekosistemi anlatacağım ancak "yazılım ekosistemi" derken ne kastettiğimi tam olarak netleştiremediyeniz a__ç__ıklamama izin verin;_

  

_Yazılımın B__ü__y__ü__k bir d__ü__nyadır aynen bizim d__ü__nyamız gibi o d__ü__nyanın i__ç__indede dev gibi bir evren vardır_

_bunu derken abartmıyorum cidden_ _ö__yle o y__ü__zden her şey d__ü__zenli bir şekilde sistemli olarak ayrılmıştır_

_tam olarak belirli makaleli veya d__ö__k__ü__manlı kanıtlanmış bir ekosistem olmasada bug__ü__n ben sizler i__ç__in_

_yazılım ekosistemi başlığı altında bunları anlatacağım_ _Ö__rneğin bizim_ _ç__evremizdeki ekosistemde_

_ağa__ç__lar,g__ö__ky__ü__z__ü__,hava,oksijen vb. gibi etkenler vardır yazılımdada pek farklı değil tek farkı konuları ve terimleri_

  

_Yazılım nedir?_

  

_Yazılım kısaca__;_ _bilgisayarların ve cihazların donanımlarını kullanarak kendi i__ç__lerindeki işlemleri ger__ç__ekleştirebilmeleri, matematiksel hesaplamalar, insan fakt__ö__r__ü__n__ü__n algılayamayacağı kadar fazla veriyi doğru oranda okuyabilen işleyebilen ve makinelerin beyinlerini oluşturan kodlardan oluşan bir dildir genelde yazılımcılar kodları_ _ç__eşitli yazılım dilleri ile yazarlar bu şekilde yukarıda belirttiğim şeyleri ve hatta fazlasını yapabilirler._

![](bilisim_sunumu_html_eff3f940.gif)

  

Modül Nedir?

  

Modül; Yazılım dilinde birden fazla fonksiyondan oluşan ve bir amacı yerine getirmek için tasarlanmış amacı kodların daha kısa ve ölçeklenebilir yazılmasına yardımcı olmaktır; örneğin bir matematik işlemini yazılımda uzunca yazmak yerine modül sayesinde tek bir fonksiyon ile halledebilirsiniz. Modüller kodları kolaylaştırmakla kalmazlar ayrıca yazılımı öğrenmeyide açık ara farkla çok ciddi şekilde kolaylaştırırlar örneğin yazılımda her şeyin bir modülü vardır Renkmi yapıcaksın modülü var İntegralmi çözüceksin modülü var Trigonometrimi çözüceksin modülü var Matematiksel bir denklemmi kurucaksın? Modülü var sadece matematikle sınırlı değil Estetik,Sistem,Matematik,Ağ,İnternet,Veri işleme veri görselleştirme coğrafi bilgi sistemleri(cbs) gibi etkenlerle alakalı kodlar yazacaksanız bunlarla alakalı modüllerde var ve sadece bunlarla sınırlı değil. düşündüğünüzden çok daha fazla modül yelpazesine sahiptirler.

  

Örnek modüller;

  

_\-------------------------------------------------------------_

_MATEMATİKSEL MOD__Ü__LLER_

_\-------------------------------------------------------------_

_Numpy Mod__ü__l__ü__;_ ![](bilisim_sunumu_html_c010468e.gif)

  

Bu modül matematiksel bir modüldür pythonda bir çok matematiksel işlemi algoritmayı ve formülü yazmayı kolaylaştırır Vektörler,Matrisler,Tensorlar gibi veri tiplerini barınıdırır numpyde vektörlere NDarray yani Array(arrey) denir Türkçesi dizi olarak geçer; ayrıca Numpy'da trigonometrik fonksiyonlar,logaritmik fonksiyonlar gibi birden fazla matematiksel fonksiyonda bulunur matrislerin vektörlerin ve tensorlerin üzerine bu fonksiyonları rahat bir şekilde uygulamnanızı sağlar bir cok fonksiyonu vardır arrayları yeniden boyutlandırma mutlak değerşlerini alma veri tiplerini değşirme(örneğin tam sayıları ondalık yapma gibi) bir cok işlevdede kullanılır Açılımı ise Numerical Python olarak geçer

  

_Math Mod__ü__l__ü__;_

  

![](bilisim_sunumu_html_24118de7.gif)

Math modülü daha çok pythonda matematiksel işlemleri uygulamak için kullanılır ancak bu modülü Numpy ile karıştırmayın ikisi çok farklıdır yine ikiside aynı fonksiyonları bulundurur ancak math modülünde vektörler matrisler tensorler gibi veri tipleri yoktur bunları desteklemez gündelik matematik veya ileri seviye matematiksel işlemleri gerçekleştirebilir sayılar üzerinde çalışır buradada nerdeyse her matematiksel fonksiyon ve işlev bulunur

  

_SymPy Mod__ü__l__ü_

  

![](bilisim_sunumu_html_331a9074.gif)

SymPy pythonda numerik işlemler ve matematiksel işlemlere destek için kullanılır karmaşık gelmesin matematik ile alakalı bir kod yazarken sembollere ihitiyaç duyarız python terminal tabanlı bir yazılım dili olduğu için terminaldeki semboller ve klavyemizden koyabileceğimiz semboller sınırlıdır o yüzden SymPy matematiksel ifadelerimize sembolleri eklememize ve semboller ile gösterim yapmamıza yardımcı olan bir modüldür ayrıca bu modülde diğerleri gibi güçlü bir modüldür

  

  

  

_\-------------------------------------------------------------_

_SİSTEM MOD__Ü__LLERİ_

_\-------------------------------------------------------------_

_Sys Mod__ü__l__ü__;_

![](bilisim_sunumu_html_63708f8.gif)

Sys modülü; pytonda sistem işlevlerini gerçekleştirmemiz için gerekli bir modüldür örneğin programımızı kapatma,terminale yazı yazdırırken daha özelleştirilebilir şekilde yazı yazmamızı sağlayan farklı fonksiyonları ve asıl işlevi olan işletim sistemi(OS) ile iletişime geçebilmek olan ve terminalle alakalı işlemlerde kullanılmasıdır;

  

_Os Mod__ü__l__ü__;_

![](bilisim_sunumu_html_8aae9e55.gif)

Os modülü; Python ile sistemimizdeki dosyalara erişim sağlamamıza yardımcı olur bu modül bilgisayarımızdaki dosyaları okuyabilir silebilir üzerine yazabilir(overwrite) dosya adından dosya dizinini bulabilir ve aklınıza gelip gelebilecek her türden dosya işlemini yapabilir bu modülün amacı ise bilgisayarınızdaki dosya sistemine erişim sağlayarak dosyalarınızı ve belgelerinizi yönetmesi onları değiştirebilmesi üzerinde oynayabilmesidir. Ancak daha bir çok işlevdede kullanılır tek işlevi dosya açıp kapatmak değildir bu modülde diğer modüller gibigüçlü ve ölçeklenebilir bir modüldür

  

  

_Subprocess Mod__ü__l__ü__;_

![](bilisim_sunumu_html_98509a83.gif)

Subprocess modülü; pythondaki bu modül sisteminizdeki terminali yönetebilir ordan komutlar çalıştırıp size çıktıları verebilir terminalinizi yönetebilir ve terminaliz ile alakalı olan aklınıza gelebilecek her türden işlemi gerçekleştirebilecek bir modüldür asıl amacı ise anlattığım gibi komut sisteminizde komutlar çalıştırmaktır.

  

  

  

_\-------------------------------------------------------------_

_SES MOD__Ü__LLERİ_

_\-------------------------------------------------------------_

  

_PyAudio Mod__ü__l__ü__;_

![](bilisim_sunumu_html_9af67b01.gif)

  

Pyaudio modülü; pytonda ses işlemleri için kullanılan bir modüldür bu modül elinizdeki bir .mp3 veya .wav dosyasını byte(bayt) düzeyinde işleyerek çalar ve size sesi verir ancak tek amacı bu değilidir;

bu modül sandığınızdan daha güçlüdür çünkü; Ses çalarken bytelarını dönebilmek gibi gelişmiş özellikler ile donatılmıştır ayrıca dahasını yapabilecek bir modüldür ve güncelleme alan modüller arasında yer alır.

  

  

_PlaySound Mod__ü__l__ü__;_

![](bilisim_sunumu_html_6fedbcc0.gif)

Playsound modülü; pythonda .wav .mp3 gibi dosya formatlarını çalabilmenizi sağlayan bir modüldür daha çok küçük işlevler için kullanılır çok büyük bir modül değildir genellikle bir programda ufak çaplı sesleri çalmak için kullanılır;

  

  

_SoundDevice Mod__ü__l__ü__;_

![](bilisim_sunumu_html_e42f64d4.gif)

  

Sounddevice modülü; Bu modül cidden çok güçlüdür bu modülün temel işlevi ses dosyalarnı alıp byte düzeyinde işleyebilmektir ayrıca bu sesleri işlerken aynı anda çalarlar ve çalarkende verileri dönerler(yani verileri istenilen yere gönderip işlenmesini sağlarlar buda senkronize bir işlem sırası oluşturur) genelde böyle şeyleri pyaudio gibi modüller ile yapmak zordur hatta çoğu zaman pek mümkün değildir ses verisinin büyüklüğü arttıkça donmalar meydana gelir ancak bu pyaudioda olur sounddevice modülünde böyle takılmalar çok nadiren gerçekleşir onun sebebide genelde yazılımcının yaptığı bir optimizasyon hatası olur ayrıca bu modülde Callback sistemi mevcuttur bu sistem ses çalınırken dediğim veri gönderme ve ekstra işlemleri gerçekleştirebilmesini sağlar AYRICA bu modülün en çarpıcı kısmıda şudur; Hem mikrafon verilerini işleyebilir yan sizin konuşmanızı algılayabilen bir fonksiyonuda bulunur hemde girdi yani eksta bir dosya ile işleyebilirsiniz veya sisteminizdeki sesleri algılaması içinde tasarlayabilirsniz bu açıdan çok zengin bir modüldür mikrofon dosya sistem sesleri gibi etkenleri işleyebilir ancak bu modülde sayılsa veri ister bu sayısal veriden kastım bir çeşit ses matrisidir genelde şöyle gözükürler

![](bilisim_sunumu_html_9045abb9.gif)

  

  

_SoundFile Mod__ü__l__ü__;_

![](bilisim_sunumu_html_1ecc2212.gif)

  

Soundfile modülü; .wav dosyalarını işlemek ve onların metadatalarını(ham verilierini) almak için kullanılan bir modüldür bu modül bir ses dosyasının kanal sayısı,örnek başına örnekleme sayısı, toplam örnek sayısı gibi bir çok veriyi size verir ancak en önemlisi ses verisini size matris formatında verebilmesidir bu modüldeki dosyayı okuma fonksiyonu cok güçlüdür dosyayı okuyup size buffer arrayını verir ve bunun içindede tamsayılar mevcuttur bu tamsayılar farklı modüller sayeseinde byte düzeyinde yorumlanır ve sese çevirilir ancak bu modül sesi doğrudan oynatamaz

  

  

  

_Wave Mod__ü__l__ü__;_

![](bilisim_sunumu_html_b8a1448d.gif)

Wave modülü pythonda .wav dosyalarını işlemek için açık ara en kapsamlı modüllerden birisidir

Wav dosyalarının Kaç saniye olduğunu saniye başına örnekleme hızınını byte matrisini toplam örnek sayısını kanal sayısını örnek genişliği gibi birden fazla değerini bizlere dönebilir ancak kötü yanlarından birisi döndüğü byte matrisini dirket olarak işleyemezsiniz numpy modülü ile bu byte matrixini buffer matrixine çevirmen gerekir ve bunu yaparkende kanal sayına göre yapman gerekir ve bunu manuel değil otonom bir şekilde yapman gerekir ancak bununlada sınırlı değil buffer array elde edildikten sonra boyut sorunları meydana gelebilir(shape sorunları) boyut sorununundan kastım şu; dönen byte matrisini byte matrisine çevirdikten sonra boyutu nötrlenir ve bu boyuttaki büyük bir matrisi işlemek istediğinizde sorunlar meydana gelir bunu çözebilirsiniz ancak kısa yoldan halletmek için büyük projelerde soundfile gibi araçlşarı kullanmanız ve sesin bilgileri içinde wave modülünü kullanmanız önerilir.

  

  

_Speech\_Recoginiton Mod__ü__l__ü__;_

![](bilisim_sunumu_html_c2dd547c.gif)

speech\_recoginiton modülü pythonda mikrofndan verdiğiniz bir sesi metine dökmek için kullanılır backendinde esasta bir dil modeli kullanır ve bu dil modeli neredeyse İçinde Türkçe'ninde bulunduğu tüm dilleri kapsıyor denebilir; Kapsamlı bir modüldür ve asıl amacı anlattığım gibi bellidir İnsan sesini yazıya çevirmek.

  

  

_\-------------------------------------------------------------_

_Ağ MOD__Ü__LLERİ_

_\-------------------------------------------------------------_

  

_Socket Mod__ü__l__ü__;_

![](bilisim_sunumu_html_964dee26.gif)

_Socket mod__ü__l__ü_ _pythonda networking yapmanızı sağlar Port,İp_ _ü__zerinden belirttiğiniz bir servera erişim sağlayıp oraya veri g__ö__nderme veri_ _ç__ekme dosya g__ö__nderme dosya_ _ç__ekme gibi işlemleri ger__ç__ekleştirebilirsiniz. Bazı mod__ü__llerinde desteği ile k__ö__t__ü__ye kullanıma a__ç__ık bir mod__ü__ld__ü__r ancak bunula birliktede aslında cokta işlevseldir bu mod__ü__l__ü__n temeli şudur; bir server oluşturursunuz ve bu servera bağlanacak bir client oluştrurursunuz bunları yaptıktan sonra serverı başlatırsınız ve o serverın ip ve portuna bağlanacak bir client kodlarsınız kodladığıonız client servera bağlanır ve serverda kurduğunuz mekanizma ip ve portu size d__ö__nd__ü__r__ü__r ve bir cihaz bağlandı diye uyarı mesajı atar işte ilk socket kodunuzu yazdınız socket temelde buna dayansada karmaşık yapıları ve birden fazla parametresi,fonksiyonu ile bazen kafaları karıştıran bir mod__ü__ld__ü__r ancak son derece kapsamlı ve g__üç__l__ü__d__ü__r siber g__ü__venlik alanlarında network testi gibi şeylerde kullanılır_ _ö__rn; Brute force ile port bulan bir sistem vb. Yani bir_ _ç__ok şeyi ger__ç__ekleştirebilen temel bir ağ mod__ü__l__ü_ _olarak python bize bunu sunar_

  

  

_Python-Nmap Mod__ü__l__ü__;_

  

![](bilisim_sunumu_html_8d8216c2.gif)

_Python-Nmap mod__ü__l__ü_ _nmap isimli terminal tabanlı bir siber g__ü__venlik aracını pythonda_ _ç__alıştırmanızı sağlar ve bu aracın cogu parametresini fonksiyonunu neredeyse hepsini i__ç__ine almıştır; peki ya nmap nedir? Nmap networking/Port tarama ağ analizi gibi işlemlerde olduk__ç__a başarılı bir port tarama aracıdır inanılmaz b__ü__y__ü__k bir komut yelpazesi ve birden fazla işlevi vardır bununla beraberde i__ç__inde birden fazla payload(__Ü__st bilgi) bulunur ancak nmap hakkında bir_ _ç__ok konu vardır ve pythondan farklı bir konuya gireceği i__ç__in şimdi tekrar pythona ge__ç__iyorum Pythondaki nmap mod__ü__l__ü_ _şu işlevleri yapıyor; a__ç__ık-kapalı port bulma port tarama portların bağlı oldugu ip adreslerini bulma ip adreslernin bağlu olduğu portları bulma etraftaki ağları taramak ve birden fazla nmap komudunu kendi_ _ç__inde_ _ç__alıştırıp_ _ç__ıktıları bize sunabilir Ayrıca bu mod__ü__l son derece k__ö__t__ü__ye kullanıma a__ç__ıktır ancak bu mod__ü__l zor ve syntax(sintaks)'ı karmaşık olduğu i__ç__in genelde script kiddie(deneyimsiz hackerlar) bu mod__ü__l__ü_ _kullanamaz veya cok daha temel d__ü__zeyde kullanabilir_

  

_Requests Mod__ü__l__ü__;_

![](bilisim_sunumu_html_6d3a711e.gif)

_Mottosu: Http for humans(insanlar i__ç__in http)_

  

Pytondaki Requests modülü HTTP ve APİ istekleri için kullanılan bir modüldür internet sitelerinden ver APİ(Application Program İnterface)'lardan veriler çekmek için kullanılır bu modül APİ den çekilen veriyi genelde iki türlü alır 1. text olarak yani html olarak alır veya 2. olarak .json formatında alır genelde 2. payload tipi çok daha yaygın kullanılır ancak özel durumlarda bu payloadlar farklı bir formata parse edlebilir Şimdi ise neler yapabilidğine gelelim; örneğin bir program kullanıyorsunuz mesela e-devletten soy ağacınızı sorugluyorsunuz sorguyu başlattığınız anda bir APİ ye istek atılıyor ve o APİ den gelen veri size gösterliyor tabikide bu tür büyük kuruluşların ve kurumların kullandığı apiler gizli olur yani bir çeşit Authotentication(yetkilendirme metodu) kullanılır bu metod APİ KEY olarak geçer örnek bir APİ key şöyle gözükür

  

AIzaSyDaGmWKa4JsXZ-HjGw7ISLn\_3namBGewQe

  

Yukarıdaki kompleks yapı bir APİ Key örneğidir tabikide bu key'in bi geçerliliği yok sadece sahte bir key ancak keyler tam olarak buna benziyor tabikide daha farklı keyler kullanan APİ ler var özel siber güvenlik önlemleri ile donatılan APİ keyleri bile mevcuttur şimdi ise HTTP İsteklerine gelelim bu yöntem siteye bir istek gönderip siteden gelen yanıtı kendi lehine kullanarak size bir .html yani .text döner bunu parse ettiğinizde içinden istediğiniz verileri bulabilirsiniz örneğin; haber başlıkları, metinler gibi web sitesi elemanlarının içindeki şeyleri çekebilirsiniz.

  

Yukarıda anlattıgım işlevleri gerçekleştirmek için tasarlanmış bu modül pythona büyük bir katkı sağlamıştır.

  

  

_Selenium Mod__ü__l__ü__;_

![](bilisim_sunumu_html_bfe49d15.gif)

  

İsmini periyodik tablonun selenyum34 elementinden alan bu modüldeki "element" kelimesi çok önemlidir;

  

esasında bir python modülü olan selenium internet sitelerindeki verilerin elementlerini kullanarak onların içinden anlamlı verileri çekip bizlere verebiliyor bunları yaparken XPATH,HTML vb vb gibi bir çok elementi destekler web sitelerinden resim fotoğraf video yazı veri sayı rakam gibi birden fazla veriyi çekebilir http istekleri ile çalışır site kaynağına erişim sağlar(bu sadece front-end yani html kodları demek herkesin görebildiği verilerdir selenium bunları parserları ile işler ve bize anlamlandırarak veriler çıkartır) kısaca bunları yapan bu modül daha bir cok işlevi olmasına rağmen kısaca ancak bu şekilde açıklanabilir.

  

  

_\-------------------------------------------------------------_

_Veri G__ö__rselleştirme MOD__Ü__LLERİ_

_\-------------------------------------------------------------_

  

_Matplotlib Mod__ü__l__ü__;_

![](bilisim_sunumu_html_dc3ac6d5.gif)

Bu modül pythonda veri görselleştirme yapmak için kullanılan bir modüldür Matris,Vektör,Tensor gibi bir çok veriyi destekler grafik olarak görselleştirir ayrıca elinizde bir görüntü matrisi var ise matplotlib sizin için bunu görselleştirebilir yani o matrisin resmini kendi figürünün içinde gösterebilir; görüntü matrixleri en az 2 boyutludur ve 0-255 arası bir renk skalası taşırlar 0 siyahı temsil ederken 255'e yaklaşıldıkça renkler beyazlaşmaya başlar ancak sadece beyaz değil Doğrusal renk sklalası vardır yani siyahtan beyaza kadar olan renkleri kapsar yoğunluğa göre görselleştirir; bu resimleri nasıl görselleştirdiğini anlatıyordu şimdi ise grafiklere geleleim matplotlibde istediğiniz grafiği çizebilirsiniz

bar grafiği, dağılım grafiği(histogram), yatay bar grafiği, nokta grafiği, çizgi grafiği, pasta grafiği(pie graph) renk haritası grafiği, yoğunluk grafiği(yukarıdaki renk barına göre az-çok olarak gösterilir gradient,rgb,..... vb birden fazla renk haritası varıdır) Ve emprik kümülatif dağılım fonksiyonu grafiği(ECDF) gibi grafikleri çizebilir ancak daha çizdiği grafikler vardır örn 2d histogram,Polar axis graph gibi neyse var daha ancak bu kadar yeter şimdi ise matplotlibin grafiklerinden birkaçtane örnek göstericem

  

![](bilisim_sunumu_html_32daf13.gif)

Örneğin burada 360 derecelik ve 1.25 amplitüd büyüklüğünde bir sinüs grafiği var matplotlib ile bir matris,vektör içindeki sinüs verilerini .plot fonksiyonu ile bu şekilde görselleştirebilirsiniz

  

  

![](bilisim_sunumu_html_5d4653a6.gif)

Burada ise bir cos(kosinüs) grafiği görüyorsunuz x değeri 12 ve amplitüd(y) değeri 1.00 büyüklüğündedir

![](bilisim_sunumu_html_dc640a6b.gif)

Burada ise bir sincos(sinüs+kosinüs) grafiği görüyorsunuz bu grafiktei sinüs ve kosinüs değerleiri biribirine doğru ve aynı verilmiş x = 16 ve y = 1.00 aynı şekilde ve üst üste bindelenmişler.

  

![](bilisim_sunumu_html_74c4b7e7.gif)

Burada ise sinüs grafiğinin kare,üçgen,testeredişi şeklindeki grafiklerini görüyorsunuz bunların 4'üde aynı grafik sadece çiziliş formülleri farklı hepsi sinüsten türemiştir.

  

![](bilisim_sunumu_html_3016a8ac.gif)

Burada ise ham bir tangent(tan(x)) grafiği görüyorsunuz bu grafik y= 400'e teğetilmiş ve x ekseni 6 büyüklüğündedir ve grafiği _"maX = 10 f = tan(x), f\[abs(f) > maX\] = np.nan"_ uygulanır ise aşağıdaki grafik elde edilir;

  

![](bilisim_sunumu_html_d1844ecc.gif)

  

  

  

Şimdi ise şu formülün grafiğini çizelim;

  

![](bilisim_sunumu_html_51af26c8.gif)

  

![](bilisim_sunumu_html_81f9915e.gif)

Kısacası matplotlib neredeyse her vektörün,matrixin grafiğini çizebiliyor basit örnekler ile başlamış olsakta aslında çok daha karmaşık grafikler çizilebiliyor  
  
  
Görüntü Gösterme Sistemi

  

  

import numpy as np

import matplotlib.pyplot as plt

  

n = 900

  

v = np.linspace(50,100,n // 100)

q = np.linspace(50,100,n // 100)

  

a = \[v,q\]

  

plt.imshow(a)

plt.show()

  

kodu ile

  

  

![](bilisim_sunumu_html_a70affd0.gif)

  

Çıktısını elde edebilirsiniz

  

  

buda yoğunluğa göre çizim yaptığını gösterir;

  

Kısaca matplotlib bu şekilde kullanılır ve böyle işlevleri vardır bu şekilde işlemlerde yardımcı olur daha bir sürü grafik türü ve birden fazla şey olmasına rağmen bu kadarı yeterli olacaktır;

  

  

  

ÖZET: Veri görselleştirme modülleri çok fazla olduğu için ve cidden uzun bir konu olduğu için şu anlık bu kadar yeter diye düşünüyorum o yüzden bu konuyu burada bitiriyorum ve diğer konuya geçiyorum

  

  

  

  

  

_\-------------------------------------------------------------_

_Otomasyon MOD__Ü__LLERİ_

_\-------------------------------------------------------------_

  

_Aslında bizim b__ö__l__ü__m__ü__m__ü__z ile bağlantılı olan bu konu Pythondada destek g__ö__r__ü__yor;_

_End__ü__striyel otomasyon b__ö__l__ü__m__ü__nde CNC, Sens__ö__r, Hareket verisi .DWG Dosyaları PLC Devreleri, Motorlar şeklinde karşımıza_ _ç__ıkan bu konu pythonda biraz farklıdır;_

  

_pythonda otomasyon genelde bir sistemin işlevini kendi_ _ü__zerine alan ve onun_ _ü__zerinden sisteminizi y__ö__neten mod__ü__ller vardır bu mod__ü__llerden_ _ç__ok fazla var o y__ü__zden ben bug__ü__n en pop__ü__ler ve en basit olanı anlatmayı tercih ediyorum_

  

_PyautoGui Mod__ü__l__ü__;_

![](bilisim_sunumu_html_63856bee.gif)

_Bu mod__ü__l pythonda sisteminizin bileşenlerini y__ö__netmek i__ç__in tasarlanmış mod__ü__ller arasına girer_

_temel işlevi klavye,mause gibi donanımları kontrol etmektir_ _ö__rneğin ger__ç__ek zamanlı şekilde fare imlecinizin ekranınız_ _ü__zerindeki (x,y) kooridnatlarını alabilir, İstediği zaman siz fark etmeden bilgisayarınızdan ekran g__ö__r__ü__nt__ü__s__ü_ _alabilir ve bunları saklayabilir. klavyenizde herhangi istediği tuşlara basabilir ve kodunuzda belirttiğiniz işlevleri yerine getire otomatize edilmiş bir sistem elde etmenizi sağlayan bir python mod__ü__l__ü__d__ü__d__ü__r i__ç__inde birden fazla fonksiyon bulunur._

  

  

_\-------------------------------------------------------------_

_Estetiksel Mod__ü__ller_

_\-------------------------------------------------------------_

_Estetiksel mod__ü__ller; yeri geldiğinde terminalinize renk katabilen, yazıları ASCİİ formatında şekilli yazabilen veya grafikler_ _ç__izerek sizi eğlendirebilen veya şaşırtabilen mod__ü__ller olarak piyasaya sunulur bu mod__ü__llerden 3 tanesini anlatıcam ve 2 tanesi terminal tabanlı olmakla beraber son 1 tanesi GUİ(Graphical User İnterface)(Grafiksel kullanıcı aray__ü__z__ü__) tabanlı olacak._

  

_Pyfiglet Mod__ü__l__ü__;_

![](bilisim_sunumu_html_3243daec.gif)

_Bu mod__ü__l termeinalinizde istediğiniz bir yazıyı yazarken o yazıyı ASCİİ formatında kaligrafik şekilde yazabilmenizi sağlayan k__üçü__k bir mod__ü__ld__ü__r temelde tek işlevi budur ekstra fonksiyonları azdır ancak vardır_

  

_Colorama mod__ü__l__ü_ _ve Back,Fore,Style parametreleri_

  

![](bilisim_sunumu_html_3cd7075a.gif)

  

Bu modül pythonda terminalinizdeki yazıların rengini,stilini,arka plan rengini sınırlı orandada olsa değiştriebilen bir modüldür en basit kullanım şekli ekranda gözüktüğü gibidir birden fazla kullanım stili varıdr ancak genelde kısa olması için bu şekilde kullanılır temelinde ASCİİ kaçış karakterleri ile renklendirme yapan bir sisteme sahiptir

  

  

  

BONUS: Pyfiglet + Colorama entegrasyonu

  

![](bilisim_sunumu_html_829dbda7.gif)

![](bilisim_sunumu_html_f4b50738.gif)

  

  

  

SON MODÜL;

  

Turtle Modülü;

![](bilisim_sunumu_html_d944805b.gif)

Bu modül pythonda aslında ne kadar özgür olduğunuzu gösteren modüllerden sadece bi tanesidir bu modülü kullanarak istediğiniz geometrik veya özel bir cismi (x,y) kooridnatlarına göre çizebilirsiniz

  

ÖRNEK OLARAK AŞAĞIDAKİ RESİMLER VERİLMİŞTİR

  

  

  

![](bilisim_sunumu_html_aae891d0.gif)

![](bilisim_sunumu_html_adc28a79.gif)

  

  

_\-------------------------------------------------------------_

_Coğrafi MOD__Ü__LLER(CBS)_

_\-------------------------------------------------------------_

  

Diğer bir adı ilede CBS(Coğrafi Bilgi Sistemi) olan bu sistemler aklınıza çok kompleks sistemler getirsede aslında sadece temel mantığını anlayarak bazı işlevleri gerçekleştirebilirsiniz bu sistemler genelde cidden karmaşık algoritmalar üzerine kurulur ancak şu anda bunlardan bahsetmiyoruz;

  

PYTHTONDA CBS MODÜLLERİ

  

_**1- Folium;**_

  

![](bilisim_sunumu_html_7d8ca899.gif)

  

![](bilisim_sunumu_html_b40930d5.gif)

  

Folium modülü çok güçlü bir coğrafi modül olarak python aracılığı ile bizlere sunulur. Bu modülde haritalar üzerinde hemen hemen her işlemi gerçekleştirebilir, haritaları ve coğrafi verileri manipüle edebilirsiniz.

  

Folium'un kısa tanımı bu şekilde yapılabilir ancak çok daha kapsamlı ve karmaşık işlerdede kullanılan bir modüldür tek başına haritaları gösteremez sadece işler,manipüle eder ve üzerinde oynama yapar haritaları size HTML olarak verir bunları genelde localhostta açarız veya basit bir sistem kurup html parse ederek harita görsellerini gösteren bir sistem yazarız işte örnek folium görselleri

  

  

![](bilisim_sunumu_html_9546b501.gif)

  

  

Yukarıdaki görselde İstanbul'a işaretçi konmuştur. Bu işaretçi folium ile konmuştur

  

Şimdi ise elimizde bir enlem,boylam matrisi olsun ve buradaki matrislere göre harita işaretçilerini koyan bir sistem yazalım;

  

Matrisimiz:

  

m = \[

\[47.5678, 132.345\],

\[-3.6789, 45.123\],

\[19.8765, -99.456\],

\[0.4567, -75.678\],

\[43.2345, 120.789\],

\[33.5678, 75.234\],

\[-22.3456, 145.678\],

\[56.2345, -76.543\],

\[-15.9876, 23.456\],

\[12.3456, 78.987\],

\[9.8765, -120.345\],

\[-8.2345, 60.123\],

\[65.4321, -87.654\],

\[1.2345, 150.234\],

\[49.8765, -4.567\]

\]

  

![](bilisim_sunumu_html_3e7015c7.gif)

  

İşte bu matrisin lok = \[enlem,boylam\] şeklinde folium ile görselleştirilmiş hali ekranda gördüğünüz gibidir.

  

İşaretçilerin ikonlarını değiştirebilirsiniz Foliumun kendisinin sağladığı ikonlar olsada kendiniz özelleştirilmiş bir ikon tasarlayıp yine ikonun yerine koyabilirsiniz şimdi ise bu görselleştirmenin aynısını farklı bir işaretçi sembolü ile yapalım;

  

![](bilisim_sunumu_html_69929894.gif)

  

İşte yukarıdaki görselde farklı bir ikon ile görselleştirilmiş veriyonunu görüyorsunuz. Daha bir çok seçenek olsada Kısaca bu şekilde gösterilir.

  

Şimdi ise gerçek dünya ile alakalı bir şey yapalım; bir işaretçinin üzerine gelince nokta grafiği meydana çıksın ve bize nüfus grafiklerini versin(temsili bir örnek test verisi kullanıldı)

  

![](bilisim_sunumu_html_9734ef2d.gif)

Bu şekilde hem harita görselleştirmesi üzerinde işaretçi gösterimi hemde işaretçi üzerinde veri görselleştirmesi yapabilen bir küçük sistem tasarlamış oldunuz.

  
Şimdi ise son işlemimize geçelim; Bu son işlemde bir haritada aynı enlem boylam yerine ısı haritası görselleştiricez.

  

![](bilisim_sunumu_html_a273fae3.gif)

  

Ekranda görmüş olduğunuz görselde ise bir ısı işaretçisi yani HeatMap var buradaki her bi noktanın radius değerini değiştirerek yoğunluk,parlaklık,belirginlik gibi özelliklerini değiştirebilirsiniz

  

Şimdilik folium ve CBS sistemleri bu kadar daha uzun bir şekilde anlatmaya kalkarsam muhtemelen makale yazmam gerekebilir makalede böyle yazılmaz bu sunum dil çok teknik ve bilimsel değil daha basit ve dost canlısı şekilde anlatmaya çalışıyorum.

  

  

  

  

_Python'da mod__ü__llerin sonu gelmez :) O y__ü__zden burada mod__ü__lleri bitiriyorum ve pythonun diğer konularına ge__ç__iyorum;_

  

  

_\-------------------------------------------------------------_

_FRAMEWORKLER_

_\-------------------------------------------------------------_

  

![](bilisim_sunumu_html_c1399e93.gif)

  
  

Framework nedir?

  
  

Framework, Bir programlama dilinde bir işlevi gerçekleştirmek için birden fazla modülün birleşmesi aynı çerçeve altında toplanması ile oluşan bir araçtır

Kısaca;

Framework, bir programlama dilinde kullanılan,

birden fazla hazır yapıyı ve aracı tek çatı altında toplayan,

geliştiricinin işini kolaylaştıran bir hazır iskelet yapıdır

  

Ayrıca;

bu araç; kurulduğu konu üzerine her işlevi gerçekleştirmek zorundadır Birden fazla framework olsada sınıflara ayrılmıştır işte bunlardan bir kaç tanesi;

  
  

*   **Aray****ü****z frameworkleri (PyQt5/6,PySide,qtpy,Kivy,flet)**
    
*   **Aİ/ML frameworkleri(TensorFlow,Keras,PyTorch)**
    
*   **Web/Ağ frameworkleri (Flask,Django)**
    

  
  

Bu şekilde örnekler verilebilir; Şimdi ise bazı örnekler verelim;

  
  

**PyQt ile yapılan bir aray****ü****z;**

![](bilisim_sunumu_html_33ae07a8.gif)

  
  

**Flask ile yazılan bir Web aray****ü****z****ü****;**

  
  

![](bilisim_sunumu_html_680af481.gif)

NOT: Flask bir arayüz frameworkü değildir WEB için APİ,Haberleşme ve dahasını sağlar ancak bazı ekstra iç modülleri ile WEB Arayüzleri elde etmenizide sağlar

  
  

  
  

**Ö****rnek bir ML/Aİ g****ö****rseli(Keras,Cv2)**

  
  

**G****ö****rsel(1.1)**

![](bilisim_sunumu_html_e7c1cb8a.gif)

**G****Ö****RSEL(1.2)**

![](bilisim_sunumu_html_dfe93ee3.gif)

  
  

**G****ö****rsel(1.1) Taşıt segmentasyon** **ö****rneği**

**G****ö****rsel(1.2) Biyolojik segmentasyon** **ö****rneği**

  
  

**Yukarıdaki g****ö****rselde Scipy,Numpy,Cv2 gibi Farklı mod****ü****llerde yer almıştır keras sadece bunların i****ç****indeki Yapay zeka(Aİ) Aracıdır**

  
  

Görsel örnekler bu şekilde verilebilir konular çok teknik ve başklarına sıkıcı gelebileceği için ve çokta uzatmak istemediğim için şu anda burada bitirip diğer konuya geçiyorum;

  
  

  
  

  
  

_\-------------------------------------------------------------_

_MATEMATİK & YAZILIM_

_\-------------------------------------------------------------_

![](bilisim_sunumu_html_950a0533.gif)

**Matematik Yazılım İlişkisi**

**Kod yazarken matematiği ne kadar g****ö****rmesekte sadee teknik şeylerede odaklansak aslında hem yazılım dilleri hemde bilgisayarlarımızın** **ç****alışma prensipleri** **ç****ok karmaşık bir matematiğe dayanıyor; Bilgisayarların** **ç****alışma prensibini duymuşsunuzdur 0-1 yani binary sistemi ile** **ç****alışır aslında ilk yazılım dilleride bu şekilde 0-1 ler ile yazılıyordu o zamanın yazılımcıları bu dillerin cok karmaşık ve cok devam ettirilebilir olmadığınını d****ü****ş****ü****n****ü****yorlardı o y****ü****zden farklı yazılım dilleri** **ç****ıkardılar binaryden sonra ilk** **ç****ıkan yazılım dili Assembly idi bununla biraz devam ettiler ancak bununda cok karmaşık oldugunu d****ü****ş****ü****nd****ü****ler sonra C gibi diller ortaya** **ç****ıktı işte bu şekilde devam ede ede artık insanlarla konuşur gibi kod yazabilir hale geldik işte olay tamda burada başlıyor biz bu kodları bu şekilde yazabiliyorsak arkadaki matematik sayesinde a****ç****ıklamama izin verin;** **Ö****rneğin pythonda "print(2\*\*2)" komudunu** **ç****alıştırdınız ve 4** **ç****ıktısını aldınız evet doğru 2** **ü****zeri 2 = 4 eder bu basit matematiği** **ö****nce python sizden aldı ve compiler(derleyici)'da derlemeye aldı derlerken işte o matematik devreye girdi yani kısaca yazılım-mateamatik birbiri ile** **ç****ok yakından bağlıdır ayrılmaz bir ikili gibidirler ikiside birbirini tamamlar**

  
  

  
  

  
  

_\-------------------------------------------------------------_

_YAZILIMDA ALGORİTMALAR_

_\-------------------------------------------------------------_

![](bilisim_sunumu_html_c389bcc2.gif)

ALGORİTMALAR

  
  

Yazılımda algoritmanın ne olduğunu bilmemiz için öncelikle algoritmanın ne olduğunu bilmeniz gerekir Yazılımda algoritma kısaca şudur;

  
  

Bir işlevi yerine getiren ve bir işlevi yerine getirmekle kalmayıp bir problemin içine koyulduğunda o problemi ortadan kaldırdan bir programın nasıl çalışacağını ona söyleyen bir mantık kodudur ve çıktıya giden yolda koda yardımcı olan yapı taşlarını oluşturan etkenlerdir. Ayrıca matematiksel olmak zorunda değildirler ancak çoğu algoritma matematiksel sınıfına girer.

Temelde algoritmalar şu şekilde sınıflandırılır;

*   **Sıralama algoritmalar (Sorting Algorithms)**
    
*   **Arama algoritmaları (Searching Algorithms)**
    
*   **Optimizasyon algoritmaları (Optimization Algorithms)**
    
*   **Programa g****ö****re şekillendirilmiş algoritmalar (kendi yazdığınız)**
    

  

Daha bir çok algoritma sınıfı vardır ancak temelde bu şekilde sınıflandırılırlar

Algoritmaları daha iyi anlamak için sırasıyla ne işe yaradıklarını açıklamama izin verin;

  

**Sıralama Algoritmaları:** Bu algoritma türü elinizdeki bir sayı dizisini veya herhangi bir veriyi algoritmaya söylediğiniz belirli bir standarta göre sıralamasını sağlayan algoritmalara verilen isimidir. Bu algoritmalar temelde Büyükten küçüğe VEYA Küçükten Büyüğe VEYA Sizin verdiğiniz Standarta göre SIRALAMA Yapar.

  

**Arama algoritmaları:** Bu algoritmalar sizin elinizdeki bir dizinin veya bir veri setinin içinde sizin belirlediğiniz anahtar kelimeyi veya sayıyı kısaca VERİYİ arar ancak bunu en optimize edilmiş ve en hızlı,doğru yoldan yapar

  

**Optimizasyon algoritmaları:** Bu algoritmalar genelde direkt olarak performans sorunlarını ortadan kaldırmak için tasarlanmışlardır; **Ö****rn:** Donmalar,Görüntü bulanıklıkları,Yavaşlamalar,Çökmeler VB gibi problemleri çözebilen yani kısaca **Performans sorunlarını b****ü****y****ü****k** **ö****l****çü****de ortadan kaldırmayı ve onların meydana gelmesini engelleyen algoritmalara \[OPTİMİZASYON ALGORİTMASI\]** denir.

  

**Programa g****ö****re şekillendirilmiş algoritmalar:** Dediğim gibi bu algoritmalar sizin kendi yazdığınız algoritmaları kapsar teknik dünyada standart bir ismi olmasada böyle bir şey vardır açıklamama izin verin; Örneğin programınızda bir problem var veya bir akış mantığı kurmanız gerekiyor bu mantığı kurarken bir algoritma yazmanız gerekebilir yazacağınız algoritma yukarıda bahsettiğim stadart türlerden olmak zorunda değildir. Kendi algoritmalarınızıda programınız için geliştirip onları kullanabilirsiniz Hatta kimi zaman bu yöntem biraz daha kullanışlı olabilir.

  

**Algoritma İsimleri:**

  

**Sıralama algoritmaları:** Selection Sort, Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Cycle Sort, 3-way Merge Sort

  

**Arama algoritmaları:** Yukarıdaki algoritmaların içine yerleştirilmiş sorgu bloklarını kapsayan tüm fonksiyonlar bu kapsama girer Ayrıca temeli Arama üzerine kurulan algoritmalar:

  

Breadth-First Search, Depth-First Search, A Search, Dijkstra’s Algorithm, Greedy Best-First Search, Iterative Deepening Depth-First Search\*

  

**Optimizasyon algoritmalar:** Genetic Algorithm, Particle Swarm Optimization, Simulated Annealing, Differential Evolution, Gradient Descent, Nelder–Mead Method

  

  

**Şeklinde s****ö****ylenebilir**

  

  

**Algoritmaların zaman karmaşıklıkları ise şu şekilde sınıflandırlır(hızlıdan-yavaşa sıra):**

  

**O(1)** \- Sabit zaman karmaşıklığı (bazı özel durumlarda olabilir, örneğin sıralama işlemi gereksizse).

  

**O(log n)** \- Lojistik zaman karmaşıklığı (örneğin Binary Search).

  

**O(n)** \- Lineer zaman karmaşıklığı (örneğin Counting Sort ve Radix Sort gibi bazı algoritmalar lineer zaman karmaşıklığına sahip olabilir).

  

**O(n log n)** \- Lineer logaritmik zaman karmaşıklığı (en verimli genel sıralama algoritmalarının çoğu, örneğin Merge Sort, Quick Sort, Heap Sort).

  

**O(n²)** \- Kuadratik zaman karmaşıklığı (bazı basit algoritmalar için, örneğin Bubble Sort, Selection Sort, Insertion Sort).

  

**O(n³)** ve üstü - Kübik veya daha yüksek dereceden karmaşıklıklar (genellikle daha nadir ve özel algoritmalar için, büyük veri setlerinde verimsiz olur).

  

  

  

![](bilisim_sunumu_html_8be64049.gif)

  

_\-------------------------------------------------------------_

_YAZILIMDA FORM__Ü__L KURMA_

_\-------------------------------------------------------------_

  

Formül: Matematiksel bir problemin çözülmesi için tasarlanmış sabit standartları olan bir matematiksel ifadedir.

  

Yazılımda ise formüller kullanılır ancak kullanım alanları daha farklıdır

  

Şimdi ekranda bir formül görüyorsunuz;

  

![](bilisim_sunumu_html_c9ec3a54.gif)

  

Bu algebra formülünün pythonda yazımı şu şekildedir.

  

_**"(a\*\*3) - (b\*\*3) = x"**_ _eder_

VE

_**"(a-b)\*((a\*\*2) + (a\*b) + b\*\*2) = x**_**"** _eder_

  

Bu formüllerden ikiside aynı sonucu verir ise doğru yazıldığını gösterir;

  

_Şimdi ise test edelim:_

  

![](bilisim_sunumu_html_646226ef.gif)

  

Evet Bu ifade doğru gibi duruyor şimdi ise gerçekten doğru olup olmadığını doğrulayalım;

  

![](bilisim_sunumu_html_7f8f4292.gif)

  

\----------------------------------------------------------------------------------------------

kod:

\----------------------------------------------------------------------------------------------

nums = \[q for q in range(25)\]

matrix = \[\[\],\[\]\]

  

for num in range(1,len(nums) + 1):

if num < len(nums) - 1:

compherm = (nums\[num - 1\]\*\*3) - (nums\[num\]\*\*3)

algebric\_comphersm = ((nums\[num - 1\] - nums\[num\])\*((nums\[num - 1\]\*\*2) + (nums\[num - 1\] \* nums\[num\]) + nums\[num\]\*\*2))

matrix\[0\].append(abs(compherm))

matrix\[1\].append(abs(algebric\_comphersm))

else:

break

  

for Nmatrix,Mmatrix in zip(matrix\[0\],matrix\[1\]):

print(Nmatrix,Mmatrix)

\----------------------------------------------------------------------------------------------

ÇIKTI

\----------------------------------------------------------------------------------------------

  

1 1

7 7

19 19

37 37

61 61

91 91

127 127

169 169

217 217

271 271

331 331

397 397

469 469

547 547

631 631

721 721

547 547

631 631

721 721

631 631

721 721

721 721

817 817

919 919

1027 1027

919 919

1027 1027

1027 1027

1141 1141

1261 1261

1261 1261

1387 1387

1387 1387

1519 1519

\----------------------------------------------------------------------------------------------

  

  

Evet görünüşe göre formül koda doğru geçirilmiş hem farklı sayılar ile hemde tek bir sayı ile doğru çıktıyı verebildi İşte yazılımda kısaca formül bu şekilde kurulabilir basit bir örnek olarak bu gösterilebilir.

  

  

  

  

  

  

  

_Sunumum bu kadardı beni dinlediğiniz i__ç__in teşekk__ü__r ederim ayrıca bu sunumumu yapmama izin veren hocalarımada ayrıca teşekk__ü__r ederim._