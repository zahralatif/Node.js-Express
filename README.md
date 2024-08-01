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

## Server-Side JavaScript-ə Giriş

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

---------------------------------------------------

## Node.js ilə Veb Server Yaratmaq

Node.js, JavaScript-dən istifadə edərək miqyaslana bilən, eyni zamanda işləyə bilən server tətbiqləri qurmaq üçün güclü bir server-tərəf runtime mühitdir. Bu, hadisə idarə olunan, bloklamayan I/O modelinə əsaslanır, bu da onu məlumat-intensive real vaxt tətbiqləri üçün yüngül və səmərəli edir. 

#### Əsas Konsepsiyalar

1. **Single-Threaded Event Loop**: Node.js, hadisələr və callback funksiyaları vasitəsilə I/O əməliyyatlarını asinxron şəkildə idarə edən single-threaded hadisə döngüsündə işləyir.
2. **Modules**: Node.js-də hər bir JavaScript faylı bir moduldur. Node.js, müxtəlif funksiyaları asanlaşdırmaq üçün HTTP modulu kimi daxili istifadə modulları ilə təmin olunur.

#### Addım-addım Bələdçi

1. **Quraşdırma**: Node.js-in quraşdırıldığına əmin olun. Siz onu [Node.js rəsmi veb saytından](https://nodejs.org/) yükləyə bilərsiniz.

2. **Yeni JavaScript Faylı Yaradın**:
   `server.js` (və ya istədiyiniz ad) adında yeni bir fayl yaradın.

3. **HTTP Modulunu İdxal Edin**:
   HTTP modulu təmin edilmiş Node.js ilə idxal edin.

   ```javascript
   const http = require('http');
   ```

4. **Serveri Yaradın**:
   Yeni server instansiyası yaratmaq üçün `http.createServer` metodundan istifadə edin. Bu metod daxil olan sorğuları idarə edən və cavabları göndərən callback funksiyasını qəbul edir.

   ```javascript
   const server = http.createServer((req, res) => {
       // Cavab HTTP başlığını HTTP statusu və Content type ilə təyin edin
       res.writeHead(200, {'Content-Type': 'text/plain'});

       // Cavab gövdəsini "Hello, World!" olaraq göndərin
       res.end('Hello, World!\n');
   });
   ```

5. **Serverin Bir Portda Dinləməsini Təmin Edin**:
   Server instansiyasında `listen` metodunu çağıraraq onu müəyyən bir portda (məsələn, 8080) dinləmək üçün qurun.

   ```javascript
   server.listen(8080, () => {
       console.log('Server http://127.0.0.1:8080/ ünvanında işləyir.');
   });
   ```

6. **Serveri İcra Edin**:
   Faylı yadda saxlayın və terminaldan Node.js istifadə edərək serveri işlədin.

   ```sh
   node server.js
   ```

   Terminalda `Server http://127.0.0.1:8080/ ünvanında işləyir.` mesajını görməlisiniz.

7. **Serverə Giriş**:
   Veb brauzerinizi açın və `http://127.0.0.1:8080/` ünvanına keçin. "Hello, World!" mesajını görməlisiniz.

#### Tam Kod Nümunəsi

Burada, Node.js ilə əsas veb server yaratmaq üçün tam kod verilmişdir:

```javascript
// HTTP modulunu idxal edin
const http = require('http');

// Serverin bir instansiyasını yaradın
const server = http.createServer((req, res) => {
    // Cavab HTTP başlığını HTTP statusu və Content type ilə təyin edin
    res.writeHead(200, {'Content-Type': 'text/plain'});

    // Cavab gövdəsini "Hello, World!" olaraq göndərin
    res.end('Hello, World!\n');
});

// Serverin 8080 portunda dinləməsini təmin edin
server.listen(8080, () => {
    console.log('Server http://127.0.0.1:8080/ ünvanında işləyir.');
});
```

### Yekun

- **Node.js**: Asinxron şəkildə I/O əməliyyatlarını idarə edən single-threaded, hadisə idarə olunan mühitdir.
- **Modullar**: Hər JavaScript faylı bir moduldur və Node.js HTTP kimi bir neçə daxili modulu əhatə edir.
- **HTTP Modulu**: HTTP sorğularını dinləyən və onlara cavab verən veb serverləri yaratmaq üçün istifadə olunur.
- **Server Yaratma**: `http.createServer()` ilə server instansiyası yaratmaq və `server.listen()` ilə müəyyən bir portda dinləməsini təmin etmək.

----------------------------------------------------------------

## Node.js Modulları ilə İş

Node.js-də modullar tətbiq inkişafının əsas hissəsidir, kodu təşkil etməyə və təkrar istifadəyə imkan verir. Bir paket, bir və ya daha çox modulların kolleksiyasıdır və `package.json` faylı paket haqqında əsas məlumatları təmin edir. Budur, Node.js modulları ilə necə işləmək haqqında ətraflı məlumat:

#### `package.json` Faylı

`package.json` faylı, layihəniz haqqında metadata, asılılıqlar, skriptlər və s. daxil olan manifest kimi xidmət edir. Budur, bir `package.json` faylının əsas strukturu:

```json
{
  "name": "today",
  "version": "1.0.0",
  "description": "A simple module to get today's date",
  "main": "lib/today.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Your Name",
  "license": "ISC"
}
```

- **name**: Paketinizin adı.
- **version**: Paketinizin versiyası.
- **main**: Paketinizin giriş nöqtəsi (məsələn, `lib/today.js`).
- **scripts**: Müxtəlif komanda skriptlərini çalışdırmaq üçün (məsələn, testlər).
- **author**: Paketinizin müəllifi.
- **license**: Paketinizin paylanma lisenziyası.

#### `require` ilə Modulları İdxal Etmək

Node.js tətbiqinizdə bir modulu istifadə etmək üçün `require` funksiyasından istifadə edərək idxal edirsiniz. Budur necə işləyir:

1. **Sadə Modul İdxalı**:
   Tutaq ki, `today.js` faylı əsas tətbiq faylınız olan `app.js` ilə eyni qovluqdadır.

   ```javascript
   // today.js
   module.exports = {
     getDate: function() {
       return new Date().toDateString();
     }
   };
   ```

   ```javascript
   // app.js
   const today = require('./today');
   console.log(today.getDate());
   ```

2. **Bir Qovluqda Varsayılan Modul**:
   Əgər modulunuz bir qovluğun içindədirsə və əsas skript `index.js` adlanırsa, onu qovluq adını göstərərək idxal edə bilərsiniz.

   ```javascript
   // mod_today/index.js
   module.exports = {
     getDayOfWeek: function() {
       const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
       return days[new Date().getDay()];
     }
   };
   ```

   ```javascript
   // app.js
   const modToday = require('./mod_today');
   console.log(modToday.getDayOfWeek());
   ```

#### Modullardan İxrac Etmək

Başqa fayllara funksiyalar və ya dəyərləri əlçatan etmək üçün `exports` obyektindən istifadə edirsiniz. Budur bir nümunə:

```javascript
// today.js
exports.dayOfWeek = function() {
  const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
  return days[new Date().getDay()];
};
```

Bu modulu idxal etdiyiniz zaman, `dayOfWeek` funksiyasına giriş əldə edə bilərsiniz:

```javascript
// app.js
const today = require('./today');
console.log(today.dayOfWeek());
```

#### Layihə Strukturunun Nümunəsi

Budur bir Node.js layihəsinin nümunə qovluq strukturu:

```
my-project/
├── mod_today/
│   └── index.js
├── today.js
├── app.js
└── package.json
```

- **mod_today/index.js**: Modul məntiqini ehtiva edir.
- **today.js**: Başqa bir modul faylı.
- **app.js**: Əsas tətbiq faylı.
- **package.json**: Layihə və asılılıqları haqqında məlumat verir.

### Yekun

- **package.json**: Node.js layihəniz haqqında metadata ehtiva edir.
- **Modullar**: Layihənizdə təkrar istifadə edilə bilən JavaScript kod parçalarıdır.
- **require**: Node.js-də modulları idxal etmək üçün istifadə olunur.
- **exports**: Bir moduldan funksiyalar və ya dəyərləri əlçatan etmək üçün istifadə olunur.

Kodunuzu modullara bölərək və layihənizi idarə etmək üçün `package.json` faylından istifadə edərək, miqyaslana bilən və saxlanıla bilən Node.js tətbiqləri yarada bilərsiniz.

-----------------------------------------------------------------------

## Node.js Modullarına Giriş

Node.js-də modullar, tətbiqləri effektiv şəkildə qurmaq və saxlamaq üçün təkrar istifadə edilə bilən kod parçalarıdır. Modullar üç növə bölünə bilər: əsas, yerli və üçüncü tərəf. 

#### Node.js Modullarının Növləri

1. **Əsas Modullar**:
   - **Tərif**: Node.js runtime-a daxil olan və əlavə kitabxanalara ehtiyac duymadan əsas funksionallıqları təmin edən modullar.
   - **Nümunələr**: `http`, `fs`, `os`, `path`, `util`, `url`, `querystring`.

2. **Yerli Modullar**:
   - **Tərif**: Sizin və ya inkişaf komandası tərəfindən tətbiqinizin bir hissəsi olaraq yaradılan xüsusi modullar.
   - **Nümunə**: Tarixlə bağlı funksionallıqları təmin edən `today.js` adlı bir modul.

3. **Üçüncü Tərəf Modulları**:
   - **Tərif**: Node.js icması tərəfindən yaradılan və onlayn mövcud olan modullar (məsələn, npm vasitəsilə).
   - **Nümunələr**: `express`, `axios`, `async`.

#### Əsas Modullar

Əsas modullar Node.js tətbiqləri üçün vacib funksionallıqları təmin edir. Burada bəzi mühüm nümunələr və kod nümunələri var:

1. **HTTP Modulu**:
   - **Məqsəd**: HTTP üzərindən məlumatları ötürmək.
   - **İstifadə**:

     ```javascript
     const http = require('http');
     http.createServer((req, res) => {
         res.write('Serverdən salam');
         res.end();
     }).listen(6000);
     ```

2. **FS (Fayl Sistemi) Modulu**:
   - **Məqsəd**: Fayl sistemi ilə qarşılıqlı əlaqə qurmaq.
   - **İstifadə (Asinxron oxuma)**:

     ```javascript
     const fs = require('fs');
     fs.readFile('sample.txt', 'utf8', (err, data) => {
         if (err) {
             console.error(err);
             return;
         }
         console.log(data);
     });
     ```

   - **İstifadə (Sinxron oxuma)**:

     ```javascript
     const fs = require('fs');
     const data = fs.readFileSync('content.md', 'utf8');
     console.log(data);
     ```

3. **OS Modulu**:
   - **Məqsəd**: Əməliyyat sistemi ilə qarşılıqlı əlaqə qurmaq.
   - **İstifadə**:

     ```javascript
     const os = require('os');
     console.log("Platforma: " + os.platform());
     console.log("Arxitektura: " + os.arch());
     ```

4. **Path Modulu**:
   - **Məqsəd**: Kataloq və fayl yolları ilə işləmək.
   - **İstifadə**:

     ```javascript
     const path = require('path');
     const result = path.basename('/content/index/home.html');
     console.log(result); // Çıxış: home.html
     ```

5. **Util Modulu**:
   - **Məqsəd**: Düzgünlüyü yoxlamaq və yardımçı funksiyalar üçün.
   - **İstifadə**:

     ```javascript
     const util = require('util');
     const str = 'Döngə %d dəfə icra olundu.';
     for (let i = 1; i <= 10; i++) {
         console.log(util.format(str, i));
     }
     ```

6. **URL Modulu**:
   - **Məqsəd**: URL-ləri pars etmək.
   - **İstifadə**:

     ```javascript
     const url = require('url');
     const webAddress = 'http://localhost:2000/index.html?lastName=Kent&firstName=Clark';
     const qry = url.parse(webAddress, true);
     const qrydata = qry.query;
     console.log(qrydata.firstName); // Çıxış: Clark
     ```

7. **QueryString Modulu**:
   - **Məqsəd**: URL-in sorğu sətirlərini pars etmək.
   - **İstifadə**:

     ```javascript
     const querystring = require('querystring');
     const qryParams = querystring.parse('lastName=Kent&firstName=Clark');
     console.log(qryParams.firstName); // Çıxış: Clark
     ```

#### Üçüncü Tərəf Modulları

Üçüncü tərəf modulları Node.js funksionallıqlarını genişləndirir. Bəzi məşhur nümunələr:

- **Express**: Minimal və çevik Node.js web tətbiq çərçivəsi.
- **Axios**: Browser və Node.js üçün vədəsiz HTTP müştərisi.
- **AsyncJS**: Asinxron JavaScript ilə işləmək üçün güclü funksiyalar təmin edən yardımçı modul.

Üçüncü tərəf modulları npm (Node Package Manager) vasitəsilə quraşdıra bilərsiniz:

```sh
npm install express
```

-----------------------------------------------------------------------

## Node Package Manager (NPM) 

Paket meneceri, proqram layihələrinin etibar etdiyi kitabxanalar və paketlər kimi asılılıqları idarə etmək üçün vacib bir vasitədir. Node Package Manager (NPM), Node.js üçün default paket meneceridir və bu asılılıqları effektiv şəkildə idarə etməkdə mühüm rol oynayır.

#### NPM-nin Əsas Funksiyaları

1. **Əmr Sırası İnterfeysi (CLI)**:
   - NPM, paketləri dərc etmək, yükləmək, quraşdırmaq, yeniləmək və silmək üçün komandalar təqdim edir.

2. **Onlayn Repozitoriya**:
   - NPM, JavaScript paketlərinin versiyalarını və asılılıqlarını izləyən ətraflı bir verilənlər bazasını saxlayır.

#### Asılılıqları Anlamaq

Asılılıqlar, layihənizin etibar etdiyi xarici kitabxanalar və ya paketlərdir. Bu asılılıqları əl ilə idarə etmək çətin və səhvlərə yol açan bir proses ola bilər ki, NPM bu prosesi avtomatlaşdıraraq üstünlük təşkil edir.

#### `package.json` Faylı

- **Məqsəd**: Layihə haqqında metadata, o cümlədən onun asılılıqlarını ehtiva edir.
- **Vacib Sahələr**:
  - `name`: Layihənin adı.
  - `version`: Layihənin versiya nömrəsi.

Əsas `package.json` faylı nümunəsi:

```json
{
  "name": "my-project",
  "version": "1.0.0"
}
```

#### Paketlərin Quraşdırılması

Paketlər, NPM vasitəsilə yerli və ya qlobal olaraq quraşdırıla bilər.

1. **Yerli Quraşdırma**:
   - **Əmr**: `npm install <package_name>`
   - **İzahı**: Paketi, layihənizin qovluğunda olan `node_modules` qovluğunda quraşdırır və yalnız həmin layihəyə əlçatan edir.

2. **Qlobal Quraşdırma**:
   - **Əmr**: `npm install -g <package_name>`
   - **İzahı**: Paketi qlobal olaraq quraşdırır və bu paketi maşındakı hər hansı bir layihəyə əlçatan edir. Qlobal quraşdırmaları diqqətlə istifadə edin ki, fərqli layihələr arasında versiya uyğunsuzluqlarının qarşısı alınsın.

#### Əmr Nümunələri

- **Yerli Quraşdırma**:

  ```sh
  npm install express
  ```

- **Qlobal Quraşdırma**:

  ```sh
  npm install -g express
  ```

#### Paketlərin İdarə Edilməsi

NPM, paketləri yeniləmək və silmək üçün də komandalar təqdim edir:

- **Paketin Yenilənməsi**:

  ```sh
  npm update <package_name>
  ```

- **Paketin Silinməsi**:

  ```sh
  npm uninstall <package_name>
  ```

----------------------------------------------------------------

## Asinxron I/O ilə Callback Proqramlaşdırması

### Əsas Konsepsiyalar

- **Asinxron Şəbəkə Əməliyyatları (Asynchronous Network Operations)**: Node.js-də şəbəkə əməliyyatları asinxron işləyir ki, cavab gözləyərkən prosessinq vaxtının itirilməsinin qarşısını alsın.
  
- **Non-blocking Əməliyyatlar**: Node.js-də bütün şəbəkə əməliyyatları dərhal geri qaytarılır, tətbiqin şəbəkə əməliyyatının tamamlanmasını gözləmədən prosessinqə davam etməsinə imkan verir.

- **Callback Funksiyaları**: Node.js asinxron əməliyyatların nəticələrini idarə etmək üçün callback funksiyalarından istifadə edir. Bu funksiyalar şəbəkə əməliyyatı tamamlandıqda çağırılır.

### İş Axını Nümunəsi (Workflow Example)

1. **HTTP Sorğusu**:
   - Tətbiq `HTTP.request()` funksiyasını çağırır və bu funksiya uzaq veb serverə sorğu göndərir.
   - Node.js cavabı gözləmədən sorğunun uğurla göndərildiyini göstərən nəticəni dərhal geri qaytarır.

2. **Callback İdarəetməsi (Callback Handling)**:
   - Uzaq server cavab verdikdə, Node.js `HTTP.request()` çağırışında təyin edilmiş callback funksiyanı çağırır.
   - Bu callback funksiya HTTP cavab mesajını emal edir.

### Ssenari Təhlili (Scenario Breakdown)

1. **Sadə HTTP Sorğusu**:
   - Tətbiq `HTTP.request()` funksiyasını çağırır.
   - Node.js sorğunu göndərir və uğur mesajı geri qaytarır.
   - HTTP cavabı alındıqda, Node.js təyin edilmiş callback funksiyanı çağıraraq cavabı idarə edir.

2. **Mürəkkəb Ssenari**:
   - Tətbiq xüsusi bir Node.js modulunu çağırır, bu modul `HTTP.request()` funksiyasını çağırır.
   - Modul sorğunu göndərir və control-u tətbiqə qaytarır.
   - Cavab alındıqda, Node.js moduldakı təyin edilmiş callback funksiyanı çağırır və bu funksiya `data` və `end` kimi hadisələri emal edir.

### Kod Nümunəsi

Budur, Node.js istifadə edərək HTTP sorğusu etmək üçün bir nümunə:

```javascript
const http = require('http');

const options = {
    hostname: 'api.weather.gov',
    path: '/stations/KSFO/observations/latest',
    method: 'GET',
};

const req = http.request(options, (res) => {
    let buffer = '';

    res.on('data', (chunk) => {
        buffer += chunk;
    });

    res.on('end', () => {
        console.log(buffer);
    });
});

req.on('error', (e) => {
    console.error(`Problem with request: ${e.message}`);
});

req.end();
```

### Hadisə İdarəetməsi (Event Handling)

- **Data Hadisəsi**: Hər dəfə bir data parçası alındıqda işləyir.
- **End Hadisəsi**: Cavab tam olduqda işləyir.
- **Error Hadisəsi**: Sorğuda bir səhv olduqda işləyir.

### Xülasə

- **Non-blocking Əməliyyatlar**: Node.js I/O əməliyyatlarını asinxron şəkildə idarə edir ki, tətbiq bloklanmasın.
- **Callbacklər**: Asinxron əməliyyatlardan gələn cavabları idarə etmək üçün istifadə olunur.
- **Hadisə yönümlü Arxitektura (Event-driven Architecture)**: Node.js şəbəkə əməliyyatları zamanı `data`, `end` və `error` kimi hadisələr yaradır və bu hadisələr hadisə dinləyiciləri (event listeners) vasitəsilə idarə oluna bilər.

----------------------------------------------------------------------

## Callback Funksiyaları Yaratmaq

### Əsas Konsepsiyalar

- **Asinxron Framework**: Node.js geniş şəkildə callback funksiyalarını istifadə edərək asinxron əməliyyatların nəticələrini idarə edir və beləliklə, bloklanmayan icra (execution) təmin edilir.

- **Callback Səhv İdarəetməsi (Error Handling in Callbacks)**: Callback funksiyasında birinci parametr adətən səhv obyektidir. Əgər səhv obyekti müəyyən olunubsa, bu bir səhv baş verdiyini göstərir; əks halda, əməliyyat uğurla başa çatmışdır.

### İş Axını Nümunəsi (Workflow Example)

1. **Səhv Yoxlaması (Error Handling)**:
   - Callback funksiyası əvvəlcə səhv parametrinin müəyyən olunub-olunmadığını yoxlayır.
   - Əgər bir səhv varsa, onu idarə edir və lazımi təmizləmələri aparır.
   - Əgər səhv yoxdursa, nəticəni işləyir.

2. **Hava Durumu Modulunda Callback Funksiyası**:
   - Əsas tətbiq hava durumu modulunun `current` funksiyasını yer parametri ilə çağırır.
   - Hava durumu modulu HTTP sorğusu çağırır və cavabı idarə etmək üçün anonim geri çağırış funksiyası təyin edir.

3. **HTTP Sorğusu üçün Callback Funksiyası**:
   - Callback funksiyası `data` (data parçaları alındıqda) və `end` (cavab tam olduqda) kimi hadisələri işləyir.

### Kod Nümunəsi


```javascript
const http = require('http');

const weather = {
    current: function(location, resultCallback) {
        const options = {
            hostname: 'api.weather.gov',
            path: `/stations/${location}/observations/latest`,
            method: 'GET',
        };

        const req = http.request(options, (res) => {
            let data = '';

            res.on('data', (chunk) => {
                data += chunk;
            });

            res.on('end', () => {
                const weatherData = JSON.parse(data);
                const temp_f = weatherData.properties.temperature.value;
                resultCallback(null, temp_f);
            });
        });

        req.on('error', (e) => {
            resultCallback(e, null);
        });

        req.end();
    }
};

// Əsas tətbiq
weather.current('KSFO', (err, temp_f) => {
    if (err) {
        console.error(`Hava durumunu aldıqda error: ${err.message}`);
    } else {
        console.log(`Cari hava dərəcəsi ${temp_f} Fahrenheit dərəcədir.`);
    }
});
```

### Callback Funksiyası Axını

1. **Tətbiq Çağırışı (Application Call)**:
   - Əsas tətbiq `weather.current()` funksiyasını bir yer və bir geri çağırış funksiyası ilə çağırır.

2. **Hava Durumu Modulu**:
   - `weather.current()` HTTP sorğusu edir.
   - Əgər sorğu uğurlu olarsa, data toplayır və callback funksiyasını `null` səhv və nəticə olaraq temperaturla çağırır.
   - Əgər sorğu uğursuz olarsa, callback funksiyasını error ilə çağırır.

3. **Nəticələri İdarəetmə**:
   - Əsas tətbiqdə callback funksiyası səhvləri yoxlayır.
   - Əgər bir səhv varsa, onu idarə edir; əks halda, temperaturu işləyir və göstərir.

### Xülasə

- **Asinxron İcra (Asynchronous Execution)**: Node.js asinxron əməliyyatları idarə etmək üçün callback-lardan istifadə edir və bloklanmayan kod icrasını təmin edir.
- **Səhv İdarəetməsi (Error Handling)**: Callback funksiyaları səhvləri yoxlayır və onları müvafiq şəkildə idarə edir.
- **Callback Zənciri (Callback Chain)**: Bir callback nəticələri digərinə ötürərək məlumat və icra axınını davam etdirə bilər.

----------------------------------------------------------------------------

## Node.js-də Anonim Callback Funksiyalarının İstifadəsi

### Əsas Konsepsiyalar

- **Callback-lar və Asinxron Sorğular**: Node.js-də tətbiqinizdən kənarda (məsələn, xarici API-ə) sorğular etmək yaygındır. Callback-ların necə işlədiyini anlamaq vacibdir, çünki onlar bu asinxron əməliyyatların nəticələrini əsas axını bloklamadan idarə edirlər.
  
- **Anonim vs. Adlı Callback-lar**: Callback-lar anonim və ya adlı ola bilər. Anonim callback-lar, sadəlik və oxunaqlılıq üçün tez-tez istifadə olunur, xüsusən də callback məntiqi başqa yerdə təkrar istifadə olunmadıqda.

### Nümunə Ssenari: Hava Durumu API Sorğusu

Bir veb sayt qurduğunuzu düşünün ki, cari temperaturu göstərir. Temperaturu əldə etmək üçün xarici hava durumu API-ə sorğu göndərməlisiniz. Əsas axını API cavabını gözləyərkən bloklasanız, bu istifadəçilərin saytla qarşılıqlı əlaqəsini maneə törədərdi. Bunun əvəzinə, cavabı asinxron şəkildə idarə etmək üçün callback-dan istifadə edirsiniz.

### Anonim Callback-ların Faydaları

- **Sadəlik və Oxunaqlılıq (Simplicity and Readability)**: Anonim funksiyalar daha sadə və oxunaqlıdır, xüsusən də qısa, birdəfəlik istifadə olunan callback-lar üçün.
- **Məntiqin Məhdudlaşdırılması (Scoped Logic)**: Geri çağırışCallback-in məntiqi funksiya çağırışının daxilində saxlanılır və bu, kodun izlənməsini asanlaşdırır.
- **Arrow Funksiyalar**: Arrow sintaksisdən (`=>`) istifadə edərək, kodu daha da qısa edə bilərsiniz.

### Nəticə

Callback-ların, xüsusən anonim olanların, istifadəsini anlamaq Node.js-də asinxron proqramlaşdırmanı mənimsəmək üçün vacibdir. Onlar tətbiqinizin asinxron əməliyyatları effektiv şəkildə idarə etməsinə imkan verir, istifadəçi təcrübəsini cavabdeh və performanslı saxlayır. Anonim callback-lardan istifadə edərək, callback məntiqi sadə və təkrar istifadə olunmadıqda kodu təmiz və idarə edilə bilən saxlayırsınız.

-----------------------------------------------------------------------------------

## Callbacklarla Bağlı Problemlər (Issues with Callbacks)

### Callbackları Anlamaq

Callback, başqa bir funksiyaya arqument olaraq ötürülən və nəticə əldə edildikdən sonra icra olunan funksiyadır. Callbacklər asinxron JavaScript üçün vacibdir, funksiyanın yalnız tələb olunan iş tamamlandıqdan sonra işləməsini təmin edir. 

```javascript
function message() {
    console.log("Bu mesaj 3 saniyədən sonra göstərilir");
}

setTimeout(message, 3000);
```

Bu nümunədə `message` `setTimeout` funksiyasına ötürülən callback funksiyasıdır. 3 saniyə gözlədikdən sonra, `setTimeout` `message` funksiyasını icra edir.

### Callbacklərin Ümumi İstifadə Halları

Callbacklər tez-tez aşağıdakı işlər üçün istifadə olunur:

- Məlumat bazasından dəyərlərə giriş
- Şəkillərin yüklənməsi
- Faylların oxunması

Bu işlər tez-tez xarici xidmətlər tərəfindən təmin olunan resursları əhatə edir və callbacklər bu resurslar mövcud olana qədər gözləyir.

### Callback Cəhənnəmi (Callback Hell)

Callbacklərdən ardıcıl tapşırıqları icra etmək üçün istifadə edərkən, funksiyalar bir-birinin içində iç-içə hala gələ bilər, bu da mürəkkəb və oxunması çətin koda səbəb olur. Bu "Callback Cəhənnəmi" və ya "Piramida Effekti" kimi tanınır. Məsələn, tort bişirmək asinxron tamamlanamayan ardıcıl addımları əhatə edir:

1. Tortun tərkiblərini alın.
2. Tərkibləri qarışdırın.
3. Tortu bişirin.
4. Tortu bəzəyin.
5. Tortu təqdim edin.

Kodda bu belə görünə bilər:

```javascript
purchaseIngredients(function(ingredients) {
    combineIngredients(ingredients, function(mixture) {
        bakeCake(mixture, function(cake) {
            decorateCake(cake, function(decoratedCake) {
                serveCake(decoratedCake);
            });
        });
    });
});
```

### İdarəetmənin İnversiyası (IoC - Inversion of Control)

İdarəetmənin inversiyası, nəzarətin kodunuzun xaricində olmasıdır. Callbacklərlə, nəzarət tez-tez üçüncü tərəf koduna verilir, bu da bir neçə problemi gətirə bilər:

- **Çoxlu Çağırışlar (Multiple Calls)**: Callback bir neçə dəfə çağırıla bilər (məsələn, bir istifadəçi düyməni bir neçə dəfə basdıqda).
- **Qaçırılmış Çağırışlar (Missed Calls)**: Callback ümumiyyətlə çağırılmaya bilər.
- **Vaxtlama Problemləri (Timing Issues)**: Callback çox erkən və ya çox gec çağırıla bilər.
- **Kontekst İtirmək (Context Loss)**: Callback kontekstini itirə bilər və ya səhv arqumentləri geri qaytara bilər.

### Nümunə: Çoxlu Klikləri İdarə Etmək

Bir üçüncü tərəf kodunda səhv olduğunu və callbackin bir neçə dəfə çağırıldığını düşünək:

```javascript
let isProcessing = false;

function processClick() {
    if (!isProcessing) {
        isProcessing = true;
        // Kartı ödə
        chargeCard(function(err, result) {
            if (err) {
                // Səhvi idarə et
            } else {
                // Nəticəni idarə et
            }
            isProcessing = false;
        });
    }
}

button.addEventListener('click', processClick);
```

Bu nümunədə `isProcessing` kartın yalnız bir dəfə ödənməsini təmin edir, düymə bir neçə dəfə basılsa belə. Ancaq, callback heç vaxt çağırılmadıqda əlavə məntiq tələb olunur, bu da kodu daha mürəkkəbləşdirir.

### Callback Cəhənnəmini Azaltmaq (Mitigating Callback Hell)

Callback cəhənnəmini və etibar problemlərini (trust issues) azaltmaq üçün bir neçə strategiya var:

1. **Şərhlər Yazmaq**: Kodun axışını izah etmək üçün şərhlər əlavə etmək.
2. **Funksiyaları Bölmək**: Böyük funksiyaları daha kiçik, idarə edilə bilən funksiyalara bölmək.
3. **Promises İstifadə Etmək**: Promiselər asinxron əməliyyatları idarə etmək üçün daha oxunaqlı bir yol təmin edir.
4. **Async/Await İstifadə Etmək**: Async/await sintaksisi asinxron kodu idarə etməyi daha da sadələşdirir.

### Nəticə

- Callbacklər asinxron JavaScript üçün vacibdir.
- "Callback cəhənnəmi" callback funksiyalarının iç-içə olmasına və kod oxunaqlılığını və saxlanmasını çətinləşdirir.
- İdarəetmənin inversiyası problemləri üçüncü tərəf koduna etibar edərkən yaranır.
- Bu problemləri azaltmaq üçün şərhlər yazmaq, funksiyaları bölmək və Promiselər və ya async/await istifadə etmək kimi strategiyalar mövcuddur.

------------------------------------------------------------------------------------

## Promislər

### Promise nədir?

Promise, asinxron əməliyyatın sonunda əldə olunacaq nəticəni (və ya uğursuzluğu) təmsil edən obyektdir. Promiselərin üç vəziyyəti var:

1. **Pending (Gözlənilir)**: Promise-in ilkin vəziyyəti.
2. **Resolved (Həll olunmuş)**: Asinxron əməliyyatın uğurla tamamlandığı vəziyyət.
3. **Rejected (Rədd edilmiş)**: Asinxron əməliyyatın uğursuz olduğu vəziyyət.

### Promise Yaratmaq

Promise-i `Promise` konstruktorundan (constructor) istifadə edərək yarada bilərsiniz. 

fayl oxumaq üçün promise istifadə olunan bir nümunə:

```javascript
const fs = require('fs');

function readFile(filename) {
    return new Promise((resolve, reject) => {
        fs.readFile(filename, 'utf8', (err, data) => {
            if (err) {
                reject(err);
            } else {
                resolve(data);
            }
        });
    });
}

// İstifadə nümunəsi:
readFile('example.txt')
    .then(data => console.log(data))
    .catch(err => console.error(err));
```

Bu nümunədə, `readFile` faylın məzmununu oxuyan bir promise qaytarır. Əgər fayl uğurla oxunursa, promise faylın məlumatı ilə həll olunur. Əgər səhv varsa, promise səhvlə rədd edilir.

### HTTP Sorğuları üçün Promislərdən İstifadə

HTTP sorğuları API-lərlə işləyərkən promislər üçün ümumi istifadə halıdır. Node.js-də `axios` paketi HTTP sorğularını promislərə bükən populyar bir kitabxanadır.

Burada `axios` istifadə olunan bir nümunə:

```javascript
const axios = require('axios');

// GET sorğusu etmək
axios.get('https://jsonplaceholder.typicode.com/todos/1')
    .then(response => {
        console.log('Həll olundu:', response.data);
    })
    .catch(error => {
        console.error('Rədd edildi:', error.message);
    });
```

Bu nümunədə, `axios.get` promise qaytarır. Promise HTTP sorğusu tamamlanana qədər gözlənilir vəziyyətdədir. Əgər sorğu uğurla tamamlanırsa, promise həll olunur və `.then` metodu cavab məlumatı ilə çağırılır. Əgər sorğu uğursuz olursa, promise rədd edilir və `.catch` metodu səhvlə çağırılır.

### Promislərin İstifadəsinin Faydaları

1. **Oxunaqlılığın Təkmilləşdirilməsi (Improved Readability)**: Promislər, dərin iç-içə callback-lərlə müqayisədə, daha oxunaqlı və saxlanması asan olan asinxron kod yazmağa imkan verir.
2. **Zəncirləmə (Chaining)**: Promislər zəncirlənə bilər, bu da ardıcıl asinxron əməliyyatları yerinə yetirməyə imkan verir.
3. **Səhvlərin İdarə Edilməsi (Error Handling)**: Promislər `.catch` istifadə edərək səhvləri təmiz bir şəkildə idarə etməyə imkan verir.

### Nümunə: Promislərin Zəncirlənməsi

```javascript
const fs = require('fs').promises;

function readFile(filename) {
    return fs.readFile(filename, 'utf8');
}

function writeFile(filename, data) {
    return fs.writeFile(filename, data);
}

// Promislərin zəncirlənməsi
readFile('example.txt')
    .then(data => {
        console.log('Fayl məzmunu:', data);
        return writeFile('example_copy.txt', data);
    })
    .then(() => {
        console.log('Fayl uğurla kopyalandı');
    })
    .catch(err => {
        console.error('Səhv:', err.message);
    });
```

Bu nümunədə, `readFile` və `writeFile` promislər qaytarır. Promislər faylı oxumaq və sonra məzmununu başqa bir fayla yazmaq üçün zəncirlənir. Əgər hər hansı əməliyyat uğursuz olursa, səhv `.catch` metodunda tutulur.

### Nəticə

- Promise, asinxron bir metod tərəfindən qaytarılan və əməliyyatın nəhayət tamamlanmasını və ya uğursuzluğunu təmsil edən obyektdir.
- Promise-in ilkin vəziyyəti gözləniləndir.
- Promislər həll oluna (uğurlu) və ya rədd edilə bilər.
- Node.js-də `axios` paketi HTTP sorğularını idarə etmək üçün geniş istifadə olunur və promislər qaytarır.
- Promislər kodun oxunaqlılığını artırır, asinxron əməliyyatların zəncirlənməsinə imkan verir və səhvlərin idarə edilməsini təmiz bir şəkildə təmin edir.

---------------------------------------------------------------------------

## JSON ilə Node.js-də işləmək

JSON (JavaScript Object Notation) insan üçün oxunması və yazılması asan, maşınlar üçün isə təhlil edilməsi və yaradılması asan olan yüngül məlumat mübadiləsi formatıdır. JSON veb inkişafında server və müştəri arasında məlumat mübadiləsi üçün geniş istifadə olunur.

### JSON Metodları

Node.js JSON məlumatları ilə işləmək üçün iki əsas metodu təmin edir:

1. **JSON.parse()**: JSON sətirini JavaScript obyektinə çevirir.
2. **JSON.stringify()**: JavaScript obyektini JSON sətirinə çevirir.

### JSON-un Təhlili

JSON sətirini JavaScript obyektinə təhlil etmək üçün `JSON.parse()` metodundan istifadə edə bilərsiniz. 
```javascript
const jsonString = '{"Company": "ABB", "Country": "AZE", "Headquarters": "28 May, Baku"}';
const jsonObject = JSON.parse(jsonString);

console.log(jsonObject);
// Çıxış: { Company: 'ABB', Country: 'AZE', Headquarters: '28 May, Baku' }
```

### JSON-un Sətirə Çevrilməsi

JavaScript obyektini JSON sətirinə çevirmək üçün `JSON.stringify()` metodundan istifadə edə bilərsiniz. Burada bir nümunə var:

```javascript
const jsonObject = {
    Company: "ABB",
    Country: "AZE",
    Headquarters: "28 May, Baku"
};
const jsonString = JSON.stringify(jsonObject);

console.log(jsonString);
// Çıxış: {"Company":"ABB","Country":"AZE","Headquarters":"28 May, Baku"}
```

### Nümunə: API-dən JSON Məlumatların Götürülməsi

JSON məlumatları qaytaran həqiqi API endpoint-dən istifadə nümunəsini görək. Hal-hazırda kosmosda olan astronavtlar haqqında məlumat verən bir API-ə HTTP sorğusu etmək üçün `axios` paketindən istifadə edəcəyik.

Əvvəlcə `axios` paketini quraşdırın:

```bash
npm install axios
```

Sonra API-dən JSON məlumatları götürmək və təhlil etmək üçün aşağıdakı kodu istifadə edin:

```javascript
const axios = require('axios');

const url = 'http://api.open-notify.org/astros.json';

axios.get(url)
    .then(response => {
        const data = response.data;
        console.log('Astronavtların sayı:', data.number);
        console.log('Astronavtlar:', data.people);
    })
    .catch(error => {
        console.error('Məlumatın götürülməsində səhv:', error);
    });
```

Bu nümunədə:

1. Biz `axios.get(url)` istifadə edərək API endpoint-nə HTTP GET sorğusu edirik.
2. Cavab JSON məlumatları ehtiva edir və `axios` tərəfindən avtomatik olaraq təhlil edilir.
3. Biz astronavtların sayını və astronavtların siyahısını konsola yazdırırıq.

### Nəticə

- JSON API məlumat mübadiləsi üçün standart formatdır və JavaScript-də təbii olaraq dəstəklənir.
- `JSON.parse()` JSON sətirini JavaScript obyektinə çevirir.
- `JSON.stringify()` JavaScript obyektini JSON sətirinə çevirir.
- Node.js-də `axios` kimi kitabxanalardan istifadə edərək API-lərdən JSON məlumatları götürə və onları asanlıqla idarə edə bilərsiniz.

----------------------------------------------------------------------------

## JSON və JavaScript ilə İşləmək

JSON (JavaScript Object Notation) məlumat seriyalizasiyası üçün standartdır və API-lərin istehlakı və yaradılması, layihə tələblərinin təyin edilməsi və yerləşdirmələrin idarə edilməsi üçün kritikdir.

### JSON haqqında Əsas Məqamlar

1. **JavaScript-də JSON**:
   - JSON JavaScript-ə daxil edilib və JavaScript obyektləri ilə işlədiyiniz zaman, əslində JSON ilə işləyirsiniz.
   - JSON obyektləri sətir formatına kodlamaq və onları yenidən JavaScript obyektlərinə dekod etmək üçün istifadə olunur.

2. **Ümumi İstifadə Halları**:
   - **API-lər**: JSON RESTful veb xidmətlərində ünsiyyət üçün ümumi formatdır.
   - **Konfiqurasiya**: JSON layihə tələblərini, xidmət olaraq platforma təkliflərini və Kubernetes iş yüklərini təyin etmək üçün istifadə olunur.
   - **Verilənlər Bazaları**: JSON MongoDB kimi JSON-yönümlü sənəd verilənlər bazalarında istifadə olunur.

3. **JSON ilə İşləmək üçün Metodlar**:
   - `JSON.parse()`: JSON sətirini JavaScript obyektinə çevirir.
   - `JSON.stringify()`: JavaScript obyektini JSON sətirinə çevirir.

### JSON-un Faydaları

- **Uyğunluq**: JSON çoxlu proqramlaşdırma dilləri, o cümlədən Python tərəfindən dəstəklənir və onu məlumat mübadiləsi üçün çox yönlü seçim edir.
- **İstifadə Asanlığı**: JSON-un sadə strukturu onu oxumağı və yazmağı asanlaşdırır.
- **Uyğunluq**: JSON müasir veb texnologiyaları tərəfindən istifadə olunur, bu da onu inkişaf etdiricilər üçün dəyərli bir bacarıq halına gətirir.

----------------------------------------------------------------------------------------

## Async/Await-a Giriş

JavaScript single-threaded skript dilidir, yəni proseslər eyni zamanda deyil, ardıcıl olaraq baş verir. Bu məhdudiyyət Promises vasitəsilə həll olundu. Promises sinxron proqramlaşdırma problemlərini həll etsə də, dərinləşmiş `then` çağırışları kodun strukturunu və oxunaqlığını mürəkkəbləşdirə bilər.

ES2017-də `async/await` təqdim olundu, bu, daha təmiz və oxunaqlı asinxron kod yazmaq üçün bir yol təqdim edir. Bir promise-ni gözləməklə, promise yerinə yetirildikdə nəticəni emal edə və ya promise rədd edildikdə hər hansı bir səhvlə başa çıxa bilərsiniz.

### Promises ilə Nümunə

Burada API sorğusunu idarə etmək üçün Promises istifadə olunan bir nümunə var:

```javascript
const axios = require('axios');
const connectToURL = (url) => {
  const req = axios.get(url);
  req.then(resp => {
      let listOfEntries = resp.data.entries;
      listOfEntries.forEach((entry) => {
        console.log(entry.Category);
      });
    })
  .catch(err => {
      console.log(err.toString());
  });
}
console.log("Before connect URL");
connectToURL('https://api.publicapis.org/entries');
console.log("After connect URL");
```

### Async/Await ilə Nümunə

Eyni nümunə daha yaxşı oxunaqlıq üçün `async/await` istifadə olunaraq yerinə yetirilə bilər:

```javascript
const axios = require('axios');
const connectToURL = async (url) => {
    try {
        const response = await axios.get(url);
        const listOfEntries = response.data.entries;
        listOfEntries.forEach((entry) => {
            console.log(entry.Category);
        });
    } catch (error) {
        console.error(error.toString());
    }
}
console.log("Before connect URL");
connectToURL('https://api.publicapis.org/entries');
console.log("After connect URL");
```

### Asinxron Fəaliyyətlərin Zəncirlənməsi

`Async/await` ardıcıl olaraq baş verməli olan bir neçə asinxron fəaliyyəti idarə edərkən özünü göstərir. Burada əvvəlcə girişlərin siyahısını aldığımız və sonra "A" ilə başlayan hər bir kateqoriya üçün təfərrüatları gətirdiyimiz bir nümunə var:

#### Promises istifadə edərək

```javascript
const axios = require('axios');
async function connectToURL(url) {
    try {
        const response = await axios.get(url);
        const listOfEntries = response.data.entries;
        let categories = new Set();
        
        // Unikal kateqoriyaları çıxar
        listOfEntries.forEach((entry) => {
            categories.add(entry.Category);
        });
        
        // "A" ilə başlayan hər bir kateqoriya üçün təfərrüatları sorğu et
        for (let category of categories) {
            if (category.startsWith("A")) {
                const resp = await axios.get(`https://api.publicapis.org/entries?Category=${category}`);
                console.log(`${category} - ${resp.data.count}`);
            }
        }
    } catch (error) {
        console.error(error.toString());
    }
}
connectToURL('https://api.publicapis.org/entries');
```

#### Async/Await istifadə edərək

```javascript
const axios = require('axios');

