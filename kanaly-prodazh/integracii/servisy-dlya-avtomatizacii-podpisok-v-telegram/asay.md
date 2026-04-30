# Asay

Asay — это платформа для создания платных каналов и клубов по подписке в Telegram. Вы можете подключить к сервису интеграцию с Prodamus и принимать оплату от клиентов через свою платёжную страницу. Ниже — инструкция, как всё настроить.

{% hint style="info" %}
Временно недоступны рекуррентные платежи
{% endhint %}

### Шаг 1. Адрес платежной страницы и ключ для настройки интеграции из личного кабинета Prodamus

👉[ ](https://help.prodamus.ru/payform/nastroika-platezhnoi-stranicy/kak-avtorizovatsya-na-platyozhnoi-stranice)[Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

1\) Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Asay
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

2\) Секретный ключ вашей формы:

* Откройте канал продаж, который хотите интегрировать с Asay
* Перейдите в раздел «Интеграции»&#x20;
* Нажмите сгенерировать ключ

<figure><img src="../../../.gitbook/assets/unknown (21).png" alt=""><figcaption></figcaption></figure>

Скопируйте и сохраните сгенерированный ключ.

{% hint style="info" %}
**Обратите внимание!** После закрытия модального окна просмотр ключа будет недоступен.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (22).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Подключение платёжного модуля Prodamus&#x20;

Авторизуйтесь в личном кабинете Asay, нажмите на вкладку «Другое» и перейдите в раздел «Подключения».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXc2UWP92kBGZFmFg4mxmKJEcMR6n2Uo8HO2Zyfefd6VehgtNmMOwUGVXs4MGXCGt_BK1ZvW_tiklkOEJF9YbJlye4dhUE1Pvnnuz5xyhQWjBLqTNNgwstmO4ACgmfGTLUPF_yaBlG0gKWO4Ne2Y4vyUfxSn?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Выберите интеграцию с Prodamus в блоке «Платёжные системы».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXc5iYGm7W0D9r8yafFzdO_HRcKt0jx-IcyvgyYNr70yex0Ef3zSfTzqdcMDsSfd-22hC5Ernwk65ZObn1VTWQ3geUexx7tqubkzWm2AQezaS5YE3bG4V5AYa_qOdfdp_fCn48PRzHA4fSRhj1kYZic1U51B?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Нажмите «Подключить».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXcX9D1ZXLmjkEn1ZvWNX_T-dMGRSItljxbJ6LwrU5Z_6LyDG2ykTLN2rxMN6KqcGRuKgoHNAZOusurm6J7k9de7QtH2JtQpmFD4g7mloeqLL38G_-KKniPhxmpcbtSMitvDJvNdIqCIfbMpd0yZuRkYaAg_?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Настройка».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXdqd5fPUloJVOHiJ61-l0rC76cpdTC9eLQouc4WFeeQVpxEYVe7afPkeaAhhCTdqwne5C3Q9DUBlwWu4h6YxKZ0IcSwzMYXA3gI_DX_6zGNb96bARx2i4a0XX5jFEylYRcP4-sT59qUTMRv8_B2CU87X6s?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Скопируйте URL-адрес из поля «Ссылка для уведомлений».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXflqxEdvchEbONgaazntE0HCblYSHzxMFRXe5Qh2sOcAPwdK2RPzmhP2-_3jzVDSWZ5CWf2Cvy4IjYI7KkCW5j4H3vEpKe4ZNmywKrih8KutPSUJyGDqvLNCiy62OLQ3H-dHWXgroEud30QWUSL3JKE462L?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес, скопированный из Asay
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

Вернитесь к подключению интеграции в личном кабинете Asay и вставьте скопированный секретный ключ в поле «Секретный ключ».

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXcMCl2I3vXlbD-BfkoE2pOy9HCxCTqUkTNZl7b9X1H7zIuhTDfsBjtmsekqlFAG582ZFbdrgw1dgOFlTA-ooqbFKR6g_nuE6tbQu0dLU2uSd1HhwcYV4z1ktgLRNTgRCs-WTT6W8hMNZz10uD1ZNpPaX5Nx?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Придумайте текст для кнопки оплаты.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXeW-WqS5S98VD2WX9x2JAfwZ9Jqh_k7aLMCebdUrlOtyg7m49-QNe7RjKmO1eawwnvBJiLauTJfwBk7XrRmaPgxK0PGRg131eanMHQwtAS-XaqM4-MCwmjsUpTLPlVvL1OzEisF529JyUad4soKTrsa18uU?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Выберите, для каких валют будет доступна оплата через Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXetY_DGweoHts0r5a8RUqXvTeoxMDDg71ox4fO95DCuWAfgPBP9PHNXXM28ZuxpWYlzGe3h1IDXtOV7zyko3MwNlFeE2rcQsKN-kXKmpzX15hsnI9VnFlqo7D7RC16K5rpt8KUrQCqQ_7OY6_U7PTmd1Bw?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Укажите ссылку на вашу платёжную страницу в Prodamus.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXeFDVRCtAGgPT9RRZANGSg4tZ3IyrHGjWq9kTTOtIgkwhUJ8pS_5QAARBw7BxZP2E8siUP9gIE4cRunyJqJ8sQTbmOokDTk01wf5vH4sAp9erDlHQYNTy4MuZZp-jgtvxLmFp3g2UEa_fp-f4lm4Gh2YeUn?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Выберите предмет расчёта.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXcLMjgetpl0ZHAJ7Eb3wVmeWsZHnpMtb1t6ZbashfJ9-WFr958rYhCumThoHHwU9dTPfRlY_i1r7VdnoQELH5Nf1ohloLfFbYvhyJ0UM-LgT4uwofsm78_HR1Tt5BPys3kB5ExTNs1v_Q7cjmu_Oo-DQGiH?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>

Нажмите «Сохранить».&#x20;

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXf0TIvj7hOsU5p2zkflB8hY4CDGc0nK8lmpWH0ggC6kzS0X9pL101ndqQ_Ag13xk46wIUIdtXzTGuMAZAitiRvhSFGgS0GF2bHj--eGZ-k9vPIeV0IRUhH4DwKuZmRy8CpBDXAPFr4A4FBFKT0d53_fks2k?key=XBqmmYOo0t6sqTZC4rkHOQ" alt=""><figcaption></figcaption></figure>



Готово! Теперь Продамус готов принимать платежи в сервисе Asay!

{% hint style="info" %}
Информация носит исключительно справочный характер и не является офертой. С актуальной редакцией оферты и тарифами Вы можете ознакомиться в разделе "[Документы](https://prodamus.ru/documents)".
{% endhint %}
