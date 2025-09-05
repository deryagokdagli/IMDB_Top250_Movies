# IMDb Top 250 Filmler Analizi

Bu projede IMDb Top 250 listesinde yer alan filmler üzerinde kapsamlı bir veri analizi gerçekleştirdim. 
Veri, Kaggle’dan CSV dosyası olarak alınmıştır ve eksik değerler (null) medyan ile doldurularak temizlenmiştir. 
Analiz sırasında Python’un **Pandas** kütüphanesi ile veri işleme ve **Matplotlib** ile görselleştirmeler yapıldı.  

Projede, filmlerin türlerine göre dağılımı, IMDb puanlarının dağılımı ve 8.0 ve üzeri filmler incelendi. 
Ayrıca filmler **5’er yıllık dönemlere** ayrılarak yıllara göre üretim sayısı analiz edildi ve **3 veya daha fazla filmi Top 250’ye giren yönetmenler** belirlendi. 
Filmlerin yaş sınıflandırmaları görselleştirilerek hangi sertifikaların baskın olduğu incelendi.  

Ekonomik boyutu analiz etmek için filmlerin **budget ve box office** verileri kullanıldı; bu verilerle **kar/zarar analizi** yapılarak en kârlı ve en zarar eden filmler **yan yana bar chart** ile görselleştirildi. 
Çubuk grafikler ve diğer görselleştirme teknikleriyle filmler farklı açılardan karşılaştırıldı.  

Bu proje, veri temizleme, analiz ve görselleştirme süreçlerini bir arada sunarak IMDb Top 250 filmlerini kapsamlı bir şekilde anlamayı amaçlamaktadır.