async function connectToURL(url) {
    try {
        const resp = await axios.get(url);
        let listOfEntries = resp.data.entries;
        let Categories = listOfEntries.map((entry) => entry.Category);
        Categories = [...new Set(Categories)];
        
        for (let Category of Categories) {
            if (Category.startsWith("A")) {
                try {
                    const resp = await axios.get(`https://api.publicapis.org/entries?Category=${Category}`);
                    console.log(`${Category} - ${resp.data.count}`);
                } catch (e) {
                    console.log(e);
                }
            }
        }
    } catch (err) {
        console.log(err.toString());
    }
}
connectToURL('https://api.publicapis.org/entries');
```

### Əsas Məqamlar

- Siz yalnız `async` funksiyasında `await` istifadə edə bilərsiniz, çünki `await` ipi (thread) promise yerinə yetirilənə qədər bloklayır.
- `Async/await` bir neçə ardıcıl olaraq yerinə yetirilməsi lazım olan asinxron əməliyyatlarla məşğul olarkən daha təmiz, oxunaqlı kod yazmağa kömək edir.

----------------------------------------------------------------------

## Node.js İmkanlarının Genişləndirilməsi

Node.js ilə HTTP server yaratmaq sadədir, lakin default Node.js frameworku məhdud imkanlara malikdir. Routing, daxil olan faylların parse edilməsi, autentifikasiya və verilənlər bazası bağlantıları kimi web server funksionallığının bir çox aspekti üçün Node.js-nin əsas imkanlarını genişləndirmək üçün xarici kitabxanalara və paketlərə ehtiyac var.

### Nümunə: Hava Məlumatlarının Parse Edilməsi

San Francisco Beynəlxalq Hava Limanı üçün hava məlumatlarına ehtiyac olduğunu düşünək. Bu məlumatları əldə etmək üçün xarici bir web serverə HTTP sorğusu göndərə və alınan məlumatları manual olaraq parse edə bilərik.

1. Hava məlumatları serverinə HTTP sorğusu göndərin.
2. XML cavabını string kimi parse edin.
3. XML cavabından temperatur məlumatlarını çıxarın.

### XML-in String Funksiyaları ilə Parse Edilməsi

JavaScript string funksiyalarından istifadə edən sadə yanaşma:

```javascript
const http = require('http');

