# Nemiling

Nemiling — сервис для организации платной подписки, приёма донатов и платных сообщений в Telegram. Вы можете подключить к платформе интеграцию с Prodamus и принимать платежи через свою платёжную страницу. Ниже — инструкция, как всё настроить.

### Шаг 1. Адрес платежной страницы и ключ для настройки интеграции из личного кабинета Prodamus

👉[ ](https://help.prodamus.ru/payform/nastroika-platezhnoi-stranicy/kak-avtorizovatsya-na-platyozhnoi-stranice)[Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Nemiling
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Nemiling
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите интеграцию&#x20;

Для этого перейдите в [Telegram-бот Nemiling](https://t.me/Nemilin_bot) и откройте «Настройки».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeVLRguVt1m7Dx7sBJPEKrPWSVepoUaBN8ZYKX_OZlcB7UABzekzRD04rZSlRJ0H_3I0s90BVKpmeAQlCk0DZA6SIcuGJHsGFREXI-QQh-zRZNaY2D8B-4rcC4YdcvM0P2Xehtoxu43kXLO9nExv58KTGgr?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Нажмите на «Платёжные системы».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdrwNhIOLuFqmaL3EKZZr6gRmPHEQlzilFxvWh76Rgycw9zUNZZKOK_s3im8Z9ju9SW9V5PPRoGH8fQ7HZgtsc5RCAIAttn_p4Vqei9-_Dd1inmr0RcSoxFbL2icw_E7IT70nJJs4hcajNez2d3BjJLvH3f?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Выберите «Prodamus».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcpy0dUGitYokRHwzQJjnQ_-euaE6V4iF2446RFP12TS0UZ0EcZus9LutVICnIGBT4CRjg1RPlfKk9l-6815W9v-n4NOJwhqkajY4DkPUHkgACI4Ik6wyshaD9PRdurC4JhPdDCmwmnpy4EOXtvjXY4dclq?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Нажмите «Подключить Prodamus».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeloiLrdiHi4qyyr4mHVJcRPvkwGRbgfug6dXsJkYNpSvO28dDl9pEsy5WGSNoJf69LiuTnSc1y5ZOULCwTbRZi5Ik122jTEkIPnBpJFwT3YWX8oA--6DDjczI5PM5vmucRCVa6220POoq59ykZ5JpsOCI?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Отправьте в диалог с ботом ссылку на вашу платёжную страницу в Prodamus.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdLR6X-NjZe9dvnFoWqC9iIN4a7RU1xeM8Lre5YTLGWr-vK2CHYGymE_n9FbNHctf2oxz52j8iYZJRkyhBVQiFfCENIRQXKppQDu6Uul0X18AEK8BWvJHbGV2PXQVJgWGKJF_pRdKPpJCK-KXZCPpHRH30?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Затем отправьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeCDhxRMUbCSMO4Nzu1QFlM4QB_OvVXhMYNrWJI6P9_HxfVwNBGnU2LyHaB1iyqFvplR-8zjUJJ5xQbm-dkEEjdtCEddj9B5GZ_LqGBfriAX75BnKamh_KSRL-fGSG83lqucTJkz_B5XGpIRIicdgWqLPdo?key=lauD48XcDQotdYqDssn9vJRq" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена, и теперь вы сможете использовать платёжный модуль Prodamus в вашем чат-боте.
