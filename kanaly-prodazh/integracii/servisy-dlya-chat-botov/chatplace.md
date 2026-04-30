# Chatplace

**ChatPlace** — это конструктор чат-ботов и AI-агентов для Instagram и TikTok. Вы можете создавать ботов прямо с телефона без кода и программистов: настраивать автоворонки, геймификацию, массовые рассылки, сбор заявок и продажи через Direct и комментарии. Боты подключаются к платежным системам, CRM и Google Sheets. Ниже — инструкция по настройке.

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Chatplace нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Chatplace
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Chatplace
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Chatplace

Откройте страницу настроек в личном кабинете Chatplace

<figure><img src="../../../.gitbook/assets/1 (19).png" alt=""><figcaption></figcaption></figure>

Перейдите на вкладку «Интеграцию» и выберите «Prodamus»

<figure><img src="../../../.gitbook/assets/2 (18).png" alt=""><figcaption></figcaption></figure>

Заполните поля:

В поле «Ссылка на payform» вставьте ссылку, которую ранее скопировали из личного кабинета продамус

<figure><img src="../../../.gitbook/assets/3 (15).png" alt=""><figcaption></figcaption></figure>

В поле «Секретный ключ» вставьте секретный ключ, который ранее создали в личном кабинете Продамус

<figure><img src="../../../.gitbook/assets/4 (16).png" alt=""><figcaption></figcaption></figure>

Если требуется, настройте остальные поля, они являются необязательными

<figure><img src="../../../.gitbook/assets/5 (16).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Подключить»

<figure><img src="../../../.gitbook/assets/6 (12).png" alt=""><figcaption></figcaption></figure>

### 3. Настройка Автоматизации для отправки оплаты

Откройте страницу «Автоматизации» и выберите автоматизацию, отвечающую за оплату

<figure><img src="../../../.gitbook/assets/7 (10).png" alt=""><figcaption></figcaption></figure>

Найдите блок, который отправляет клиенту ссылку на оплату и выберите платежную систему «Prodamus»

<figure><img src="../../../.gitbook/assets/8 (9).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Chatplace!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
