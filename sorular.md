# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. **Git nedir?**
    Versiyon kontrol sistemidir. Projede hata ya da daha kararlı sürüm için geriye dönmek gerektiğinde faydalıdır. Ayrıca projenin birden fazla geliştiricisi olduğunda karışıklığı engeller.
2. **Git ile GitHub arasında ne fark var?**
    Git projenin yerelde versiyon kontrol sistemi iken Github uzak bilgisayarda tutulan ve internete bağlı her yerden erişim sağlayan sistemdir. Github, git'den daha esnek yapısı ve kolay arayüz kullanımı ile projenin işleyişini hızlandırır. Ayrıca Github fork gibi kendine ait işlevsel kavramları vardır.
3. **Neden bir branch oluşturuyoruz?**
    **Bir projenin üzerinde farklı bir branch ile değişiklikler yapılabilir. Bu ana branch etkilenmeden olduğu için asıl projede kayıp olmaz. Yeni branch üzerinden yapılan değişiklikler onaylandığında ana branch ile merge edilerek birleştirilir.
4. **Pull Request'in amacı nedir?**
    Proje kodlarında geliştirme yaptıktan sonra proje sahibine bu değişikliklerin iletilmesini sağlar. Proje sahibi eğer onaylarsa kodlar merge edilebilir.
5. **Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?**
   main/master branch üzerindeyken;
   `git checkout -b 'mehmetali-degirmenci'`
   kodu ile geçiş yaparım. Eğer bu isimde branch yoksa new branch olarak kendisi oluşturacaktır.
   

6. **`git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.**
   - `git fetch` uzaktan değişiklikleri indirir ancak yerel branch üzerinde hemen entegre etmez. Entegre için manual kontrol ister.
   - `git merge` farklı branch üzerindeki değişiklikleri birleştirir.
   - `git pull` uzaktan değişiklikleri çeker ve yerel branch üzerinde hızlıca entegre eder. Merge conflict oluşturabileceğinden çakışmaların yönetilmesi gerekebilir. 

7. **Merge conflict nedir?**
   Genellikle farklı dallar üzerinde çalışılan projelerde merge işlemi yapıldığında ortaya çıkan bir çakışmadır. Aynı kod bölümünde farklı değişiklikler yapıldığında, bir dosyanın bir branch üzerinde silindiği ama diğer branch üzerinde değişikliklerin yapıldığı durumda ya da bir branch üzerinde dosyanın ismi değiştirilirken diğerinde içeriğinin değiştirilmesi gibi durumlarda çakışma oluşmasına denir. 

8. **Merge conflict'i nasıl çözeriz?**
   Conflict oluştuğunda manual müdahale gerekir. Git bu çakışmaların olduğu bölümleri işaretler ve geliştirici ekibin bunu çözümlemesini ister. İki farklı değişiklik arasında hangisinin kullanılacağı tespit edilir ve onaylanır. 
   
