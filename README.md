# Node.js və Express ilə Back-End proqramlarının inkişafı

## Giriş
Stack Overflow-un 2022-ci ildə keçirdiyi sorğunun nəticələrinə əsasən, developerlərin təxminən 50%-i Node.js istifadə etdiyini bildirmişdir ki, bu da onu server-side texnologiyaları arasında ən çox istifadə edilən edir. Eyni zamanda, Express ümumilikdə dördüncü ən populyar veb texnologiya olaraq siyahıya alınmış və ən populyar server-side veb framework olaraq seçilmişdir. Node.js, server-side JavaScript tətbiqlərini işlədə bilən bir runtime mühitidir, Express isə Node.js üzərində işləyən və tətbiqlərin inkişafı üçün istifadə edilən server-side JavaScript veb frameworkudur.


# Back-end və Front-end Development

## Back-end Development

Back-end development, server-side development olaraq da tanınır və istifadəçilərin görmədiyi veb saytın və ya tətbiqin hissəsini yaratmaqdan ibarətdir. Serveri, bazanı və tətbiq məntiqini idarə edir və frontend-in lazım olan məlumatlara və funksionallığa çıxışını təmin edir. 

### Back-end Development-in Əsas Komponentləri:

1. **Server**: Müştərilərə şəbəkə üzərindən resurslar, məlumatlar, xidmətlər və ya proqramlar təmin edən hardware və ya software.
2. **Database**: Asanlıqla əldə edilə bilən, idarə edilə bilən və yenilənə bilən strukturlu məlumatlar toplusu.
* *SQL Databases*: Relational bazalar, məsələn MySQL, PostgreSQL və SQLite.
* *NoSQL Databases*: Non-relational bazalar, məsələn MongoDB, Cassandra və Redis.
3. **Server-Side Proqramlaşdırma dilləri**: 
* *Node.js*: Chrome-un V8 JavaScript mühərriki üzərində qurulmuş JavaScript runtime.
* *Python*: Oxunaqlılığı və səmərəliliyi ilə tanınan yüksək səviyyəli proqramlaşdırma dili.
* *Ruby*: Sadəliyə fokuslanmış dinamik, açıq mənbəli proqramlaşdırma dili.
* *Java*: Geniş miqyaslı tətbiqlər üçün istifadə edilən çox yönlü və güclü proqramlaşdırma dili.
4. **Framework və Kitabxanalar**:
* *Express*: Minimalist və çevik Node.js veb tətbiq framework-ü.
* *Django*: Sürətli inkişafı təşviq edən yüksək səviyyəli Python veb framework-ü.
* *Ruby on Rails*: Ruby ilə yazılmış server-tərəfli veb tətbiq framework-ü.
* *Spring*: Java inkişafı üçün hərtərəfli framework.

![backend-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/MViVvlPdNXL3L5SESrIGmA/Backend-1.png)

### Back-end Developer-in Məsuliyyətləri:

1. **Məlumatların İşlənməsi və Təhlükəsizliyi**:
   - **Məlumat Bazası Dizaynı**: Məlumatların səmərəli və təhlükəsiz saxlanmasını təmin etmək üçün məlumat bazası strukturunun dizaynı.
   - **Məlumatların Şifrələnməsi**: Məlumatların təhlükəsizliyini təmin etmək üçün şifrələmə texnologiyalarının tətbiqi.
   - **Təhlükəsizlik Protokolları**: SQL injection və digər kibertəhlükələrdən qorunmaq üçün təhlükəsizlik tədbirlərinin görülməsi.

2. **Server və Baza İdarəetməsi**:
   - **Serverlərin Quraşdırılması və İdarə Edilməsi**: Serverlərin quraşdırılması və müştəri sorğularını idarə etmək üçün optimallaşdırılması.
   - **Yedəkləmə və Bərpa**: Məlumatların itirilməsinin qarşısını almaq üçün yedəkləmə proseslərinin qurulması və bərpa strategiyalarının tətbiqi.

