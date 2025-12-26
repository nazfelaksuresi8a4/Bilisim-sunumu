Yazılım Ekosistemi sunumu

‎3 ‎Aralık ‎2025 ‎Çarşamba

Yazılım Ekosistemi nedir?;
Yazılım denince aklınıza neler geliyor? Belkide hiç bir şey gelimiyor ancak zaten gelmesinede gerek yok .
Bugün sizlere hem yazılımın ne olduğunu basit bir dille açıklayacağım hemde yazılımın içindeki ekosistemi anlatacağım ancak "yazılım ekosistemi" derken ne kastettiğimi tam olarak netleştiremediyeniz açıklamama izin verin;

Yazılımın Büyük bir dünyadır aynen bizim dünyamız gibi o dünyanın içindede dev gibi bir evren vardır 
bunu derken abartmıyorum cidden öyle o yüzden her şey düzenli bir şekilde sistemli olarak ayrılmıştır 
tam olarak belirli makaleli veya dökümanlı kanıtlanmış bir ekosistem olmasada bugün ben sizler için  
yazılım ekosistemi başlığı altında bunları anlatacağım Örneğin bizim çevremizdeki ekosistemde 
ağaçlar,gökyüzü,hava,oksijen vb. gibi etkenler vardır yazılımdada pek farklı değil tek farkı konuları ve terimleri 

Yazılım nedir?

Yazılım kısaca; bilgisayarların ve cihazların donanımlarını kullanarak kendi içlerindeki işlemleri gerçekleştirebilmeleri, matematiksel hesaplamalar, insan faktörünün algılayamayacağı kadar fazla veriyi doğru oranda okuyabilen işleyebilen ve makinelerin beyinlerini oluşturan kodlardan oluşan bir dildir genelde yazılımcılar kodları çeşitli yazılım dilleri ile yazarlar bu şekilde yukarıda belirttiğim şeyleri ve hatta fazlasını yapabilirler.
 

 Modül Nedir?

Modül; Yazılım dilinde birden fazla fonksiyondan oluşan ve bir amacı yerine getirmek için tasarlanmış amacı kodların daha kısa ve ölçeklenebilir yazılmasına yardımcı olmaktır; örneğin bir matematik işlemini yazılımda uzunca yazmak yerine modül sayesinde tek bir fonksiyon ile halledebilirsiniz. Modüller kodları kolaylaştırmakla kalmazlar ayrıca yazılımı öğrenmeyide açık ara farkla çok ciddi şekilde kolaylaştırırlar örneğin yazılımda her şeyin bir modülü vardır Renkmi yapıcaksın modülü var İntegralmi çözüceksin modülü var Trigonometrimi çözüceksin modülü var Matematiksel bir denklemmi kurucaksın? Modülü var sadece matematikle sınırlı değil Estetik,Sistem,Matematik,Ağ,İnternet,Veri işleme veri görselleştirme coğrafi bilgi sistemleri(cbs) gibi etkenlerle alakalı kodlar yazacaksanız bunlarla alakalı modüllerde var ve sadece bunlarla sınırlı değil. düşündüğünüzden çok daha fazla modül yelpazesine sahiptirler.

Örnek modüller;

-------------------------------------------------------------
		MATEMATİKSEL MODÜLLER
-------------------------------------------------------------
Numpy Modülü;                                                                       

Bu modül matematiksel bir modüldür pythonda bir çok matematiksel işlemi algoritmayı ve formülü yazmayı kolaylaştırır Vektörler,Matrisler,Tensorlar gibi veri tiplerini barınıdırır numpyde vektörlere NDarray yani Array(arrey) denir Türkçesi dizi olarak geçer; ayrıca Numpy'da trigonometrik fonksiyonlar,logaritmik fonksiyonlar gibi birden fazla matematiksel fonksiyonda bulunur matrislerin vektörlerin ve tensorlerin üzerine bu fonksiyonları rahat bir şekilde uygulamnanızı sağlar bir cok fonksiyonu vardır arrayları yeniden boyutlandırma mutlak değerşlerini alma veri tiplerini değşirme(örneğin tam sayıları ondalık yapma gibi) bir cok işlevdede kullanılır Açılımı ise Numerical Python olarak geçer

Math Modülü;

 
Math modülü  daha çok pythonda matematiksel işlemleri uygulamak için kullanılır ancak bu modülü  Numpy ile karıştırmayın ikisi çok farklıdır yine ikiside aynı fonksiyonları bulundurur ancak math modülünde vektörler matrisler tensorler gibi veri tipleri yoktur bunları desteklemez gündelik matematik veya ileri seviye matematiksel işlemleri gerçekleştirebilir sayılar üzerinde çalışır buradada nerdeyse her matematiksel fonksiyon ve işlev bulunur 

