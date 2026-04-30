# E-AUTOPAY

E-AutoPay — это сервис для организации приёма заказов, оплаты и создания партнёрской программы. Вы можете подключить к платформе интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### Шаг 1. Собираем данные и производим настройки на стороне Продамуса&#x20;

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе E-AutoPay нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с E-AutoPay
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с E-AutoPay
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

Далее добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://xxxx.e-autopay.com/ordering/prodamus/notification.php](https://xxxx.e-autopay.com/ordering/prodamus/notification.php). Вместо xxxx нужно вставить логин вашего аккаунта. Его можно скопировать из адресной строки браузера при авторизации в личном кабинете E-AutoPay.

<figure><img src="https://lh7-us.googleusercontent.com/x0TWZaGBb0nEl8F6uKUpdrnO1hPWadPNj_PBypwnlBNbwF3mpJMXSyaUeAtl1OLRxKoCjZxdMU3W16PSh-1muXQRHt1Z5sY6S_qQw-0b3X38RIztBNYqtmhYbul3lnRj8Si6ml0KkXcC9SpK2OBvLQE" alt=""><figcaption></figcaption></figure>

* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Настройка интеграции на стороне E-AutoPay

Авторизуйтесь в личном кабинете и перейдите в раздел «Финансы» → «Настройка способов оплаты».

<figure><img src="https://lh7-us.googleusercontent.com/VONffqx-fm1ihekDJQgsBv6Sy0LRM8CepEAWsJQUJiMHzYsVwMU7D9MjgQ_ASnQLmqRc_kD3_0OzP41O59SeBv-m-cImAR0GZChPGgzUQHUyUjf4ulkeQ4UQ9bDR9a4mgSn1Fy7NflIlZkv0CavcL_8" alt=""><figcaption></figcaption></figure>

Выберите интеграцию с Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/vK366A2vn83jSVYQV9S0N8CQfIOPK9-nK6UAjwE_DdKBLKewX7s7tlvBzUe23l8TNUzp2iVVpaqJMTcDCAdUCgDXM8I3hnqZRBSc8_o2Ne6AQEDz8LN2yBiQMH6Ej0rueol4FmuvPCs0EW6Fl5uiEQ4" alt=""><figcaption></figcaption></figure>

Установить галочку в поле «Принимать оплату через Продамус».

<figure><img src="https://lh7-us.googleusercontent.com/CdDOw5-8ezDGsLktPRS7A7tjZ5OX88MxNAYFm4Ife12bNwB9N9zDd1172cOIz2ncuFR4XaRdhAlIb2T98gXqldnMd8FEaPfVGG-F2qGh0fCGNWmMGI0lHRv_-EjK5lT8q00KU4Q7DKBT06Y_e-sCYk0" alt=""><figcaption></figcaption></figure>

Укажите в поле «URL-адрес платёжной формы» ссылку на вашу платёжную страницу в Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/qAdUXPfmoWT8t6K4rZeFMTgdWQL17dG86XDa1fm_H03x2VSaluh01aSRN04wQjhAYv2CPQl1EKtRPhrswe5WaYBFSwpRH11MYOQtdLsemWK-koRQXHLKLoLu_VbPa-O_2OfY90vQqQd3MFKnaMsUGXY" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/DR1NRS8E5wbBipTlRL21EqxdXgcDoKRjPGpmpxAuNIanEwBiX7JMd2aqU6KBhuice0EyDvBP2_bCS_rbVC6g2uV180_rNUUonZYRMZ4sutZmRKRelJXTLxi367EiTh1wqsruI0TP10rSvjWyicJGZjQ" alt=""><figcaption></figcaption></figure>

Выберите, в какой валюте будет формироваться стоимость платежей.

<figure><img src="https://lh7-us.googleusercontent.com/JEpehqcxBay2ds9ZZTi0JqwO_zNYe5dgMHMgZRC8CimmgyKm4Yo6JhK8WU4V_7OpDSVlYN-UBdx94Ls55aiSt1B0EgndcCQLuUnOk3aKKEAP2b25wtBLOFBYpu5ZnUKHvWR2znbVh5YPoEwiYDdJ5og" alt=""><figcaption></figcaption></figure>

Укажите, какой по счёту будет оплата через Prodamus в таблице выбора способов оплаты.

<figure><img src="https://lh7-us.googleusercontent.com/BFO45JQ1L8PUNu7d1XEIt1EuVrBovVCFXu5oP_Svi3eIislxif1AZ0gq7rfWzX_8RsTbZveBg6xlQ9fY9QyzKf2rvt1JSZJl9sOhFcQKaB3Ul_lOlP5hT1o_wvTHuVVRdRbc23g3GxkPeYRPA_x3_go" alt=""><figcaption></figcaption></figure>

Придумайте название и описание способа оплаты.

<figure><img src="https://lh7-us.googleusercontent.com/kkQkvFqkARaa4B9aNzW9W1VRiUIrexp9ElxxGPt_P_uBz1BAEnnUgoy8s0njZd33hBZzGdrv_yttsOIWxTu-bao40aWzIe5Sr_rS-KiNi4Q8KFI_WLEPdewearno4TkUGiacYAodpD7cjuEn6ps7Ogk" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="https://lh7-us.googleusercontent.com/MtZu7kP_48yvhSYxWg4mJtUHnJvA-NkrcL5_B9yoWwObFEXzeI0rpXkpz9i2wCRB1DA_M_790dE-0kT_0OLPEuJ89K6Zq5a_ufcsiEXTLhPL2_ROBOkEIK-4k9yv5G2EVDHAfVhI4s0p1x73RXlfcyg" alt=""><figcaption></figcaption></figure>



Готово! интеграция настроена. Теперь ваши клиенты смогут оплачивать заказы в E-AutoPay через вашу платёжную страницу в Prodamus.