const options = {
    hostname: 'example.com',
    port: 80,
    path: '/weather',
    method: 'GET'
};

const req = http.request(options, (res) => {
    let buffer = '';
    
    res.on('data', (chunk) => {
        buffer += chunk;
    });

    res.on('end', () => {
        const matches = buffer.match(/<temp_f>(.*?)<\/temp_f>/);
        if (matches) {
            const temperature = matches[1];
            console.log(`Temperature: ${temperature}`);
        } else {
            console.log('Temperature data not found');
        }
    });
});

req.on('error', (e) => {
    console.error(`Problem with request: ${e.message}`);
});

req.end();
```

### String Parsingin Məhdudiyyətləri

- **XML Strukturunu Nəzərə Almır (Ignores XML Structure)**: String uyğunlaşdırma XML məlumat strukturunu nəzərə almır, bu da onu daha az etibarlı edir.
- **Səhv Yaratma Riski (Error-Prone)**: Zədələnmiş XML məlumatları səhvlərə səbəb ola bilər.
- **Effektiv Deyil (Inefficient)**: Kompleks XML məlumatları üçün XML ağacının qurulması string uyğunlaşdırmadan daha effektivdir.
- **Baxım (Maintenance)**: XML strukturundakı dəyişikliklər regular ifadənin yenilənməsini tələb edir.

### XML-i xml2js ilə Parse Etmək

Daha güclü bir yanaşma `xml2js` paketindən istifadə edərək XML məlumatlarını JavaScript obyektinə parse etməkdir. Bu paket tamamilə JavaScript ilə yazılmışdır və xarici XML parsinq kitabxanalarına ehtiyac yoxdur.

#### Quraşdırma

`xml2js` paketindən istifadə etmək üçün onu npm vasitəsilə quraşdırmalısınız:

```sh
npm install xml2js
```

#### xml2js ilə Nümunə

Budur, XML məlumatlarını `xml2js` ilə necə parse etmək olar:

```javascript
const http = require('http');
const xml2js = require('xml2js');