3. **API İnkişafı və İnteqrasiyası**:
   - **API Dizaynı**: Tətbiqlərin və xidmətlərin bir-biri ilə əlaqə saxlaması üçün API-lərin dizaynı və inkişafı.
   - **RESTful və GraphQL API-lər**: HTTP sorğuları ilə işləyən RESTful və daha effektiv məlumat sorğusu üçün GraphQL API-lərin qurulması.

4. **Proqramlaşdırma və Script Yazma**:
   - **Server-Tərəfli Kod Yazma**: JavaScript (Node.js), Python, Ruby, PHP və Java kimi dillərdə server tərəfində məntiqi işlətmək üçün kod yazma.
   - **Skript Yazma**: Serverin funksionallığını təmin etmək üçün skriptlərin yazılması və idarə edilməsi.

5. **Miqyaslana Bilən Sistemlərin İnkişafı**:
   - **Yük Paylanması**: Server yükünü tarazlaşdırmaq üçün texnologiyaların tətbiqi.
   - **Miqyaslana Bilən Baza Dizaynı**: Artan məlumat həcmini idarə edə biləcək baza strukturlarının yaradılması.

6. **Performance Optimizasiyası**:
   - **Keşləşdirmə**: Daha sürətli məlumat əldə etmək üçün məlumatların keşləşdirilməsi.
   - **Sorğu Optimizasiyası**: Daha səmərəli məlumat sorğusu üçün SQL sorğularının optimizasiya edilməsi.

7. **Bacarıqlı Əlaqə və Komanda İşbirliyi**:
   - **Komanda Əlaqəsi**: Frontend developerlar və digər komanda üzvləri ilə effektiv əməkdaşlıq.
   - **Sənədləşdirmə**: Yazılmış kodların və proseslərin sənədləşdirilməsi.

![backend-2](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/Qhj5N3YPD4eCcd7iSA95pQ/Backend-2.png)



## Front-end Development

Front-end development, client-side development olaraq da tanınır və istifadəçilərin birbaşa qarşılıqlı əlaqə qurduğu veb saytın və ya tətbiqin hissəsini yaratmaqdan ibarətdir. Bu, istifadəçinin vizual olaraq təcrübə etdiyi və qarşılıqlı əlaqə qurduğu hər şeyi əhatə edir.

### Front-end Development-in Əsas Komponentləri:

1. **HTML (HyperText Markup Language)**: Veb səhifələrin strukturu, başlıqlar, paraqraflar, şəkillər və bağlantılar kimi elementlərin tərtib edilməsi.
2. **CSS (Cascading Style Sheets)**: Veb səhifələrin dizaynı, düzülüş, rənglər, şriftlər və responsive-lik daxil olmaqla stilin müəyyənləşdirilməsi.
3. **JavaScript**: Veb səhifələrdə formalar, animasiyalar və dinamik məzmun yeniləmələri kimi interaktiv xüsusiyyətlərin təmin edilməsi.
4. **Framework və Kitabxanalar**:
   - **React**: İstifadəçi interfeysləri qurmaq üçün JavaScript kitabxanası.
   - **Angular**: Veb tətbiqləri qurmaq üçün TypeScript əsaslı framework.
   - **Vue.js**: İstifadəçi interfeysləri qurmaq üçün inkişaf edən JavaScript framework-ü.

![frontend-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/rddWsb0t8rXd9nlaMG7DoQ/Frontend-1.png)

### Front-end Developer-in Məsuliyyətləri:

1. **İstifadəçi Təcrübəsinin Təmin Edilməsi**:
   - **Təcrübənin Dizaynı**: İstifadəçi interfeysi və dizayn prinsipləri əsasında istifadəçi dostu və estetik cəhətdən xoş bir təcrübə yaratmaq.
   - **Responsive Dizayn**: Tətbiqin müxtəlif ekran ölçülərinə uyğun olaraq optimallaşdırılması.

2. **İnteraktiv Elementlərin İnkişafı**:
   - **JavaScript Kodlaşdırması**: Formlar, animasiyalar və digər dinamik xüsusiyyətlər üçün JavaScript kodlarının yazılması.
   - **Asinxron Məlumat Yüklənməsi**: AJAX və Fetch API-ləri istifadə edərək məlumatların serverdən alınması və yenilənməsi.

