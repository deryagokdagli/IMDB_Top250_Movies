[TR]
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

[EN]
# IMDb Top 250 Movies Analysis

In this project, a comprehensive data analysis was conducted on movies listed in the IMDb Top 250. 
The data was obtained from a CSV file on Kaggle, and missing values (nulls) were cleaned by filling them with the median. 
During the analysis, Python's **Pandas** library was used for data processing and **Matplotlib** for visualizations.

The project examined the distribution of movies by genre, the distribution of IMDb ratings, and movies with ratings of 8.0 and above. 
Additionally, movies were grouped into 5-year periods to analyze production counts over time, and directors with three or more films in the Top 250 were identified. 
The age classifications of the films were visualized to determine which ratings were most common.

To analyze the economic dimension, the films' **budget** and **box office** data were used; a profit/loss analysis was performed, and the most profitable and least profitable films were visualized using side-by-side bar charts. 
Bar charts and other visualization techniques allowed for a comparative view of the movies from different perspectives.

This project aims to provide a comprehensive understanding of IMDb Top 250 movies by combining data cleaning, analysis, and visualization processes.

