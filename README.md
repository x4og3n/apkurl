
asanlıqla APK faylından APK sənədindən URL və IP son nöqtələrini çıxarır .TXT çıxışına. Bu, bir tətbiq ilə əlaqəli son nöqtələri tez müəyyənləşdirmək üçün qırmızı komanda, nüfuz testləri və inkişaf etdiricilər tərəfindən məlumat toplamaq üçün uygundur.

** Qeyd: Tool Smali'yi sökür və URL və IPSi müəyyənləşdirmək üçün Java parçalanmasını həyata keçirir.

* [Diggy] tərəfindən ilhamlanan (https://github.com/s0md3v/diggy), yenidən yazılır və IP dəstəyi, daha güclü regex, filtrləmə və jadx parçalanması ilə yenidən baxılır. *

## istifadə
`` ``
./apkurl.sh /path/to/apk/file.apk
`` `'

Ayrıca "/ install.sh`" tərəfindən asanlıqla asanlıqla daxil ola bilərsiniz.

Varsayılan olaraq "Son nöqtələr" qovluğunda 2 çıxış faylı var:
- \ <Akskname \> _ Endpoints.txt - ** URL yolları olan son nöqtələri ehtiva edir, dublikatlar **
- \ <Akskname \> _ Uniqurls.txt - ** Unikal Endpoints ** ehtiva edir

Varsayılan olaraq, proqram son nöqtələrin aşkar edildiyi APK fayl yolunu daxil etmir.
Giriş etmək üçün aşağıdakı kimi emri daxil edin:

`` ``
apkurl /path/to/apk/file.apk giriş
`` `'

## asılılıqlar
Bu vasitələrin asan quraşdırılması üçün `apt` istifadə edin:
- apktool
- jadx

Bu vasitə yalnız sınaq məqsədləri üçündür. Sahib olmamaq və ya sınamaq üçün icazə verdiyiniz hər hansı bir sistemdə həssaslığı istismar etmək üçün istifadə etməyin. 
