

PROJECT TIMELINE

**İÇİNDEKİLER**

**1. Projenin Tanımı ........................................................................2**

**2. Kullanılan Teknolojiler...............................................................2**

**3. Personel Calendar......................................................................2**

3.1. Haftalık Takvim**........................................................................3**

3.2. Günlük Takvim**........................................................................3**

3.3. Ajanda **...................................................................................4**

3.4. Kayıt Ekleme**...........................................................................4**

3.5. Kayıt Güncelleme veya Silme**...................................................5**

**4. Atlas-Pegasus Project........................................................................6**

4.1. İsim Soyisme Göre Filtreleme**......................................................6**

4.2. Kayıt Ekleme **........................................................................7**

4.3. Kayıt Güncelleme**........................................................................8**

4.4. Popup Ekranı İle Süreçleri Görüntüleme **......................................8**

**5. Project Details........................................................................9**

5.1. Kayıt Ekleme**........................................................................10**

5.2. Kayıt Silme **........................................................................10**

5.3. Kayıt Güncelleme**........................................................................11**

5.4. Proje Filtreleme**........................................................................11**

**6. Employees ....................................................................................12**

6.1. Kayıt Ekleme**........................................................................13**

6.2. Kayıt Silme**........................................................................13**

6.3. Kayıt Güncelleme**........................................................................14**





**1. Projenin Tanımı**

Personelin hangi zamanda hangi iş üzerinde çalıştığını ve mevcut projelerin süreçlerinin tutulduğunu

gösteren bir web uygulamasıdır.

**2. Kullanılan Teknolojiler**

Bu proje Asp .net MVC ile kodlanmış olup veritabanı olarak MS SQL kullanılmıştır.

NOT: Önyüz değişikliği için bootstrap 3.0. versiyonu dışında bir sürüm kullanmayınız.

**3. Personel Calendar (Kişisel Takvim)**

Personel calendar sekmesi ilk açıldığında Resim 1.deki takvim gösterilmektedir. Takvimde personel

bazlı kayıtlar yer almaktadır.

•

•

Tavkim üzerinde boş bir alana tıklayarak kayıt ekleme yapabiliriz.

Takvim üzerinde kayda tıklandığında (Personel ismine) personele ait proje ismi ,başlangıç

tarihi , bitiş tarihi, edit ve remove alanları görünmektedir. Edit ve remove butonları ile

düzenleme veya silme işlemleri yapılmaktadır.

•

Haftalık gösterim, günlük gösterim ve ajanda sayfalarından da ekleme silme veya güncelleme

işlemi yapılabilmektedir.

Resim 1. Anasayfa





**3.1.Kişisel Takvim (Haftalık)**

Week butonuna basıldığında Resim 1.1.deki takvim gösterilmektedir. Aylık takvimde yapılan tüm

işlemler haftalık takvimde de yapılmaktadır.

Resim 1.1. Haftalık

**3.2.Kişisel Takvim (Günlük)**

Day butonuna basıldığında Resim 1.2.deki takvim gösterilmektedir. Aylık takvimde yapılan tüm

işlemler günlük takvimde de yapılmaktadır.

Resim 1.2. Günlük





**3.3.Kişisel Takvim (Ajanda)**

**3.4.**Agenda butonuna basıldığında Resim 1.3.deki takvim gösterilmektedir. Aylık takvimde

yapılan tüm işlemler agenda üzerinde de yapılmaktadır.

Resim 1.3. Ajanda

**3.5.Kişisel Takvim- Kayıt Ekleme**

Takvim üzerinde boş bir alana tıklandığında karşımıza gelen pencereden seçimleri yaparak save

butonu ile kayıt oluşturulmaktadır.

•

•

•

•

•

Employee alanı seçilmesi zorunlu alandır. Seçilmez ise kayıt ekleme yapılmamaktadır.

Project name alanı seçilmez ise null gösterilmektedir.

Project color seçilmez ise default “green” rengini atamaktadır.

Is Full Day event alanı seçilir ise End alanı kapatılıp, Start alanındaki tarih ile kayıt eklenir.

Close butonu ile popup ekranı kapanmaktadır.

Resim 1.4. Takvime Kayıt Ekleme





