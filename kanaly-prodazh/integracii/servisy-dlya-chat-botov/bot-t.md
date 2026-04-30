# BOT-T

BOT-T — это сервис для создания чат-ботов в Telegram. Вы можете подключить к платформе интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### Шаг 1. Подключение интеграции на стороне Prodamus

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе BOT-T нам понадобятся данные:\
1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с BOT-T
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с BOT-T
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
* Вставьте адрес [https://api.bot-t.com/payment/prodamus](https://api.bot-t.com/payment/prodamus)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение оплаты в личном кабинете BOT-T

Авторизуйтесь в личном кабинете BOT-T и перейдите в раздел «Боты».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfNHVK9YgOM7BiDpE_1OLWNHmSy0iJeHkLA5xv8LcxnS2eiJdCrf5kBVZAL3mcz-HcSQa5JnE2MJ0ySHTis6z-TO82ALU22tIfkH4EnuMN0-YrAhyc25toEEG1vSd1RGeHTnQnT02j-yztRZcN6BVG1ZN6z?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Откройте бота, к которому хотите подключить платёжный модуль Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeeIOkJ2sYEWedScb6rLY-WpW8ZPOAGxjhUgHtFuR9ksl2SbY9aws6oZ45oBoAixnUuLbdASTA4PlKyhEwChBpwAX8UuZudE6rYhmcDqjsFWHs0raceKXmZB2jmgnTmYueU-StIrnxWg9EsjNxHQc0UQ8Q?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Перейдите в раздел «Способы оплаты».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXckVpwaTEVz4fSoKGYZvkpoTa3JUSKVV99pI3UzAEIj-Q0I5IkRnicLk2uIfmlFzFp0z_rjlevRKHcR6ZUWhszQ72fR0S6DCQEIBnM6M0RZDVNXW0Gm7JsbRQqeCU50PGDIjSEVtEqNlC59VdT719ytCQ7Z?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Нажмите «Добавить группу оплат».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd8nhndpddmKUj1SQaGybibnvrMIqTYgVZRCDV75FfWMkRXR9cUwJan7HYzpNuhjSEDQaR5_lxzFVhclMDiyrxVoop68ax1Wmd66FXsWTBQfHrf6sLbSDbyYRnMTHaeaWteeriaferrK2rnd6V-I9mBwGnP?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Выберите интеграцию с Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf2U7wMPtBr3bJ5lf9sPb2vPNyXtWvLiFXHR-t4P_pN8MyG5TSbvgSBSjQCN4jrFZRWiPNO5HRlbJaOlnSGPJeV7thtAee14LQwPbgKKe0xocu6yyjoi3VSvogTAd14Ll5mABAbFz4fvt4DGHmS9NKFsGo?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Вставьте в поле «domain» ссылку на вашу платёжную страницу.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcHezL82cmPyB-U6km7YvhFewrVb-RRfxLbcHZiHiOq89heiAW5BS7Ehb-MatGo1dzAMy1nGCkDLJiwEaAnVjhgERvOZKHPl9orUHP2p1HWtN1ZwVtAecair-nS3EudsrgPnTXVUqYFVG24WOIdUG9gmaVj?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Вставьте в поле «secret key» ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf5qPfx0aU7x4cQ_yTRtu2B9-IYxz7Vgxe6TqF3Bi4EIbRHmjBSaXvxdjvVCX-l7iLaqmWL5PISd1fQpan26DWel-3mWC4sRXDeQ1jQVXVFYJtRkBq24-0JkkmDli2QxW7UQUe8_F6TPJHNJ8chloxPJIYb?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Выберите «Рабочий режим», если хотите сразу принимать оплаты реальными деньгами. Оставьте «Тестовый режим», если хотите сначала протестировать приём оплат.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdCRPFuFru78NF_hr6B8d61DArTN2zNHK9-COgdN-PJGEApLrEiSDw4P5iQJxGg3e13Tj3re2d-EO5-vkfT8pvIWKdI9YcEg7GHVEBkw-47RNIwcJx4eu6YMlIrOJtjF8fMaUsqAwvqCnTqgZwrYJL6v1F3?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXegUQKmTIjTAHxi3GgpfLiSqoPhTEQurh4a9SyGesYOHXq3wknHXZ6WDVyBKgNeT2ueTK09beQQTGRVbceu10bhhF62wE-TicJ0-Kzz3AKUSNsbd6biF7e9P_wDeh8DE6ONLBOpqUMPvmDvgxpnbP4GDxYC?key=7A0JxSPzdhGksCvFTs4lNg" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена — и теперь ваши покупатели смогут оплачивать товары в вашем Telegram-боте через Prodamus.
