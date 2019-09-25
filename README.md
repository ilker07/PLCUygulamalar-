# PLCUygulamalar-


![STAJ1](https://user-images.githubusercontent.com/55693489/65607556-6e0e0d00-dfb5-11e9-97cd-b29110348d5a.jpg)
RS LOGİX 500 te yapılan ilk çalışma.Bu ladder programında Input 0 stop butonu,Input 1 butonu ise start olarak çalışır.Input 1 e basıldığı zaman Output 4 kanalı üzerinden 0 yanar.O:4/0 kontağı ile de mühürleme yapılır.0 numaralı butona basıldığı zaman program başa döner.


![staj2](https://user-images.githubusercontent.com/55693489/65608005-2b990000-dfb6-11e9-9b8e-5570206d8387.jpg)
Bu çalışmada I:2/1 butonuna basıldığı zaman O:4/0 yanar.O:4/0 kontağıyla mühürleme yapılır.O:4/0 yandıktan sonra TON komutuyla 5 sn lik  timer çalışır.Timer 5 sn. saydıktan sonra T4:0/DN ile saymayı bitirir ve O:4/1 yanar.

![staj3](https://user-images.githubusercontent.com/55693489/65608097-55eabd80-dfb6-11e9-8667-56774a497eac.jpg)
![staj4](https://user-images.githubusercontent.com/55693489/65608110-5be09e80-dfb6-11e9-91e7-d394df6abaf0.jpg)
Bu çalışmada önce 0 yanar.1 sn. sonra 1 yanar.1 sn. sonra 2 yanar.3 sn. bekler.2 söner.3 sn.bekler.1 söner.3sn. bekler ve 0 söner.

![staj5](https://user-images.githubusercontent.com/55693489/65608175-7a469a00-dfb6-11e9-8fdc-5a62033dd81e.jpg)
Bu çalışmada I:2/0 start butonu,I:2/1 butonu stop olarak çalışır.Starta basıldıktan sonra program T4:2/EN ile karşılır.Bu komut T4:2 Aktif olmadığı zaman akım geçer anlamına gelir ve oradan geçer ve O:4/0 yanar ve T4:1 aktifleşir.5 sn. saydıktan sonra O:4/4 yanar(5 sn.).

![staj6](https://user-images.githubusercontent.com/55693489/65608220-8fbbc400-dfb6-11e9-8aa0-1e6169f9555b.jpg)
Bu çalışmada I:2/0 a basıldıktan sonra O:4/5 yanar.T:4/1 aktif olmadığı için O:4/2 yanar.T4:0 aktifleşir.15 sn. saydıktan sonra O:4/0 yanar.Sonra T:4/1 aktifleşir,o ve 2 söner.5 sn. saydıktan sonra O:4/1 yanar.

![staj7](https://user-images.githubusercontent.com/55693489/65608311-b1b54680-dfb6-11e9-8fdc-b9792a82d209.jpg)
Bu çalışmada I:2/0 start,I:2/1 stop olarak kullanıldı.Starta basıldıktan sonra B3:0/0 aktifleşir.Sonra T4:0 aktifleşir.2 sn. saydıktan sonra O:4/0 ı move komutuyla belirtilen yere taşır.

![staj8](https://user-images.githubusercontent.com/55693489/65608516-03f66780-dfb7-11e9-94a5-5fb6e2e96a51.jpg)
![staj9](https://user-images.githubusercontent.com/55693489/65608528-08bb1b80-dfb7-11e9-9aa1-5dd3e25ecd48.jpg)
![staj10](https://user-images.githubusercontent.com/55693489/65608534-0d7fcf80-dfb7-11e9-961b-1195f667c9b5.jpg)
![staj11](https://user-images.githubusercontent.com/55693489/65608538-107ac000-dfb7-11e9-865a-1ca1d8d54a43.jpg)
![staj12](https://user-images.githubusercontent.com/55693489/65608543-1375b080-dfb7-11e9-8be9-032338c46386.jpg)
![staj13](https://user-images.githubusercontent.com/55693489/65608550-15d80a80-dfb7-11e9-81a4-193845c3c025.jpg)
![staj14](https://user-images.githubusercontent.com/55693489/65608557-18d2fb00-dfb7-11e9-8638-82e26dfaccf5.jpg)
Bu çalışmada start butonu basıldıktan sonra timer ve move komutları yardımıyla 2 sn aralıklarla D,E,R ve S harfleri yazdırıldı.


