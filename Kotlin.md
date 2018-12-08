# Kotlin

## Nedir?

Kotlin; 2011 yılında duyurulan, 2012 yılında ise Apache 2 lisansı altında açık kaynak kodlu olarak kullanıma sunulmuş olan programlama dilidir. Rusya merkezli bir şirket olan Jetbrains tarafından geliştirilmiş olup ismini Kotlin Adası'ndan almıştır.
Kotlin'in ortaya çıkışında Java programlama dilinden daha iyi bir programlama dili oluşturma fikri etkili olmuştur.
Bu sebepten ötürü derleme süresi gibi performans etkenlerinden taviz vermeden Java'ya göre sade ve özgün bir sözdizimi ile JVM (Java Virtual Machine - Java sanal makinesi) üzerinde -Java ile tam uyumlu- çalışabilen statik bir programlama dili geliştirilmiştir.
(Statik programlama dillerinde değişken tipleri program yazılırken belirtilir. `int x = 10;` [Java] Dinamik dillerde ise değişken tipi çalışma esnasında belirlenir. `x = 10` [Python])

Kotlin'in birkaç önemli özelliğini aşağıdaki şekilde listelemek mümkündür.
- Nesne yönelimli bir programlama dilidir.
- Kotlin projesi açık kaynak kodludur.
- Java ve Javascript ile uyumlu çalışmaktadır. Java'da yazılan kodu Kotlin'e çevirebilir, Java kütüphanelerine Kotlin ile erişebilirsiniz. Yazdığınız kodu Javascript koduna derlemeniz de mümkündür. Bu özellikleri, Kotlin'i sunucu ve istemci tabanlı web uygulamaları geliştirmek için uygun bir dil haline getirmektedir.
- Kotlin ile Android uygulamaları geliştirilebilir. Bu açıdan kendisi Java'ya alternatif bir programlama dilidir. Ancak önümüzdeki yıllarda Java alternatif konumuna düşecek gibi duruyor :) Google I/O 2017 etkinliğinde Kotlin, resmi bir Android geliştirme dili olarak duyurulmuştur.
- Kotlin'in en önemli özelliklerinden biri de bir çok hataya (exception) yol açan null veri tipini ele alış şeklidir.
NullPointerException (NPE) hatalarının önüne geçmek için Kotlin'de pek çok önlem alınmış ve bu sayede Java'daki güvenlik sorunları giderilmeye çalışılmıştır.
Ayrıntı için bkz: https://kotlinlang.org/docs/reference/null-safety.html
- Kotlin'in resmi sitesinde (http://kotlinlang.org) dilin 4 temel özelliğine değinilmiştir. Bunlar sözdiziminin özlü olması (az kod, çok iş), NPE konusunda güvenli olması, Java ve kütüphaneleri ile uyumlu olması ve pek çok IDE (Integrated development environment - tümleşik geliştirme ortamı) tarafından desteklenmesidir.

## Nerelerde Kullanılır?

JVM -> Java kütüphanelerini kullanarak Java sanal makinesi üzerinde çalışacak sunucu tabanlı uygulamalar geliştirebilirsiniz.
Android -> Java ile karşılaştırıldığında hiçbir kısıtlama olmadan Android uygulamaları geliştirebilirsiniz.
Browser -> Kotlin ile yazdığınız kodları Javascript olarak derleyip uygulamalar geliştirebilirsiniz.
http://kotlinlang.org/docs/reference/js-overview.html
Native -> Sanal makinenin (JVM gibi) tercih edilmediği veya sanal makine kullanımının mümkün olmadığı sistemlerde bu köprüyü aradan kaldırmak ve native (donanım bazında) çalışan uygulamalar geliştirmek için Kotlin Native kullanıma sunulmuştur. (Buna gömülü sistemler, iOS verilebilir.) Kotlin Native birçok platformda desteklenmektedir.
http://kotlinlang.org/docs/reference/native-overview.html

## Sektördeki Yeri

Hem Android geliştirme alanında hem de Java/Javascript uyumluluğu konusunda sağladığı yararlar Kotlin'in popülaritesini her geçen yıl artırmaktadır.
Sektörde yeri çok yeni olmasına rağmen hızlı bir yükseliş gösterdiğini ve özellikle Android konusunda tercih edildiğini söylemek yanlış olmayacaktır.

## Frameworks

https://spring.io -> Kendi sunduğu API'ler ile Kotlin kullanarak sunucu tabanlı uygulamalar geliştirmenizi sağlamaktadır.
http://vertx.io -> JVM üzerinde Reactive (reaktif: yan etmenler ile işleyebilen) uygulamalar geliştirilebilmektedir. Kotlin desteği bulunmaktadır.
https://github.com/ktorio/ktor -> Kotlin ile web uygulamaları oluşturmayı sağlayan, JetBrains tarafından geliştirilmiş bir framework'tür.
https://github.com/kotlin/kotlinx.html -> Kotlin ile HTML sayfalar oluşturmak için DSL çözümü sunan bir kütüphanedir. JSP ve FreeMarker gibi şablonlara alternatif olarak geliştirilmiştir.
(DSL: Domain Specific Language - Belirli bir çözüm için belirlenmiş programlama dili)

## Yararlı Linkler
 http://kotlinlang.org
 https://kotlinlang.org/docs/tutorials/
 

