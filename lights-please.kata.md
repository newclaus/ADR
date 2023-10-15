# Lights, Please

A home electronics giant wants to build a system for home automation: turning lights on and off, locking and unlocking doors, remote camera observation, and future unspecified behavior.

* Users: each system will be sold to consumers (small families), but the company expects to sell thousands of these units in the first three years.
* Requirements:
    * the system must be as turnkey as possible, but be sold in modular units (camera, lock, thermostat, etc) for easy purchase
    * the units must be accessible over the Internet (for remote monitoring and access), and it is assumed the user will have an existing WiFi setup (router and connection) to tap into
    * customers can program the system to control the various modules according to their own needs.
    * the electrical engineering for the units will be taken care of by other groups, and the software protocols for controlling the modules is flexible, according to the needs/designs of your architecture. (They will handle implementing the module side of the protocol, once you have specified it to them.)
* Additional Context:
    * willing to invest a large sum to get this new line of business off the ground
    * collects data from customers who opt in to gather broader statistics
    * international company

## Бизнес-цель

Разработать систему автоматизации умного дома. Требуется простая в управлении система с подключаемыми модульными блоками, распространяемая по всему миру.

## Бизнес-драйверы

* Независимая разработка системы и подключаемых модульных блоков
* Взаимодействие с системой по сети Интернет

## Стейкхолдеры и их потребности

* Клиенты:
    * Максимально простые установка и использование продукта
    * Оплата и подключение только нужных модульных блоков (осутствие необходимости оплачивать неиспользуемые продукты)
    * Настройка и управление отдельных модульных блоков
    * Использование системы через Интернет
    * Мульти-язычный продукт
    * Отказ от сбора статистики
* Разработчики подключаемых модулей:
    * Создание независимых интегрируемых модульных блоков с централизованным управлением
    * Простая интеграция с системой
    * Возможность расширения системы для интеграции модульного блока с принципиально новыми функциями (функции, которые не возможно задействовать в рамках текущей реализации системы)
* Команда разработки:
    * Система не должна зависеть от внутренней реализации модульных блоков

## Атрибуты качества

* Клиентские данные должны быть безопасно сохранены.
* Повышенные требования к безопасности из-за возможности оплаты
* Требования к безопасности при взаимодействии с системой и ее модулями по сети Интернет
* Минимальное количество ошибок при оплате
* Удобство (простота) использования
* Расширяемость и конфигурируемость (в дальнейшем будут появляться новые модульные блоки)
