## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
    -  Git versiyon kontrolu icin kullanilan bir tur sistemdir. Bu sistem sayesinde projemizde yaptigimiz degisiklikleri gorebilir ve degisikliklerin kopyalari arasinda gecis yapilabiliriz.

2. Git ile GitHub arasında ne fark var?
    - Git yukarida da bahsettigim gibi versiyon kontrol sistemidir ve bunun sayesinde kaydettigimiz kisimlardan tekrar tekrar baslayabiliriz. GitHub ise yaptigimiz projelerin baskalariyla paylasimini kolaylastiran bir uygulamadir. Daha detayli aciklamam gerekirse ortak yapilan bir proje de gelistiricilerin yaptigi gelistirmeleri birbirleriyle paylasmak icin kullandiklari bir yerdir.

3. Neden bir branch oluşturuyoruz? 
    - Branch olusturmak ana projemizi karmasikliktan kurtarmaya yaramaktadir. Projemizde emin olmadigimiz degisiklikleri master branch e yapmadan once yeni bir yan branch olusturup onun ustunde deneyebiliriz ve calistigina emin olduktan sonra yapilan degisiklikleri master branch e cekebiliriz.

4. Pull Request'in amacı nedir?
    - Ortak yapilan projedeki yeni guncellemeleri kendi kod butunlugumuzle birlestirmek icin kullandigimiz bir ozelliktir.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
    - git checkout komutu ile ana brachten aktarmak istedigimiz branchi aktif hale getirdigimiz komuttur. Bu islemden sonra git merce komutu ile de main branch uzerinden yan branche entegre edilmesi saglanir.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    - git fetch kullanmak istedigimiz ozelligi kendi yerelimize getirmeden baska yerden kullanabilmemizi saglar. git pull ise baskasinin yaptigi dosyalarin kopyasinin bizim yerelimize getirmesidir. git merce komutu main branchde yapilan isleri yan branche entegre etmesidir.

7. Merge conflict nedir?
    - Merge conflict olayi ayni proje uzerinde calisan kisilerin ayni bolumde yaptigi degisikliklerin birbirini etkileme durumudur. Bu durum sonucunda merge edilemez ve degisiklikleri yapan kisilerin kendi arasinda konusup duzeltmesi gereken bir durumdur.

8. Merge conflict'i nasıl çözeriz?
    - Merge conflict olayi gerceklestigi zaman degisiklikleri yapan kisilerin birlikte karar verip yaptiklari degisiklikleri kontrol etmesi gerekmektedir.