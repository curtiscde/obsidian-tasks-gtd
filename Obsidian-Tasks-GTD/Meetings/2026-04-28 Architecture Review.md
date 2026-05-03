#meeting

## Notes
Reviewed the proposed design for the new notification service. Key decision: use an event-driven approach with a message queue rather than direct API calls. This decouples the services and allows for retries on failure. Agreed to use the existing RabbitMQ setup rather than introducing a new tool. An ADR must be written before implementation begins.

## Actions
- [ ] #gtd/focus Write Architecture Decision Record (ADR) for notification service 📅 2026-05-04
- [ ] #gtd/quick Share decision summary with the wider team on Slack 📅 2026-04-29
- [ ] #gtd/waiting Backend team to confirm RabbitMQ has capacity for additional queues
