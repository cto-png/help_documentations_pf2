# Smartbotpro

**Smartbot Pro** — это платформа для создания чат-ботов и ИИ-ассистентов с визуальным конструктором и встроенными интеграциями. Вы можете автоматизировать продажи и поддержку без кода: настраивать сценарии по триггерам, подключать Telegram WebApp-магазин с каталогом и корзиной, обучать ИИ на своих данных (OpenAI/YandexGPT), сегментировать базу и отправлять рассылки. Боты работают в Telegram и VK, интегрируются с CRM, платежными системами, GetCourse и Google Таблицами через API или готовые коннекторы. Ниже — инструкция по настройке.

### Шаг 1. Собираем данные и производим настройки на стороне Продамуса&#x20;

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Smartbotpro нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Smartbotpro
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Smartbotpro
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
* Вставьте адрес [https://auth.smartbotpro.ru/api/users\_payments/callbacks/prodamus](https://auth.smartbotpro.ru/api/users_payments/callbacks/prodamus)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Smartbotpro

Перейдите на страницу «Интеграции»

<figure><img src="../../../.gitbook/assets/1 (30).png" alt=""><figcaption></figcaption></figure>

Найдите платежный метод «Prodamus» и нажмите кнопку «Перейти»

<figure><img src="../../../.gitbook/assets/2 (26).png" alt=""><figcaption></figcaption></figure>

Введите домен платежной формы

{% hint style="info" %}
Например, если у вас адрес https://<mark style="background-color:orange;">edu2</mark>.payform.ru/, то необходимо ввести только <mark style="background-color:orange;">edu2</mark>
{% endhint %}

<figure><img src="../../../.gitbook/assets/3 (23).png" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, ранее скопированный из настроек платежной формы

<figure><img src="../../../.gitbook/assets/4 (24).png" alt=""><figcaption></figcaption></figure>

Нажмите кнопку «Сохранить»

<figure><img src="../../../.gitbook/assets/5 (24).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Smartbotpro!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
