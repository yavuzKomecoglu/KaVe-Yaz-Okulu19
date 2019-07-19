# KaVe - Yaz Okulu'19
Karmaşık Sistemler ve Veri Bilimi Yaz Okulu - 2019 

### "I dream of painting and then I paint my dream." - Vincent Van Gogh
<img src="https://www.vincentvangogh.org/images/paintings/self-portrait-with-straw-hat.jpg" width="250px"  />

Tüm zamanların en iyi sanat eserlerini derin öğrenme teknikleri kullanarak sınıflandırıcı geliştirmeye çalışacağız.

Sınıflandırıcının amacı, giriş olarak verilecek bir resmin hangi sanatçı tarafından resmedildiğini tespit etmek olacak.



## Veri Kümesi

[Best Artworks of All Time](https://www.kaggle.com/ikarus777/best-artworks-of-all-time) veri kümesi, [Icaro](https://www.kaggle.com/ikarus777) adlı kullanıcının Kaggle üzerinde paylaştığı herkese açık bir veri kümesidir.

**Veri kümesinde 50 sanatçının toplam 8446 adet sanat eserlerinden oluşuyor**

**3 dosyadan oluşuyor;**

- artists.csv: Her sanatçı için bilgi tablosu.
- images.zip: Klasörlere bölünmüş ve sıralı olarak numaralandırılmış (full size) resim koleksiyonu.
- resized.zip: aynı koleksiyon ancak resimler yeniden boyutlandırıldı ve klasör yapısından çıkarıldı.


## Çalışma Dosyaları 🖥️
- Kurulumsuz tarayıcı üzerinde jupyter notebook ile mybinder üzerinde çalıştırabilmek için [tıklayınız](https://mybinder.org/v2/gh/yavuzKomecoglu/KaVe-Yaz-Okulu19/master).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yavuzKomecoglu/KaVe-Yaz-Okulu19/master)

### Google Colab

- [1-Dataset-Analysis.ipynb](https://colab.research.google.com/github/yavuzKomecoglu/KaVe-Yaz-Okulu19/blob/master/1-Dataset-Analysis-best-artworks-of-all-time.ipynb) - Kaggle API ile veri kümesinin indirilme işlemleri ve analiz işlemlerinden oluşan çalışma dosyası.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yavuzKomecoglu/KaVe-Yaz-Okulu19/blob/master/1-Dataset-Analysis-best-artworks-of-all-time.ipynb)


- [2-Training.ipynb](https://colab.research.google.com/github/yavuzKomecoglu/KaVe-Yaz-Okulu19/blob/master/2-Training-best-artworks-of-all-time.ipynb) - Modelin oluşturulması, eğitilmesi, performansın değerlendrilmesi ve web url ile test etme işlemlerinden oluşan çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yavuzKomecoglu/KaVe-Yaz-Okulu19/blob/master/2-Training-best-artworks-of-all-time.ipynb)
   

