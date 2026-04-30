# 1С-Битрикс

Если ваш сайт сделан в CMS «1C-Битрикс», вы можете подключить к нему интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

## 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе 1С-Битрикс нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с 1С-Битрикс
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с 1С-Битрикс
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Если у вас уже настроен адрес для уведомлений об оплате на другой url, то этот блок можно пропустить и сразу перейти к следующему шагу настройки интеграции
{% endhint %}

Далее добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://site\_name/bitrix/tools/prodamus\_sale\_notification.php](https://site_name/bitrix/tools/prodamus_sale_notification.php), где site\_name - домен вашего сайта 1С-Битрикс
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Установите модуль оплаты Prodamus

Для этого авторизуйтесь на сайте в режиме администратора, перейдите в раздел «Marketplace» и выберите «Каталог решений».

<figure><img src="https://lh7-us.googleusercontent.com/Y7P0TGzPb_DSAw2dPd9-xSZuRmIKgiIkK4a6bH0OFV8PWirLig3Kw72S8OG04xmOiV9F7BqW9hF3r9PDBgBB1F-WTdXmzTJOOSGZcTiSre0Uu74RFYIAPnOuxSRNFPMK3E3hAoKjv8FxCYrTkz4EeR8" alt=""><figcaption></figcaption></figure>

Введите в поисковой строке «Prodamus».

<figure><img src="https://lh7-us.googleusercontent.com/RM-i6sAUor0ySzn7jJASdovGfDbsN_JLsmed_w0PjaB6d6kMd3Dcf6DtcQ-fsNP8D5ItNEcizthysv8LUcYByLWSvAi1yjDwq5hO14EZ2KULf3wcV_66Axwj000POeo7BVp479NvlnA2_WBvIg6w4-c" alt=""><figcaption></figcaption></figure>

Нажмите «Установить».

<figure><img src="https://lh7-us.googleusercontent.com/vszhFT4MdRUeKuk0Af62yeKtOmFwF9OEbhn5NSRKQ5x9FwpxDw7mqVkxG41Y9PXeUDVyuLExc4A6eRfJdnzGs3AWkYKsbcuXOjDJvbOdGegsZJJ5xrdlg0PsenSXsRX3G7QN89RMKT5PZXGX-ITOT9E" alt=""><figcaption></figcaption></figure>

Нажмите «Загрузить».

<figure><img src="https://lh7-us.googleusercontent.com/LzYF-n7R6lMoEGf7VzKKTnrJ_r3i7LDg3gu9m8Loa4rQk0ma9P8u2x9-vrLeEJ34qLh7wpMK_xCvGyK1cnbvP9VvJD6v7hhnhJS7scnttUpMfzV8zg0F4cdsefwoVV_a_3s7rUkdtm-rLIjmRLuKPLE" alt=""><figcaption></figcaption></figure>

Подтвердите согласие с условиями лицензионного соглашения.

<figure><img src="https://lh7-us.googleusercontent.com/BAvhXRGAFV8bSTCs3zer9asqMm2iJG1k4h7FysTZUdyPt3oS3n355ag8sxzyIigN5kllY1SWqvP9_SBUdygCE724XOjXVXB2PZ0o284v14cehIyomvAHsTYS7HMKqNgD9zbJwxpCjphgiPRX4FuDl_w" alt=""><figcaption></figcaption></figure>

Нажмите «Установить».

<figure><img src="https://lh7-us.googleusercontent.com/emMdllfMiFPy9p5Y0FClCzsHFOSYERRgR_AUVbtlFdN9qmttXP5J8VaMd1iBq1Xgh09MC_0HrUi3Rxb6ajtFcBI2PrGPEr_iFl8BJUduNDBBemDKKHR9ZAl4Ekg_-4DSiwUWGLfpPeUJ-vwWWjTWRm0" alt=""><figcaption></figcaption></figure>

Модуль оплаты установлен.

<figure><img src="https://lh7-us.googleusercontent.com/9xEnxixob2A01HFkHeOPZMmjpoei1h0qN0lTfJb7EPgghd5hfOwzWEKa5iOjZwk_XqT7oaO19IWkl6gl3yBRcMe3sos7ZPsaqbK0WQOuBVV5LSngiHdPuotTi6NSJg-vrOHcrvZDN4rGr8yKBVjgteY" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключите к модулю оплаты свою платёжную страницу