SymPy Modülü

 
SymPy pythonda numerik işlemler ve matematiksel işlemlere destek için kullanılır karmaşık gelmesin matematik ile alakalı bir kod yazarken sembollere ihitiyaç duyarız python terminal tabanlı bir yazılım dili olduğu için terminaldeki semboller ve klavyemizden koyabileceğimiz semboller sınırlıdır o yüzden SymPy matematiksel ifadelerimize sembolleri eklememize ve semboller ile gösterim yapmamıza yardımcı olan bir modüldür ayrıca bu modülde diğerleri gibi güçlü bir modüldür 



-------------------------------------------------------------
			SİSTEM MODÜLLERİ
-------------------------------------------------------------
Sys Modülü;
 
Sys modülü; pytonda sistem işlevlerini  gerçekleştirmemiz için gerekli bir modüldür örneğin programımızı kapatma,terminale yazı yazdırırken daha özelleştirilebilir şekilde yazı yazmamızı sağlayan farklı fonksiyonları ve asıl işlevi olan işletim sistemi(OS) ile iletişime geçebilmek olan ve terminalle alakalı işlemlerde kullanılmasıdır;

Os Modülü;
 
Os modülü; Python ile sistemimizdeki dosyalara erişim sağlamamıza yardımcı olur bu modül bilgisayarımızdaki dosyaları okuyabilir silebilir üzerine yazabilir(overwrite) dosya adından dosya dizinini bulabilir ve aklınıza gelip gelebilecek her türden dosya işlemini yapabilir bu modülün amacı ise bilgisayarınızdaki dosya sistemine erişim sağlayarak dosyalarınızı ve belgelerinizi yönetmesi onları değiştirebilmesi üzerinde oynayabilmesidir. Ancak daha bir çok işlevdede kullanılır tek işlevi dosya açıp kapatmak değildir bu modülde diğer modüller gibigüçlü ve ölçeklenebilir bir modüldür 


Subprocess Modülü;
 
Subprocess modülü; pythondaki bu modül sisteminizdeki terminali yönetebilir ordan komutlar çalıştırıp size çıktıları verebilir terminalinizi yönetebilir ve terminaliz ile alakalı olan aklınıza gelebilecek her türden işlemi gerçekleştirebilecek bir modüldür asıl amacı ise anlattığım gibi  komut sisteminizde komutlar çalıştırmaktır.



-------------------------------------------------------------
				SES MODÜLLERİ
-------------------------------------------------------------

PyAudio Modülü;
 

Pyaudio modülü; pytonda ses işlemleri için kullanılan bir modüldür bu modül elinizdeki bir .mp3 veya .wav dosyasını byte(bayt) düzeyinde işleyerek çalar ve size sesi verir ancak tek amacı bu değilidir;
bu modül sandığınızdan daha güçlüdür çünkü; Ses çalarken bytelarını dönebilmek gibi gelişmiş özellikler ile donatılmıştır ayrıca dahasını yapabilecek bir modüldür ve güncelleme alan modüller arasında yer alır.


PlaySound Modülü;
 
Playsound modülü; pythonda .wav .mp3 gibi dosya formatlarını çalabilmenizi sağlayan bir modüldür daha çok küçük işlevler için kullanılır çok büyük bir modül değildir genellikle bir programda ufak çaplı sesleri çalmak için kullanılır;


SoundDevice Modülü;
 

Sounddevice modülü; Bu modül cidden çok güçlüdür bu modülün temel işlevi ses dosyalarnı alıp byte düzeyinde işleyebilmektir ayrıca bu sesleri işlerken aynı anda çalarlar ve çalarkende verileri dönerler(yani verileri istenilen yere gönderip işlenmesini sağlarlar buda senkronize bir işlem sırası oluşturur) genelde böyle şeyleri pyaudio gibi modüller ile yapmak zordur hatta çoğu zaman pek mümkün değildir ses verisinin büyüklüğü arttıkça donmalar meydana gelir ancak bu pyaudioda olur sounddevice modülünde böyle takılmalar çok nadiren gerçekleşir onun sebebide genelde yazılımcının yaptığı bir optimizasyon hatası olur ayrıca bu modülde Callback sistemi mevcuttur bu sistem ses çalınırken dediğim veri gönderme ve ekstra işlemleri gerçekleştirebilmesini sağlar AYRICA bu modülün en çarpıcı kısmıda şudur; Hem mikrafon verilerini işleyebilir yan sizin konuşmanızı algılayabilen bir fonksiyonuda bulunur hemde girdi yani eksta bir dosya ile işleyebilirsiniz veya sisteminizdeki sesleri algılaması içinde tasarlayabilirsniz bu açıdan çok zengin bir modüldür mikrofon dosya sistem sesleri gibi etkenleri işleyebilir ancak bu modülde sayılsa veri ister bu sayısal veriden kastım bir çeşit ses matrisidir genelde şöyle gözükürler 
						 


SoundFile Modülü;
 

Soundfile modülü; .wav dosyalarını  işlemek ve onların metadatalarını(ham verilierini) almak için kullanılan bir modüldür bu modül bir ses dosyasının kanal sayısı,örnek başına örnekleme sayısı, toplam örnek sayısı gibi bir çok veriyi size verir ancak en önemlisi ses verisini size matris formatında verebilmesidir bu modüldeki dosyayı okuma fonksiyonu cok güçlüdür dosyayı okuyup size buffer arrayını verir ve bunun içindede tamsayılar mevcuttur bu tamsayılar farklı modüller sayeseinde byte düzeyinde yorumlanır ve sese çevirilir ancak bu modül sesi doğrudan oynatamaz 