const options = {
    hostname: 'example.com',
    port: 80,
    path: '/weather',
    method: 'GET'
};

const req = http.request(options, (res) => {
    let buffer = '';
    
    res.on('data', (chunk) => {
        buffer += chunk;
    });

    res.on('end', () => {
        xml2js.parseString(buffer, (err, result) => {
            if (err) {
                console.error('Failed to parse XML:', err);
                return;
            }
            const temperature = result.current_observation.temp_f[0];
            console.log(`Temperature: ${temperature}`);
        });
    });
});

req.on('error', (e) => {
    console.error(`Problem with request: ${e.message}`);
});

req.end();
```

### Əsas Müddəalar

- **Üçüncü Tərəf Paketləri**: İnkişaf etdiricilər Node.js funksionallığını `xml2js` kimi üçüncü tərəf paketlərindən istifadə edərək genişləndirirlər.
- **String Parsinqi**: XML məlumatlarının string parsinqi səhvlərə meyillidir və məlumat strukturunu nəzərə almır.
- **xml2js**: Bu paket XML stringlərini JavaScript obyektlərinə çevirir, XML məlumatları ilə işləməyi asanlaşdırır.
- **npm**: Node.js paketlərini idarə etmək üçün npm tətbiqindən istifadə edin və layihəniz üçün lazım olan asılılıqların olduğunu təmin edin.

------------------------------------------------------------------------

## Üçüncü Tərəf Node.js Uzantıları (Extensions) ilə İşləmək

Node.js-də üçüncü tərəf paketlərdən istifadə inkişafı əhəmiyyətli dərəcədə sadələşdirir, layihələrin tamamlanmasını sürətləndirir və funksionallığı artırır. Geniş istifadə olunan bəzi paketlər və onların üstünlükləri:

### Serverless Framework

Serverless Framework buludda serverless mikroxidmətləri geniş infrastruktur koduna ehtiyac olmadan yerləşdirməyə imkan verir. Serverless tətbiqlərinin yaradılmasını, konfiqurasiyasını və yerləşdirilməsini sadələşdirir, bulud inkişafını daha əlçatan və effektiv edir.

### Lodash

Lodash arraylər, obyektlər və digər kolleksiyalar üzərində işləmək üçün çoxsaylı funksiyalar təqdim edən utilitar kitabxanadır. Elementlərin tapılması, məlumatların sıralanması və kolleksiyaların manipulyasiyası kimi tapşırıqları sadələşdirir, inkişaf etdiricilərə vaxt və səylərini qənaət etdirir.

### Axios

Axios, RESTful API-lərlə qarşılıqlı əlaqəni asanlaşdıran promise-based HTTP müştərisidir. GET, POST, PUT, DELETE və digər HTTP metodlarını dəstəkləyir və promise və async/await üçün daxilində dəstəklə sorğuların və cavabların idarə edilməsini sadələşdirir.

### Express Middleware

Express tətbiqləri tez-tez müxtəlif funksionallıqlar üçün middleware-lərdən asılıdır, o cümlədən:

- **Autentifikasiya**: JSON Web Tokens (JWT) kimi autentifikasiya üçün middleware web tətbiqlərinin təhlükəsizliyini sadələşdirir.
- **Body Parsing**: `body-parser` kimi middleware-lər daxil olan sorğu body-lərini işləyir, form təqdimatları və JSON məlumatlarının idarə edilməsini asanlaşdırır.
- **Logging**: `morgan` kimi middleware-lər HTTP sorğularını qeydə alır, debugging və monitorinqdə kömək edir.

### Nümunə: Axios və Lodash istifadə edilməsi

Bir Node.js tətbiqində Axios və Lodash-dan necə istifadə edə bilərsiniz:

```javascript
const axios = require('axios');
const _ = require('lodash');

