# Taplink

Taplink — платформа для создания небольших сайтов и лендингов. Вы можете подключить к сервису интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### Шаг 1. Настройка интеграции в личном кабинете Prodamus

👉  [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://taplink.cc/payments/prodamus/result.html](https://taplink.cc/payments/prodamus/result.html)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Далее создайте секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Taplink
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение метода оплаты в личном кабинете Taplink

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXePV7j-FHZTgVD_G4FLbMQHXXZOltvyW1m6ru2QjNXiDX-rrBMkZ5-Et0MiU6mksNl4C5RprLArdH4XR1o-z1i270mx9Mj12hcxnIKt4GG4jCr46He2S5YD4Se9Y52fTEDSwL90sC8ho_nzc4_ovhl3p3BO?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Приём платежей» и нажмите «Добавить платёжную систему».&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXfZ86bgDI0YSOrDqN0NBtyHkDQP6AVLOpZWx0hPNsehQVOCcwJ7O0ZttIgAGGcOnra4SsVp8gAqZliwjeWUfXphOYJp1I15jMzKy81t5WuuBk3gNkkAQ9x2LcH8Ypitb8qYNINh0hcAMauSTm85Kjrdef31?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Выберите платёжную систему «Prodamus».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXfihgCHOOcGXe-zBKKYoOxS9y9WpwGYssRH3fUyLwYyOk4C8T-v09VfY0DBipYvb7AkjdYQvIoQo6DBEA_LE3Ew4lrjLhC6Mu9QHPlkdpk4RvkJOwyHEhW8kztk3FN79dmoE6bWoVwPMyTLxmqjM_O9fCvc?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Выберите страну, в которой вы зарегистрированы в Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXfJu5Fd1RhlAiRTgp3AxqOloAvMYHwfuPnruAC0Iu0ZPsY7oCbIp0r4A7QxQEhe1-hNhLvBRki2iseVPFjXFCpQOGlsmI3ndVpaJv8PC7y_xHREf4k62rJOehHTOLr6cnSFCgISnZnwaFdf8r6NTAKulO09?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Укажите ваш поддомен в Prodamus.

* Откройте канал продаж, который хотите интегрировать с Taplink
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Например,** если полный адрес вашей платёжной страницы был бы [https://integrationtest.payform.ru/](https://integrationtest.payform.ru/), то в настройках интеграции нужно было бы указать только поддомен integrationtest.
{% endhint %}

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXc7zkA1vHXR83Ot62Dv4ggMZ6sYQ34ShiWnvarGuWysgBTZcqoVw4pGuOMGSRNgIfEHG-hiVmAjczQzjaA7Qg4wyLIAekms6SCh9u2PUK1vyZwAhd0ozc8wZN3jIEHe-v2P3AsoPbXgP8DnyUmrlXj1dZ2C?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXczDLBdSlJjbJe4GsW94eeXsCfPl294yP5hzWzj3UndyTvRN-UM10mRhzPCQjUJVKABaqGsY60mawsbOB0I7BX_rOcof18e3UEJcP8_913F8QdS5u8vS03Js7wjBa1GIck4dUGQ5Tj7uWFnFsz30_GCb8PN?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Отметьте методы оплаты, которые будут доступны вашим клиентам при оплате заказов.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXdfLK7ATGQuUPL6GBvHU7CSycWJwYMEujgSyD5N7_u0YkyFBLEZ72o8JSsTM6jhB9BQCXDIY30WTj_6OkhTT6jmzMdMc3tkI9MWTHqaoPbLjn6qySMro_4XYpUujYpkj7Ejp60yTAwtZQGzBOpeUnBWTXg?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Выберите «Тестовый режим», если после настройки интеграции сначала хотите протестировать её. Если хотите сразу принимать оплату реальными деньгами, выбирайте «Рабочий режим».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXd4XWW_90mfU0iGsGpXfV_E70B9GL9lHEdnUtpQKr7GVmFHHy7QK0SjBbB_b7YvFbxqmkbJxMPNe4KstZXiHL4OGFj-5Fo9YqN5chlMHK0WNLirwWVP3yV6c-b8Bpa2mJf3r5YCau8lfME8yTOPnBqTuns6?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXf0NZZbPWLs1c4Kg3hxlmNwLk7hP4_6Be02d-GOKF-cXpgxRPrjPPXcStGAlZhQ9iFe63WxXLo1zUxZpNkCnwIEqGBhcCAjGiTvf04cjKWPcA0OfGhpGpfIS8P1aiTIpHVABABWluJID_UcTOGGF2uXUddt?key=mpJNdMcaxGSjW8o48DDwHQ" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена. Теперь покупатели смогут оплачивать заказы на вашем сайте через платёжную страницу в Prodamus.
