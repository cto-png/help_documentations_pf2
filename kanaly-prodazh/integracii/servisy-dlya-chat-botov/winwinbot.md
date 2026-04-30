# WinWinBot

WinWinBot – конструктор чат-ботов для онлайн-школ.

### Настройки интеграции

Откройте раздел «Платежи и заявки», далее перейдите на вкладку «Прием платежей» и нажмите кнопку «Создать интеграцию»

<div><figure><img src="../../../.gitbook/assets/13.jpg" alt=""><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/1 (16).png" alt=""><figcaption></figcaption></figure></div>

На следующем экране укажите произвольное название интеграции и выберите платежную систему Prodamus из списка платежных агрегаторов:

<figure><img src="../../../.gitbook/assets/2 (16).png" alt=""><figcaption></figcaption></figure>

У вас откроется 2 дополнительные настройки, где нужно указать Домен и Секретный ключ.

Домен — это ваша платежная страница в Prodamus: &#x20;

* Откройте канал продаж, который хотите интегрировать c WinWinBot
* Скопируйте домен платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Чтобы получить секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с WinWinBot
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

Введите домен и секретный ключ в WinWinBot и нажмите «Сохранить»:

<figure><img src="../../../.gitbook/assets/3 (13).png" alt=""><figcaption></figcaption></figure>

Интеграция создана, теперь вам нужно скопировать полученный в WinWinBot адрес для уведомлений:

<figure><img src="../../../.gitbook/assets/4 (14).png" alt=""><figcaption></figcaption></figure>

Далее добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес, полученный от WinWinBot
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Интеграция завершена.

### Отправка оплаты

Чтобы отправить подписчику сообщение в чат-бот с оплатой:

* Откройте раздел «Платежи и заявки», далее перейдите на вкладку «Каталог товаров» и нажмите кнопку «Создать товар»

<figure><img src="../../../.gitbook/assets/5 (14).png" alt=""><figcaption></figcaption></figure>

* Укажите название товара, его фото, цену и выберите платежную интеграцию с Prodamus, которую вы только что создали.

<figure><img src="../../../.gitbook/assets/6 (11).png" alt=""><figcaption></figcaption></figure>

* Теперь вы можете отправлять этот товар в любой рассылке в вашем боте. Создайте новую рассылку (любого типа) и добавьте к сообщению кнопку -> «Кнопка со ссылкой на покупку товара»

<figure><img src="../../../.gitbook/assets/8 (8).png" alt=""><figcaption></figcaption></figure>

* В мессенджере такая рассылка будет выглядеть так:

<figure><img src="../../../.gitbook/assets/9 (7).png" alt=""><figcaption></figcaption></figure>

\
И переход по кнопке будет открывать страницу оплаты:

<figure><img src="../../../.gitbook/assets/10 (12).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
