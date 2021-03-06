# JUnit Interview Questions

## Что такое Unit Testing

Модульное тестирование или _Unit Testing_ - процесс проверки на корректность функционирования отдельных частей исходного кода программы путем запуска тестов в искусственной среде.

## Что такое Fixture

**Фикстура или Fixture** - состояние среды тестирования, которое требуется для успешного выполнения тестового метода. Может быть представлено набором каких-либо объектов, состоянием базы данных, наличием определенных файлов, соединений и прочее.

### Какие аннотации используются для создания фикстур

Предусмотрено четыре аннотации две для фикстур уровня класса и две для уровня метода.

- `@BeforeClass` - Запуск перед выполнением класса
- `@Before` - Запуск перед каждым тестовым методом
- `@After` - Запуск после каждого тестого метода
- `@AfterClass` - Запуск после выполнения класса
  
## Для чего нужна аннотация `@Ignore`

Аннотация `@Ignore` заставляет инфраструктуру тестирования проигнорировать данный тестовый метод. Аннотация предусматривает наличие комментария о причине игнорирования теста.