// Public API-dən məlumatların əldə edilməsi
async function fetchData(url) {
    try {
        const response = await axios.get(url);
        const data = response.data;

        // Lodash istifadə edərək məlumatları filtr edin və sıralayın
        const filteredData = _.filter(data.entries, entry => entry.Category === 'Animals');
        const sortedData = _.sortBy(filteredData, 'API');

        sortedData.forEach(entry => {
            console.log(`API: ${entry.API}, Description: ${entry.Description}`);
        });
    } catch (error) {
        console.error(`Error fetching data: ${error}`);
    }
}

fetchData('https://api.publicapis.org/entries');
```

### Verilənlər Bazaları ilə İşləmək

Verilənlər bazaları ilə işləyərkən, NPM paketləri həm relasional, həm də NoSQL bazaları ilə qarşılıqlı əlaqəni sadələşdirir. Populyar bəzi paketlərə aşağıdakılar daxildir:

- **Sequelize**: PostgreSQL, MySQL və SQLite kimi SQL bazaları üçün ORM.
- **Mongoose**: MongoDB üçün ODM, sxem dizaynını və məlumat doğrulamasını sadələşdirir.
- **Knex.js**: Müxtəlif relasional verilənlər bazaları üçün SQL sorğu qurucusu, ORM-lərdən daha çevik yanaşma təklif edir.

### Nümunə: Mongoose ilə MongoDB istifadə edilməsi

Mongoose istifadə edərək MongoDB bazası ilə necə qarşılıqlı əlaqə qurmaq olar:

```javascript
const mongoose = require('mongoose');

// Bazaya qoşulma
mongoose.connect('mongodb://localhost/mydatabase', { useNewUrlParser: true, useUnifiedTopology: true });

// Sxem təyin edilməsi
const userSchema = new mongoose.Schema({
    name: String,
    email: String,
    password: String
});

// Model yaradılması
const User = mongoose.model('User', userSchema);

