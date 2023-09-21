# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, bir versiyon kontrol sistemidir. Yazılım geliştirme süreçlerini takip etmek, değişiklikleri yönetmek, işbirliği yapmak ve kod tabanını sürdürülebilir bir şekilde yönetmek için kullanılan bir araçtır. Git, dosyaların ve projenin farklı sürümlerini kaydetmek için kullanılır ve birden çok kullanıcı arasında işbirliği yapmayı kolaylaştırır.

2. Git ile GitHub arasında ne fark var?

Git ile GitHub Arasındaki Farklar:

Git, bir versiyon kontrol sistemidir ve projenin yerel sürüm kontrolünü sağlar. Git, komut satırı veya grafiksel bir kullanıcı arayüzü kullanılarak kullanılabilir.
GitHub, bir web tabanlı bir platformdur ve Git depolarını barındırır. GitHub, projelerin uzak sunucularda depolanmasını, işbirliği yapılmasını ve paylaşılmasını sağlar. Birçok kişi tarafından kullanılan bir kod barındırma ve işbirliği platformudur.

3. Neden bir branch oluşturuyoruz?
   Bir branch oluşturmanın nedenleri şunlardır:

Yeni bir özellik veya geliştirme üzerinde çalışırken ana projeyi bozmadan değişiklikler yapma.
Birden çok kişinin aynı projede çalışmasını sağlayarak işbirliği yapma.
Farklı sürümleri veya düzeltmeleri izleme ve yönetme.
İş akışını düzenli ve organize tutma.

4. Pull Request'in amacı nedir?
   Pull Request'in amacı, bir branch'teki değişikliklerin ana branch'e (genellikle "main" veya "master" olarak adlandırılır) birleştirilmesini önermek ve tartışmak için kullanılır. Pull Request açıldığında, diğer geliştiriciler değişiklikleri gözden geçirebilir, yorumlar yapabilir ve onaylayabilir veya reddedebilir. Bu, değişikliklerin güvenli bir şekilde ana projeye entegre edilmesini sağlar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout hedef-branch-adı

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch, uzak depodan (örneğin, GitHub) güncellemeleri indirir, ancak yerel çalışma kopyasını değiştirmez.
   git merge, farklı branch'ler arasındaki değişiklikleri birleştirir.
   git pull, aslında git fetch ve git merge işlemlerini bir arada yapar, yani uzak depodan güncellemeleri çeker ve otomatik olarak mevcut branch ile birleştirir.

7. Merge conflict nedir?

Merge Conflict, farklı branch'lerde aynı dosyanın aynı satırlarında yapılan çakışan değişiklikler sonucunda ortaya çıkar. Bu, Git'in hangi değişikliklerin birleştirileceğini otomatik olarak belirleyemediği durumdur.

8. Merge conflict'i nasıl çözeriz?

Merge conflict'i çözmek için şunları yapabilirsiniz:

Değişikliklerin çakıştığı dosyaları elle düzenleyin, çatışan kısımları belirleyin ve istediğiniz değişiklikleri yapın.
Dosyaları düzenledikten sonra git add komutuyla çözülen dosyaları işaretleyin.
Ardından git commit ile çözümü kaydedin.
Son olarak, git merge veya Pull Request'i tamamlamak için kullanabileceğiniz diğer birleştirme komutlarını kullanarak birleştirmeyi tamamlayın.