**3.6.Kişisel Takvim - Kayıt Silme ve Güncelleme**

Takvim üzerinde oluşturduğumuz kayıt üzerine(Personel ismine) tıkladığımızda edit veya remove

butonları ile güncelleme ve silme işlemleri yapılmaktadır.

•

•

Edit butonuna tıklandığında , bilgileri alarak bizi Kayıt ekleme sayfasına yönlendiriyor.

Remove butonuna tıklandığında, “Are you sure?” sorusunu sorarak tamam veya iptal

cevabını verdiğimzde işlemimiz gerçekleştirilebilmektedir.

•

Close butonu ile popup ekranı kapanmaktadır.

Resim 1.5. Tavkim Güncelleme veya Silme





**4. Atlas-Pegasus Project**

•

Atlas Project sayfasında atlasa ait, pegasus project sayfasında pegasusa ait projeler

listelenmektedir.

•

•

PROJECT\_ST alanında proje tamamlandı veya henüz başlamadı ise 0, proje aktif ise 1

yazılmaktadır. PROJECT\_ST 0 olan projeler All Project sayfasında görüntülenmektedir.

Projeye farklı renk ataması yaparken renk kodu veya ingilizce rengin ismi yazılmalıdır. Örneğin

kırmızı için red veya #ff2400(renk kodu) olacak şekilde eklenmelidir.

•

•

•

•

•

•

Yanlış renk ismi girildiğinde otomatik olarak navy blue değerini alacaktır.

Create new butonu ile yeni kayıt , edit butonu ile güncelleme yapılabilir.

Show butonu projeye ait analiz, geliştirme tasarım... sürecine ait bilgileri göstermektedir.

Search butonu ile yanındaki textbox’a girilen veriyle kişi ismine göre filtreleme yapılmaktadır.

Show all butonuna tıklandığında tekrarda tüm projeler görüntülenmektedir.

Atlas veya pegasus projelerinden herhangi bir kayıt silmeden önce project details sayfasından

ilgili projeye ait analiz tasarım geliştirme... gibi alanlar silinmelidir.

Resim 2. Atlas Project

**4.1.İsim Soyisme Göre Filtreleme**

•

Search butonunun yanındaki textbox’a aramak istediğimiz kişinin ismini yazarak filtreleme

yapılmaktadır.

•

Show all butonuna tıklandığında tüm kayıtlar görünmektedir.

Resim 2.1. Filtreleme





**4.2.Atlas-Pegasus Create**

Yeni Proje ekleme yaparken ilgili değerler için bazı koşullar vardır.

•

•

•

•

•

•

•

TEAM\_DEVOPS alanı maksimum 700 karakter olmalıdır.

PROJECT\_NUMBER alanı maksimum 30 karakter olmalıdır.

PROJECT\_NAME alanı maksimum 100 karakter olmalıdır.

PROJECT\_ST alanı 0 veya 1 girilmelidir.

MILESTONES alanı maksimum 30 karakter olmalıdır.

COLOR alanı maksimum 30 karakter olmaktadır.

COLOR değeri white veya içinde white geçen değer OLMAMALIDIR. Örneğin AntiqueWhite,

FloralWhite...

Bu koşullar Resim 2.2.’de gösterilmiştir.

Resim 2.2. Atlas-Pegasus Project Kayıt Ekleme





**4.3. Atlas-Pegasus Edit**

Proje güncelleme işlemi yaparken bazı koşullar gereklidir.

•

•

•

•

•

•

•

TEAM\_DEVOPS alanı maksimum 700 karakter olmalıdır.

PROJECT\_NUMBER alanı 0-100.000.000 arasında olmalıdır.

PROJECT\_NAME alanı maksimum 100 karakter olmalıdır.

PROJECT\_ST alanı 0 veya 1 girilmelidir.

MILESTONES alanı maksimum 30 karakter olmalıdır.

COLOR alanı maksimum 30 karakter olmaktadır.

COLOR değeri white veya içinde white geçen değer OLMAMALIDIR. Örneğin AntiqueWhite,

FloralWhite...

Resim 2.3. Atlas-Pegasus Project Kayıt Güncelleme

**4.4.Atlas-Pegasus Show**