Wave Modülü;
 
Wave modülü pythonda .wav dosyalarını işlemek için açık ara en kapsamlı modüllerden birisidir 
Wav dosyalarının Kaç saniye olduğunu saniye başına örnekleme hızınını byte matrisini  toplam örnek sayısını kanal sayısını örnek genişliği gibi birden fazla değerini bizlere dönebilir ancak kötü yanlarından birisi döndüğü byte matrisini dirket olarak işleyemezsiniz numpy modülü ile bu byte matrixini buffer matrixine çevirmen gerekir ve bunu yaparkende kanal sayına göre yapman gerekir ve bunu manuel değil otonom bir şekilde yapman gerekir ancak bununlada sınırlı değil buffer array elde edildikten sonra boyut sorunları meydana gelebilir(shape sorunları) boyut sorununundan kastım şu; dönen byte matrisini byte matrisine çevirdikten sonra boyutu nötrlenir ve bu boyuttaki büyük bir matrisi işlemek istediğinizde sorunlar meydana gelir bunu çözebilirsiniz ancak kısa yoldan halletmek için büyük projelerde soundfile gibi araçlşarı kullanmanız ve sesin bilgileri içinde wave modülünü kullanmanız önerilir.


Speech_Recoginiton Modülü;
 
speech_recoginiton modülü pythonda mikrofndan verdiğiniz bir sesi metine dökmek için kullanılır backendinde esasta bir dil modeli kullanır ve bu dil modeli neredeyse İçinde Türkçe'ninde bulunduğu tüm dilleri kapsıyor denebilir; Kapsamlı bir modüldür ve asıl amacı anlattığım gibi bellidir İnsan sesini yazıya çevirmek.


-------------------------------------------------------------
				Ağ MODÜLLERİ
-------------------------------------------------------------

Socket Modülü;
 
Socket modülü pythonda networking yapmanızı sağlar Port,İp üzerinden belirttiğiniz bir servera erişim sağlayıp oraya veri gönderme veri çekme dosya gönderme dosya çekme gibi işlemleri gerçekleştirebilirsiniz. Bazı modüllerinde desteği ile kötüye kullanıma açık bir modüldür ancak bunula birliktede aslında cokta işlevseldir bu modülün temeli şudur;  bir server oluşturursunuz ve bu servera bağlanacak bir client oluştrurursunuz bunları yaptıktan sonra serverı başlatırsınız ve o serverın ip ve portuna bağlanacak bir client kodlarsınız kodladığıonız client servera bağlanır ve serverda kurduğunuz mekanizma ip ve portu size döndürür ve bir cihaz bağlandı diye uyarı mesajı atar işte ilk socket kodunuzu yazdınız socket temelde buna dayansada karmaşık yapıları ve birden fazla parametresi,fonksiyonu ile bazen kafaları karıştıran bir modüldür ancak son derece kapsamlı ve güçlüdür siber güvenlik alanlarında network testi gibi şeylerde kullanılır örn; Brute force ile port bulan bir sistem vb. Yani bir çok şeyi gerçekleştirebilen temel bir ağ modülü olarak python bize bunu sunar 


Python-Nmap Modülü;

 
Python-Nmap modülü nmap isimli  terminal tabanlı bir siber güvenlik aracını pythonda çalıştırmanızı sağlar ve bu aracın cogu parametresini fonksiyonunu neredeyse hepsini içine almıştır; peki ya nmap nedir? Nmap networking/Port tarama ağ analizi gibi işlemlerde oldukça başarılı bir port tarama aracıdır inanılmaz büyük bir komut yelpazesi ve birden fazla işlevi vardır bununla beraberde içinde birden fazla payload(Üst bilgi) bulunur ancak nmap hakkında bir çok konu vardır ve pythondan farklı bir konuya gireceği için şimdi tekrar pythona geçiyorum Pythondaki nmap modülü şu işlevleri yapıyor; açık-kapalı port bulma port tarama portların bağlı oldugu ip adreslerini bulma ip adreslernin bağlu olduğu portları bulma etraftaki ağları taramak ve birden fazla nmap komudunu kendi çinde çalıştırıp çıktıları bize sunabilir Ayrıca bu modül son derece kötüye kullanıma açıktır ancak bu modül zor ve syntax(sintaks)'ı karmaşık olduğu için genelde script kiddie(deneyimsiz hackerlar) bu modülü kullanamaz veya cok daha temel düzeyde kullanabilir 

Requests Modülü;
 
Mottosu: Http for humans(insanlar için http)