Для этого откройте раздел «Магазин» и выберите «Платёжные системы» → «Добавить платёжную систему».

<figure><img src="https://lh7-us.googleusercontent.com/1mErT95aHMTZm9uM-yeS5vS_YTb3jQrRtD6EVBH_s_ljVIAckqT25aLlDY9-lHQbugpkdhfbjsDJMSDhfSsPnP8ZZas5sqkXMqEPC-O6SCjAjimNsVZ-OoW1xh3ZEIgsY14mFGFIwNxCzkjkTCyD_MY" alt=""><figcaption></figcaption></figure>

Выберите «Платёжный модуль Prodamus» в поле «Обработчик».

<figure><img src="https://lh7-us.googleusercontent.com/sUomPx5tA3kRhnB5-71-izYDnheyjjgQItBuoL00HpUt3_La7Vh8k5XhtTEJWX1hftkmtqXRWElfLBzmZtV86A8MEQgAheXwQd4YzcElTJ_Jjb3mKo3CtMXCna1IYan2jt6PxxOTGDGjPI_N0QYKK1c" alt=""><figcaption></figcaption></figure>

Придумайте описание метода оплаты. Его будут видеть ваши клиенты при оплате заказа.

<figure><img src="https://lh7-us.googleusercontent.com/8AjZUR8Q86OMKEZOpIzoKfqNFZGm9GWRnBNsUPWrRgbJoCIqqrIR3hMewBNQhpchHsQANHkhf2WxNaGHt5yberd_iUS8SMijECBiXfbd04Obpf5ww3myHX3S-32DJ99wG-Kyfv1gsBOGQA0NILGw7Es" alt=""><figcaption></figcaption></figure>

Пролистайте страницу вниз и нажмите «Показать все».

<figure><img src="https://lh7-us.googleusercontent.com/saUbSuU_9GAA3wNsrAtRzNpRyEI3Qrcl_uDjzgkv69IRDJC0SOAw_m87bGbAosIlyScFu9AXkN3Y3EIz2F9ae9Py3sX_eisxhe0GtlGk62LUOAyYnodKLD0sgA3uc3WWt65dNJ4WjXEFlnSGhAiysGY" alt=""><figcaption></figcaption></figure>

Укажите в поле «URL платёжной формы» ссылку на вашу платёжную страницу, ранее полученную в личном кабинете Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/iDNDai08u8LGSjwvbXCzsMoxswnivBEC8G27joeqI_yUKPnPfKz7QbzMdyYsNZQpQH_HwlQD30MjrYfNKY2hJoNYX2JOVQs64bw16DC4kj5uHasN1DWInZMcYmS-JLdxySxEEQ-8vQWXJwrWRoLCq2g" alt=""><figcaption></figcaption></figure>

Вставьте в поле «Секретный ключ» токен для подключения интеграции, полученный в личном кабинете Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/_CMUpssaY5yQRWbryU3GTRy_n5elf5S4nM8Ij8y__gKj_Xp3_gAV4kQWFv2pi2AlX5g9-gefi7QKCTfBvoxzLJETcZ8aND5wB2bF9TaSCyAidUE9TvNWAGHpWbjZ4zDvL76wjaSp1OS0prWu-gAQT6w" alt=""><figcaption></figcaption></figure>

Укажите в поле «Список доступных платёжных систем» коды методов оплаты, которые будут доступны клиентам на вашем сайте. Чтобы разделить несколько методов, используйте символ «|».

{% hint style="info" %}
**Пример:** AC|PC|QW|SBP.
{% endhint %}

<details>

<summary>Доступные методы оплат</summary>

