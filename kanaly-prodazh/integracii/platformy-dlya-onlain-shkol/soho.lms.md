# SOHO.LMS

Интеграция с сервисом SOHO.LMS позволяет принимать оплату от клиентов через платёжную страницу Prodamus. Ниже — инструкция, как всё настроить.

### Шаг 1. Создайте секретный ключ в личном кабинета Prodamus

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настройки интеграций Prodamus c SOHO.LMS вам понадобится API-ключ. Чтобы получить его:

* Откройте канал продаж, который хотите интегрировать с внешним сервисом
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Авторизуйтесь в личном кабинете SOHO.LMS и перейдите в раздел «Настройки» → «Приём платежей» <a href="#h.p04627ijx4u9" id="h.p04627ijx4u9"></a>

<figure><img src="../../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

Выберите в каталоге юридических лиц вашу компанию.

<figure><img src="../../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

Выберите «Prodamus. PayForm» в блоке «Способы получения оплаты».

<figure><img src="../../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Настройте интеграцию <a href="#h.tduuoa5x7n1d" id="h.tduuoa5x7n1d"></a>

Укажите в поле «Host» название вашей платёжной страницы. Например, если бы URL-адрес вашей платёжной страницы был name.payform.ru, то в этом поле нужно было бы указать только name.

<figure><img src="../../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

Вставьте в поле «Секретный ключ» токен, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="../../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

Отметьте методы оплаты, которые будут доступны вашим клиентам при оформлении заказа.

<figure><img src="../../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

Нажмите «Добавить».

<figure><img src="../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена. Теперь, когда клиент будет оформлять заказ, его оплата будет проходить через вашу платёжную страницу в Prodamus.

<figure><img src="../../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>
