# Botmaker

Botmaker — это конструктор чат-ботов для Telegram с бесплатным тарифом и широкими маркетинговыми возможностями. Вы можете создавать полноценных ботов прямо в браузере без навыков программирования: настраивать кнопочное меню, товары и услуги, триггерные рассылки, сегментировать пользователей и подключать магазин. Боты интегрируются с CRM (например, amoCRM), аналитикой и UTM-метками. Ниже — инструкция по настройке.

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Botmaker нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Botmaker
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Botmaker
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
* Вставьте адрес [https://app.botmaker.co/](https://app.botmaker.co/)&#x20;
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Botmaker

Перейдите на страницу «Платежные сервисы» и нажмите кнопку «+ Добавить сервис»

<figure><img src="../../../.gitbook/assets/1 (23).png" alt=""><figcaption></figcaption></figure>

В появивишимся платежном методе нажмите кнопку  «Редактировать»

<figure><img src="../../../.gitbook/assets/2 (21).png" alt=""><figcaption></figcaption></figure>

В блоке  «Сервис» выберите платежный метод  «Prodamus»

<figure><img src="../../../.gitbook/assets/3 (18).png" alt=""><figcaption></figcaption></figure>

&#x20;Заполните поле «Название»&#x20;

<figure><img src="../../../.gitbook/assets/4 (19).png" alt=""><figcaption></figcaption></figure>

В поле «Адрес  платежной» вставьте адрес платежной системы, полученный из личного кабинета Продамуса

<figure><img src="../../../.gitbook/assets/5 (19).png" alt=""><figcaption></figcaption></figure>

В поле «Секретный ключ магазина» вставьте секретный ключ, сгенерированный в личном кабинете Продамуса

<figure><img src="../../../.gitbook/assets/6 (15).png" alt=""><figcaption></figcaption></figure>

Нажмите «Проверить интеграцию», чтобы убедиться, что все настроено корреткно

<figure><img src="../../../.gitbook/assets/7 (13).png" alt=""><figcaption></figcaption></figure>

### 3. Добавление метода оплаты в товар

Перейдите на страницу «Товары и услуги», нажмите кнопку «+ Добавить товар или услугу» или выберите уже созданный товар

<figure><img src="../../../.gitbook/assets/8 (12).png" alt=""><figcaption></figcaption></figure>

Введите название товара

<figure><img src="../../../.gitbook/assets/9 (9).png" alt=""><figcaption></figcaption></figure>

В блоке «Оплата» выберите ранее настроенный платежный метод

<figure><img src="../../../.gitbook/assets/10 (14).png" alt=""><figcaption></figcaption></figure>

Укажите стоимость товара

<figure><img src="../../../.gitbook/assets/11 (8).png" alt=""><figcaption></figcaption></figure>

При необходимости добавтие описание для товара или услуги перед покупкой

<figure><img src="../../../.gitbook/assets/12 (6).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Botmaker!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
