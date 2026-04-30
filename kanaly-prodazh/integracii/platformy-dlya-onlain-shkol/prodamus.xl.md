# Prodamus.XL

Prodamus.XL — платформа для создания онлайн-школ и управления ими. Вы можете подключить к сервису интеграцию со своей платёжной страницей и принимать оплату от клиентов. Ниже — инструкция как всё настроить.

### Шаг 1. Настройте интеграцию на стороне Prodamus <a href="#h.sa3zscu9q3rx" id="h.sa3zscu9q3rx"></a>

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://w.lpxl.ru/checkout-notification/prodamus](https://w.lpxl.ru/checkout-notification/prodamus)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Затем создайте «Секретный ключ»:

* Откройте канал продаж, который хотите интегрировать с Prodamus.XL
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ. Его нужно будет вставить в личном кабинете Prodamus.XL.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>



### Шаг 2. Создайте платёжную интеграцию в личном кабинете Prodamus.XL <a href="#h.564noecsu8yp" id="h.564noecsu8yp"></a>

Для этого перейдите в «Настройки» → «Приём платежей».

<figure><img src="../../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

Нажмите «Создать платёжную интеграцию» и выберите «Продамус».

<figure><img src="../../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

Настройте интеграцию. Заполните поля:

**Название.** Придумайте, как будет называться интеграция.

<figure><img src="../../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

**Описание.** Его будут видеть ваши клиенты при выборе метода оплаты.

<figure><img src="../../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

**Текст кнопки оплаты.** Если вам не подходит стандартное название «Оплатить с Prodamus», придумайте для кнопки оплаты своё название.

<figure><img src="../../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

**Основной способ оплаты.** Если включить эту настройку, платёжный модуль Prodamus будет выделяться среди других методов оплаты в списке интеграций.

<figure><img src="../../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

**Валюта.** Укажите, в какой валюте клиенты будут оплачивать заказы. На выбор доступны рубли, доллары США, евро и тенге.

<figure><img src="../../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Важно!** Чтобы принимать платежи в иностранной валюте, к вашей платёжной странице должен быть подключён международный метод оплаты.
{% endhint %}

**Адрес аккаунта.** Укажите URL-адрес вашей платёжной страницы в Prodamus.

<figure><img src="../../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

**Секретный ключ.** Вставьте токен, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="../../../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

Нажмите «Создать».

<figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена. Теперь, когда клиент введёт свои данные и нажмёт на кнопку оплаты заказа на вашем сайте, его перенаправит на платёжную страницу в Prodamus, где покупателю останется только внести платёж.
