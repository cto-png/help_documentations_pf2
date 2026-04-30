# School-Master

School-master — платформа для создания онлайн-школы без арендных платежей и процентов от оборота. Вы можете подключить к сервису интеграцию с Prodamus и принимать платежи от клиентов через свою платёжную страницу.

### Шаг 1. Настройка интеграции на стороне Prodamus

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес  [https://ваш-сайт.ru/payments/prodamus/result.php](about:blank). Вместо «ваш-сайт» нужно указать логин, под которым вы авторизуетесь в личном кабинете School-master.
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Затем нужно получить секретный ключ:

* Откройте канал продаж, который хотите интегрировать с School-Master
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Настройка интеграции на стороне School-master

Авторизуйтесь в личном кабинете и перейдите в раздел «Настройки».

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeCplFEoM5UGKUpUHJoa_wExtPgxj9EivRwRrziANAZFYVfB3hNn1dZLO43eZ-SVVI-wDyXk74zJJpfNA0815nHVVdsyqm2ZNFfrsAhmcTO5x5D8OEwcXzpw7V4L3TOlDkOspUh8Xp8X07iR_5aFNML6Bf9?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Выберите в списке интеграций платёжный модуль Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXc8xYYP0tUBKRNjHgeb2OaHYcJTMNB9I8qTpNWEz5JiSvwrqsKai3wAVF7jmLzsCaSv8IrX9gBVytnTqvejcdeCN6ty1TLTXFMiOewmebs3D4-ndpfu4KNXiXkYRKQ3DrLfM1cHgXFyGyjxKv6qwsHkDZw?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Придумайте название метода оплаты. Его будут видеть ваши покупатели.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfOMuhiyGxa6bqYvuQrK_-iSDXZwlda6vXjOr4xHCH7gcxwX18hG3bXGucj6XGzqL0bQJa8J6EQmbYfdZQhZxXVrrDGmRFAl8NDfj4m9-8CwAR5iPNl_-UsUWDUwlchMf_OXu_LSmtVs-usQGqIXkzEe-_t?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Укажите в поле «Порядок вывода», каким по счёту ваши покупатели будут видеть платёжный модуль Prodamus среди других способов оплаты.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfFxyEJLAKVvWCXQhVrZZstK9q98p2C8vVnNolMrm2Sv0BhbkkEh9aMKgfjT0b45kxG9qX8HdeMgWbHf4684bheBy_nAir5pvPVTSAiucMci_lPnEdkK28SrCvrjhxXcRCXFWel8qd1m7zZWZrT65CDzhAN?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Включите интеграцию.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXduxkDYYGKtfmLN1toI5nhHKxY0BQ-edK9dmmGHiTd7aMN4dIJ-CQRwFCAOJDQhjPO9_4e5hWrUczX4w87SM9SDXdRqVQaLzHVr0Ou2oiqvc3zu7y9gDVnKFfcYTdIfy79O_15dDhtxpZ0p5tIqE3cG9pna?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Придумайте описание способа оплаты.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd3582b-hJYbbtkeZwclyF8T56MjE8-NNgszfUmRQwvOFv96I-KCWwBjp2leEgzNj0gHGZ7BZSbUlsQepPPLGeDFIa8tm4TMQKXRtu_5SK24zw6O8GYNQGHBIRb-gACdrRa8MoQi3BTh5j8P6I4skzUHJSQ?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Укажите в поле «Адрес платёжной страницы» ссылку на вашу платёжную страницу в Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdUzMLFw0HTn09zK_8oCtP-fCK6o75nBjgZnVhAWG2hUPxnlvFuUVdjTc1ibCxm2a03Tv-FcIFT_75JRBNbGWjZvpuh-Lpeb9VDUMXT5y0QI8Sil_Y1PL-RZAo2ZqMiDUhWMFW2h2TgDfOPSoKiJMMjRnCX?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Вставьте секретный ключ, который вы ранее скопировали из личного кабинета Prodamus.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdwiVHeC-SB7cp7zrVC4K_0UtXb4T3Ifs38B-pOS0R-hP99_B3niPaKe9TxCYyrykNR4BJNk3osAxGaDnbE4j1xcUc3Be5E7iRV6bjzDVf1_qZNh0uVNETEssgPNExm6uBXyB_YJGF-tPj_VAGiunalT3UV?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Сохраните изменения.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf0fS1Lv4xOiGb-k3Nwk3kNzfKqkNQHZK4WzOelTFYedmP2r8zrnk4pycflkpcr2PVtA-sAoHcNDsshFxF8QqUwrgsywuJo2hA8vgAr9O__t8goJeueKcZ2Tyc3Un2pnmDAG2Jn9ghmltuWmShCJSt41kgJ?key=T3obcVaLCYdJdY9bcDMgwg" alt=""><figcaption></figcaption></figure>

Готово: интеграция настроена и теперь ваши клиенты смогут оплачивать заказы на вашем сайте через платёжную страницу в Prodamus.
