# Wordpress

Если ваш сайт сделан на WordPress, вы можете подключить к нему возможность оплачивать заказы через Prodamus. Ниже — инструкция, как всё настроить.

### Шаг 1. Установите плагин WooCommerce <a href="#h.4ijrelffckzn" id="h.4ijrelffckzn"></a>

Он понадобится, чтобы подключить к сайту возможность совершать оплату через Prodamus. Чтобы установить плагин, авторизуйтесь в личном кабинете WordPress, выберите вкладку «Плагины» и нажмите «Добавить новый».

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Популярные», выберите плагин WooCommerce и нажмите «Установить».

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Установите плагин оплаты Prodamus <a href="#h.9d8bkn952qlj" id="h.9d8bkn952qlj"></a>

Для этого сначала скачайте файл с плагином себе на компьютер.

{% file src="../../../.gitbook/assets/wc-prodamus.zip" %}

Затем в личном кабинете WordPress откройте раздел «Плагины» и нажмите «Добавить новый».

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

Нажмите «Загрузить плагин», загрузите файл с плагином и установите его в WordPress.

<figure><img src="../../../.gitbook/assets/image8.gif" alt=""><figcaption></figcaption></figure>

### Шаг 3. Настройте оплату <a href="#h.71qm26sou4xw" id="h.71qm26sou4xw"></a>

Для этого выберите вкладку «WooCommerce» и нажмите на «Настройки».

<figure><img src="../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Платежи», включите оплату через плагин Prodamus и нажмите на «Управление».

<figure><img src="../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

Включите «Активность способа оплаты», чтобы активировать для клиентов оплату через Prodamus.

<figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

Придумайте название и описание способа оплаты.

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

Укажите в поле «Адрес платёжной страницы» ссылку на вашу платёжную страницу.

<figure><img src="../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ. Его можно найти [в личном кабинете Prodamus](https://help.prodamuspay.ru/~/revisions/4aZT2HbxT10S1SYWoSW0/kanaly-prodazh/integracii/kak-sozdat-sekretnyi-klyuch-dlya-podklyucheniya-integracii)

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

Для корректной работы плагина обязательно установите следующие настройки статусов:

* «Статус заказа» → «В обработке».
* «Статус заказа, из которого можно переходить к оплате» → «Ожидается оплата».

<figure><img src="../../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

Укажите в поле «URL-адрес для возврата пользователя без оплаты» ссылку, по которой будут направляться клиенты при неудачной оплате заказа.

<figure><img src="../../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

Укажите в поле «URL-адрес для возврата пользователя при успешной оплате» ссылку, по которой будут направляться клиенты при успешной оплате заказа.

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

Выберите валюту, в которой будут оплачиваться заказы.

<figure><img src="../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

Нажмите «Сохранить изменения».

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

### Шаг 4. Установите для каждого товара доступные методы оплаты <a href="#h.dqr45lufvy9z" id="h.dqr45lufvy9z"></a>

Перейдите в раздел «Товары».

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

Откройте товар, для которого вы хотите подключить или отключить методы оплаты.

<figure><img src="../../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

Проскорольте страницу вниз и отметьте галочками методы оплаты, которые будут доступны клиентам при покупке продукта.

<figure><img src="../../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

Нажмите «Обновить», чтобы сохранить изменения.

<figure><img src="../../../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>



Готово! Интеграция настроена. Теперь, когда клиент перейдёт в корзину, укажет свои контактные данные и нажмёт на кнопку оформления заказа, откроется платёжная страница Prodamus — и покупателю останется выбрать способ оплаты и оплатить покупку.
