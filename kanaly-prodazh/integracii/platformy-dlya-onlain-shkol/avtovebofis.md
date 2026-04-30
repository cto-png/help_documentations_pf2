# АвтоВебОфис

«АвтоВебОфис» — платформа для продаж онлайн-курсов и управления онлайн-школой. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### Шаг 1. Настройте интеграцию на стороне Prodamus <a href="#h.sa3zscu9q3rx" id="h.sa3zscu9q3rx"></a>

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес https://<mark style="background-color:yellow;">name</mark>.autoweboffice.ru/?r=api/ps/prodamus. Вместо <mark style="background-color:yellow;">name</mark> нужно указать идентификатор вашей учётной записи.
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Идентификатор можно посмотреть в личном кабинете «АвтоВебОфис» в разделе «Настройки» → «Основные настройки».

<figure><img src="../../../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Сохранить».

Затем нужно получить секретный ключ:

* Откройте канал продаж, который хотите интегрировать с внешним сервисом
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию <a href="#h.z8v68kwvzzrt" id="h.z8v68kwvzzrt"></a>

Для этого авторизуйтесь в личном кабинете «АвтоВебОфис» и перейдите в «Настройки» → «Продажи» → «Способы оплаты».

<figure><img src="../../../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

Выберите «Продамус».

<figure><img src="../../../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

Отметьте галочкой настройку «Используется».

<figure><img src="../../../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

Придумайте название способа оплаты. Оно будет отображаться для покупателей.

<figure><img src="../../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

Укажите ссылки, на которые будут перенаправляться покупатели при успешной и неудачной оплате заказа.

<figure><img src="../../../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="../../../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

Укажите адрес вашей платёжной страницы в Prodamus.

<figure><img src="../../../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Описание и логотип».

<figure><img src="../../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

Если вам не подходит стандартное лого метода оплаты, вы можете заменить его на своё. Для этого нажмите «Выбрать файл» и загрузите изображение со своего компьютера. Ширина картинки не должна превышать 98 пикселей.

<figure><img src="../../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

Придумайте для метода оплаты описание. Его будут видеть покупатели.

<figure><img src="../../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

Если вы хотите оставить для покупателей инструкцию по оплате заказа, поставьте галочку в поле «Показывать инструкцию для клиента». Вставьте инструкцию в текстовую форму.

<figure><img src="../../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Условия показа».

<figure><img src="../../../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

Укажите для способа оплаты минимальную и максимальную сумму. Если сумма заказа не будет соответствовать указанным лимитам, то клиент не сможет оплатить заказ через Prodamus.

<figure><img src="../../../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

✅ Укажите в поле «Заказ состоит только из указанных товаров» список товаров, на которые **будет** распростроняться оплата через Prodamus.

❌ Укажите в поле «В заказе нет ни одного из указанных товаров» список товаров, на которые **не будет** распростроняться оплата через Prodamus.

<figure><img src="../../../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Скидки».

<figure><img src="../../../.gitbook/assets/image (139).png" alt=""><figcaption></figcaption></figure>

Если вы хотите, чтобы ваши клиенты получали скидку при оплате через Prodamus, поставьте галочку в поле «Использовать дополнительную скидку при оплате этой платёжной системой». Установить размер скидки можно в процентах или в валюте («Сумма»).

<figure><img src="../../../.gitbook/assets/image (140).png" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="../../../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена. Теперь, когда клиент при оформлении заказа введёт свои данные и нажмёт на кнопку оплаты, его перенаправит на платёжную страницу в Prodamus, где покупателю останется только внести платёж.
