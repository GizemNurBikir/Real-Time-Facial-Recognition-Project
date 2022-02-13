# Real-Time-Facial-Recognition-Project
Gerçek Zamanlı Yüz Tanıma Projesi: Yüz tanıma, bir kişinin yüzünü kullanarak kimliğini tanımlamanın veya doğrulamanın bir yoludur. Yüz tanıma sistemleri, kişileri fotoğraflarda, videolarda ya da gerçek zamanlı olarak tanımlamak için kullanılabilir. Yüz tanıma, biyometrik güvenliğin bir kategorisidir.
Yüz tanıma nasıl çalışır: 
1. adım: Yüz algılama ve Yüz analizi; Kamera, ister tek başına ister kalabalık içerisinde olsun, yüz görüntüsünü algılar ve bulur. Görüntü, kişiyi doğrudan karşıdan veya yan profilden gösterebilir. Ardından, yüzün görüntüsü kaydedilip analiz edilir. Çoğu yüz tanıma teknolojisi, 3D yerine 2D görüntüler kullanır çünkü 2D görüntüyü halka açık fotoğraflarla veya bir veritabanındakilerle daha kolay eşleştirir. Yazılım, yüzünüzün geometrisini okur. Amaç, yüzünüzü ayırt edici kılan belirgin noktaları tanımlamaktır.
2. adım: Görüntüyü veriye çevirme; Yüz yakalama işlemi, kişinin yüz özelliklerini baz alarak analog bilgileri (yüz) dijital bilgiler kümesine (veri) dönüştürür. Yüzünüzün analizi, temelde bir matematik formülüne dönüştürülür. Bu sayısal koda yüz izi adı verilir. Parmak izlerinin benzersiz olması gibi, her insanın kendine özgü bir yüz izi vardır.
3. adım: Eşleştirme; Yüz iziniz, bilinen diğer yüzlerden oluşan bir veritabanıyla karşılaştırılır.Yüz izinizin yüz tanıma veritabanındaki bir görüntüyle eşleşmesi durumunda bir karar verilir.

Projede Kullanılan Yapılar;
Programlama dili: Python
Kütüphane: OpenCV

Oluşturulan platform: PyCharm
İşletim Sistemi: Windows 11
İşlemci: Intel

Paketler; 
PILasOPENCV	2.7	
Pillow	9.0.1	
Pillow-PIL	0.1.dev0	
freetype-py	2.2.0	
gif2numpy	1.3	
kaitaistruct	0.9	
mss	6.1.0	
numpy	1.22.2	
numpy2gif	1.0	
opencv-contrib-python	4.5.5.62	
pip	21.1.2	
setuptools	57.0.0	
wheel	0.36.2	

NOT: Projenin çalıştırılması için proje içerisinde "veriseti" isimli boş bir klasör oluşturulmalıdır. Gerçek zamanlı elde edilen görüntü kayıtları bu klasöre kaydedilecektir. Projede yer alan "veriseti" klasörü mevcut veri içermediği için GitHub projesine yüklenememiştir.