// Yeni istifadəçinin yaradılması və saxlanması
const newUser = new User({ name: 'John Doe', email: 'john.doe@example.com', password: 'securepassword' });
newUser.save((err) => {
    if (err) {
        console.error('Error saving user:', err);
    } else {
        console.log('User saved successfully');
    }

    // Bazanın əlaqəsinin bağlanması
    mongoose.connection.close();
});
```

### Nəticə

Üçüncü tərəf Node.js paketlərindən istifadə inkişaf səmərəliliyini artırır və inkişaf etdiricilərə dayanıqlı, miqyaslana bilən tətbiqlər yaratmağa imkan verir. Serverless Framework, Lodash, Axios və verilənlər bazası konnektorları kimi paketlər ümumi tapşırıqları sadələşdirir və müasir web tətbiqləri yaratmaq üçün güclü alətlər təqdim edir.

------------------------------------------------------------------------------

## Web Frameworklərə Giriş

Node.js tez-tez web framework kimi qarışdırılır, lakin əslində server tərəfində JavaScript kodunu icra edən runtime mühitdir. Bu, brauzer xaricində JavaScript tətbiqlərini işlətmək üçün zəruri infrastrukturu təmin edir, developerlərə server tərəfində tətbiqlər yaratmağa imkan verir. Bunun əksinə olaraq, veb framework veb tətbiqlərini inkişaf etdirmək üçün strukturlaşdırılmış bir yol təqdim edən alətlər və kitabxanalar toplusudur. Veb frameworklər adətən yönləndirmə (routing), middleware, verilənlər bazası qarşılıqlı əlaqəsi (database interaction) və digər komponentlər üçün funksiyalar təqdim edir.

### Node.js və Web Frameworklər

Node.js ilə veb tətbiqlər yaratmaq üçün developlər tez-tez əlavə alətlər və abstraksiyalar təmin edən veb frameworklərdən istifadə edirlər. Bu frameworklər əvvəlcədən təyin edilmiş strukturlar və ümumi funksionallıqlar təklif edərək inkişafı sürətləndirir və developlərə tətbiqin unikal xüsusiyyətlərinə daha çox diqqət yetirməyə imkan verir.

### Arxitektura Nümunələri: MVC və REST API-ləri

Veb developmentdə 2 ümumi arxitektura nümunəsi istifadə olunur: Model-View-Controller (MVC) və Representational State Transfer (REST) API-ləri. Bu nümunələr tətbiqin tələblərindən asılı olaraq birlikdə və ya ayrı-ayrılıqda istifadə edilə bilər.

#### Model-View-Controller (MVC)

MVC tətbiqi üç komponentə ayıran bir arxitektura nümunəsidir:

1. **Model**: Tətbiqin məlumatlarını və iş məntiqini idarə edir. O, verilənlər bazası ilə qarşılıqlı əlaqədə olur və məlumat manipulyasiyasını həyata keçirir.
2. **View**: Məlumatı istifadəçiyə təqdim etməkdən məsuldur. Model tərəfindən təmin edilən məlumatlar əsasında istifadəçi interfeysini göstərir.
3. **Controller**: Model və view arasında vasitəçi rolunu oynayır. İstifadəçi girişlərini emal edir, modeli yeniləyir və göstəriləcək view-u müəyyən edir.

MVC arxitekturasını dəstəkləyən frameworklərə aşağıdakılar daxildir:

- **Express**: Veb tətbiqlər və API-lər yaratmaq üçün geniş istifadə olunan minimalist və çevik Node.js veb frameworkü. O, MVC nümunəsini dəstəkləyir və müxtəlif middleware seçimləri təklif edir.
- **Koa**: Express-in arxasında duran komanda tərəfindən hazırlanmışdır, Koa daha kiçik və daha ifadəli olmaq üçün nəzərdə tutulmuşdur. Asinxron əməliyyatları idarə etmək üçün async funksiyalarından istifadə edir və səhv idarə edilməsinə daha müasir yanaşma təklif edir.
- **NestJS**: Ölçeklenebilir (scalable) server tərəfli tətbiqlər yaratmaq üçün bir framework. TypeScript istifadə edir və Angular ilə yaxşı inteqrasiya olunur, onu full-stack tətbiqlər yaratmaq üçün uyğun edir. O, MVC nümunəsini izləyir və obyekt yönümlü və funksional reaktiv proqramlaşdırmanı dəstəkləyir.

#### REST API-ləri

REST (Representational State Transfer) şəbəkə tətbiqlərinin dizaynı üçün arxitektura üslubudur. REST API-ləri standart HTTP metodlarından istifadə edərək, GET, POST, PUT, PATCH və DELETE kimi müxtəlif veb xidmətləri arasında ünsiyyəti təmin edir. REST-in əsas prinsiplərinə daxildir:

- **Statelessness**: Müştəridən serverə hər sorğu sorğunu anlamaq və emal etmək üçün lazım olan bütün məlumatları ehtiva etməlidir. Server sorğular arasında müştəri vəziyyətini saxlamır.
- **Müştəri-Server Ayrımı (Client-Server Separation)**: Müştəri və server müstəqil fəaliyyət göstərir, müstəqil yeniləmələrə və miqyaslanmaya imkan verir.
- **Resurs Mərkəzli (Resource-Based)**: Resurslar (məlumat obyektləri kimi) URL-lərlə təmsil olunur və bu resurslar üzərində əməliyyatlar HTTP metodlarından istifadə etməklə həyata keçirilir.

### Populyar Node.js Veb Frameworkləri

1. **Express.js**: 
   - **Güclü Cəhətləri**: Geniş istifadə olunur, geniş middleware dəstəyi, sadəlik və çeviklik.
   - **İstifadə Halları**: Veb tətbiqlər, RESTful API-lər və mikroxidmətlər.

2. **Koa**:
   - **Güclü Cəhətləri**: Müasir dizayn, async/await istifadə edir, yüngüldür.
   - **İstifadə Halları**: Yüksək performanslı və mürəkkəb tətbiqlər.

3. **Socket.io**:
   - **Güclü Cəhətləri**: Müştərilər və serverlər arasında real-time iki istiqamətli ünsiyyət, WebSocket dəstəyi.
   - **İstifadə Halları**: Chat tətbiqləri, canlı yeniləmələr, çox oyunçu oyunları.

4. **Hapi.js**:
   - **Güclü Cəhətləri**: Təhlükəsizlik yönümlü, zəngin plugin sistemi, konfiqurasiya yönümlü.
   - **İstifadə Halları**: API serverləri, HTTP-proxy tətbiqləri.

5. **NestJS**:
   - **Güclü Cəhətləri**: TypeScript dəstəyi, modul arxitektura, Angular ilə inteqrasiya.
   - **İstifadə Halları**: Müəssisə tətbiqləri, genişlənə bilən server tərəfli tətbiqlər.

-------------------------------------------------------------------------------------

## Express Veb Tətbiq Framework-ü

Express, Node.js runtime mühitinin üzərində qurulmuş populyar veb tətbiq frameworküdür. Bu, HTTP sorğularını və cavablarını idarə etməyi, middleware-ləri idarə etməyi və aşağı səviyyəli detalları abstracting edərək web inkişaf sadələşdirir. Bu abstraksiya inkişaf etdiricilərə tətbiqlərini daha səmərəli təşkil etməyə və inkişaf prosesini sürətləndirməyə imkan verir.

### Express-in Əsas Xüsusiyyətləri

1. **Middleware İnteqrasiyası**: Express, loglama, autentifikasiya, məlumatların parsinqi və digər tapşırıqları yerinə yetirmək üçün istifadə oluna bilən middleware paketlərini inteqrasiya etmək üçün güclü mexanizmlər təmin edir. Middleware funksiyaları hər bir gələn sorğu üçün ardıcıl olaraq icra olunur, bu da inkişaf etdiricilərə tətbiq məntiqini modullaşdırmağa və idarə etməyə imkan verir.

2. **HTTP Sorğularının İdarə Edilməsi**: Express bütün HTTP metodlarını (GET, POST, PUT, DELETE və s.) dəstəkləyir və müxtəlif endpointlər üçün route handlerlərini müəyyən etmək üçün sadə sintaksis təmin edir. Bu, yaxşı müəyyən edilmiş routelar və sorğu idarəetməsi ilə API-lər və veb tətbiqlər yaratmağı asanlaşdırır.

3. **Şablon Mühərrikləri və SSR (Template Engines and SSR**: Express şablonları quraraq server tərəfində render (SSR) üçün istifadə edilə bilər. Bu, SEO dostu tətbiqlər yaratmaq və ilkin səhifənin yüklənmə vaxtlarını yaxşılaşdırmaq üçün xüsusilə faydalıdır.

4. **API İnkişafı**: Express adətən RESTful API-lər yaratmaq üçün istifadə olunur, burada o, məlumat qatı (data layer) ilə qarşılıqlı əlaqə üçün interfeys kimi fəaliyyət göstərir. Bu, JSON formatında məlumatı `res.json` metodu ilə müştəriyə geri göndərir, bu da API-lərin qurulmasını və istifadə edilməsini asanlaşdırır.

### Express Tətbiqinin Qurulması

Express tətbiqini qurmaq üçün bu beş addımı yerinə yetirin:

1. **Express-i Asılılıq Kimi Elan Edin (Declare Express as a Dependency)**: Layihə qovluğunuzda `package.json` faylı yaradın və buraya Express daxil olmaqla asılılıqları əlavə edin. Bu fayl modulun metadata-sını, məsələn, ad, versiya, təsvir, əsas skript və asılılıqları (dependencies) təsvir edir.

2. **npm Install Komandası İcra Edin**: `npm install` komandasından istifadə edərək elan edilmiş asılılıqları (dependencies), o cümlədən Express-i yükləyin və quraşdırın. Bu komanda `package.json` faylını oxuyur və zəruri modulları `node_modules` qovluğuna quraşdırır.

3. **Express Tətbiqini İdxal Edin və Yaradın**: Əsas JavaScript faylınızda (məsələn, `app.js`) Express modulunu idxal edin və Express tətbiqi nümunəsi yaradın. Bu nümunə routelar və middleware qurmaq üçün istifadə olunacaq.

4. **Route Handlers Yaradın**: Fərqli endpointlər üçün `app.get`, `app.post` və s. kimi metodlardan istifadə edərək route handlers təyin edin. Hər bir route handler müəyyən bir endpointə sorğu göndərildikdə yerinə yetiriləcək məntiqi müəyyən edir.

5. **HTTP Serveri Başladın**: Müəyyən edilmiş port nömrəsi ilə `app.listen` metodunu çağıraraq serveri başladın. Bu metod verilmiş portda əlaqələri bağlayır və dinləyir, serverin sorğuları qəbul etməyə başlamasına imkan verir.

### Nümunə Quraşdırma

```json
// package.json
{
  "name": "temperature",
  "version": "1.0.0",
  "description": "Amerika Birləşmiş Ştatlarında mövcud hava şəraitini əldə edin.",
  "main": "app.js",
  "dependencies": {
    "express": "^4.0.0"
  }
}
```

```javascript
// app.js
const express = require('express');
const app = express();

// Əsas ana səhifə üçün marşrut işləyicisi təyin edin
app.get('/', (req, res) => {
  res.send('Hello World!');
});

// Serveri 3000 portunda başladın
app.listen(3000, () => {
  console.log('Server is running on http://localhost:3000');
});
```

----------------------------------------------------------------------------

## İlk Express Veb Tətbiqiniz

### 1. Express-i Asılılıq Kimi Elan Edin (Declare Express as a Dependency
İlk olaraq, layihənizin `package.json` faylında Express-i asılılıq kimi elan etməlisiniz. Bu fayl layihənin asılılıqlarını və metadata-sını idarə edir. Əgər `package.json` faylınız yoxdursa, layihə qovluğunuzda aşağıdakı əmr vasitəsilə birini yarada bilərsiniz:

```sh
npm init -y
```

Daha sonra, Express-i asılılıq kimi əlavə edin:

```json
{
  "name": "my-express-app",
  "version": "1.0.0",
  "description": "Sadə bir Express veb tətbiqi",
  "main": "mynodeserver.js",
  "dependencies": {
    "express": "^4.0.0"
  }
}
```

### 2. Asılılıqları Quraşdırın (Install Dependencies)
`package.json` faylında qeyd olunan Express modulu və digər asılılıqları quraşdırmaq üçün aşağıdakı əmri icra edin:

```sh
npm install
```

Bu, `node_modules` adlı bir qovluq yaradacaq və Express və onun asılılıqlarını bu qovluğa quraşdıracaq.

### 3. Express Modulunu İdxal Edin və Express Tətbiqi Yaradın (Import the Express Module and Create an Express Application)
Layihə qovluğunuzda `mynodeserver.js` kimi yeni bir JavaScript faylı yaradın. Bu faylda Express-i idxal edin və Express tətbiqi nümunəsi yaradın:

```javascript
// mynodeserver.js
const express = require('express');
const app = express();
```

### 4. Route Handler Yaradın (Create a Route Handler)
Gələn HTTP sorğularını idarə etmək üçün route handlerləri qurun. Bu nümunədə, hava məlumatını əldə etmək üçün bir route yaradacağıq. İşləyici URL-dən yer kodunu çıxaracaq və bir mesajla cavab verəcək:

```javascript
app.get('/temperature/:location_code', (req, res) => {
  const location = req.params.location_code;
  // Hava məlumatını əldə etməyi simulyasiya edin
  res.send(`Verilmiş yer üçün mövcud hava şəraiti: ${location}`);
});
```

Bu marşrutda, `:location_code` bir route parametridir və `req.params.location_code` vasitəsilə əldə edilə bilər.

### 5. HTTP Serverini Başladın (Start an HTTP Server)
Nəhayət, serveri müəyyən bir portda dinləyərək başladın. Burada biz 8080 portundan istifadə edirik:

```javascript
app.listen(8080, () => {
  console.log('Server işə düşdü: http://localhost:8080');
});
```

### Tətbiqi İşlətmək (Running the Application)
Express tətbiqinizi başlatmaq üçün terminalda aşağıdakı əmri icra edin:

```sh
node mynodeserver.js
```

Veb brauzerinizi açın və `http://localhost:8080/temperature/some_location_code` ünvanına keçin (burada `some_location_code` əvəzinə hər hansı bir mətn yerləşdirin). Siz verilmiş yer kodu üçün hava şəraitini göstərən bir mesaj görməlisiniz.

----------------------------------------------------------------

## Express və Back-end JavaScript Frameworkləri ilə İşləmək

**Express framework-ü** Node.js üçün geniş yayılmış bir seçimdir və back-end veb tətbiqləri yaratmaq üçün effektivdir. Onun sintaksisi və yüksək səviyyəli API dizaynı, **REST API endpointləri** yaratmaq üçün xüsusi ilə faydalıdır. Bu frameworkün populyarlığı və güclü icması sayəsində müxtəlif middleware-lər inkişaf etdirilib və bunlar aşağıdakı kimi tapşırıqları sadələşdirir:

- **Body məzmununun parse edilməsi**: `body-parser` kimi middleware JSON və URL-encoded məlumatların asanlıqla parse edilməsinə imkan yaradır.
- **Autentifikasiya**: `passport` kimi middleware müxtəlif autentifikasiya strategiyalarını dəstəkləyir.
- **İstifadəçi sessiyalarının idarə edilməsi**: `express-session` kimi middleware sessiya məlumatlarını idarə edir.
- **Sorğu loglarının aparılması**: `morgan` HTTP sorğularını log etmək üçün geniş yayılmış middleware-dir.

### Express-in Əsas Üstünlükləri

1. **Populyarlıq və Ekosistem**: Express Node.js üçün ən populyar frameworklərdən biridir. Bu populyarlıq, çoxlu sayda paket və middleware ilə zəngin ekosistemin inkişafına kömək edib ki, bu da inkişafı sürətləndirir.

2. **Middleware çevikliyi**: Express-də middleware nümunəsi tərtibatçılara sorğu və cavabları incə detallarla idarə etməyə imkan verir. Bu çeviklik, sorğu-cavab dövriyyəsinin müxtəlif nöqtələrində xüsusi məntiq və ya transformasiyaların tətbiq olunmasını mümkün edir.