3. **Təhlükəsiz və Performanslı Veb Tətbiqlərin Yaradılması**:
   - **Kodun Performansını Təmin Etmək**: Yük vaxtını azaltmaq və istifadəçi təcrübəsini artırmaq üçün optimizasiya işlərinin aparılması.
   - **Təhlükəsizlik Tədbirləri**: XSS (Cross-Site Scripting) və digər təhlükəsizlik zəifliklərinə qarşı mühafizə tədbirlərinin görülməsi.

4. **Dizayn və İnkişaf Üçün Alətlərin İstifadəsi**:
   - **Version Control**: Git kimi alətlərdən istifadə edərək kod versiyalarının idarə edilməsi.
   - **Frontend Frameworklərin İstifadəsi**: React, Angular və Vue.js kimi frameworklərdən istifadə edərək sürətli və effektiv inkişaf.

5. **Komanda ilə Əməkdaşlıq**:
   - **Layihə Planlaşdırılması**: Backend developerlar və dizaynerlərlə birlikdə layihənin məqsəd və tələblərinə uyğun inkişafın təmin edilməsi.
   - **Geri Dönüşlərin Əldə Edilməsi**: İstifadəçilərin və komanda üzvlərinin fikirlərini toplayaraq tətbiqin təkmilləşdirilməsi.

![frontend-2](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/NrlSmmPp0FA22OCoUgIo3A/front-3.png)


----------------------------------------------

# Node.js (ümumi giriş)

## Full-stack Tətbiqi

Full-stack tətbiqi aşağıdakı komponentləri əhatə edir:

#### Müştəri Tərəfi:

İstifadəçilərin qarşılıqlı əlaqə qurduğu veb sayt və mobil tətbiqlər.

#### Server Tərəfi:

Müştəri tərəfindən edilən sorğuları işləyir və cavabları müştəriyə göndərir. Bulud server, tətbiq serveri və məlumat bazasını yerləşdirir.

![node-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0220EN-SkillsNetwork/Readings/images/client_server.png)

### Open Source and Cross-Platform:

JavaScript, HTML səhifələrinin müştəri tərəfində doğrulanması üçün idealdır, çünki çox yönlü və platformalar-arası uyğunluğa malikdir. İstifadəsinin asanlığını nəzərə alaraq, JavaScript server tərəfi kodlaşdırma üçün də uyğunlaşdırıldı və nəticədə Node.js meydana gəldi. Node.js bir işləmə mühiti kimi fəaliyyət göstərir və xüsusi lisenziyaya ehtiyac duymur. Bununla yanaşı, açıq mənbə təbiəti sayəsində Node.js üçün çox sayda paket və kitabxana inkişaf etdirilmişdir. Üstəlik, Node.js kodu Linux, Windows və Mac OSX kimi müxtəlif əməliyyat sistemlərində problemsiz şəkildə işləyə bilər.

### V8 Engine:

Yazdığınız hər bir kod parçası işlənməli və maşın tərəfindən oxunan formaya çevrilməlidir. Node.js dünyasında, JavaScript kodu Google V8 mühərriki ilə icra edilir. V8, yüksək performansı ilə tanınan və Google tərəfindən inkişaf etdirilən açıq mənbə mühərrikidir, eyni zamanda bütün Google Chrome brauzerlərində inteqrasiya edilmişdir. Bundan əlavə, müasir brauzerlər, məsələn, Microsoft Edge və Firefox, Node.js kodunu icra etmək üçün V8 mühərrikini istifadə edir.

### Event-Driven, Asynchronous, Non-Blocking, Single-Threaded: 

Server prosesləri "single-threaded" və ya "multi-threaded" olaraq təsnif edilə bilər. Single-threaded mühitdə yalnız bir əmrlə işlənir, multi-threaded mühitdə isə eyni anda birdən çox əmrlə işlənir. Single-threaded olmasına baxmayaraq, Node.js asinxron və bloklanmayan təbiəti ilə performansda mükəmməldir. Bu o deməkdir ki, bir proses icra edilərkən proqramın tamamlanmasını gözləməyə ehtiyac yoxdur. Node.js hadisə-əsaslıdır (event-driven), yəni şəbəkədən oxumaq və ya məlumat bazasına və ya fayl sisteminə daxil olmaq kimi giriş/çıxış (I/O) əməliyyatı yerinə yetirildikdə bir hadisə işlənilir. Bu bloklanmayan davranış serverin cavabdeh qalmasını və eyni anda bir neçə işi yerinə yetirməsini təmin edir, multi-threaded mühitə bənzəyir.

