# Mikrodenetleyici Tabanlı Oyun Makinesi

## Proje Amacı
Bu projenin amacı, çeşitli araçlar kullanarak mikrodenetleyici tabanlı bir oyun makinesi
geliştirmektir.
Oyuncu, bir fiziksel palet kontrol cihazını kullanarak bir topu yansıtarak OLED
ekrandaki tuğlaları kırmaya çalışacaktır. Oyuncu, fiziksel bir "palet kontrol cihazı" kullanacak.
Bu cihaz, potansiyometre ile kontrol edilecek. OLED ekran, oyunculara oyun alanını gösterir.
Üst kısımda tuğlalar, alt kısımda ise oyuncunun kontrol ettiği palet ve zıplayan bir top bulunur.
Oyuncunun amacı, topu kullanarak üst taraftaki tuğlaları kırmaktır. Top, oyuncunun kontrol
ettiği paleti kullanarak yukarı doğru yansır. Top, tuğlalara çarptığında, tuğla kaybolur ve
oyuncu “1” puan kazanır. Bu puan 7 segment display ile gösterilmelidir. Top, palet veya
duvarlara çarptığında yönü değişir. Ekranın sağ ve sol taraflarıda bir duvar kabul edilmelidir.
Oyun başarılı bir şekilde biterse topun önceki hızına göre yüzde 20 fazla olacak şekilde bir
sonraki oyun başlamalıdır. Bir sonraki yere geçildiğinde skorbord ekranı sıfırlanmamalıdır.
Oyun, topun alt kısmından düşmesi durumunda sona erer.

![devre](https://github.com/icsiee/BrickBreakingGame/assets/122745583/bc437e89-d8b7-4e6c-aa49-2dbc8fd11828)

### Clone the repository
```sh
git clone https://github.com/icsiee/BrickBreakingGame.git
cd BrickBreakingGame
