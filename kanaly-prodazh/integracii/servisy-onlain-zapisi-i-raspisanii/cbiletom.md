# CBiletom

**Cbiletom.ru** — это онлайн-сервис для покупки, продажи и переоформления билетов на концерты, в театры, на спортивные события и фестивали. Вы можете подобрать билеты прямо с телефона без очередей и посредников: фильтровать по дате, ценовому диапазону, сектору зала, а также предлагать свои билеты другим пользователям. Сервис интегрируется с популярными платежными системами, электронными билетами и API концертных площадок. Ниже — инструкция по настройке.

### Шаг 1. Собираем данные и производим настройки на стороне Продамуса&#x20;

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе CBiletom нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с CBiletom
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с CBiletom
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
* Вставьте адрес [https://cbiletom.ru/api/payments/prod.php](https://cbiletom.ru/api/payments/prod.php)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Настройка интеграции на стороне CBiletom

Перейдите на страницу «События», отредактируйте нужное Вам событие или создайте новое

<figure><img src="../../../.gitbook/assets/1 (3).png" alt=""><figcaption></figcaption></figure>

Введите название вашего события

<figure><img src="../../../.gitbook/assets/2 (3).png" alt=""><figcaption></figcaption></figure>

Выберите дату вашего события

<figure><img src="../../../.gitbook/assets/3 (3).png" alt=""><figcaption></figcaption></figure>

Настройте время проведения события

<figure><img src="../../../.gitbook/assets/4 (2).png" alt=""><figcaption></figcaption></figure>

Выберите место проведения события

<figure><img src="../../../.gitbook/assets/5 (2).png" alt=""><figcaption></figcaption></figure>

Нажмите на кнопку «Добавить тип оплаты»

<figure><img src="../../../.gitbook/assets/6 (2).png" alt=""><figcaption></figcaption></figure>

Выберите «Продамус» в поле «Платежная система»&#x20;

<figure><img src="../../../.gitbook/assets/7 (2).png" alt=""><figcaption></figcaption></figure>

Вставьте ссылку на платежную форму, полученную в личном кабинете Продамуса

<figure><img src="../../../.gitbook/assets/8 (1).png" alt=""><figcaption></figcaption></figure>

В поле «Секретный ключ» вставьте секретный ключ, созданный в личном кабинете Продамуса

<figure><img src="../../../.gitbook/assets/9.png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Сохранить»

<figure><img src="../../../.gitbook/assets/10.png" alt=""><figcaption></figcaption></figure>

Сохраните настройки события

<figure><img src="../../../.gitbook/assets/11.png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе CBiletom!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