### JSON Payload

JSON (JavaScript Object Notation) "açar-dəyər cütləri" *("key-value pairs")* şəklində formatlanmışdır. Payload (yük) müştəri ilə server arasında ötürülən məlumatları təmsil edir. Müştəri serverə məlumat göndərmək istədikdə, bunu JSON obyektində edir.

```json
{
    "name": "John",
    "age": "24",
    "email": "johnparker@gmail.com"
}
```

Yuxarıdakı obyekt JSON-dur. Bu məlumat sorğu daxilində göndərildikdə, dəyərləri sadəcə `request.name` və s. istifadə edərək çıxarıla bilər.

Eyni şəkildə, cavab da JSON şəklində göndərilir.

```json
{
    "status": "ok",
    "message": "Successfully added"
}
```

### Express Framework-ü

Node.js server yaratmaq üçün paketlər təqdim etsə də, Express framework-ü API-lər və endpointlər yaratma prosesini sadələşdirir. API endpointi müştəridən serverə edilən sorğu üçün xüsusi bir giriş nöqtəsidir.

--------------------------------------------------------

## Node.js-in Full-stack Development-də Üstünlükləri

1. **Birləşdirilmiş Dili**: Node.js-in istifadə edilməsi, inkişaf etdiricilərə həm müştəri tərəfində, həm də server tərəfində JavaScript-dən istifadə etməyə imkan tanıyır. Bu, fərqli dillər arasında keçid etmə ehtiyacını azaldır və inkişaf prosesini daha uyğun və səlis edir.

2. **Davamlı Alətlər**: Node.js istifadə edərkən test etmə və asılılıq idarəetmə alətlərini həm müştəri tərəfi, həm də server tərəfi kodu üzərində tətbiq edə bilərsiniz. Bu, NPM-dən paket idarəetməsi üçün istifadə etməyi də əhatə edir.

3. **İcma və Resurslar**: Node.js geniş və aktiv bir icmaya malikdir, bu da əhatəli öyrənmə resursları və dəstək deməkdir. Peşəkar inkişaf etdiricilərin 50%-dən çoxu Node.js-dən istifadə edir, bu da onun populyarlığını və faydalılığını əks etdirir.

4. **JavaScript İnkişaf etdiriciləri üçün Asan Keçid**: Əgər JavaScript ilə tanışsınızsa, Node.js-ə keçid backend inkişafı üçün yeni bir dili öyrənməkdən daha hamar olacaq.

5. **Asinxron Proqramlaşdırma**: Node.js single-threaded, bloklanmayan I/O modeli və hadisə-əsaslı arxitekturadan istifadə edir, bu da çox sayda eyni anda əlaqəni effektiv şəkildə idarə edə bilir.

6. **Performans**: Google V8 mühərriki üzərində qurulan Node.js, sürətli işləmə və yüksək yükləmə tələb edən senarilərdə mükəmməl nəticələr verir, məsələn, onlayn oyunlar, çat tətbiqləri və real-vaxt məlumat emalı.

7. **Mikroservislərlə Uyğunluq**: Node.js mikroservis memarlığı ilə yaxşı uyğun gəlir, burada xidmətlər kiçik, fokuslanmış və miqyaslana biləndir.

8. **Paketsiz İmkanlar**: NPM qeydiyyatı geniş seçimi olan paketlər təqdim edir, inkişaf imkanlarını artırır və tətbiqlərin yaradılma prosesini sürətləndirir.

---------------------------------------------------------------------

## Node.js-də Import və Require

Node.js-də modullar, tətbiqin müxtəlif hissələrində təkrar istifadə edilə bilən funksionallığın özündə saxlayan, müstəqil bölmələrdir. Bu modullar fərdi fayllar və ya çoxsaylı fayl və qovluqlardan ibarət kolleksiyalar ola bilər. Modulyar yanaşma mürəkkəb kodun idarə edilə bilən hissələrə bölünməsinə və kodun təkrar istifadəsinin təşviq edilməsinə kömək edir.