3. **Sürət və istifadənin asanlığı**: Express sadəliyi və sürəti ilə tanınır. Tərtibatçılar sürətlə server qurub inkişaf etməyə başlaya bilərlər ki, bu da həm prototipləşdirmə, həm də istehsal mühitləri üçün idealdır.

4. **Aşağı səviyyəli kodun abstraksiyası**: Express istifadə edərək, tərtibatçılar HTTP sorğu və cavablarının işlənməsi üçün təkrarlanan kod yazmaqdan qaça bilərlər. Bunun əvəzinə, onlar tətbiq məntiqi və iş qaydalarına diqqət yetirə bilərlər.

5. **Ən yaxşı təcrübələr**: Express sənaye standartlarına uyğun olaraq hazırlanmışdır və təhlükəsiz və saxlanıla bilən tətbiqlərin qurulması üçün etibarlı əsas təmin edir.

6. **Miqyaslama qabiliyyəti**: Express miqyaslana bilən tətbiqlərin inkişafını dəstəkləyir. Həm front, həm də back tərəfdə JavaScript istifadə etməklə, tərtibatçılar istər front, istərsə də back tərəfdə eyni kodu istifadə edə bilərlər.

7. **Performans**: Google V8 mühərrikindən istifadə edərək, Express minimal gecikmə ilə yüksək performans təmin edə bilər və səmərəli icra və cavab vaxtlarını dəstəkləyir.

8. **Keşləşdirmə**: Express, keşləşdirmə dəstəyi ilə veb tətbiqlərin performansını artırır və hər sorğu üçün kodu yenidən icra etməyə ehtiyacı azaldır.

9. **Üçüncü tərəf tətbiqləri ilə inteqrasiya**: Express müxtəlif üçüncü tərəf tətbiqləri və xidmətləri ilə asanlıqla inteqrasiya edir və bu da onun funksionallığını və çevikliyini artırır.

### Praktiki İstifadə və Öyrənmə Döngüsü

Bir çox tərtibatçı, xüsusən back-end developmentə yeni başlayanlar, Express-in sadəliyi və mövcud geniş sənədlər və resurslar sayəsində əlçatan olduğunu düşünür. Daha çox infrastruktura dair məsələləri həll edən idarə olunan bulud xidmətlərini üstün tutan bəzi tərtibatçılar olsa da, Express back-end memarlığı üzərində daha çox nəzarət etmək istəyənlər üçün əla seçim olaraq qalır.

Ümumiyyətlə, **Express.js** Node.js ekosistemində back-end inkişafı üçün güclü bir vasitədir. O, sadəliyi və çevikliyi birləşdirərək tərtibatçılara möhkəm və miqyaslana bilən tətbiqlər yaratmağa imkan verir. İstər API-lər, istərsə də veb tətbiqləri yaradırsınızsa, ya da digər xidmətlər ilə inteqrasiya edirsinizsə, Express bu işi səmərəli şəkildə yerinə yetirmək üçün möhkəm bir əsas təmin edir.

----------------------------------------------------------------------

## Middleware və Routerlərə Giriş

**Middleware** paylanmış sistemdə müxtəlif komponentlər arasında əlaqə və məlumat idarəçiliyini təmin edən vasitəçi proqram təminatıdır. Bu, tətbiqlər, məlumat bazaları və xidmətlər arasında qarşılıqlı əlaqələri asanlaşdırır, istifadəçilər üçün problemsiz bir təcrübə təmin edir.

### Express-də Middleware

**Express** Node.js üçün populyar bir veb tətbiq frameworküdür və onun güclü yönləndirmə imkanları və middleware dəstəyi ilə tanınır. Express-də middleware funksiyaları HTTP sorğularını idarə etmək, məlumatları işləmək və cavablar yaratmaq üçün nəzərdə tutulub. Tətbiqin memarlığının mühüm bir hissəsini təşkil edir, modulyar və təkrar istifadə edilə bilən kod yaratmağa imkan verir.

**Middleware-in Əsas Xüsusiyyətləri:**
1. **Məlumatın İdarə Edilməsi**: Middleware sorğu məlumatlarını işləyə bilər, məsələn, JSON bodylərini parse etmək və ya forma göndərişlərini idarə etmək.
2. **Sorğu/Cavab İdarəçiliyi**: Sorğu və cavabları idarə edə bilər, loglama, autentifikasiya, səhvlərin idarə edilməsi və daha çox şey daxildir.
3. **Yönləndirmə**: Middleware, URL və HTTP metodu əsasında sorğuları müvafiq idarəedici funksiyalara yönləndirə bilər.

### Mesajlaşma Frameworkləri və Məlumat Formatları

Express və oxşar frameworklərdə front və back tərəf arasında ünsiyyət əsasən **JSON** və **REST API-lər** vasitəsilə aparılır. Bu, məlumat mübadiləsi üçün standart format və metod təmin edir, fərqli sistemlərin qarşılıqlı əlaqəsini asanlaşdırır. Daha köhnə çərçivələr oxşar məqsədlər üçün XML və SOAP-dan istifadə edə bilər.

**Veb Xidmətləri və API-lər**: Veb xidmətlər, o cümlədən REST API-lər, internet üzərindən tətbiqlərin ünsiyyəti üçün standart bir yol təmin edir. Bu xidmətlər HTTP metodlarından (məsələn, GET, POST, PUT, DELETE) istifadə edərək resurslarla qarşılıqlı əlaqə yaradır.

### Veb Serverlər və Yönləndirmə

**Veb server** middleware rolunda çıxış edir, veb saytı məlumat bazasına bağlayır. Biznes məntiqini idarə edir, sorğuları işləyir və məlumatları uyğun şəkildə yönləndirir. **Yönləndirmə** gələn HTTP sorğularının, sorğunun URL-si və metoduna əsaslanaraq spesifik idarəedici funksiyalara xəritələnməsi prosesidir.

**Yönləndirmə Funksiyaları**:
- **Router.get()**: Məlumatları əldə etmək üçün HTTP GET sorğularını idarə edir.
- **Router.post()**: Yeni məlumatlar yaratmaq üçün HTTP POST sorğularını idarə edir.
- **Router.put()**: Mövcud məlumatları yeniləmək üçün HTTP PUT sorğularını idarə edir.
- **Router.delete()**: Məlumatları silmək üçün HTTP DELETE sorğularını idarə edir.

Bu router funksiyaları Express **Router sinfinin** bir hissəsidir və tətbiqdə routerları müəyyən etmək üçün istifadə olunur. Onlar iki əsas arqumenti qəbul edirlər:
1. **URL Yol**: Sorğunun yönləndirildiyi son nöqtə.
2. **Geri Çağırış Funksiyası**: Sorğunu idarə edən və cavab yaradan funksiya.

### Əlavə Middleware Funksiyaları

Yönləndirmədən əlavə, middleware müxtəlif digər vəzifələri yerinə yetirə bilər:
- **Təhlükəsizlik**: Təhlükəsiz ünsiyyəti təmin etmək üçün məlumatların şifrələnməsi və şifrəsinin açılması.
- **Yük İdarəçiliyi (Load Management)**: Yükü balanslaşdırmaq və performansı artırmaq üçün gələn trafikin bir neçə server arasında paylanması.
- **Məlumatın İdarə Edilməsi**: Məlumatların müştəriyə qaytarılmadan əvvəl filtrasiya, sıralama və ya dəyişdirilməsi.

Express-də middleware, tətbiqlərin qurulması üçün modulyar yanaşma təmin edir və tərtibatçılara təmiz, saxlanıla bilən və təkrar istifadə edilə bilən kod yaratmağa imkan verir. Bu, tətbiqin iş prosesinin müxtəlif aspektlərini, sadə məlumat parse edilməsindən mürəkkəb təhlükəsizlik tədbirlərinə qədər, idarə etmək üçün çeviklik təmin edir.

-------------------------------------------------------------------------

## Routing, Middleware və Şablonlar

### Express-də Routing

Routing, serverin müxtəlif routelara və HTTP metodlarına (GET, POST, PUT, DELETE) gələn sorğuları effektiv şəkildə idarə etməsinə imkan verən əsas aspektdir. Server hər bir sorğunu düzgün şəkildə emal etməli və ya lazım olduqda uyğun xəta mesajları qaytarmalıdır. Express-də routing iki səviyyədə idarə oluna bilər:

1. **Tətbiq səviyyəli routing**: Bu, tətbiq daxilində birbaşa hər bir route-u və HTTP metodunu idarə etməkdir. Bu yanaşma az sayda endpointlər üçün sadədir, lakin routeların sayı artdıqca daha çətin olur. Məsələn:
   ```javascript
   app.get('/user/about/:id', (req, res) => { /* GET sorğusunu idarə et */ });
   app.post('/user/about/:id', (req, res) => { /* POST sorğusunu idarə et */ });
   app.get('/item/about/:id', (req, res) => { /* GET sorğusunu idarə et */ });
   app.post('/item/about/:id', (req, res) => { /* POST sorğusunu idarə et */ });
   ```

2. **Router səviyyəli routing**: Bu metod `express.Router()` sinifindən istifadə edərək modulyar route idarəediciləri yaratmaqdır. Bu, xüsusən çoxsaylı routelara malik tətbiqlər üçün daha idarəediləbilən və təşkilatlanmışdır. Məsələn:
   ```javascript
   const itemRouter = express.Router();
   const userRouter = express.Router();

   itemRouter.get('/about', (req, res) => { /* item haqqında */ });
   itemRouter.get('/detail', (req, res) => { /* item detal */ });

   userRouter.get('/about', (req, res) => { /* user haqqında */ });
   userRouter.get('/detail', (req, res) => { /* user detal */ });

   app.use('/item', itemRouter);
   app.use('/user', userRouter);
   ```

### Middleware

Express-də middleware funksiyaları, tətbiqin sorğu-cavab dövründə sorğu (`req`), cavab (`res`) və növbəti funksiyaya (`next`) giriş əldə edən funksiyalardır. Middleware, sorğu və cavab obyektlərini dəyişdirə, sorğu-cavab dövrünü sonlandıra və növbəti middleware funksiyasını çağıra bilər.

**Middleware Növləri:**
1. **Tətbiq səviyyəli Middleware**: Bu middleware `app.use()` ilə tətbiq instansiyasına bağlanır. Autentifikasiya, loglama və sessiya idarəçiliyi kimi tapşırıqlar üçün istifadə edilə bilər. Məsələn:
   ```javascript
   app.use((req, res, next) => {
     if (req.headers['password'] === 'pwd123') {
       console.log('Giriş icazə verildi:', new Date());
       next();
     } else {
       res.status(403).send('Qadağan edildi');
     }
   });
   ```

2. **Router səviyyəli Middleware**: Bu middleware xüsusi bir router instansiyası üçün tətbiq edilir. Beləliklə, yalnız müəyyən routelar üçün middleware tətbiq edə bilərsiniz. Məsələn:
   ```javascript
   userRouter.use((req, res, next) => {
     console.log('User route girişi');
     next();
   });
   ```

3. **Xəta İdarəetmə Middleware**: Bu middleware tətbiqdəki səhvləri idarə edir. Bu, dörd arqument tələb edir: xəta, sorğu, cavab və növbəti. `next` istifadə edilməsə belə, metod imzasında daxil edilməlidir. Məsələn:
   ```javascript
   app.use((err, req, res, next) => {
     console.error(err.stack);
     res.status(500).send('Nəsə səhv oldu!');
   });
   ```

4. **Daxili Middleware**: Express, statik faylları xidmət etmək üçün `express.static`, JSON yüklərini parse etmək üçün `express.json` və daha çox şey kimi daxili middleware funksiyalarına malikdir.

