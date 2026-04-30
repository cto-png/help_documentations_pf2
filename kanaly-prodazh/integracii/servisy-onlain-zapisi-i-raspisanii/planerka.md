# Планерка

Планерка — это конструктор онлайн-записи для экспертов, коучей и психологов. Вы можете настроить страницу записи без кода и программистов: синхронизировать календарь, принимать оплату, автоматически создавать ссылки на Zoom, рассылать напоминания в Telegram и почту, а также встроить виджет на сайт. Сервис подключается к платежным системам, Google и Яндекс.Календарю. Ниже — инструкция по настройке.

{% hint style="info" %}
При [регистрации](https://connect.prodamus.ru/?ref=PLANERKA) в Продамусе, можете указать промокод PLANERKA для получения особых условий&#x20;
{% endhint %}

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать
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
* Вставьте адрес [https://te2c.planerka.app/prodamus/callback/](https://te2c.planerka.app/prodamus/callback/)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Планерке

Перейдите на страницу «Интеграции»

<figure><img src="../../../.gitbook/assets/1 (4).png" alt=""><figcaption></figcaption></figure>

Найдите блок «Дополнительные приложения» и нажмите на «Продамус»

<figure><img src="../../../.gitbook/assets/2 (4).png" alt=""><figcaption></figcaption></figure>

Откроется страница с подключением платежного метода, нажмите кнопку «Подключить»

<figure><img src="../../../.gitbook/assets/3 (4).png" alt=""><figcaption></figcaption></figure>

Вставьте  адрес платежной страницы, который ранее скопировали из личного кабинета, в поле «Ссылка на вашу платежную форму Продамус»

<figure><img src="../../../.gitbook/assets/4 (3).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который ранее создали в личном кабинете, в поле «Секретный ключ Продамус»

<figure><img src="../../../.gitbook/assets/5 (3).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Подключить»

<figure><img src="../../../.gitbook/assets/6 (3).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Добавьте оплату <a href="#id-dokumentaciya-shag3.dobavteoplatu" id="id-dokumentaciya-shag3.dobavteoplatu"></a>

Выберите нужную встречу и нажмите «Редактировать»

<figure><img src="../../../.gitbook/assets/7 (3).png" alt=""><figcaption></figcaption></figure>

Найдите блок «Сделать встречу платной»

<figure><img src="../../../.gitbook/assets/8 (2).png" alt=""><figcaption></figcaption></figure>

Включите прием платежей через Продамус

<figure><img src="../../../.gitbook/assets/9 (1).png" alt=""><figcaption></figcaption></figure>

Укажите стоимость встречи

<figure><img src="../../../.gitbook/assets/10 (1).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Сохранить»

<figure><img src="../../../.gitbook/assets/11 (1).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Планерка!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