Modulun daxilindəki kodu xarici tətbiqdə istifadə etmək üçün inkişaf etdiricilər `require()` və ya `import()` ifadələrindən istifadə edirlər. Bu iki üsul arasındakı seçim istifadə olunan modul spesifikasiyasından asılıdır. Node.js əsasən iki modul spesifikasiyasını dəstəkləyir: CommonJS və ES modulları.

#### Modul Spesifikasiyaları

1. **CommonJS**:
   - **Node.js-də Default**: Node.js, JavaScript kodunu standart olaraq CommonJS modulları kimi qəbul edir.
   - **Sintaksis**: Modulları import etmək üçün `require()` istifadə edir.
   - **Export**: Funksionallığı export etmək üçün `module.exports` istifadə edir.

2. **ES Modulları**:
   - **Node.js-də Aktivləşdirmək**: ES modullarını `.mjs` fayl uzantısından istifadə etməklə aktivləşdirmək mümkündür.
   - **Sintaksis**: Modulları gətirmək üçün `import` və funksionallığı əlçatan etmək üçün `export` istifadə edir.
   
#### `require` və `import` Arasındakı Əsas Fərqlər

1. **Kodda Yerləşmə (Placement in Code)**:
   - **require**: Faylın hər hansı bir yerində, o cümlədən funksiyalar və şərtli ifadələr daxilində çağırıla bilər.
   - **import**: Faylın əvvəlində çağırılmalı və şərtli olaraq yüklənə bilməz.

2. **Bağlama (Binding)**:
   - **require**: Dinamik olaraq bağlanır, yəni modul həlli icra vaxtında baş verir. Funksiyaların təriflərinə əlaqələndirilməsindəki səhvlər yalnız kod icra olunduqda aşkar edilə bilər.
   - **import**: Statik olaraq bağlanır, səhvlərin tərtib vaxtında aşkar olunmasına imkan verir, bu da daha yaxşı səhv yoxlamasını təmin edir.

3. **Sinxron və Asinxron (Synchronous vs. Asynchronous)**:
   - **require**: Sinxron, modulları xətti, bloklaşdırıcı şəkildə yükləyir və işləyir.
   - **import**: Asinxron, modulların paralel olaraq yüklənməsinə imkan verir, bu da iri miqyaslı tətbiqlərdə performansı artırır.

#### Nümunə Kod

**CommonJS Nümunəsi**:

*CommonJS ilə Export*:
```javascript
// message.js
module.exports = "Hello programmers";
```

*CommonJS ilə Import*:
```javascript
// main.js
let msg = require('./message.js');
console.log(msg); // Nəticə: Hello programmers
```

**ES Modulları Nümunəsi**:

*ES Modulları ilə Export*:
```javascript
// module.mjs
const a = 1;
export { a as myValue };
```

*ES Modulları ilə Import*:
```javascript
// main.mjs
import { myValue } from './module.mjs';
console.log(myValue); // Nəticə: 1
```

### Nəticə

- **Modullar**: Node.js-də özündə kodu saxlayan və təkrar istifadəni və idarə olunmasını təşviq edən müstəqil bölmələrdir.
- **Spesifikasiyalar**: CommonJS və ES modulları, fərqli import/export sintaksisi ilə.
- **require vs. import**:
  - `require`: Dinamik, sinxron, hər yerdə istifadə edilə bilər.
  - `import`: Statik, asinxron, faylın əvvəlində istifadə edilməlidir.
  
Bu iki import metodunun fərqlərini və müvafiq istifadə hallarını başa düşmək, Node.js tətbiqlərində daha səmərəli və səhvsiz kod yazmağa kömək edir.

----------------------------------------------------------------

### Server-Side JavaScript-ə Giriş

JavaScript, veb inkişafında ən təsirli proqramlaşdırma dillərindən biri olmuşdur. Əvvəlcə statik veb səhifələrə dinamik davranış əlavə etmək üçün yaradılan JavaScript, indi həm müştəri, həm də server tərəflərində işləyən çox yönlü bir dildir. 

