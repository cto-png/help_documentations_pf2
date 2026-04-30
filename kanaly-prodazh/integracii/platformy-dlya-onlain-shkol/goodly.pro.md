# GOODLY.PRO

Goodly.pro — платформа для размещения интернет-магазина, в которой можно создавать и продавать обучающие курсы, тренинги, вебинары и email-рассылки. Вы можете подключить к платформе интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе GOODLY.PRO нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с GOODLY.PRO
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с GOODLY.PRO
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию

Перейдите в личный кабинет Goodly.pro, откройте «Способы оплаты» и нажмите «Добавить способ».&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeJZqgcjCCR3gWviCOkBqRpDVGuMMJEZ40XHBvNBjp24fIjKGie_icN9rrR9NDCHIQJEsK3exQmi8I1pH1n9YvN7Rk42F8Fny6p2Bt7YBOE8RZRVFALyw0-6OldJVK0fko20VN22HEKlwpnKUrl2K5L3O6N?key=abwiSabZdf9gezyM07zsmAnA" alt=""><figcaption></figcaption></figure>

Заполните поля:&#x20;

* **«Платёжная система».** Выберите «Продамус»
* **«Название».** Придумайте наименование способа оплаты, его будут видеть клиенты при оформлении заказа
* **«Процент комиссии».** Комиссия устанавливается на ваше усмотрение. Эта опция работает, если в общих настройках магазина комиссия возлагается на покупателя
* **«Категория и способ оплаты».** Выберите, как клиенты будут оплачивать заказ
* **«Ссылка на страницу оплаты».** Укажите ссылку на вашу платёжную страницу в Prodamus
* **«Секретный ключ».** Вставьте токен, который вы ранее скопировали из личного кабинета Prodamus

Нажмите кнопку «Добавить способ оплаты и продолжить».&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcoRsvHPxb-BOVUmzIn9HYQHq0aTSMhqYXIj7r74ptc8pz63UuMjM54P9bSzGsc04j_9ObzkXIP1vXjFQL11IpD7ilguucAwZV_eRLo36DO9kVU9jnEFbjx0R4FAqPioiLmCmt1TTB16_N6J4f3_MKpgePb?key=abwiSabZdf9gezyM07zsmAnA" alt=""><figcaption></figcaption></figure>

Скопируйте ссылку для HTTP-уведомлений в Goodly.pro.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdgreofqytuRYZrhKCQ1OkB9vJ6_IiQFUWoJuE8P3wMt9QkPeZHFqYFJcifNbs_HntjW-uPdhmocWduDso7XfNkzb6xLS0H-wvd8luEUoFIA-_EFwjMoY3C-GbBrzD5epvR8kE8aruJc6wKdF-FyWLcB146?key=abwiSabZdf9gezyM07zsmAnA" alt=""><figcaption></figcaption></figure>

### Шаг 3. Настройте отправку уведомлений

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес, полученный в настройках GOODLY.PRO
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>



Готово: интеграция настроена. Теперь ваши клиенты смогут оплачивать заказы в Goodly.pro через платёжную страницу в Prodamus.
