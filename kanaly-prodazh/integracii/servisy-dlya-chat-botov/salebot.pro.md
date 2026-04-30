# Salebot.pro

SaleBot.pro - это многофункциональный мультиканальный конструктор чат-ботов

{% hint style="info" %}
Важно! Доступно только на тарифе "Инфобиз"
{% endhint %}

### Как подключить Продамус

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для подключения Prodamus Вам понадобятся URL-платежной формы и секретный ключ.

* Откройте канал продаж, который хотите интегрировать с SaleBot
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ можно получить в личном кабинете:

* Откройте канал продаж, который хотите интегрировать с SaleBot
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

Адрес для уведомлений: **https://chatter.salebot.pro/prodamus\_callback/result**

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://chatter.salebot.pro/prodamus\_callback/result](https://chatter.salebot.pro/prodamus_callback/result)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Для подключения Prodamus необходимо перейти в раздел "Эквайринг"

<figure><img src="../../../.gitbook/assets/1 (12).png" alt=""><figcaption></figcaption></figure>

Далее необходимо просто указать данные, о которых говорили выше, в форму:

<figure><img src="../../../.gitbook/assets/2 (12).png" alt=""><figcaption></figcaption></figure>

Форма платежной системы "Продамус" в разделе "Эквайринг"

> **ВАЖНО!** url - платежной формы указываем **БЕЗ https://**



Готово! Подробнее по настройке SaleBot можете прочитать тут [SaleBot.pro | Prodamus Как сформировать ссылку на оплату](https://docs.salebot.pro/integracii/platezhnye-sistemy/platezhnaya-sistema-prodamus-prodamus#kak-sformirovat-ssylku-na-oplatu)

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
