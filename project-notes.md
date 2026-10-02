# Заметки по архитектуре
- Основная СУБД: PostgreSQL
- Жизненный цикл заявки: New -> In Progress -> Escalated -> Resolved -> Closed
- Формат обмена данными: Hybrid (REST JSON for Web, gRPC for internal services)
- Очередь сообщений: RabbitMQ
- Оповещения: Telegram Bot API