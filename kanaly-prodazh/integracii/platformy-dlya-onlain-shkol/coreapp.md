# CoreApp

CoreApp — платформа, на которой можно создавать онлайн-курсы, вебинары и live-уроки. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе CoreApp нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с CoreApp&#x20;
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с CoreApp&#x20;
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
* Вставьте адрес [https://v2.coreapp.ai/payments/prodamus/hook](https://v2.coreapp.ai/payments/prodamus/hook)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение интеграции в личном кабинете CoreApp

Перейдите в личный кабинет CoreApp, нажмите на иконку своего профиля и выберите режим «Личный кабинет».

<figure><img src="https://lh7-us.googleusercontent.com/yKlJH46StSUN2KYtFSGDRN4V-CbY1uWZ34Vntb9VTIH91CCHaoxlH74PwgKkF3hUKZ6CH8SzgnSC7zq9HvBR8LUtkXrt24cPwUWHoedKy2_33-Zoi2TuvtqmTsFESq1_Mr_iwWUjhrkT2Ww9RoMxxPA" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Моя школа».

<figure><img src="https://lh7-us.googleusercontent.com/kA98Vrp4GltEXGidZITN-3wY1SxpnXnDdb114cj3L0nD3qK95UtCh7OvfpKl-5Trnya_aeFgN19317XD-NS0fNePCzMAtGsKZT-FPPPaUcfyQ_zAcgbmRUgnIhhjEMjP4hB6xtt-Mvl4fu6Pl6BGa3c" alt=""><figcaption></figcaption></figure>

Перейдите в раздел «Платёжные системы» и нажмите кнопку «Подключить» напротив логотипа Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/FRu5DvlXg85Ut9BYLaMnudy1CX4BWGg-KWvQmD6YzmTgQliPUYmT8TUaf27r3YDzo14JJASclaJMh7TTXJnFAkL9UqNR72RF_L8-DrHUM_X1OdJ6oDGVmh6ZrLeuZk_SYb6aF3_i1Tj-sOvtY7ng8s0" alt=""><figcaption></figcaption></figure>

Укажите ссылку на вашу платёжную страницу, полученную в личном кабинете Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/T_s5y8qKAkjRJiYplFfYfTyecN9dN8IxaRO6tiEdb2vCWZpV8AtJadwH5wCPUWsn307B0oNA9Ue_nru-fh8uxc2GfuCWtd6z4gdyTIbgcfH163Uuh6X22xBaDMZhPSkQE6OZgLNY5tMmgf0IrSs6n7U" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее создали в личном кабинета Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/Q1svTnlnn9q4nLE7kg0mPNWgoTezMDGhv7kECugy-1zqHL-pbZgFjUkFXMA8av4U8DVnvH3lPN2cMyerkruChNhZ5TvyQY2wpAknzMMl2ulpIeE23ssEwrFuYkRxJiRfzzIpdHyVbYb0BtL940Vs5Zw" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Подключить».

<figure><img src="https://lh7-us.googleusercontent.com/WCkpwpZS5VKhzVHcEzs96eYCfdkwYw7JIol4GHzRAyOeG5N5ScFUYNza3Ypjra8ajvpkUoQflg_ixMmw8GnbsAx_6eSOYIgqK7O4kdQ0ncNzO-YGq3DG-xNa8JVzgXezoHsZrmeXPmC1ttzSXfKObic" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе CoreApp!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