| Название метода                                  | Код метода                                            |
| ------------------------------------------------ | ----------------------------------------------------- |
| Open banking, Онлайн банкинг Европы              | yottapay                                              |
| SberPay                                          | sbol                                                  |
| T-PAY                                            | tpay                                                  |
| Visa/Mastercard, EUR                             | overpayeur                                            |
| Visa/MasterCard/МИР, RUB                         | AC                                                    |
| WB кошелек                                       | wbpay                                                 |
| Банковская карта                                 | ACkztjp                                               |
| Быстрый платеж                                   | SBP                                                   |
| В кредит от Фреш Кредит                          | fresh\_credit                                         |
| В рассрочку от Фреш Кредит на 10 месяцев         | fresh\_installment\_0\_0\_10                          |
| В рассрочку от Фреш Кредит на 12 месяцев         | fresh\_installment\_0\_0\_12                          |
| В рассрочку от Фреш Кредит на 18 месяцев         | fresh\_installment\_0\_0\_18                          |
| В рассрочку от Фреш Кредит на 24 месяца          | fresh\_installment\_0\_0\_24                          |
| В рассрочку от Фреш Кредит на 36 месяцев         | fresh\_installment\_0\_0\_36                          |
| В рассрочку от Фреш Кредит на 6 месяцев          | fresh\_installment\_0\_0\_6                           |
| Кредит от Т-Банка                                | credit                                                |
| Кредит от Т-Банка                                | TINKOFF\_API\_CREDIT                                  |
| Оплата в EUR                                     | ACEURGV                                               |
| Оплата в EUR                                     | ACEURKB                                               |
| Оплата в EUR                                     | ACeurxp                                               |
| Оплата в GBP                                     | ACGBPGV                                               |
| Оплата в USD                                     | ACUSDGV                                               |
| Оплата в USD                                     | ACUSDKB                                               |
| Оплата в USD                                     | ACusdxp                                               |
| Оплата в рассрочку Долями                        | dolyame:installment                                   |
| Оплата в рублях                                  | AC                                                    |
| Оплата в тенге                                   | ACf                                                   |
| Оплата в тенге                                   | ACkz                                                  |
| Оплата картой, кроме РФ                          | MONETAWORLD                                           |
| Оплата частями "Давай делить"                    | davay\_delit                                          |
| Плати Частями                                    | sbrf\_bnpl                                            |
| Рассрочка ВсегдаДа  на 10 месяцев                | vsegdada\_installment\_0\_0\_10                       |
| Рассрочка ВсегдаДа  на 12 месяцев                | vsegdada\_installment\_0\_0\_12                       |
| Рассрочка ВсегдаДа на 18 месяцев                 | vsegdada\_installment\_0\_0\_18                       |
| Рассрочка ВсегдаДа  на 24 месяца                 | vsegdada\_installment\_0\_0\_24                       |
| Рассрочка ВсегдаДа на 3 месяца                   | vsegdada\_installment\_0\_0\_3                        |
| Рассрочка ВсегдаДа  на 36 месяцев                | vsegdada\_installment\_0\_0\_36                       |
| Рассрочка ВсегдаДа на 4 месяца                   | vsegdada\_installment\_0\_0\_4                        |
| Рассрочка ВсегдаДа  на 6 месяцев                 | vsegdada\_installment\_0\_0\_6                        |
| Кредит ВсегдаДа  на 12 месяцев                   | vsegdada\_creditline\_0\_0\_12                        |
| Кредит ВсегдаДа на 10 месяцев                    | vsegdada\_creditline\_0\_0\_10                        |
| Кредит ВсегдаДа  на 24 месяца                    | vsegdada\_creditline\_0\_0\_24                        |
| Кредит ВсегдаДа на 3 месяца                      | vsegdada\_creditline\_0\_0\_3                         |
| Кредит ВсегдаДа на 4 месяца                      | vsegdada\_creditline\_0\_0\_4                         |
| Кредит ВсегдаДа на 6 месяцев                     | vsegdada\_creditline\_0\_0\_6                         |
| Рассрочка от ProOnline на 12 месяцев             | proonline\_installment\_0\_0\_12                      |
| Рассрочка от ProOnline на 12 месяцев. Казахстан  | proonline\_installment\_kz\_0\_0\_12                  |
| Рассрочка от ProOnline на 12 месяцев. Кыргызстан | proonline\_installment\_0\_0\_12                      |
| Рассрочка от ProOnline на 18 месяцев             | proonline\_installment\_0\_0\_18                      |
| Рассрочка от ProOnline на 18 месяцев. Казахстан  | proonline\_installment\_kz\_0\_0\_18                  |
| Рассрочка от ProOnline на 18 месяцев. Кыргызстан | proonline\_installment\_0\_0\_18                      |
| Рассрочка от ProOnline на 24 месяца              | proonline\_installment\_0\_0\_24                      |
| Рассрочка от ProOnline на 24 месяца. Казахстан   | proonline\_installment\_kz\_0\_0\_24                  |
| Рассрочка от ProOnline на 24 месяца. Кыргызстан  | proonline\_installment\_0\_0\_24                      |
| Рассрочка от ProOnline на 6 месяцев              | proonline\_installment\_0\_0\_6                       |
| Рассрочка от ProOnline на 6 месяцев. Казахстан   | proonline\_installment\_kz\_0\_0\_6                   |
| Рассрочка от ProOnline на 6 месяцев. Кыргызстан  | proonline\_installment\_0\_0\_6                       |
| Рассрочка от Банков-партнёров на 10 месяцев      | direct\_installment\_0\_0\_10                         |
| Рассрочка от Банков-партнёров на 12 месяцев      | direct\_installment\_0\_0\_12                         |
| Рассрочка от Банков-партнёров на 18 месяцев      | direct\_installment\_0\_0\_18                         |
| Рассрочка от Банков-партнёров на 24 месяца       | direct\_installment\_0\_0\_24                         |
| Рассрочка от Банков-партнёров на 3 месяца        | direct\_installment\_0\_0\_3                          |
| Рассрочка от Банков-партнёров на 36 месяцев      | direct\_installment\_0\_0\_36                         |
| Рассрочка от Банков-партнёров на 6 месяцев       | direct\_installment\_0\_0\_6                          |
| Рассрочка от Т-Банка                             | installment\_0\_0\_10                                 |
| Рассрочка от Т-Банка                             | installment\_0\_0\_3                                  |
| Рассрочка от Т-Банка                             | installment\_0\_0\_6                                  |
| Рассрочка от Т-Банка на 10 месяцев               | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_10 |
| Рассрочка от Т-Банка на 12 месяцев               | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_12 |
| Рассрочка от Т-Банка на 18 месяцев               | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_18 |
| Рассрочка от Т-Банка на 24 месяца                | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_24 |
| Рассрочка от Т-Банка на 3 месяца                 | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_3  |
| Рассрочка от Т-Банка на 36 месяцев               | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_36 |
| Рассрочка от Т-Банка на 4 месяца                 | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_4  |
| Рассрочка от Т-Банка на 6 месяцев                | TINKOFF\_API\_SUBSIDIZED\_HIGH\_INSTALLMENT\_0\_0\_6  |
| Рассрочка ОТП на 10 месяцев                      | otp\_installment\_0\_0\_10                            |
| Рассрочка ОТП на 12 месяцев                      | otp\_installment\_0\_0\_12                            |
| Рассрочка ОТП на 18 месяцев                      | otp\_installment\_0\_0\_18                            |
| Рассрочка ОТП на 24 месяца                       | otp\_installment\_0\_0\_24                            |
| Рассрочка ОТП на 3 месяца                        | otp\_installment\_0\_0\_3                             |
| Рассрочка ОТП на 4 месяца                        | otp\_installment\_0\_0\_4                             |
| Рассрочка ОТП на 6 месяцев                       | otp\_installment\_0\_0\_6                             |
| Рассрочки Продамус                               | broker\_installment\_0\_0\_10                         |
| Рассрочки Продамус                               | broker\_installment\_0\_0\_12                         |
| Рассрочки Продамус                               | broker\_installment\_0\_0\_24                         |
| Рассрочки Продамус                               | broker\_installment\_0\_0\_6                          |
| Расчетный счет                                   | invoice                                               |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_10                           |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_12                           |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_18                           |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_24                           |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_36                           |
| Сбербанк Рассрочка                               | sbrf\_installment\_0\_0\_6                            |
| СБП                                              | SBP                                                   |
| Частями от Продамус                              | installment                                           |
| Частями от Продамус                              | installment\_5\_21                                    |
| Частями от Продамус                              | installment\_6\_28                                    |
| Частями от Продамус (v3.0)                       | installment\_10\_28:v3.0                              |
| Частями от Продамус (v3.0)                       | installment\_12\_28:v3.0                              |
| Частями от Продамус (v3.0)                       | installment\_4\_14:v3.0                               |
| Частями от Продамус (v3.0)                       | installment\_5\_21:v3.0                               |
| Частями от Продамус (v3.0)                       | installment\_6\_28:v3.0                               |
| Яндекс Пэй                                       | yandexpay                                             |
| Яндекс Сплит на 12 и 24 месяца                   | yandex\_installment\_0\_0\_12                         |
| Яндекс Сплит на 2 месяца                         | yandex\_installment\_0\_0\_2                          |
| Яндекс Сплит на 4 месяца                         | yandex\_installment\_0\_0\_4                          |
| Яндекс Сплит на 6 месяцев                        | yandex\_installment\_0\_0\_6                          |