Show butonuna tıklandığında Project details sayfasından eklediğimiz , ilgili projeye ait analiz, tasarım ,

geliştirme... süreçleri görünmektedir.

Resim 2.3. Atlas-Pegasus Project Popup Ekranı





**5. Project Details**

Projelere ait analiz tasarım geliştirme... kayıtları bulunmaktadır.

•

•

Buradaki Kayıtlar projelerin popup ekranında gösterilmektedir.

Her proje kendi rengi ile renklendirilmektedir.

Resim 3. Project Details





**5.1.Project Details Kayıt Ekleme**

Proje detay ekleme işlemi yaparken ilgili değerler için bazı koşullar vardır.

•

•

•

•

•

•

MILESTONES\_TYPE alanı maksimum 30 karakter olmalıdır.

S\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

E\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

PER alanı maksimum 4 karakter girilmelidir.

LAST\_ST alanı 0 yada 1 girilmelidir.

Bu koşullar Resim 3.1.’de gösterilmiştir.

Resim 3.1. Project Details Kayıt Ekleme

**5.2.Project Details Kayıt Silme**

Project Details sayfasından istediğimiz sürecin delete butonuna tıklandığında karşımıza gelen

ekrandan(Resim 3.2.) Delete butonuna basarak silme işlemi yapılmaktadır.

Resim 3.2. Project Details Kayıt Silme





**5.3.Project Details Kayıt Güncelleme**

Proje Detay güncelleme işlemi yaparken ilgili değerler için bazı koşullar vardır.

•

•

•

•

•

•

MILESTONES\_TYPE alanı maksimum 30 karakter olmalıdır.

S\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

E\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

PER alanı maksimum 4 karakter girilmelidir.

LAST\_ST alanı 0 yada 1 girilmelidir.

Bu koşullar Resim 3.3.’de gösterilmiştir.

Resim 3.3. Project Details Güncelleme

**5.4.Project İsmine Göre Filtreleme**

•

Search butonunun yanındaki textbox’a aramak projenin ismini yazarak filtreleme

yapılmaktadır.

•

Show all butonuna tıklandığında tüm kayıtlar görünmektedir.

•

Resim 3.4. Filtreleme





**6. Employees**

Employees sekmesine tıklandığında Resim 4. Açılmaktadır. Resim 4.’te bulunan kişi isimleri, kişisel

takvimde bulunan dropdownlist içinde görüntülenmektedir.

•

Create new butonu ile yeni kayıt ,edit butonu ile düzenleme ve delete butonu ile silme

işlemleri yapılmaktadır.

Resim 4. Employees Index





**6.1.Employees Kayıt Ekleme**

Kayıt ekleme işlemi yaparken ilgili değerler için bazı koşullar vardır.

•

•

•

•

•

Tüm alanlar boş bırakılabilir.

Eğer doldurulacaksa NAME\_SURNAME alanı maksimum 30 karakter olmalıdır.

Eğer doldurulacaksa statu alanı 0 yada 1 girilmelidir.

Eğer doldurulacaka C\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

Eğer doldurulacaksa TP alanı maksimum 30 karakter olmalıdır.

Bu koşullar resim 4.1.’de gösterilmiştir.

Resim 4.1. Kişi Ekleme

**6.2.Employees Kayıt Silme**

Employees sayfasından istediğimiz kişinin delete butonuna tıklandığında karşımıza gelen

ekrandan(Resim 4.2.) Delete butonuna basarak silme işlemi yapılmaktadır.

Resim 4.2. Kişi Silme





**6.3.Employees Kayıt Güncelleme**

Kayıt güncelleme işlemi yaparken ilgili değerler için bazı koşullar vardır.

•

•

•

•

•

Tüm alanlar boş bırakılabilir.

Eğer doldurulacaksa NAME\_SURNAME alanı maksimum 30 karakter olmalıdır.

Eğer doldurulacaksa statu alanı 0 yada 1 girilmelidir.

Eğer doldurulacaka C\_DATE alanı yyyy-mm-dd veya yyyy.mm.dd şeklinde girilmelidir.

Eğer doldurulacaksa TP alanı maksimum 30 karakter olmalıdır.

Bu koşullar resim 4.3.’de gösterilmiştir.

Resim 4.3. Kişi Güncelleme

