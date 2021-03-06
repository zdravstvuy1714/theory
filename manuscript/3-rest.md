# REST

## Что такое REST?
**Representational State Transfer** (Передача состояния представления) – это согласованный набор архитектурных принципов для создания более масштабируемой и гибкой сети.

## Принципы REST

1. **Client-Server** (Клиент-серверная архитектура) – отделение клиента от сервера.

2. **Stateless** (Без состояния) – сервер не должен хранить какой-либо информации о клиентах. В запросе должна храниться вся необходимая информация для обработки запроса и если необходимо, идентификации клиента.

3. **Cacheable** (Кэшируемость) – каждый ответ сервера должен иметь пометку, можно ли его кэшировать.

4. **Uniform interface** (Единообразие интерфейса) – единый интерфейс определяет интерфейс между клиентами и серверами

5. **Layered system** (Многоуровневая система) – в REST допускается разделить систему на иерархию слоев, но с условием, что каждый компонент может видеть компоненты только непосредственно следующего слоя. Например, если вы вызываете службу PayPal, а он в свою очередь вызывает службу Visa, вы о вызове службы Visa ничего не должны знать.

6. **Code-On-Demand** (Код по мере необходимости) – в REST позволяется загрузка и выполнение кода или программы на стороне клиента.