</details>

Если хотите, чтобы покупателям были доступны все методы оплаты, поставьте галочку в чекбоксе напротив поля «По умолчанию».

<figure><img src="https://lh7-us.googleusercontent.com/-VvD2eSfuwDbxPSVqNBbJZQJeLw8k5aGtA7-jOlQTdLjTrP3tkMCIOL0kMDSEt9768OncAfzE0Q3DmtYSrVKf2mdjjqvRyamZSbjQJfoyAHHKjuuRs4ZN_SDjWeMvjs0QUmQerHBrq16QF1VPfh2ox4" alt=""><figcaption></figcaption></figure>

Поставьте галочку в чекбоксе напротив полей «Боевой режим» или «По умолчанию»

<figure><img src="https://lh7-us.googleusercontent.com/7E_XeZTH0XL7i3nqFdYoCLuPzwApJMKaQo0H621whoGwRh7bDUt1dzwEV3p_FHUc9KIBepu93n9zP-gIpspULdXe87Pria_EzunUL-L2yOFn0o2KZ_YGCLPa1sH1cvyTYtburVWs7rHqh7P497kh-Hc" alt=""><figcaption></figcaption></figure>

Укажите в поле «Глобальная страница возврата без оплаты» ссылку, по которой будут направляться клиенты при отказе оплачивать заказ. Если поставить галочку в чекбоксе напротив поля «По умолчанию», настройка будет отключена.

