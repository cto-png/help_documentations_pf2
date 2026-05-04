# Torrow

Torrow — это платформа для автоматизации клиентских сервисов, записи на услуги и управления бизнес-процессами. Интеграция с Prodamus позволяет клиентам оплачивать услуги в несколько кликов через вашу платёжную страницу. Это упрощает процесс записи, повышает конверсию и делает взаимодействие с вашим сервисом более удобным. Ниже — пошаговая инструкция по настройке интеграции.

### Шаг 1. Собираем данные и производим настройки на стороне Продамуса&#x20;

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Torrow нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Torrow
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Torrow
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
* Вставьте адрес [https://torrow.net/payments/hooks/prodamus](https://torrow.net/payments/hooks/prodamus)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию

Для этого авторизуйтесь в личном кабинете Torrow и перейдите в необходимый раздел.

<figure><img src="../../../.gitbook/assets/1 (29).png" alt=""><figcaption></figcaption></figure>

Создайте ресурс.

<figure><img src="../../../.gitbook/assets/2 (25).png" alt=""><figcaption></figcaption></figure>

Укажите название «Продамус» в поле «Название».&#x20;

<figure><img src="../../../.gitbook/assets/3 (22).png" alt=""><figcaption></figcaption></figure>

Выберите «Оплата» в поле «Тип использования».

<figure><img src="../../../.gitbook/assets/4 (23).png" alt=""><figcaption></figcaption></figure>

Выберите «Prodamus» в поле «Тип оплаты».

<figure><img src="../../../.gitbook/assets/5 (23).png" alt=""><figcaption></figcaption></figure>

Укажите ссылку на вашу платёжную страницу в Prodamus.

<figure><img src="../../../.gitbook/assets/6 (18).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="../../../.gitbook/assets/7 (16).png" alt=""><figcaption></figcaption></figure>

Активируйте «Тестовый аккаунт», если необходимо проверить оплату в тестовом режиме.

<figure><img src="../../../.gitbook/assets/8 (15).png" alt=""><figcaption></figcaption></figure>

Придумайте комментарий к оплате.

<figure><img src="../../../.gitbook/assets/9 (12).png" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="../../../.gitbook/assets/10 (17).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Добавьте оплату <a href="#id-dokumentaciya-shag3.dobavteoplatu" id="id-dokumentaciya-shag3.dobavteoplatu"></a>

Откройте нужную услугу/событие и нажмите «Изменить».

<figure><img src="../../../.gitbook/assets/11 (11).png" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Способы оплаты».

<figure><img src="../../../.gitbook/assets/12 (9).png" alt=""><figcaption></figcaption></figure>

Выберите способ оплаты «Продамус» и нажмите кнопку сохранения.

<figure><img src="../../../.gitbook/assets/13 (5).png" alt=""><figcaption></figcaption></figure>

Сохраните услугу/событие.

<figure><img src="../../../.gitbook/assets/14 (5).png" alt=""><figcaption></figcaption></figure>



Готово! Интеграция настроена. Теперь вы сможете принимать оплату за услуги и события через платёжную страницу в Prodamus.&#x20;
