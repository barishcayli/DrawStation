## DrawStation

Bu proje tren diagramı çizilmesi için yardımcı bir uygulamadır. Bir diagrama eklenecek her şey bulunmaktadır (Track, Point, AutomaticBlock, Signal, Station). Çizilen diagram konumlarına göre veri tabanına kaydedilmektedir. Diagram çizmek için her bir nesne özellikleri seçilerek ayrı ayrı eklenir ve bunlar kaydırılabilir konumları, özellikleri değiştirilebilir şekildedir.

##  Kullanılan Teknolojiler

- Java
- Spring Boot Framework
- JavaFX
- PostgreSQL
- Hibernate
- Lombok

## Tanıtım

- Diagram çiziminde eklenecek olan nesne eklendikten sonra kaydırılarak yerleştirilebilir ve istenilen şekilde diagram çizilebilir. Çizim bittikten sonra kaydet dediğimizde veri tabanına kaydedilir ve daha sonrasında kullanılmak üzere ya da değişiklik yapılmak üzere saklanır.
  
![image](https://github.com/user-attachments/assets/07876ce1-1f3d-4d4b-a323-d2ec06e9e31a)

- Örnek bir makas aşağıda ki gibi özellikleri girilir ve ekrana eklenir ardından kaydırma işlemleri ile yerleştirilir.

![image](https://github.com/user-attachments/assets/3de219ad-fd81-44d3-a920-3abd952f4d9e)

- Eklenen direkt çizilir ve isteğe göre tekrar değiştirilir. Yapılan değişiklikler olduğunda ekranın altında bir kaydet butonu bulunur ve kaydet dediğimizde api ile gönderimi sağlanır veri tabanına kaydedilir. Reset butonuna tıkladığımızda ise yapılan değişiklikler geri alınır.

![image](https://github.com/user-attachments/assets/e3b62782-854e-4ff7-b99b-fec66bf6460a)

- Kullanıcı kolaylığı için ve çizim yapılırken daha anlaşılır olması için değiştirilebilir bir tabanımız vardır.

 ![image](https://github.com/user-attachments/assets/ad9eb9cc-bbe2-4d61-89d6-6337cd788fbb)

- Çizilen diagramda konumları daha kolay belirleyebilmek için çizgiler ekleyebiliriz bu sayede çizilen nesnelerin düzlemi daha kolay belirlenir.
![image](https://github.com/user-attachments/assets/023072f3-fa63-44d3-b188-73166fc55108)

- İstasyon filtreleme ile istenilen istasyon tek görüntülenebilir ya da düzenlenebilir.
 ![image](https://github.com/user-attachments/assets/a0708fce-b9ce-412f-b878-7cb61e2d61e9)

- Her bir nesnenin kendine ait listesi bulunmaktadır.
  ![image](https://github.com/user-attachments/assets/e96ce259-b312-457a-ab1b-b28f6d6a1711)

- Nesnelerin birbirlerine olan bağlantılarını senkronize etmek için bir buton bulunmaktadır. Bu butona basıldığında görselde birbirine bağlı olan nesnelerin önceki, sonraki ve reverse özellikleri doldurulur yani bağlanır.
- ![image](https://github.com/user-attachments/assets/7821968a-d6ae-4dc7-a5e7-b3b3b1bcf020)

 ## Genel

 Bu proje benim staj sürecimde geliştirdiğim projelerden birisidir. Savronik bünyesinde kullanılmak üzere geliştirdiğim bu projeyi uzun yıllar kullanıma hazır hale getirdim. Backend için Spring kullandım ve frontend ile iletişimi için api kullandım. Yapılmak istenen işlem(CRUD, Senkronize işlemleri, Filtreleme vs.) api ile bildiriliyor ve buna göre bir geri dönüş sağlanarak kullanıcıya yansıtılmaktadır.

 ## Nisan 2025 - Mayıs 2025

 ## Barış Çaylı







 





