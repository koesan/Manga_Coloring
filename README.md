# Google Colab'da Gan türevi mimariler ile manga renklendirme

Bu projede, siyah-beyaz manga resimlerini renkli hale getirmek için iki ayrı GAN türevi mimari kullanılmıştır: Pix2PixHD ve CycleGAN.

İlk projede, Pix2PixHD modeli kullanılarak eşleşmiş siyah-beyaz ve renkli manga resim çiftleri üzerinde çalışılmıştır. Pix2PixHD, yüksek kaliteli görüntü dönüşümleri sağlamak üzere NVIDIA tarafından geliştirilmiş bir GAN modelidir. Bu model, denetimli öğrenme ile eğitilerek gerçekçi ve doğru bir şekilde renklendirilmiş manga resimleri üretmeyi hedeflemektedir.

İkinci projede ise CycleGAN modeli kullanılmıştır. CycleGAN, eşleşmemiş veri çiftleriyle çalışarak iki farklı domain (siyah-beyaz ve renkli manga resimleri) arasında dönüşüm gerçekleştirir. Bu model, denetimsiz öğrenme sayesinde farklı veri setleri ile renk transferi yapmayı mümkün kılar.