<figure><img src="https://lh7-us.googleusercontent.com/8xABgX5mQCK7FNB3rlmNM4PbDJ-O3ZYI9UNN-dA6C9xDJGdG0YdLIZ4uh3jdXazC6quSZi6B31EYZsm4rge1MLbLzP0oS9UmATER3YXLueM6BjG2g1IGL4FymaZWIihRrP_XP2c4aNMIBR1WQYiZILE" alt=""><figcaption></figcaption></figure>

Укажите, какой статус оплаты будет присваиваться заказу после его оплаты.

<figure><img src="https://lh7-us.googleusercontent.com/Zyd3cwDRFt_E2H1BnAsVdO8cZuqteEvkZiRyI9lKXr1k5kAjPMfMvMQSmcENAA7u-1kC2sTCOz8JrM_kh5RS_oKeRcnQo2rL_pgz3_-cB9yjcBMKJGTtP33RqrcANUO4QDBMAnBAl9tbkfdoGYDmvcA" alt=""><figcaption></figcaption></figure>

Сохраните настройки.

<figure><img src="https://lh7-us.googleusercontent.com/6nroVtVcC7JUzMXloRkLyQlzu0wsGmx5xtMRkVtKTpGB7GutqHt8mrJujWyqDPD8hXjKkNE3Kfw6PkB9Z1T2hw9rreMXHW1cGioC1h99Al7noNFQGfsP323VBIm7APie4AXEjaaS94NOrx-P_ZihaSw" alt=""><figcaption></figcaption></figure>

### Шаг 3. Настройте отправку доступов к обучающим материалам

Для этого откройте «Настройки» → «Настройки модулей» → «Модуль оплаты Prodamus».

