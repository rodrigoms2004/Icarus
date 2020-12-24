# Projeto Icarus

Lançamento de balão meteorológico para filmagem da curvatura da Terra

### Tutorial

[Tutorial](https://www.stratoflights.com/en/tutorial/weather-balloon-tutorial/)

[Calculadora de gás Hélio](https://www.stratoflights.com/en/tutorial/helium-calculator/)

### Balão escolhido

800g transportando carga de 1.5kg com eficiência, com máximo de 6 m³ de gás hélio

Diâmetro de lançamento: de 1.8 a 2.4 metros
Diâmetro de estouro: aproximadamente 7 metros
Faixa de altitude de estouro: entre 26 km e 32 km

[Balão Meteorológico de Grande Altitude - 800g](http://www.mundoclima.com.br/produtos/balao-meteorologico-de-grande-altitude-800g/)


### Pressão atmosférica pela altitude

Calculadora de pressão atmosférica
[Atm Calculator](https://www.digitaldutch.com/atmoscalc/)


### Calculo da pressão

Lançamento em São Paulo, SP 760 metros do nível do mar, 92.5 KPa


Pela lei de Boyle-Mariotte
```
(p1*v1)/t1 = (p2*v2)/t2
```

*Condições de lançamento*
```
p1 = 92.5 kPa
v1 = 3 m³ ou 3000 litros
t1 = 25 C = 298.15 K
```

*Condições de estouro estimando 26 km de altitude*
```
p2 = 2.153 kPa
v2 = ?
t2 = -50.5 = 222.65 K

(p1*v1)/t1 = (p2*v2)/t2

v2 = (p1*v1*t2) / (t1 * p2)
v2 = (92.5 kPa * 3000 L * 222.65 K) / (298.15 K * 2.153 kPa)
v2 = (92.5 kPa * 3000 L) / 2.153 KPa
v2 = 96251 L ~= 96.25 m³
```


*Condições de estouro estimando 32 km de altitude*
```
p2 = 0.868 kPa
v2 = ?
t2 = -44.5 = 228.65 K

(p1*v1)/t1 = (p2*v2)/t2

v2 = (p1*v1*t2) / (t1 * p2)
v2 = (92.5 kPa * 3000 L * 228.65 K) / (298.15 K * 0.868 kPa)
(92.5 * 3000 * 228.65) / (298.15 * 0.868)
v2 =p1*v1) / p2
v2 = (92.5 kPa * 3000 L) / 0.868 KPa
v2 = 245176.95 L ~= 245.176 m³
```

## Comm WisLink-Cellular-RAK2011



### Arduino Library

https://github.com/RAKWireless/WisLTE_Arduino

https://pt.aliexpress.com/item/32956394655.html?spm=a2g0o.productlist.0.0.34126ff3dNew3d&algo_pvid=78eada6b-970d-45f8-bdb7-c55c2b2b6368&algo_expid=78eada6b-970d-45f8-bdb7-c55c2b2b6368-14&btsid=0bb0623d16087707361785097e498a&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_



https://www.rakwireless.com/en-us/wis-link

https://downloads.rakwireless.com/Cellular/WisLink-Cellular-RAK2011/



### Links úteis


Pressão atmosférica em milibar

[Pressão atmosférica em mbar](https://www.climadobrasil.com.br/pressao)


Conversão milibar para kPa 1 mbar = 0.1 kPa
[Google mbar -> kPa](https://www.google.com/search?sxsrf=ACYBGNSiJ2YNljN4g9IwVUoHwd-VjxnYBQ%3A1580477305751&ei=eSs0Xsu0LdSx5OUPqqaeuAQ&q=mbar+to+kpa&oq=mbar+to+kpa&gs_l=psy-ab.3..0i273j0l4j0i22i30l2j0i22i10i30j0i22i30l2.63563.65321..66433...0.2..0.221.1060.0j4j2......0....1..gws-wiz.......0i71j35i39j0i20i263j0i10j0i203.Z0tkKs-SHU4&ved=0ahUKEwiL1Ynj-K3nAhXUGLkGHSqTB0cQ4dUDCAs&uact=5)

Conversão milibar para mmHg 1 mbar = 0.750062 mmHg
[Google mbar -> mmHg](https://www.google.com/search?sxsrf=ACYBGNRMZewlMVj4lYED1Zqtw0lF6JWkoQ%3A1580477373138&ei=vSs0XtaDCJGH0AbGwbrYCQ&q=mbar+to+mmhg&oq=mbar+to+mm&gs_l=psy-ab.3.0.0i203l3j0j0i20i263l2j0l4.103983.104119..105311...0.3..0.160.309.0j2......0....1..gws-wiz.......0i71.nmuxnWJ7Vc0)

[Balloon Trajectory Forecasts](http://weather.uwyo.edu/upperair/balloon_traj.html)

[Lei de Boyle sobre a transformação isotérmica](https://mundoeducacao.bol.uol.com.br/quimica/lei-boyle-sobre-transformacao-isotermica.htm)


[Lançamento de balão meteorológico à estratosfera](https://garoa.net.br/wiki/Lan%C3%A7amento_de_bal%C3%A3o_meteorol%C3%B3gico_%C3%A0_estratosfera)

[Balão Meteorológico de Grande Altitude - 600g](http://www.mundoclima.com.br/produtos/balao-meteorologico-de-grande-altitude-600g)

[Balloon Trajectory Forecasts](http://weather.uwyo.edu/upperair/balloon_traj.html)

[Equipe HAB Mauá lança balão meteorológico no espaço](https://blog.maua.br/2018/05/equipe-hab-imt-lanca-balao-meteorologico-no-espaco/)


[Locação de gás hélio 20L (3m³) para +/- 300 balões de 09 polegadas](https://saopaulooxigenio.com.br/produto/locacao-de-gas-helio-20l-3m%c2%b3-para-300-baloes-de-09-polegadas/)