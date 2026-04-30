# Tilda.cc

## Собираем данные на стороне Продамуса

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Tilda нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Tilda
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Tilda
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение платёжного модуля Prodamus&#x20;

Переходим в раздел «Настройки сайта»

<figure><img src="../../../.gitbook/assets/1 (21).png" alt=""><figcaption></figcaption></figure>

Далее раздел «Платежные системы»

<figure><img src="../../../.gitbook/assets/2 (20).png" alt=""><figcaption></figcaption></figure>

Прокручиваем вниз и выбираем «Prodamus»

<figure><img src="../../../.gitbook/assets/3 (17).png" alt=""><figcaption></figcaption></figure>

Далее в поле логин вставляем адрес вашей платежной страницы без https://\
Например: demo.payform.ru

<figure><img src="../../../.gitbook/assets/4 (18).png" alt=""><figcaption></figcaption></figure>

Вставляем cекретный ключ, ранее созданный в личном кабинете Продамуса, в поле «Секрет для подписи заказа»

<figure><img src="../../../.gitbook/assets/5 (18).png" alt=""><figcaption></figcaption></figure>

Скопируйте URL-адрес из поля «URL для уведомлений»

<figure><img src="../../../.gitbook/assets/6 (14).png" alt=""><figcaption></figcaption></figure>

Откройте нужный канал продаж и перейдите в раздел «Уведомления»

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах»
* Вставьте адрес, скопированный из Tilda
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Дополнительно можно настроить страницу после успешной оплаты и страницу ошибки. Это могут быть любые созданные вами страницы на тильде. Заполняем их соответственно в поля «URL СТРАНИЦЫ УСПЕХА» и «URL ОТКАЗА»

<figure><img src="../../../.gitbook/assets/7 (12).png" alt=""><figcaption></figcaption></figure>

Сохраните настройки интеграции

<figure><img src="../../../.gitbook/assets/8 (11).png" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Tilda!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
