# EdproBiz

EdproBiz — это LMS-платформа для создания и продажи обучающих продуктов. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

{% hint style="info" %}
Временно недоступны рекуррентные платежи
{% endhint %}

## 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Edprobiz нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Edprobiz&#x20;
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Edprobiz&#x20;
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
*   Вставьте адрес _https://school**N**-1.edpro.biz/prodamus-webhook/notification_\
    &#xNAN;_\*где N — ID вашей административной панели_<br>

    <figure><img src="../../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Настройка интеграции на стороне сервиса EdproBiz <a href="#h.eyqodli4fvz" id="h.eyqodli4fvz"></a>

Авторизуйтесь в личном кабинете EdproBiz и перейдите в раздел «Настройки» → «Интеграции».

<figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

Выберите интеграцию с Prodamus и нажмите «Настроить».

<figure><img src="../../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Укажите в поле «Ссылка» адрес вашей платёжной страницы.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Нажмите «Подключить».

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Создание способа оплаты <a href="#h.xq1apzp8yd5j" id="h.xq1apzp8yd5j"></a>

Перейдите в «Настройки» → «Способы оплаты».

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

Нажмите «Создать способ оплаты».

<figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

* Выберите проект, для которого создаётся способ оплаты
* Укажите способ оплаты «Продамус»
* В поле «Печать чека» выберите «Без чека»
* В поле «Комиссия» впишите значение «0». Корректный размер комиссии будет автоматически передаваться через Prodamus

<figure><img src="https://lh5.googleusercontent.com/1FE-mcM8smi5VuxOb-cFNhqhybPUiCO1rXuhCX2XeXVncRHe7wK4QcN1amQpylioa2Nxh_7kIYc6dqDdATD8lBy9_jSs4rQJAgriN_gQzqJTW17wH5AHx6B1JGaUIUdPg0IyBgdKs1oz_f4BT8-xArw" alt=""><figcaption></figcaption></figure>

Нажмите «Создать».

<figure><img src="https://lh5.googleusercontent.com/DmNsaHpQm-xSDGi3lljXyz7XLJueWa8StLRAl8cPNf8PvZUb4_ZoQdGX7EE76OMJdolodBVM5Pu8nqX2Obfo-m7DqkYowOuLsOvHt00Lm9YJPRlbryrryEKrEde5sZXvKx84D8BGXQYQ8-EkY_8JYLI" alt=""><figcaption></figcaption></figure>

### Шаг 4. Подключите способ оплаты к торговой позиции&#x20;

Для этого откройте раздел «Продажи» и перейдите во вкладку «Позиции».

<figure><img src="https://lh6.googleusercontent.com/C6Z9SxGzJ6s9AjHjqzuqp2kP5vpbDCXsiFgrEe1cH6xQW2mPnY7PP4fQum0Bw_QFHgFcIWfsS8-FvE9z31tTPGCv-xizVyUg9davUMhiMv3lRpmP8f4Zg5_iv8vV9HEXBCNPITnQNfJk4cnGqpmlOv4" alt=""><figcaption></figcaption></figure>

Откройте карточку нужного продукта и перейдите во вкладку «Способы оплаты».

<figure><img src="https://lh5.googleusercontent.com/gm5XmTBt-tcd_rDvxWB093UNmx6sbQHxalGE_WDiewaO9V38P9nzMb7MnRPYlEzCYvJlmuqXGoFA1E0fR8jXfJCMYWu-5rxtEFCG9LUu8rXwroXAcXCLBlGTCrxm5utBLN1cWEu3tkoL9F-LRnWEV7Q" alt=""><figcaption></figcaption></figure>

Отметьте галочкой способ оплаты «Продамус» и нажмите «Сохранить».&#x20;

<figure><img src="https://lh3.googleusercontent.com/ihyOD4y1p1I4Pi4Q4c6bbRAsxnPWcAQMzItAXNIxVoER_RKGDVN9jec0qvQeWcss7oT3X7odSrHZZpb8YbiHT00gMo9g1JM3SFaHqfCOVjCXxlw_JZHkB4julCnszGuuxbEXCMI_yf64E_tKScosgsw" alt=""><figcaption></figcaption></figure>

### Шаг 5. Создайте заказ и отправьте ссылку на оплату клиенту

Для этого выберите «Продажи» и откройте раздел «Заказы».

<figure><img src="../../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

Нажмите «Создать заказ».&#x20;

<figure><img src="../../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

Выберите клиента, который будет оплачивать заказ.

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

Выберите ваш продукт в поле «Позиции».

<figure><img src="../../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

Нажмите «Создать заказ».

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

После этого автоматически откроется карточка созданного заказа. Нажмите в ней на кнопку «Ссылка на оплату».

<figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

Скопируйте ссылку на оплату из адресной строки браузера и отправьте её клиенту. Когда клиент перейдёт по ней, ему нужно будет выбрать способ оплаты «Продамус» и внести платёж.&#x20;

<figure><img src="https://lh4.googleusercontent.com/GiCb5b50btl2_65KFX0wzFbq-kFbsSUspvtwyVjT2DMlXyMfPSMfseF5cr8obNfxI1aCbpUYgdmKQlt4abNn8OAhTS4YM0cXFP2iKdi3W8G2ivLCsIrntgypy5ehbKtph2Z79QXzP-Y7KyxLSz2XvTg" alt=""><figcaption></figcaption></figure>
