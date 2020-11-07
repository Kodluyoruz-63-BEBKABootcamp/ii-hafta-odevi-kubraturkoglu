# ÖDEV 2
 ## 1. Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?
  
  > Açık kaynak, uygun bir lisans olmadan açık kaynak değildir. Başkalarına çalışmanızı değiştirebileceklerini ve yeniden kullanabileceklerini açıkça söylemediğiniz sürece, 
 başkalarına yalnızca kodunuzu göstermiş olursunuz.
 Repomuza lisans eklerken dikkat etmemiz gerekenler kodumuza hangi lisansın uygun olduğudur. Lisanslar yazdığın koda göre içerdiği içeriklere göre değişiklik gösterir.
  ### Reponuzda kullanabilecceğiniz bazı lisanslar:
  - MIT License
  - GNU Lesser General Public License v3.0
  - Mozilla Public License 2.0
  - GNU Affero General Public License v3.0
  - The Unlicense
  - Apache License 2.0
  - GNU General Public License v3.0
  
## 2. Merge - Squash-Rebase arasındaki farklar nelerdir?

*squash* Kaynak dalınıza dokunmaz  ve istediğiniz yerde tek bir işlem oluşturur.

 Rebase  aynı kaynak dalında  şunlarla devam etmenize olanak sağlar :
- yeni bir üs
- daha temiz bir tarih

## 3. Agile-Scrum-Kanban kavramlarını araştırınız.

### Agile 
***Agile*** proje yönetimi ve yazılım geliştirmeye yönelik yinelemeli bir yaklaşımdır.
Ekiplerin küçük artışlar üzerinde çalışmasına ve değişikliklere hızlı bir şekilde yanıt vermesine olanak sağlaması Agile'nın kullanımını arttıran bir etkendir.

### **Scrum**
Scrum, insanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde sunarken, karmaşık uyarlanabilir sorunları ele alabilecekleri bir çerçevedir
- Scrum basittir. 
- Bu, iç içe geçmiş zorunlu bileşenlerden oluşan büyük bir koleksiyonun tam tersidir.
- Scrum bir metodoloji değildir .
- Scrum, bilimsel  deneycilik yöntemini uygular .
  
 ### **Kanban**
 Kanban, bir süreç içinde hareket ederken işi yönetmek için görsel bir sistemdir. Kanban, hem süreci (iş akışını) hem de bu süreçten geçen fiili işi görselleştirir.
 Kanban'ın amacı, sürecinizdeki olası darboğazları belirlemek ve bunları düzeltmektir, böylece iş, optimum hızda veya iş hacminde maliyet etkin bir şekilde geçebilir.
  Kanban, size ne üreteceğinizi, ne zaman üreteceğinizi ve ne kadar üreteceğinizi söyleyen bir zamanlama sistemi olarak kullanıldığı yalın ve tam zamanında üretim (JIT) ile ilgili bir kavramdır . 
 Kanban Metodu, iş akışını yönetmek ve iyileştirmek için bir dizi ilke ve uygulamayı takip eder. Bir kuruluşun süreçlerinde kademeli iyileştirmeleri teşvik eden evrimsel,
 yıkıcı olmayan bir yöntemdir. Bu ilkeleri ve uygulamaları izlerseniz, Kanban'ı iş sürecinize olan faydaları en üst düzeye çıkarmak için başarıyla kullanabileceksiniz -
 akışı iyileştirin, döngü süresini azaltın, müşteriye değeri artırın, daha büyük öngörülebilirlikle - bunların hepsi herhangi bir işletme için çok önemlidir bugün.
 
## 4. Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız

GitHub flow, dağıtımların düzenli olarak yapıldığı ekipleri ve projeleri destekleyen, hafif, dal tabanlı bir iş akışıdır.
1: Git
Git, ücretsiz ve açık kaynak dağıtılmış bir sürüm kontrol sistemidir 
2. Pre commit
pre-commit, siz kodunuzu işlemeden önce hatalar için kontrol eder. ön işleme yapılandırılabilir.
3. Atlassian Stash
Güvenlik duvarının arkasındaki Git depolarını yönetmek için merkezi bir çözümdür. ...
4. Diff So Fancy
diff-so-fancy, git Contrib'un fark vurgulamasının iyi görünen çıktısına dayanır .
5. TortoiseGit
Windows kabuk uzantısı olarak uygulanan bir Git revizyon kontrol istemcisidir .

## 5. Gang of Four(GOF) 

## 6. Interface ve Abstract sınıflar arasındaki farklar nelerdir?
### Abstract sınıflar
Abstract sınıflar sınıf hiyerarşisinde genellikle base class (temel sınıf) tanımlamak için kullanılan ve soyutlama yeteneği kazandıran sınıflardır. Bir sınıfı abstract yapmak için abstract keywordünü kullanırız.

### Interface 
Interface, içerisinde sadece kendisinden türeyecek olan sınıfların içini dolduracağı metod tanımlarının bulunduğu ve soyutlama yapmamıza olanak sağlayan bir yapıdır.
Interface’leri tanımlarken interface keywordünü kullanırız. Tanımladığımız yapının interface olduğunu belirtmek için isminin önüne I harfini getirmek bir best-practice 
olacaktır. Böylece kodlama yaparken inherit aldığımız yapının bir class mı yoksa interface mi olduğunu kolaylıkla ayırt edebiliriz.


Interface | Abstract 
--- | --- 
Constructor içermez | Constructor içerebilir
Statik üyeler içermez | Static üyeler içerir


Abstract sınıflar en az bir tane abstract metod bulundurması bir best practice’tir.
