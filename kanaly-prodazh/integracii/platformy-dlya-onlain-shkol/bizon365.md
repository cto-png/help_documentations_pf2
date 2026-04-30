# Bizon365

Bizon 365 — платформа, на которой можно создавать курсы, вебинары и онлайн-тексты. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

## 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Bizon365 нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Bizon365
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Bizon365
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
* Вставьте адрес [https://start.bizon365.ru/kassa-processing/](https://start.bizon365.ru/kassa-processing/)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение интеграции в личном кабинете Bizon 365

Перейдите в личный кабинет Bizon 365 и нажмите «Настроить кассу».&#x20;

<figure><img src="../../../.gitbook/assets/1 (22).png" alt=""><figcaption></figcaption></figure>

Перейдите в раздел «Платёжные системы».

<figure><img src="https://lh7-us.googleusercontent.com/oXt5AQybMVNV4A1psErFRflm_aJMlElJ9i7lLWDJp7SmnJAR0lojqpCp2XHN9-peL72gV1u97XSQFliyl14Rr5G9gqHISc1_VMEXzZgamNhPQaQ3WI9YKriP6RieDedeno_KbcY0NueY613veDiNgtU" alt=""><figcaption></figcaption></figure>

Откройте интеграцию с Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/A0zZ0YULr1U_X7M9H2xMs7VZcFUqCxU3daP1AIqoDZGShbsL68GmoOrhWk4Ry5oplklskkS5i-CC2w2BZNwuQo2FpipYeke3ufeLWj9hh9c6ANoh4zEbGfmzTIykPxIlSiJQ9hwCAKzozarLRlPR_b4" alt=""><figcaption></figcaption></figure>

Укажите адрес вашей платёжной страницы в Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/QPPckzxXo2XzqefSTZZAkiaNFor5Kqj39DiP-jY1ydPQqYkfBsSCz0vD9-J1wKSKn-kEcYvmdHnPk1kWpxfbuxr3bNoILlTiGYxlxEdbbU3G5JByBOWcwkUIhBBOf7QQ0LB5JdFbKo73ypj9YM1VGJ0" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/YgGciYZCwavnphbgsbWrRtDTRedYx0w71YgwFmtUmXY24ZCEwKudnMVwMErG7SulxH8spr4ezunZeJhFmhujY6VUG-sZeqhbqxkqDz-JcTgUgYnEGIVTLoOnMp07u09wcjsJDuG7XCvN6RVNQJoDrt4" alt=""><figcaption></figcaption></figure>

Придумайте описание метода оплаты. Его будут видеть ваши клиенты при оформлении заказа.&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/eVczLDShYbPbdcVAK6sxLXl1y8jVq3PTZRZjzgUjIJ8_dDmCVYjZP1__Yo-ETVnf8BkCShUTRt6jCPEzDTNPzJUy2ZNnNOh-_d8QxSK0mJAJ2tkONYoAOMnh6Qdu3epJK-B5Iy7j6DA3I-OnMU_118o" alt=""><figcaption></figcaption></figure>

Укажите приоритет отображения платёжного модуля Prodamus в списке методов оплаты. Например, если указать в этом поле цифру 1, то для ваших покупателей Prodamus будет отображаться на первом месте среди других подключённых методов оплаты.

<figure><img src="https://lh7-us.googleusercontent.com/kIbNP_nNRLuZ-SP_4Y_jiy1qrjvbQkBDq0zvx2Qm9eO0bIFzmmBRk975LrIggKl8FCM5sSZDpzUPrj3uwhyYSjvep5eZ1YsnCniKZEAgzcWQoYcAN_rdCBPMP1vONIUERM9t0Gns1BFlwmCTjsqGdjs" alt=""><figcaption></figcaption></figure>

Если вашим менеджерам положено вознаграждение за продажу, вы можете указать его сумму или процент в поле «Комиссия».

<figure><img src="https://lh7-us.googleusercontent.com/qZeWCCYZs0Sl12Kt-ptJLSisEfvBYknGcD2yPc2u-bi3Yl2MAmZUeueFvBBUDhz0zK7O6csiLcFJm9Xhsqii5zqxoXeLIGrrx6zegJDDVfyaoxr72gZCyABIIBIcMEL8w9H7qr9G6HYJOFGhasrxWnA" alt=""><figcaption></figcaption></figure>

Укажите для метода оплаты минимальную и максимальную сумму заказа. Если указанная сумма будет меньше или больше заданных лимитов, покупатель не сможет оплатить заказ через Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/S8JPtb3ChFmVtnhSuNe6vymUbLSglZFRuwgL6M6rNVKbFAHj9i4PdF3FkxEuK4aorMvJKt4xc_IPJ60TyhOprb8qGWiUdkpoepXrvlDpqS-EZ6_XPnMuurydlipVoAl3bhZIOII69124U9I0dNqlBC8" alt=""><figcaption></figcaption></figure>

Нажмите «Сохранить настройки».&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/up6q10NlPAh2La6eVz2WMUHUfVPpadmyssexhuTl2iOw4YP9TF1j0oOurrKfcMsy7r-gRWKF67GEAAI_L9NP41ju0q_cQHv2gcEANex5ND9CBR3xrFUZaXQFhD6VteKAn7tKt_yHl97jyq6WjC3ZkIo" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена. Теперь метод оплаты будет доступен для ваших товаров в Bizon 365.
