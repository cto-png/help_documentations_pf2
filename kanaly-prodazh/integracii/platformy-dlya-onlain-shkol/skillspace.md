# Skillspace

Skillspace — это платформа для продажи курсов и организации дистанционного обучения. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

## 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Skillspace нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Skillspace
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Skillspace
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
* Вставьте адрес [https://skillspace.ru/api/payment/result/prodamus](https://skillspace.ru/api/payment/result/prodamus)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию на стороне Skillspace&#x20;

Для этого авторизуйтесь в личном кабинете Skillspace и перейдите в раздел «Настройки школы».

<figure><img src="https://lh3.googleusercontent.com/GegMGTFoTux3F26sf643VeiNiW1b-S0iQtvPskMvWZpmh-EG6xhnQBrFQ_Vsa7cw-iBD6H3V8-PGNPzv4_ShBf_ndDqJIkOp7eklIp7ZmDshrgyI6ODnMxN59N_55AVbrvOMfkWiDX_oqwZ6R0YGn3s" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Способы оплаты» и нажмите «Добавить другой способ оплаты».

<figure><img src="https://lh5.googleusercontent.com/wrRY6qklT9yq5staUoPiW4k2JPqs92UCFxFW2MTup0cW8omwXiXK2TQ5Y3Vigu-Oxve5Km3nswexhB8bInvZ-QNNWmqdV4rCHYQZAqU1d_axwFg7ESi0gZnfhjI06lL4XTgswPPEYHMY-szWItalCXc" alt=""><figcaption></figcaption></figure>

Выберите «Prodamus» в поле «Способ оплаты».

<figure><img src="https://lh5.googleusercontent.com/8eDRa805owdIl77tiLyuwPTD0eEQwDppt3_gvmdHh6wEwZ0H-A_4ek7bP4oLbqUcVPvTUGNOOtVrE0gTisZw1RT01MCvDB3CF9CXVSzDdxNc7PownVwgpqisP3sCPTMxImebHULPxTTv0DMpp-xbT5A" alt=""><figcaption></figcaption></figure>

Придумайте название способа оплаты.

<figure><img src="https://lh3.googleusercontent.com/26MrvxCsZJGqqhEjfLjY5fda1na-lexC3z9xT6WX2DphpQhKNuD44jEntTh81h1-LxhMLZ8cJIA0GuS1Yqh_RFoDtzGzyjOtUBlMWrK_nU_FvRKivIWy9WHDz5SJzQeIirNohIqSjZlXTX6cjQT79AY" alt=""><figcaption></figcaption></figure>

Укажите ссылку на вашу платёжную страницу.

<figure><img src="https://lh5.googleusercontent.com/c8juZUIteiVc1cDrkrgjKQzksjg2b7R3R5DjxTc2C__FxjxYCu6Cvl75H7BTtXiMY9Qls3-xDsMJQITqurIcCKi0NP7eEFllTvJ0NCgFd18ezm0AjLoHVGHkqFfnj-H3_6RXuoYeCokAWBs6mcnRv8c" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее сгенерировали в личном кабинете Prodamus.

<figure><img src="https://lh6.googleusercontent.com/LtyKtJ16MXGrypuq0nv2WPdjwO1zgyfh3ySr8OC7-DNd48RLTP21pYaWJF0GZy0o3wri2jV_hZpaimY6tope_zl2MrHF6_Y3hR6c9bXy0g4I9CNa6-99Z4nj6MEfz__fy93SaPsDfcB-fw3GSOrasMk" alt=""><figcaption></figcaption></figure>

Поставьте галочку в поле «Я указал HTTP-уведомление в настройках продамуса».

<figure><img src="https://lh3.googleusercontent.com/ftBkVa_53u8HfJ_MEiH2KEtgtP2cZnyjkP0zQ6HY-ACE351GfAv-cFV0W1ZmVTvIrnY0OlCByORnI9UcYy15BL2coYFY0h0D02xOurEqZWKno6ZXotuxDReuRPiCblILl0L21uNKIdkUNcFrmHW5kgM" alt=""><figcaption></figcaption></figure>

Нажмите «Добавить».&#x20;

<figure><img src="https://lh6.googleusercontent.com/nD9IPIQzLCBQ1SmNAGdPjUmTglJV_eaPy2nqlMSCCJVXCndtQVdphnrEDVPl8fYRwgSgxhEeiNTM64kp2DC8DInsilvzo5GcOrcuG6zEtSFa5lGyLhnunlA90ZCkaGHrK_O1jPw7gUUVmv_1H_PHGPc" alt=""><figcaption></figcaption></figure>

### Шаг 3. Подключите способ оплаты к курсу

Для этого перейдите в раздел «Курсы».&#x20;

<figure><img src="https://lh3.googleusercontent.com/_z1bGpj2asCBs4_T_-37ijRohtm8NCxTDF1qF-ikxnWaB-av26zkQGG-cvEmEAAY9XVAin74FFOmf_gthBqsCyFuqfsyBGgFHXks8AA5cbvKjCyli1G93r7k3tMtRJEd1DZoVD6PBqm2joJZZMKG1Fw" alt=""><figcaption></figcaption></figure>

Нажмите «Редактировать курс».

<figure><img src="https://lh4.googleusercontent.com/GMVxg5KmrtR2u37MvPvKMR27c-u8LhvvY0oT0FIf-EgErHIiGjvjYzG-LtBaTAW6ZD9VXNdAtYCpF00RI7KIDctXXmbsrUxYBbWUQ7I9rVNFqLqYo_x2fcL5XddOIMScZsCzdtnkLO5ylHLpNhL8Rvw" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Настройки курса».

<figure><img src="https://lh3.googleusercontent.com/QIH7MZdkzmfY9lO0R2lVZRyPcQ7e-hxJelzY8TMSE0mnKKZE1pF0VxU1zVlW2dArny0z6q9-KSnR52TUHBwkqYkIJC0AdYNFYBUO848JzO5huwHJQkhTNDTUrV9hoA9dMEAecsaQjJ6DSB2JRF8w5Lk" alt=""><figcaption></figcaption></figure>

Найдите блок «Стоимость и оплата» и выберите «Prodamus» в поле «Способ приёма платежей».

<figure><img src="https://lh5.googleusercontent.com/S1jVCJ_d-2DvzQWhfr8OLyZuPQjSOnFwmApG8J_wAayjZkt4fBB_mwUUDGpI3mq1Lc4Eb3qTTe5YqzMIkfFH8C5x6xEH1-btfpWJqHk3J2Im34rcqDmxorqqSWcqwaHX1J941vffFHa_S9PGUgWMrvc" alt=""><figcaption></figcaption></figure>

Опубликуйте курс, чтобы сохранить изменения.

<figure><img src="https://lh6.googleusercontent.com/4i7X6XT_Qz-MoOBmhwu8IqVPKVNHBKSuE3fZJwNtvc5BVPf78_u0lhJwFvEJqwTfg-W-lnfo47fNg8N_JSb7voBxdIEE1URsf-cePyUCVikyHkwCUtVEkUJxfvBnDhLMMr7sHthuBjPfyx5Xg7JAUBo" alt=""><figcaption></figcaption></figure>



Готово: интеграция настроена. Теперь, когда клиент нажмёт кнопку оплаты на сайте вашего курса, его перенаправит на платёжную страницу в Prodamus, где покупателю останется только внести платёж.