Pytondaki Requests modülü HTTP ve APİ istekleri için kullanılan bir modüldür internet sitelerinden ver APİ(Application Program İnterface)'lardan veriler çekmek için kullanılır bu modül APİ den çekilen veriyi genelde iki türlü alır 1. text olarak yani html olarak alır veya 2. olarak .json formatında alır genelde 2. payload tipi çok daha yaygın kullanılır ancak özel durumlarda bu payloadlar farklı bir formata parse edlebilir Şimdi ise neler yapabilidğine gelelim; örneğin bir program kullanıyorsunuz mesela e-devletten soy ağacınızı sorugluyorsunuz sorguyu başlattığınız anda bir APİ ye istek atılıyor ve o APİ den gelen veri size gösterliyor tabikide bu tür büyük kuruluşların ve kurumların kullandığı apiler gizli olur yani bir çeşit Authotentication(yetkilendirme metodu) kullanılır bu metod APİ KEY olarak geçer örnek bir APİ key şöyle gözükür

		
        AIzaSyDaGmWKa4JsXZ-HjGw7ISLn_3namBGewQe

Yukarıdaki kompleks yapı bir APİ Key örneğidir tabikide bu key'in bi geçerliliği yok sadece sahte bir key ancak keyler tam olarak buna benziyor tabikide daha farklı keyler kullanan APİ ler var özel siber güvenlik önlemleri ile donatılan APİ keyleri bile mevcuttur şimdi ise HTTP İsteklerine gelelim bu yöntem  siteye bir istek gönderip siteden gelen yanıtı kendi lehine kullanarak size bir .html yani .text döner bunu parse ettiğinizde içinden istediğiniz verileri bulabilirsiniz örneğin; haber başlıkları, metinler gibi web sitesi elemanlarının içindeki şeyleri çekebilirsiniz.

Yukarıda anlattıgım işlevleri gerçekleştirmek için tasarlanmış bu modül pythona  büyük bir katkı sağlamıştır. 


Selenium Modülü;
 

İsmini periyodik tablonun selenyum34 elementinden alan bu modüldeki "element" kelimesi çok önemlidir;

esasında bir python modülü olan selenium internet sitelerindeki verilerin elementlerini kullanarak onların içinden anlamlı verileri çekip bizlere verebiliyor bunları yaparken XPATH,HTML	 vb vb gibi bir çok elementi destekler web sitelerinden resim fotoğraf video yazı veri sayı rakam gibi birden fazla veriyi çekebilir http istekleri ile çalışır site kaynağına erişim sağlar(bu sadece front-end yani html kodları demek herkesin görebildiği verilerdir selenium bunları parserları ile işler ve bize anlamlandırarak veriler çıkartır) kısaca bunları yapan bu modül daha bir cok işlevi olmasına rağmen kısaca ancak bu şekilde açıklanabilir.

 

-------------------------------------------------------------
	    Veri Görselleştirme MODÜLLERİ
-------------------------------------------------------------

Matplotlib Modülü;
 
Bu modül pythonda veri görselleştirme yapmak için kullanılan bir modüldür Matris,Vektör,Tensor gibi bir çok veriyi destekler grafik olarak görselleştirir ayrıca elinizde bir görüntü matrisi var ise matplotlib sizin için bunu görselleştirebilir yani o matrisin resmini kendi figürünün içinde gösterebilir; görüntü matrixleri en az 2 boyutludur ve 0-255 arası bir renk skalası taşırlar 0 siyahı temsil ederken 255'e yaklaşıldıkça renkler beyazlaşmaya başlar ancak sadece beyaz değil Doğrusal renk sklalası vardır yani siyahtan beyaza kadar olan renkleri kapsar yoğunluğa göre görselleştirir; bu resimleri nasıl görselleştirdiğini anlatıyordu şimdi ise grafiklere geleleim matplotlibde istediğiniz grafiği çizebilirsiniz 
bar grafiği, dağılım grafiği(histogram), yatay bar grafiği, nokta grafiği, çizgi grafiği, pasta grafiği(pie graph) renk haritası grafiği, yoğunluk grafiği(yukarıdaki renk barına göre az-çok olarak gösterilir gradient,rgb,..... vb birden fazla renk haritası varıdır) Ve emprik kümülatif dağılım fonksiyonu grafiği(ECDF) gibi grafikleri çizebilir ancak daha çizdiği grafikler vardır örn 2d histogram,Polar axis graph gibi neyse var daha ancak bu kadar yeter şimdi ise   matplotlibin grafiklerinden birkaçtane örnek göstericem 

 
Örneğin burada 360 derecelik ve 1.25 amplitüd büyüklüğünde bir sinüs grafiği var matplotlib ile bir matris,vektör içindeki sinüs verilerini  .plot fonksiyonu ile bu şekilde görselleştirebilirsiniz


 
Burada ise bir cos(kosinüs) grafiği görüyorsunuz x değeri 12 ve amplitüd(y) değeri 1.00 büyüklüğündedir
 
