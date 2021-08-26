Burada İstanbula dair açık kaynaklarla bir kaç uygulama yaptım.



Makine Öğrenimi Algoritmaları ile  İBB Verisetlerinden İlçere Göre Doğalgaz Tüketimi , Nüfus ve Sosyal Ekonomik Statü Skoru veri setleri kullanılarak , Sosyoekonmik statü skoru ve Nüfusa göre Doğalgaz tüketim tahmini yaptım.Bunun için makine öğrenimi kütüphanesi olan sklearn dört ayrı modelini  kullandım.


İBB Veri Setlerinden Sağlık Kurumları Veri Seti ve Nüfus verilerinden yararlanarak ilk olarak KeplerGL kütüphanesini kullanıp , Yataklı Hastane konumlarını noktalar olarak gösterimini yaptık.Nokta Büyüklükleri yatak sayısıyla orantılı.Ardından veriler üzerinde matematiksel işlemler ile İlçelere göre 1000 kişi başına düşen yatak sayısını bulup plotly kütüphanesi yardımıyla hem yatak  hem de düşey olarak görselleştirdim.


En sonuncuda da Google Earth Engine verileri kullanarak earth engine'da gömülü Makina Öğrenimi algoritmaları ile (Kmeans Kümeleme)  
arazi örtüsünü 5 sınıfına ayırarak görselleştirmesini yaptım.