<figure><img src="https://lh7-us.googleusercontent.com/Sb3gZMThdf0jfgCyz1D4eirg1_sG0_CXkPZeztxShAm9HtlkDgjh2wvUr6PLrw0XoTb-wBux3WQZ9bencZDi5RPWhiGq3bePtoj4H6FJr-gua9gvefn6y6l2P2FXzkUhhHhbQ27tX1e0X4zMV3fLuPI" alt=""><figcaption></figcaption></figure>

Выберите в поле «Инфоблок каталога» раздел сайта с вашими товарами и поставьте галочку в чекбоксе напротив поля «Отображать платный контент на странице успеха оплаты». Сохраните изменения.

<figure><img src="https://lh7-us.googleusercontent.com/O7s2tylGNYD9CnqABjSZ2XLKGODrsp6pXTRUbBa628rR1dqbLq2e26iIxWBITo0sqaN6M9YJ5Be8BN7WnLr-oOXwP8PBVYSL8oLnyIzwrsopOzHwFKy-mClQBX0pgCicq7BJP_pFojk8_qVj04ErqMo" alt=""><figcaption></figcaption></figure>

Перейдите в раздел «Магазин» и откройте карточку товара, для которого хотите настроить отправку доступов.

<figure><img src="https://lh7-us.googleusercontent.com/3R-VUYEwexx3Og7stTSSyDUf4FoTffePb0P8SzmA_DJ86DODZKKL4jJywCu-4dpAELDfiDjxfCokrzkjDbxeffcsh8gXvdDID7wXpYUmbHpg0OCRVofxATZH4IZXIImuNO3TO02FFyRGgDhh5j1Ko4w" alt=""><figcaption></figcaption></figure>

После открытия нужной карточки пролистайте страницу вниз и заполните поле «Платный контент». В нём нужно указать:

* Название и стоимость обучающего материала
* Ссылку на получение обучающего материала
* Логин и пароль для доступа к обучающему материалу (если таковые имеются)

Вот пример правильного заполнения поля: «Спасибо за покупку курса “Easy Breazy” за 4 990 рублей. Чтобы получить доступ к нему, перейдите по ссылке https://english-for-dummies/easy-breazy. Доступы для входа: hskmrw (логин), krw45k21 (пароль)».

<figure><img src="https://lh7-us.googleusercontent.com/NTUPucCQuNmLfU8ZPZARhWVYY7zgOen17VLqRgClPj7ZublISJ-ygbOhW1PSeH0wyIPVt2e3UqVxdDGrwG_dQM30hfM1XMqAKxvYOdF3cmEo8763-RXH4gLNzyfVLRba8ASEkm8Q3kTCsanx3u28lD8" alt=""><figcaption></figcaption></figure>

Сохраните настройки и повторите это действие для других ваших продуктов.

<figure><img src="https://lh7-us.googleusercontent.com/3H0I2TbJTmiwV_LdvggHpCr2tBhttOjkwNH_NV8jd5W9SZp3gM38swoQXECXoXy6ol3SMox6xWviRhK8aHgOiinMaKcQ5_tXOx_bEAR9f3J6VOv1q_83eq1QsdAKamWbbKJGcunvlSc66FHmLFyYHGM" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Если заказ клиента состоит из нескольких позиций, то доступы по каждой из них будут отправлены покупателю одним письмом на email, а также будут отображены на странице успеха оплаты.
{% endhint %}

Готово: интеграция настроена. Теперь, когда клиент будет оплачивать заказ через модуль оплаты Prodamus, откроется ваша платёжная страница, на которой покупателю останется только выбрать удобный способ оплаты и внести платёж.

<figure><img src="https://lh7-us.googleusercontent.com/kyBS2m778UMDx1fkxLHcYJDWuQrCrHgEhQGYdmXvRaLGSxHO5YzPnR6B0Xvyr0K3AoyugzhLZtFNCyAYiHFHU8k2Xcs1HzXNZHvT0gjU_tPjp-AZp5RHRqfTESqsKBKFMD69JP4y33nUx7YX5NPIl2U" alt=""><figcaption></figcaption></figure>
