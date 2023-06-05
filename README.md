# DENSENET ÇALIŞMASI

29 Mayıs 2023 tarihinde EMKA Academy'nin düzenlediği "TensorFlow - Keras Görüntü Sınıflandırmaya Giriş" eğitiminde  Emincan Yılmaz ve Kaan Bıçakçı TensorFlow dataset içeriklerinden "plant_village" veriseti üzerinden aşağıdaki konulara giriş yaptılar:
* Data Prepocess (Veri Ön Hazırlık)
* Modelling
  * ANN
  * Basic CNN
  * Functional API

Bu dokümanda eğitim sonucunda verilen task çalışması yapılmıştır. tf.keras.applications modulü altındaki denset modeli kullanılarak acc değerleri incelenmiştir.

Conv2D CNN modelinde görülen acc:0.9276 değerine karşılık densenet modelinde 0.6043 elde edilmiştir. Ancak değerlerin farklılığının epochs değerlerinden kaynaklandığı düşünülmektedir. Eğitim esnasında yaşanın GPU ve CPU sorunlarından dolayı densenet modeli istenildiği gibi eğitilemedi. Yine de densenet kullanımı eğitim amaçlı olarak gerçekleştirildiğinden sonuç gözardı edildi.