Burada ise bir sincos(sinüs+kosinüs) grafiği görüyorsunuz bu grafiktei sinüs ve kosinüs değerleiri biribirine doğru ve aynı verilmiş x = 16 ve y = 1.00 aynı şekilde ve üst üste bindelenmişler.

 
Burada ise sinüs grafiğinin kare,üçgen,testeredişi şeklindeki grafiklerini görüyorsunuz bunların 4'üde aynı grafik sadece çiziliş formülleri farklı hepsi sinüsten türemiştir.

 
Burada ise ham bir tangent(tan(x)) grafiği görüyorsunuz bu grafik y= 400'e teğetilmiş ve x  ekseni 6 büyüklüğündedir ve grafiği "maX = 10 f = tan(x), f[abs(f) > maX] = np.nan" uygulanır ise  aşağıdaki grafik elde edilir;

 



Şimdi ise şu formülün grafiğini çizelim; 

 

 
Kısacası matplotlib neredeyse her vektörün,matrixin grafiğini çizebiliyor basit örnekler ile başlamış olsakta aslında çok daha karmaşık grafikler çizilebiliyor 


Görüntü Gösterme Sistemi


import  numpy as np 
import matplotlib.pyplot as plt 

n = 900

v = np.linspace(50,100,n // 100)
q = np.linspace(50,100,n // 100)

a = [v,q]

plt.imshow(a)
plt.show()

kodu ile 


 

Çıktısını elde edebilirsiniz


buda yoğunluğa göre çizim yaptığını gösterir;

Kısaca matplotlib bu şekilde kullanılır ve böyle işlevleri vardır bu şekilde işlemlerde yardımcı olur daha bir sürü grafik türü ve birden fazla şey olmasına rağmen bu kadarı yeterli olacaktır;



ÖZET:  Veri görselleştirme modülleri çok fazla olduğu için ve cidden uzun bir konu olduğu için şu anlık bu kadar yeter diye düşünüyorum o yüzden bu konuyu burada bitiriyorum ve diğer konuya geçiyorum 

 




-------------------------------------------------------------
		Otomasyon MODÜLLERİ
-------------------------------------------------------------

Aslında bizim bölümümüz ile bağlantılı olan bu konu Pythondada destek görüyor;
Endüstriyel otomasyon bölümünde CNC, Sensör, Hareket verisi .DWG Dosyaları PLC Devreleri, Motorlar şeklinde karşımıza çıkan bu konu pythonda biraz farklıdır; 

pythonda otomasyon genelde bir sistemin işlevini kendi üzerine alan ve onun üzerinden sisteminizi yöneten modüller vardır bu modüllerden çok fazla var o yüzden ben bugün en popüler ve en basit olanı anlatmayı tercih ediyorum 

PyautoGui Modülü;
 
Bu modül pythonda sisteminizin bileşenlerini yönetmek için tasarlanmış modüller arasına girer 
temel işlevi klavye,mause gibi donanımları kontrol etmektir örneğin gerçek zamanlı şekilde fare imlecinizin ekranınız üzerindeki (x,y) kooridnatlarını alabilir, İstediği zaman siz fark etmeden bilgisayarınızdan ekran görüntüsü alabilir ve bunları saklayabilir. klavyenizde herhangi istediği tuşlara basabilir ve kodunuzda belirttiğiniz işlevleri yerine getire otomatize edilmiş bir sistem elde etmenizi sağlayan bir python modülüdüdür içinde birden fazla fonksiyon bulunur.


-------------------------------------------------------------
			Estetiksel Modüller
-------------------------------------------------------------
Estetiksel modüller; yeri geldiğinde terminalinize renk katabilen, yazıları ASCİİ formatında şekilli yazabilen veya grafikler çizerek sizi eğlendirebilen veya şaşırtabilen modüller olarak piyasaya sunulur bu modüllerden 3 tanesini anlatıcam ve 2 tanesi terminal tabanlı olmakla beraber son 1 tanesi GUİ(Graphical User İnterface)(Grafiksel kullanıcı arayüzü) tabanlı olacak.

Pyfiglet Modülü;
 
Bu modül termeinalinizde istediğiniz bir yazıyı yazarken o yazıyı ASCİİ formatında kaligrafik şekilde yazabilmenizi sağlayan küçük bir modüldür temelde tek işlevi budur ekstra fonksiyonları azdır ancak vardır 

Colorama modülü ve Back,Fore,Style 		parametreleri

 

Bu modül pythonda terminalinizdeki yazıların rengini,stilini,arka plan rengini sınırlı orandada olsa değiştriebilen bir modüldür en basit kullanım şekli ekranda gözüktüğü gibidir birden fazla kullanım stili varıdr ancak genelde kısa olması için bu şekilde kullanılır temelinde ASCİİ kaçış karakterleri ile renklendirme yapan bir sisteme sahiptir 



BONUS: Pyfiglet + Colorama entegrasyonu

 
 



SON MODÜL;

Turtle Modülü;
 
Bu modül pythonda aslında ne kadar özgür olduğunuzu gösteren modüllerden sadece bi tanesidir bu modülü kullanarak istediğiniz geometrik veya özel bir cismi (x,y) kooridnatlarına göre çizebilirsiniz

ÖRNEK OLARAK AŞAĞIDAKİ RESİMLER VERİLMİŞTİR



 
 


-------------------------------------------------------------
		Coğrafi MODÜLLER(CBS)
-------------------------------------------------------------

Diğer bir adı ilede CBS(Coğrafi Bilgi Sistemi) olan bu sistemler aklınıza çok kompleks sistemler getirsede aslında sadece temel mantığını anlayarak bazı işlevleri gerçekleştirebilirsiniz bu sistemler genelde cidden karmaşık algoritmalar üzerine kurulur ancak şu anda bunlardan bahsetmiyoruz;

			PYTHTONDA CBS MODÜLLERİ

1- Folium;

 

 

Folium modülü çok güçlü bir coğrafi modül olarak python aracılığı ile bizlere sunulur. Bu modülde haritalar üzerinde hemen hemen her işlemi gerçekleştirebilir, haritaları ve coğrafi verileri manipüle edebilirsiniz.

Folium'un kısa tanımı bu şekilde yapılabilir ancak çok daha kapsamlı ve karmaşık işlerdede kullanılan bir modüldür tek başına haritaları gösteremez sadece işler,manipüle eder ve üzerinde oynama yapar haritaları size HTML olarak verir bunları genelde localhostta açarız veya basit bir sistem kurup html parse ederek harita görsellerini gösteren bir sistem yazarız işte örnek folium görselleri


 


Yukarıdaki görselde İstanbul'a işaretçi konmuştur. Bu işaretçi folium ile konmuştur

Şimdi ise elimizde bir enlem,boylam matrisi olsun ve buradaki matrislere göre harita işaretçilerini koyan bir sistem yazalım;

Matrisimiz:

m = [
    [47.5678, 132.345],
    [-3.6789, 45.123],
    [19.8765, -99.456],
    [0.4567, -75.678],
    [43.2345, 120.789],
    [33.5678, 75.234],
    [-22.3456, 145.678],
    [56.2345, -76.543],
    [-15.9876, 23.456],
    [12.3456, 78.987],
    [9.8765, -120.345],
    [-8.2345, 60.123],
    [65.4321, -87.654],
    [1.2345, 150.234],
    [49.8765, -4.567]
]

 

İşte bu matrisin lok = [enlem,boylam] şeklinde folium ile görselleştirilmiş hali ekranda gördüğünüz gibidir.

İşaretçilerin ikonlarını değiştirebilirsiniz Foliumun kendisinin sağladığı ikonlar olsada kendiniz özelleştirilmiş bir ikon tasarlayıp yine ikonun yerine koyabilirsiniz şimdi ise bu görselleştirmenin aynısını farklı bir işaretçi sembolü ile yapalım;

 

İşte yukarıdaki görselde farklı bir ikon ile görselleştirilmiş veriyonunu görüyorsunuz. Daha bir çok seçenek olsada Kısaca bu şekilde gösterilir. 

Şimdi ise gerçek dünya ile alakalı bir şey yapalım; bir işaretçinin üzerine gelince nokta grafiği meydana çıksın ve bize nüfus grafiklerini versin(temsili bir örnek test verisi kullanıldı)

 
Bu şekilde hem harita görselleştirmesi üzerinde işaretçi gösterimi hemde işaretçi üzerinde veri görselleştirmesi yapabilen bir küçük sistem tasarlamış oldunuz.

Şimdi ise son işlemimize geçelim; Bu son işlemde bir haritada aynı enlem boylam yerine ısı haritası görselleştiricez.

 

Ekranda görmüş olduğunuz görselde ise bir ısı işaretçisi yani HeatMap var buradaki her bi noktanın radius değerini değiştirerek yoğunluk,parlaklık,belirginlik gibi özelliklerini değiştirebilirsiniz

Şimdilik folium ve CBS sistemleri bu kadar daha uzun bir şekilde anlatmaya kalkarsam muhtemelen makale yazmam gerekebilir makalede böyle yazılmaz bu sunum dil çok teknik ve bilimsel değil daha basit ve dost canlısı şekilde anlatmaya çalışıyorum.




Python'da modüllerin sonu gelmez :) O yüzden burada modülleri bitiriyorum ve pythonun diğer konularına geçiyorum;


-------------------------------------------------------------
		FRAMEWORKLER
-------------------------------------------------------------

 

				Framework nedir?

Framework, Bir programlama dilinde bir işlevi gerçekleştirmek için birden fazla modülün birleşmesi aynı çerçeve altında toplanması ile oluşan bir araçtır 
Kısaca;
Framework, bir programlama dilinde kullanılan,
birden fazla hazır yapıyı ve aracı tek çatı altında toplayan,
geliştiricinin işini kolaylaştıran bir hazır iskelet yapıdır

Ayrıca;
bu araç; kurulduğu konu üzerine her işlevi gerçekleştirmek zorundadır Birden fazla framework olsada sınıflara ayrılmıştır işte bunlardan bir kaç tanesi;

⦁	Arayüz frameworkleri (PyQt5/6,PySide,qtpy,Kivy,flet)
⦁	Aİ/ML frameworkleri(TensorFlow,Keras,PyTorch)
⦁	Web/Ağ frameworkleri (Flask,Django)

Bu şekilde örnekler verilebilir; Şimdi ise bazı örnekler verelim;

PyQt ile yapılan bir arayüz;
 

Flask ile yazılan bir Web arayüzü;

 
NOT: Flask bir arayüz frameworkü değildir WEB için APİ,Haberleşme ve dahasını sağlar ancak bazı ekstra iç modülleri ile WEB Arayüzleri elde etmenizide sağlar 


Örnek bir ML/Aİ görseli(Keras,Cv2)

Görsel(1.1)
 
GÖRSEL(1.2)
 

Görsel(1.1) Taşıt segmentasyon örneği
Görsel(1.2) Biyolojik segmentasyon örneği

Yukarıdaki görselde Scipy,Numpy,Cv2 gibi Farklı modüllerde yer almıştır keras sadece bunların içindeki  Yapay zeka(Aİ) Aracıdır

Görsel örnekler bu şekilde verilebilir konular çok teknik ve başklarına sıkıcı gelebileceği için ve çokta uzatmak istemediğim için şu anda burada bitirip diğer konuya geçiyorum;



	-------------------------------------------------------------
		MATEMATİK & YAZILIM
-------------------------------------------------------------
 
		Matematik Yazılım İlişkisi
Kod yazarken matematiği ne kadar görmesekte sadee teknik şeylerede odaklansak aslında hem yazılım dilleri hemde bilgisayarlarımızın çalışma prensipleri çok karmaşık bir matematiğe dayanıyor; Bilgisayarların çalışma prensibini duymuşsunuzdur 0-1 yani binary sistemi ile çalışır aslında ilk yazılım dilleride bu şekilde 0-1 ler ile yazılıyordu o zamanın yazılımcıları bu dillerin cok karmaşık ve cok devam ettirilebilir olmadığınını düşünüyorlardı o yüzden farklı yazılım dilleri çıkardılar binaryden sonra ilk çıkan yazılım dili Assembly idi bununla biraz devam ettiler ancak bununda cok karmaşık oldugunu düşündüler sonra C gibi diller ortaya çıktı işte bu şekilde devam ede ede artık insanlarla konuşur gibi kod yazabilir hale geldik işte olay tamda burada başlıyor biz bu kodları bu şekilde yazabiliyorsak arkadaki matematik sayesinde açıklamama izin verin; Örneğin pythonda "print(2**2)" komudunu çalıştırdınız ve 4 çıktısını aldınız evet doğru 2 üzeri 2 = 4 eder bu basit matematiği önce python sizden aldı ve compiler(derleyici)'da derlemeye aldı derlerken işte o matematik devreye girdi yani kısaca yazılım-mateamatik birbiri ile çok yakından bağlıdır ayrılmaz bir ikili gibidirler ikiside birbirini tamamlar



-------------------------------------------------------------
		YAZILIMDA ALGORİTMALAR
-------------------------------------------------------------
		
 
		ALGORİTMALAR

Yazılımda algoritmanın ne olduğunu bilmemiz için öncelikle algoritmanın ne olduğunu bilmeniz gerekir Yazılımda algoritma kısaca şudur;

Bir işlevi  yerine getiren ve bir işlevi  yerine getirmekle kalmayıp bir problemin içine koyulduğunda o problemi ortadan kaldırdan bir programın nasıl çalışacağını ona söyleyen bir mantık kodudur ve çıktıya giden yolda koda yardımcı olan yapı taşlarını  oluşturan etkenlerdir. Ayrıca matematiksel olmak zorunda değildirler ancak çoğu algoritma matematiksel sınıfına girer.
Temelde algoritmalar şu şekilde sınıflandırılır;
⦁	Sıralama algoritmalar (Sorting Algorithms)
⦁	Arama algoritmaları (Searching Algorithms)
⦁	Optimizasyon algoritmaları (Optimization Algorithms)
⦁	Programa göre şekillendirilmiş algoritmalar (kendi yazdığınız)

Daha bir çok algoritma sınıfı vardır ancak temelde bu şekilde sınıflandırılırlar
Algoritmaları daha iyi anlamak için sırasıyla ne işe yaradıklarını açıklamama izin verin;

Sıralama Algoritmaları: Bu algoritma türü elinizdeki bir sayı dizisini veya herhangi bir veriyi algoritmaya söylediğiniz belirli bir standarta göre sıralamasını sağlayan algoritmalara verilen isimidir. Bu algoritmalar temelde Büyükten küçüğe VEYA Küçükten Büyüğe VEYA Sizin verdiğiniz Standarta göre SIRALAMA Yapar.

Arama algoritmaları: Bu algoritmalar sizin elinizdeki bir dizinin veya bir veri setinin içinde sizin belirlediğiniz anahtar kelimeyi veya sayıyı kısaca VERİYİ arar ancak bunu en optimize edilmiş ve en hızlı,doğru yoldan yapar

Optimizasyon algoritmaları: Bu algoritmalar genelde direkt olarak performans sorunlarını ortadan kaldırmak için tasarlanmışlardır; Örn: Donmalar,Görüntü bulanıklıkları,Yavaşlamalar,Çökmeler VB gibi problemleri çözebilen yani kısaca Performans sorunlarını büyük ölçüde ortadan kaldırmayı ve onların meydana gelmesini engelleyen algoritmalara [OPTİMİZASYON ALGORİTMASI] denir.

Programa göre şekillendirilmiş algoritmalar: Dediğim gibi bu algoritmalar sizin kendi yazdığınız algoritmaları kapsar teknik dünyada standart bir ismi olmasada böyle bir şey vardır açıklamama izin verin; Örneğin programınızda bir problem var veya bir akış mantığı kurmanız gerekiyor bu mantığı kurarken bir algoritma yazmanız gerekebilir yazacağınız algoritma yukarıda bahsettiğim stadart türlerden olmak zorunda değildir. Kendi algoritmalarınızıda programınız için geliştirip onları kullanabilirsiniz Hatta kimi zaman bu yöntem biraz daha kullanışlı olabilir.

Algoritma İsimleri:

Sıralama algoritmaları: Selection Sort, Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Cycle Sort, 3-way Merge Sort

Arama algoritmaları: Yukarıdaki algoritmaların içine yerleştirilmiş sorgu bloklarını kapsayan tüm fonksiyonlar bu kapsama girer Ayrıca temeli Arama üzerine kurulan algoritmalar:

Breadth-First Search, Depth-First Search, A Search, Dijkstra’s Algorithm, Greedy Best-First Search, Iterative Deepening Depth-First Search*

Optimizasyon algoritmalar: Genetic Algorithm, Particle Swarm Optimization, Simulated Annealing, Differential Evolution, Gradient Descent, Nelder–Mead Method


Şeklinde söylenebilir


Algoritmaların zaman karmaşıklıkları ise şu şekilde sınıflandırlır(hızlıdan-yavaşa sıra):

O(1) - Sabit zaman karmaşıklığı (bazı özel durumlarda olabilir, örneğin sıralama işlemi gereksizse).

O(log n) - Lojistik zaman karmaşıklığı (örneğin Binary Search).

O(n) - Lineer zaman karmaşıklığı (örneğin Counting Sort ve Radix Sort gibi bazı algoritmalar lineer zaman karmaşıklığına sahip olabilir).

O(n log n) - Lineer logaritmik zaman karmaşıklığı (en verimli genel sıralama algoritmalarının çoğu, örneğin Merge Sort, Quick Sort, Heap Sort).

O(n²) - Kuadratik zaman karmaşıklığı (bazı basit algoritmalar için, örneğin Bubble Sort, Selection Sort, Insertion Sort).

O(n³) ve üstü - Kübik veya daha yüksek dereceden karmaşıklıklar (genellikle daha nadir ve özel algoritmalar için, büyük veri setlerinde verimsiz olur).



			
 

-------------------------------------------------------------
	YAZILIMDA FORMÜL KURMA
-------------------------------------------------------------

Formül: Matematiksel bir problemin çözülmesi için tasarlanmış sabit standartları olan bir matematiksel ifadedir.

Yazılımda ise formüller kullanılır ancak kullanım alanları daha farklıdır 

Şimdi ekranda bir formül görüyorsunuz;

 

Bu algebra formülünün pythonda yazımı şu şekildedir.

"(a**3) - (b**3) = x" eder
VE
"(a-b)*((a**2) + (a*b) + b**2) = x" eder

Bu formüllerden ikiside aynı sonucu verir ise doğru yazıldığını gösterir;

Şimdi ise test edelim:

 

Evet Bu ifade doğru gibi duruyor şimdi ise gerçekten doğru olup olmadığını doğrulayalım;

 

----------------------------------------------------------------------------------------------
kod:
----------------------------------------------------------------------------------------------
nums = [q for q in range(25)]
matrix = [[],[]]

for num in range(1,len(nums) + 1):
    if num < len(nums) - 1:
        compherm = (nums[num - 1]**3) - (nums[num]**3)
        algebric_comphersm = ((nums[num - 1] - nums[num])*((nums[num - 1]**2) + (nums[num - 1] * nums[num]) + nums[num]**2))
        
        matrix[0].append(abs(compherm))
        matrix[1].append(abs(algebric_comphersm))
    
    else:
        break

for Nmatrix,Mmatrix in zip(matrix[0],matrix[1]):
    print(Nmatrix,Mmatrix)
----------------------------------------------------------------------------------------------
ÇIKTI
----------------------------------------------------------------------------------------------

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
----------------------------------------------------------------------------------------------


Evet görünüşe göre formül koda doğru geçirilmiş hem farklı sayılar ile hemde tek bir sayı ile doğru çıktıyı verebildi İşte yazılımda kısaca formül bu şekilde kurulabilir basit bir örnek olarak bu gösterilebilir.







Sunumum bu kadardı beni dinlediğiniz için teşekkür ederim ayrıca bu sunumumu yapmama izin veren hocalarımada ayrıca teşekkür ederim.