#### JavaScript-in Mənşəyi və İnkişafı

- **Müştəri Tərəfli Başlanğıclar**: JavaScript ilk olaraq veb brauzerlər daxilində icra olunmaq üçün yaradıldı və statik HTML səhifələrini dinamik, interaktiv xüsusiyyətlərlə zənginləşdirdi.
- **İnterpretasiya Edilən Dil**: Kompilyasiya olunan dillərdən fərqli olaraq, JavaScript interpretasiya edilir, yəni icra edilmədən əvvəl kompilyasiya mərhələsinə ehtiyac yoxdur.
- **Java ilə Əlaqəsi Yoxdur**: Adına və oxşar sintaksisinə baxmayaraq, JavaScript Java proqramlaşdırma dilindən törəmə deyil.
- **Geniş Dəstək**: Bütün müasir veb brauzerlər JavaScript-i dəstəkləyir, onu veb inkişafı üçün hər yerdə mövcud bir vasitə halına gətirir.

#### Ənənəvi Veb Tətbiqi Axını

1. **İstifadəçi İnterfeysi (UI)**: HTML və CSS istifadə edilərək yaradılır.
2. **Müştəri Tərəfli Məntiq**: İstifadəçi UI ilə qarşılıqlı əlaqə yaratdıqda, JavaScript müştəri tərəfli iş məntiqini idarə edir.
3. **Veb Xidmət Sorğusu**: JavaScript serverə sorğular göndərir, adətən JSON üzərindən HTTP istifadə olunur.
4. **Server Tərəfli Emal**: Ənənəvi olaraq, server tərəfli emal Java və ya PHP kimi dillərdən istifadə etməklə həyata keçirilirdi.
5. **Cavab**: Server sorğunu emal edir və müştəriyə məlumat qaytarır.

#### Node.js və Server-Side JavaScript

Node.js, JavaScript-in imkanlarını server tərəfinə qədər genişləndirir və inkişaf etdiricilərə həm müştəri, həm də server tərəfli kodu JavaScript-də yazmağa imkan verir. Node.js ilə proses belə görünür:

1. **İstifadəçi İnterfeysi (UI)**: HTML və CSS istifadə edilərək yaradılır.
2. **Müştəri Tərəfli Məntiq**: JavaScript müştəri tərəfli iş məntiqini idarə edir.
3. **Veb Xidmət Sorğusu**: Müştəri tərəfli JavaScript tətbiqi, JSON formatında məlumat göndərərək HTTP sorğusu edir.
4. **REST Veb Xidməti**: Sorğunu serverdə qarşılayan RESTful xidmət.
5. **Node.js Serveri**: Başqa bir backend dilində yazılmış tətbiqi çağırmaq əvəzinə, Node.js serveri sorğunu JavaScript istifadə edərək emal edir.

#### Node.js-in Faydaları

- **Birləşmiş Dil**: İnkişaf etdiricilər həm müştəri, həm də server tərəflərində JavaScript istifadə edə bilər, bu da inkişaf prosesini sadələşdirir.
- **Miqyasa Uyğunluq**: Node.js çoxsaylı eyni vaxtlı əlaqələri səmərəli şəkildə idarə etmək üçün nəzərdə tutulmuşdur, bu da onu miqyasa uyğun tətbiqlər üçün uyğun edir.
- **Minimal Alətlər Dəsti**: Node.js server tətbiqlərini yaratmaq üçün minimal alətlər dəsti ilə sürətli inkişafı təmin edir.

### Yekun

- **JavaScript**: Əvvəlcə müştəri tərəfli dil kimi, indi Node.js ilə server tərəfli inkişafda istifadə olunur.
- **Node.js**: Server tərəfli JavaScript-i təmin edən, miqyasa uyğun, səmərəli və sürətli server tətbiqlərinin inkişafını mümkün edən bir framework.
- **Birləşmiş İnkişaf**: Həm müştəri, həm də server tərəfli kodu JavaScript-də yazmaq, inkişaf axınını sadələşdirir və yeni inkişaf etdiricilər üçün öyrənmə əyrisini azaldır.