5. **Üçüncü Tərəf Middleware**: Bunlar icma tərəfindən təqdim edilən middleware funksiyalarıdır və npm vasitəsilə quraşdırıla bilər. Məsələn, sorğu bodylərini parse etmək üçün `body-parser`.

### Şablonlar (Templating)

Şablonların render edilməsi, serverə məlumatlara əsaslanan HTML məzmununu dinamik şəkildə yaratmağa imkan verir. Express müxtəlif şablon mühərriklərindən istifadə edərək görünüşləri render edə bilər. Bu misalda, `express-react-views` paketi serverdə React komponentlərini render etmək üçün istifadə olunur:

```javascript
app.set('views', path.join(__dirname, 'myviews'));
app.set('view engine', 'jsx');
app.engine('jsx', require('express-react-views').createEngine());

app.get('/', (req, res) => {
  res.render('index', { name: 'User' });
});
```

Burada, `views` qovluğunda JSX faylları var ki, bu fayllar HTML strukturunu müəyyən edir və server göstərilən məlumatlara əsaslanaraq tam HTML səhifələrinə render edir.

Nəticə olaraq, **routing**, **middleware** və **şablonlar** Express tətbiqinin əsas komponentləridir, sorğuları idarə etməyə, məlumatları emal etməyə, cavabları idarə etməyə və dinamik məzmunu səmərəli şəkildə göstərməyə imkan verir.

------------------------------------------------------------------------

## Autentifikasiya və Avtorizasiya

Autentifikasiya və avtorizasiya veb tətbiqlərinin təhlükəsizliyində vacib rol oynayır. Autentifikasiya istifadəçinin şəxsiyyətini təsdiqləyir, avtorizasiya isə onların giriş səviyyələrini müəyyən edir. Aşağıda, Node.js-də geniş istifadə olunan üç autentifikasiya üsulu haqqında danışırıq: sessiyaya əsaslanan, tokenə əsaslanan və parolsuz autentifikasiya.

### Sessiyaya Əsaslanan Autentifikasiya

Sessiyaya əsaslanan autentifikasiya serverin istifadəçi sessiyalarını idarə etməsini nəzərdə tutur. Proses aşağıdakı kimidir:

1. **Giriş**: İstifadəçi öz giriş məlumatlarını təqdim edir.
2. **Təsdiq**: Server bu məlumatları verilənlər bazası ilə müqayisə edərək yoxlayır.
3. **Sessiyanın Yaradılması**: Uğurlu təsdiqdən sonra, server bir sessiya yaradır və unikal sessiya identifikatoru (ID) təyin edir; bu identifikator verilənlər bazasında saxlanılır.
4. **Sessiya ID-nin Saxlanması**: Sessiya ID istifadəçinin brauzerində cookie olaraq saxlanılır.
5. **Sessiyanın İdarə Edilməsi**: Sessiya ID növbəti sorğuları təsdiqləmək üçün istifadə olunur və istifadəçi çıxış etdikdə və ya sessiya müddəti bitdikdə silinir.

### Tokenə Əsaslanan Autentifikasiya

Tokenə əsaslanan autentifikasiya JSON Web Token (JWT) kimi tokenlərdən istifadə edərək istifadəçi sessiyalarını idarə edir. Bu üsul iki əsas mərhələdən ibarətdir:

#### Tokenə Əsaslanan Autentifikasiya Prosesi

1. **Autentifikasiya**:
   - İstifadəçi giriş məlumatlarını təqdim edir, server onları təsdiqləyir.
   - Uğurlu təsdiqdən sonra, server istifadəçi məlumatları və iddialarını ehtiva edən bir ID token (JWT) yaradır.
   - Müştəri bu tokeni adətən local storage və ya cookie-lərdə saxlayır.

2. **Avtorizasiya**:
   - Müştəri tokeni növbəti sorğularda avtorizasiya başlığında göndərir.
   - Server tokeni təsdiqləyir və tokenin iddialarına əsasən giriş hüququ verir.

![Tokenə Əsaslanan Autentifikasiya Axını](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0220EN-SkillsNetwork/Readings/images/tokenworkflow.png)

Tokenlər aşağıdakılardan ibarətdir:
- **Başlıq (Header)**: Tokenin növünü və hash algoritmini göstərir.
- **Yük (Payload)**: İstifadəçi iddialarını ehtiva edir (məsələn, icazələr, rollar).
- **İmza (Signature)**: Tokenin bütövlüyünü təmin edir.

### Parolsuz Autentifikasiya

Parolsuz autentifikasiya parollardan fərqli faktorlarla şəxsiyyəti təsdiq edir. Ümumi metodlar aşağıdakılardır:

1. **Biometrik məlumatlar**: Barmaq izləri, üz tanıma və s.
2. **Sehrli Linklər**: İstifadəçinin e-poçtuna göndərilən birdəfəlik istifadə olunan bağlantılar.
3. **Birdəfəlik Şifrələr (OTP)**: Mobil cihazlara göndərilən kodlar.

#### Parolsuz Autentifikasiya Necə İşləyir

- **Açıq/Şəxsi Açar Cütləri**: İstifadəçinin cihazı qeydiyyat zamanı bir açar cütü yaradır.
  - **Açıq Açar**: Tətbiq ilə saxlanılır.
  - **Şəxsi Açar**: İstifadəçinin cihazında təhlükəsiz şəkildə saxlanılır.

- **Autentifikasiya Prosesi**:
  - Server açıq açarla şifrələnmiş bir giriş çağırışı göndərir.
  - İstifadəçinin cihazı şəxsi açarla bu çağırışı deşifrə edir və istənilən əməliyyatı yerinə yetirir (məsələn, biometrik məlumatları təsdiqləmək).
  - Cavab serverə geri göndərilir.

![Parolsuz Autentifikasiya Axını](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0220EN-SkillsNetwork/Readings/images/reg-verify.png)

### Ümumi Nəticə

- **Autentifikasiya** istifadəçinin şəxsiyyətini təsdiqləyir.
- **Sessiyaya Əsaslanan Autentifikasiya** server tərəfindən idarə olunan sessiyalar və cookie-lərdən istifadə edərək istifadəçi vəziyyətini idarə edir.
- **Tokenə Əsaslanan Autentifikasiya** JWT-lərdən istifadə edərək istifadəçi məlumatlarını asanlıqla saxlayır.
- **Parolsuz Autentifikasiya** açıq/şəxsi açar cütləri və alternativ faktorlardan istifadə edərək təhlükəsizliyi və istifadəçi rahatlığını təmin edir.

----------------------------------------------------------------

## Node.js-də Autentifikasiya

Autentifikasiya istifadəçinin şəxsiyyətini təsdiqləmək prosesidir. Bu, istifadəçinin kim olduğunu müəyyən edir və onların şəxsiyyətinə əsasən hansı resurslara daxil ola biləcəklərini göstərir. Node.js-də əsasən üç əsas autentifikasiya yanaşması istifadə olunur: sessiyaya əsaslanan, tokenə əsaslanan və parolsuz autentifikasiya. Bu yanaşmalar arasında **tokenə əsaslanan autentifikasiya** genişlənəbilənlik, elastiklik və təhlükəsizlik xüsusiyyətlərinə görə ən populyardır.

### Tokenə Əsaslanan Autentifikasiya

Tokenə əsaslanan autentifikasiya prosesi belədir:

1. **İstifadəçi Girişi**:
   - İstifadəçi öz istifadəçi adı və şifrəsini serverə göndərir.
   - Server bu məlumatları, adətən, verilənlər bazasına qarşı yoxlayır.

2. **Tokenin Yaradılması**:
   - Uğurlu təsdiqdən sonra, server istifadəçi məlumatlarını və iddialarını ehtiva edən token, adətən JSON Web Token (JWT), yaradır.
   - Token müştəriyə göndərilir və müştəri tərəfindən local storage və ya cookie-də saxlanıla bilər.

3. **Tokenin İstifadəsi**:
   - Sonrakı sorğular üçün müştəri tokeni avtorizasiya başlığında göndərir.
   - Server tokeni yoxlayır və istifadəçini autentifikasiyadan keçirir, resurslara daxil olma hüququ verir.

#### Tokenə Əsaslanan Autentifikasiyanın Üstünlükləri

- **Genişlənəbilənlik (Scalability)**: Tokenlər müştəri tərəfdə saxlanılır, bu da server yüklənməsini azaldır və tətbiqlərin genişləndirilməsini asanlaşdırır.
- **Elastiklik**: Tokenlər müxtəlif serverlər və tətbiqlər arasında istifadə edilə bilər, vahid autentifikasiya prosesini təmin edir.
- **Təhlükəsizlik**: JWT-lər imzalanıb şifrələnə bilər, bu da manipulyasiyanın qarşısını alır və xüsusi şifrələmə açarı olmadan icazəsiz oxunmanın qarşısını alır.

### Express.js API Serverinin Qurulması

Tokenə əsaslanan autentifikasiya nümunəsini göstərmək üçün istifadəçi autentifikasiyasına əsasən işçi məlumatlarına çıxış təmin edən Express.js API serveri yaradacağıq. Tətbiq iki əsas API-yə malik olacaq:

1. **POST API**: Giriş etmək və token almaq üçün istifadə olunur.
2. **GET API**: Yalnız autentifikasiyadan keçmiş istifadəçilərə giriş icazəsi verilən işçi məlumatlarına çıxış üçün istifadə olunur.

#### Nümunə Kod

**Serverin Qurulması**:
```javascript
const express = require('express');
const jwt = require('jsonwebtoken');
const bodyParser = require('body-parser');

const app = express();
const JWT_SECRET = 'your_jwt_secret_key'; // Təhlükəsiz açarla əvəz edin

app.use(bodyParser.json());
```

**Giriş Endpointi** (`signin`):
```javascript
app.post('/signin', (req, res) => {
  const { username, password } = req.body;
  // Real tətbiqdə, istifadəçi verilənlər bazasından götürüləcək
  if (username === 'user' && password === 'password') {
    const token = jwt.sign({ username }, JWT_SECRET);
    res.json({ token });
  } else {
    res.status(401).json({ message: 'Yanlış istifadəçi adı və/və ya şifrə' });
  }
});
```

**Qorunan Endpoint** (`/employees`):
```javascript
app.get('/employees', (req, res) => {
  const token = req.headers['authorization'];
  if (!token) {
    return res.status(401).json({ message: 'Token yoxdur' });
  }

  try {
    const decoded = jwt.verify(token.split(' ')[1], JWT_SECRET);
    // İstifadəçi icazələrini yoxlayın və müvafiq cavab verin
    res.json({ message: 'İşçi Endpointinə giriş müvəffəqiyyətli oldu' });
  } catch (error) {
    res.status(401).json({ message: 'Bu resursa giriş üçün daxil olun' });
  }
});
```

**Server Dinləyicisi**:
```javascript
app.listen(5000, () => {
  console.log('API Server http://localhost:5000 ünvanında işləyir');
});
```

### Əsas Nöqtələr

- **Tokenə Əsaslanan Autentifikasiyanın Üstünlükləri**:
  - **Genişlənəbilənlik**: Tokenlər müştəri tərəfdə idarə olunur, bu da server yüklənməsini azaldır.
  - **Elastiklik**: Tokenlər müxtəlif serverlər və tətbiqlər arasında istifadə edilə bilər.
  - **Təhlükəsizlik**: JWT-lər imzalanıb şifrələnə bilər, təhlükəsiz ünsiyyəti təmin edir.

- **API Endpointləri**:
  - **POST API** (`/signin`): İstifadəçi autentifikasiyası və tokenin yaradılması üçün istifadə olunur.
  - **GET API** (`/employees`): Tokenlə təsdiqlənmiş istifadəçilər üçün qorunan resurslara çıxış imkanı verir.

-----------------------------------------------------------------

