# Multy.Ai

**Multy.Ai** — это платформа для создания универсальных AI-агентов и мультиканальных чат-ботов для бизнеса в Telegram, WhatsApp, Instagram и на сайтах. Вы можете разрабатывать интеллектуальных ассистентов без кода и технических специалистов: настраивать многопользовательские режимы, автоматические сценарии поддержки, сбор лидов, аналитику диалогов и продажи через любой мессенджер. Боты интегрируются с CRM, платежными системами, ChatGPT и корпоративными базами знаний. Ниже — инструкция по настройке.

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Multy.Ai нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Multy.Ai
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Multy.Ai
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Multy.Ai

Перейдите на страницу «Интеграции» и выберите в платежных системах «Prodamus»

<figure><img src="../../../.gitbook/assets/1 (20).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Добавить»

<figure><img src="../../../.gitbook/assets/2 (19).png" alt=""><figcaption></figcaption></figure>

В поле «Имя аккаунта (поддомена)» вставьте поддомен адреса платежной страницы, ранее полученный в личном кабинете Продамус. Например, если домен равен <mark style="background-color:orange;">demo.payform.ru</mark>, то необходимо вставить только <mark style="background-color:orange;">demo</mark>

<figure><img src="../../../.gitbook/assets/3 (16).png" alt=""><figcaption></figcaption></figure>

В поле «Секретный ключ» вставьте скретный ключ, ранее созданный в личном кабинете Продамус.

<figure><img src="../../../.gitbook/assets/4 (17).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Сохранить»

<figure><img src="../../../.gitbook/assets/5 (17).png" alt=""><figcaption></figcaption></figure>

Откройте сохранившийся метод оплаты, спуститесь в самый низ и скопируйте ссылку из поля «Webhook URL для настройки уведомлений»

<figure><img src="../../../.gitbook/assets/12 (5).png" alt=""><figcaption></figcaption></figure>

Вернитесь в личный кабинет Продамус, откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес, полученный в Multy.Ai&#x20;
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### 3. Настройка Блок-схемы для отправки оплаты

Перейдите на страницу «Блок-схемы» и нажмите кнопку «Добавить схему»

<figure><img src="../../../.gitbook/assets/6 (13).png" alt=""><figcaption></figcaption></figure>

В поиске введите «prodamus» и выберите блок-схему «Оплаты в Prodamus»

<figure><img src="../../../.gitbook/assets/7 (11).png" alt=""><figcaption></figcaption></figure>

Откройте созданную блок-схему, найдите блок «Создать заказ» и выберите продкут, который хотите продавать через Продамус

<figure><img src="../../../.gitbook/assets/8 (10).png" alt=""><figcaption></figcaption></figure>

Далее найдите блок «Создать ссылку» и выберите ранее добавленный метод оплаты

<figure><img src="../../../.gitbook/assets/9 (8).png" alt=""><figcaption></figcaption></figure>

Затем найдите блок «Переключить интеграцию» и выберите нужного вам бота

<figure><img src="../../../.gitbook/assets/10 (13).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Включить»

<figure><img src="../../../.gitbook/assets/11 (7).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Multy.Ai!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
