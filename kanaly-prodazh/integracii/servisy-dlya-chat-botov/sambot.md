# SamBot

Sambot — это платформа для создания чат-ботов, автоворонок и автоматизации бизнес-процессов. Вы можете подключить к сервису интеграцию с платежными системами и принимать оплату от клиентов через бота. Ниже — инструкция, как всё настроить.

{% hint style="info" %}
При [регистрации](https://connect.prodamus.ru/?ref=SAMBOT) в Продамусе, можете указать промокод SAMBOT для скидки 2000 рублей &#x20;
{% endhint %}

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе SamBot нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с SamBot
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с SamBot
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### 2. Настройки платежного метода в SamBot

Перейдите в раздел Приём платежей и добавьте новый способ приёма платежей.

<figure><img src="../../../.gitbook/assets/1 (8).png" alt=""><figcaption></figcaption></figure>

* Выберите в качестве Платёжной системы Prodamus.

<figure><img src="../../../.gitbook/assets/2 (8).png" alt=""><figcaption></figcaption></figure>

* Укажите Заголовок на своё усмотрение.

<figure><img src="../../../.gitbook/assets/3 (7).png" alt=""><figcaption></figcaption></figure>

* Укажите URL-адрес платёжной формы, который вы ранее скопировали

<figure><img src="../../../.gitbook/assets/4 (6).png" alt=""><figcaption></figcaption></figure>

* Укажите Секретный ключ, который вы ранее скопировали

<figure><img src="../../../.gitbook/assets/5 (6).png" alt=""><figcaption></figcaption></figure>

* Выберите нужную валюту

<figure><img src="../../../.gitbook/assets/6 (5).png" alt=""><figcaption></figcaption></figure>

* Выберите автоматическую обработку платежей.

<figure><img src="../../../.gitbook/assets/7 (5).png" alt=""><figcaption></figcaption></figure>

* Нажмите кнопку "Добавить".

<figure><img src="../../../.gitbook/assets/8 (3).png" alt=""><figcaption></figcaption></figure>

### 3. Настройка Реакции для отправки оплаты

Перейдите в ту Реакцию, которая должна запустить приём оплаты через систему Продамус.

<figure><img src="../../../.gitbook/assets/9 (2).png" alt=""><figcaption></figcaption></figure>

* Добавьте текст призывы к действию.

<figure><img src="../../../.gitbook/assets/10 (2).png" alt=""><figcaption></figcaption></figure>

* Добавьте кнопку с призывом к действию.

<figure><img src="../../../.gitbook/assets/11 (2).png" alt=""><figcaption></figcaption></figure>

Введите текст сообщения и нажмите "Добавить кнопку"

<figure><img src="../../../.gitbook/assets/12.png" alt=""><figcaption></figcaption></figure>

Выберите тип кнопки (слева от текста кнопки)

<figure><img src="../../../.gitbook/assets/13.png" alt=""><figcaption></figcaption></figure>

* Укажите текст на кнопке.

<figure><img src="../../../.gitbook/assets/14.png" alt=""><figcaption></figcaption></figure>

* Выберите из имеющихся у вас способов оплаты тот, который вы настроили на систему Продамус.

<figure><img src="../../../.gitbook/assets/15.png" alt=""><figcaption></figcaption></figure>

* Укажите сумму оплаты.

<figure><img src="../../../.gitbook/assets/16.png" alt=""><figcaption></figcaption></figure>

* Укажите назначение платежа.

<figure><img src="../../../.gitbook/assets/17.png" alt=""><figcaption></figcaption></figure>

* Выберите Реакцию, которая должна запуститься при успешной оплате.

<figure><img src="../../../.gitbook/assets/18.png" alt=""><figcaption></figcaption></figure>

* При необходимости можете назначить покупателю метки или указать данные в персональные параметры.
* Сохраните настройки

<figure><img src="../../../.gitbook/assets/19.png" alt=""><figcaption></figcaption></figure>

* Нажмите кнопку "Добавить"

<figure><img src="../../../.gitbook/assets/20.png" alt=""><figcaption></figcaption></figure>

* Сохраните настройки Реакции

<figure><img src="../../../.gitbook/assets/21.png" alt=""><figcaption></figcaption></figure>

Обязательно самостоятельно протестируйте оплату через бота!



Готово! Теперь Продамус готов принимать платежи в сервисе SamBot!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
