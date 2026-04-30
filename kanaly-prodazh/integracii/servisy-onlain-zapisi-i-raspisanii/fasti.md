# Фасти

Фасти — сервис умного планирования рабочего времени.&#x20;Организуем онлайн-запись, напоминаем о встречах&#x20;и помогаем следить за уровнем стресса.

### Шаг 1. Собираем данные и производим настройки на стороне Продамуса&#x20;

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Фасти нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Фасти
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Фасти
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Если у вас уже настроен адрес для уведомлений об оплате на другой url, то этот блок можно пропустить и сразу перейти к следующему шагу настройки интеграции
{% endhint %}

Далее добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://api.fasti.me/api/v4-b2p/prodamus/webhook/payment](https://api.fasti.me/api/v4-b2p/prodamus/webhook/payment)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию

Для этого авторизуйтесь в личном кабинете Фасти и перейдите на вкладку «Интеграции».

<figure><img src="../../../.gitbook/assets/1 (25).png" alt=""><figcaption></figcaption></figure>

Откройте раздел «Продамус».

<figure><img src="../../../.gitbook/assets/2 (23).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Подключить»

<figure><img src="../../../.gitbook/assets/3 (20).png" alt=""><figcaption></figcaption></figure>

У вас откроются настройки интеграции, где необходимо будет ввести следующие данные:

1\) Имя способа оплаты

<figure><img src="../../../.gitbook/assets/4 (21).png" alt=""><figcaption></figcaption></figure>

2\) Ссылку на платежную страницу

<figure><img src="../../../.gitbook/assets/5 (21).png" alt=""><figcaption></figcaption></figure>

3\) Секретный ключ

<figure><img src="../../../.gitbook/assets/6 (16).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Добавьте оплату <a href="#id-dokumentaciya-shag3.dobavteoplatu" id="id-dokumentaciya-shag3.dobavteoplatu"></a>

Перейдите на вкладку «Встречи»

<figure><img src="../../../.gitbook/assets/7 (14).png" alt=""><figcaption></figcaption></figure>

Выберите тип встречи

<figure><img src="../../../.gitbook/assets/8 (13).png" alt=""><figcaption></figcaption></figure>

Укажите название встречи

<figure><img src="../../../.gitbook/assets/9 (10).png" alt=""><figcaption></figcaption></figure>

Укажите адрес встречи

<figure><img src="../../../.gitbook/assets/10 (15).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Далее»

<figure><img src="../../../.gitbook/assets/11 (9).png" alt=""><figcaption></figcaption></figure>

Настройте встречу, включите настройку «Включить оплату через Продамус» и укажите цену

<figure><img src="../../../.gitbook/assets/12 (7).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Далее»

<figure><img src="../../../.gitbook/assets/13 (3).png" alt=""><figcaption></figcaption></figure>

Выберите расписание для встречи, либо создайте новое и нажмите кнопку «Создать тип события»

<figure><img src="../../../.gitbook/assets/14 (3).png" alt=""><figcaption></figcaption></figure>



Готово! Интеграция настроена. Теперь вы сможете принимать оплату за встречи через платёжную страницу в Prodamus.&#x20;
