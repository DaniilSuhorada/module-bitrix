# module-bitrix
Модуль для платформы 1C-Bitrix

1. Регистрируемся на Paybox.money
2. Устанавливаем модуль через маркетплейс на сайте https://marketplace.1c-bitrix.ru/solutions/paybox.pay/ или в админке битрикса переходим Маркетплейс->Каталог решений и находим модуль Paybox (Оплата через Paybox)
3. В разделе Магазин->Платежные системы нажимаем "Добавить платежную систему"
4. Заполняем настройки: 

| Поле | Описание |
| --- | --- |
| Обработчик | Paybox |
| Merchant ID | Идентификатор продавца в системе PayBox (merchant_id) |
| Secret Key | Платежный пароль (secret_key), который задается в настройках магазина и известен только магазину и PayBox'у. |
| Статус после успешной оплаты | Устанавливаем статус после успешной оплаты |
| Статус после отказа | Устанавливаем статус после отказа |
| Статус после отмены | Устанавливаем статус после отмены платежа (возврата) |
| Тестовый режим | В случае если вы находитесь в боевом режиме, но вам нужно провести тестовый транзакции, ставите Y и все транзакции будут создаваться по тестовым платежным системам.|
| Тип идентификатора заказа | По умолчанию передает в систему ID заказа, при выборе пункта "Номер заказа" будет передавать в систему номер заказа, но только в случае, когда включен шаблон генерации номеров заказа |
