# Emdesell

Emdesell — это конструктор онлайн-школ и платформа для создания, продажи и упаковки курсов. Вы можете запускать обучение без программистов: добавлять видео, тесты, домашние задания, выдавать сертификаты и настраивать автоворонки. Сервис интегрируется с платежными системами, Email, Telegram, VK, а также защищает контент от пиратов. Ниже — инструкция по настройке.

{% hint style="info" %}
При [регистрации](https://connect.prodamus.ru/?ref=Emdesell) в Продамусе, можете указать промокод Emdesell для получения особых условий&#x20;
{% endhint %}

### 1. Собираем данные на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Emdesell нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Emdesell
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Emdesell
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### 2. Настройка платежного метода в Emdesell

Перейдите на страницу «Настройки» и откройте вкладку «Платежная система» и включите «Внутрисистемные платежи» &#x20;

<figure><img src="../../../.gitbook/assets/1 (6).png" alt=""><figcaption></figcaption></figure>

Выберите платежный метод «Prodamus»

<figure><img src="../../../.gitbook/assets/2 (6).png" alt=""><figcaption></figcaption></figure>

Вставьте  адрес платежной страницы, который ранее скопировали из личного кабинета, в поле «Адрес магазина»&#x20;

<figure><img src="../../../.gitbook/assets/3 (5).png" alt=""><figcaption></figcaption></figure>

Вставсьте секретный ключ, который ранее создали в личном кабинете, в поле  «Секретный ключ»

<figure><img src="../../../.gitbook/assets/4 (4).png" alt=""><figcaption></figcaption></figure>

В разделе «Размер НДС» выберите  «Без НДС»

<figure><img src="../../../.gitbook/assets/5 (4).png" alt=""><figcaption></figcaption></figure>

Включите платежный метод «Prodamus»

<figure><img src="../../../.gitbook/assets/6 (4).png" alt=""><figcaption></figcaption></figure>

Нажмите на кнопку  «Сохранить изменения»

<figure><img src="../../../.gitbook/assets/7 (4).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Emdesell!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
