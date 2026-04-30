# Creatium

Creatium — это конструктор сайтов с функционалом no-code, позволяющий создавать интернет-магазины, блоги, каталоги и лендинги без программистов и дизайнеров. Вы можете управлять каждым элементом дизайна через Zero-блок, настраивать квиз-формы и калькуляторы, принимать платежи через корзину, подключать CRM и рассылки, а также проводить A/B тесты. Ниже — инструкция по настройке.

## 1. Собираем данные и производим настройки на стороне Продамуса.

👉 [Инструкция: как авторизоваться на платёжной странице](https://help.prodamuspay.ru/)

Для настроек в системе Creatium нам понадобятся данные:\
Адрес платежной страницы:

* Откройте канал продаж, который хотите интегрировать с Creatium
* Скопируйте адрес платежной страницы

<figure><img src="../../../.gitbook/assets/7 (7).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Если у вас уже настроен адрес для уведомлений об оплате на другой url, то этот блок можно пропустить и сразу перейти к следующему шагу настройки интеграции
{% endhint %}

Далее добавим в наш платежный кабинет - URL адрес для уведомлений об оплате.

Откройте нужный канал продаж и перейдите в раздел «Уведомления».

<figure><img src="../../../.gitbook/assets/unknown (19).png" alt=""><figcaption></figcaption></figure>

* Включите тумблер «Уведомления о разовых оплатах».&#x20;
* Вставьте адрес [https://integration.prodamus.ru/creatium/](https://integration.prodamus.ru/creatium/testingqapf22/?paymentKey=224777c2bf1b1f03b7212047563b2658f8f50bdb6f5d6f82590d290d0eac4702)
* Поставьте галочку в поле «Заказ оплачен»
* Сохраните изменения.

<figure><img src="../../../.gitbook/assets/unknown (20).png" alt=""><figcaption></figcaption></figure>

### Шаг 2. Настройка интеграции на стороне сервиса Creatium <a href="#h.necgj4h7o3wm" id="h.necgj4h7o3wm"></a>

Для этого авторизуйтесь в личном кабинете Creatium и перейдите в раздел «Интеграции и уведомления».

<figure><img src="../../../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

Откройте вкладку «Платёжные системы» и нажмите «Подключить новую платёжную систему».

<figure><img src="../../../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>

Выберите платёжную систему «Продамус».

<figure><img src="../../../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>

Впишите в поле «Имя» название интеграции.

<figure><img src="../../../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

Укажите в поле «URL» шаблон:

[https://integration.prodamus.ru/creatium/<mark style="background-color:orange;">name</mark>/?system=payform](https://www.google.com/url?q=https://integration.prodamus.ru/creatium/name/?system%3Dpayform\&sa=D\&source=editors\&ust=1690904114471926\&usg=AOvVaw0vG29OXhZRFPm3eKM7cdgl).

Вместо <mark style="background-color:orange;">name</mark> нужно указать название вашей платёжной страницы. Например, если бы URL-адрес вашей платёжной страницы был https://prodamus.payform.ru/, то вам нужно было бы взять из него только prodamus — это и есть название.

<figure><img src="../../../.gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>

Если вы хотите перенаправлять клиентов после оплаты на определённые URL-адреса, добавьте в шаблон значения success и error. В этом случае шаблон будет выглядеть так:

https://integration.prodamus.ru/creatium/name/?system=payform\&success=\_\_\_\&error=\_\_\_

* Укажите вместо name название вашей платёжной страницы
* После success= укажите URL-адрес, на который будет перенаправлен покупатель после успешной оплаты заказа
* После error= укажите URL-адрес, на который будет перенаправлен покупатель при неудачной оплате заказа

<figure><img src="../../../.gitbook/assets/image (148).png" alt=""><figcaption></figcaption></figure>

Сохраните изменения.

<figure><img src="../../../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

### Шаг 3. Настройте оплату заказа <a href="#h.1sba9fep82m6" id="h.1sba9fep82m6"></a>

В Creatium есть два вида оплаты: через корзину и напрямую по нажатию кнопки. Рассмотрим, как настроить оба варианта.

**Оплата через корзину.** Откройте товарную страницу вашего сайта и нажмите на «Настройки кнопки» в карточке продукта.

<figure><img src="../../../.gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Действие» и выберите «Добавить товар в корзину».

<figure><img src="../../../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

Перейдите на страницу корзины.

<figure><img src="../../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

Откройте страницу настроек кнопки оформления покупки.

<figure><img src="../../../.gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Действие» и выберите «Отправить форму или перейти к следующему шагу».

<figure><img src="../../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

Откройте «Настройки формы».

<figure><img src="../../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Форма» и выберите в качестве действия после отправки данных «Переход к оплате».

<figure><img src="../../../.gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

Нажмите «Опубликовать», чтобы сохранить изменения.

<figure><img src="../../../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

Готово: теперь, когда клиент перейдёт в корзину и оформит заказ, его перенаправит на вашу платёжную страницу, где ему останется выбрать способ оплаты и внести платёж.

**Оплата через кнопку.** Откройте товарную страницу вашего сайта и нажмите на «Настройки кнопки» в карточке продукта.

<figure><img src="../../../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

Перейдите во вкладку «Действие» и выберите «Открыть окно».

<figure><img src="../../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

Нажмите на кнопку оплаты.

<figure><img src="../../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

Откройте «Настройки формы».

<figure><img src="../../../.gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>

Выберите в качестве действия после отправки формы «Переход к оплате».

<figure><img src="../../../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

Нажмите «Опубликовать», чтобы сохранить изменения.

<figure><img src="../../../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>



Готово: теперь, когда клиент оформит заказ, его перенаправит на вашу платёжную страницу, где ему останется выбрать способ оплаты и внести платёж.
