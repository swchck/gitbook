# KISS

`KISS` акроним для «Keep it simple» — принцип проектирования, принятый в ВМС США в 1960.

Принцип KISS утверждает, что большинство систем работают лучше всего, если они остаются простыми, а не усложняются. Поэтому в области проектирования простота должна быть одной из ключевых целей, и следует избегать ненужной сложности. Вариации на фразу включают «англ. Keep it Simple, Silly», «Keep it short and simple», «keep it small and simple», «Keep it simple, stupid».

Этот принцип лучше всего иллюстрируется историей, когда Джонсон вручил команде инженеров-конструкторов несколько инструментов, бросив им вызов с тем, что реактивный самолёт, который они проектировали, должен быть ремонтируемым для среднего механика в поле в боевых условиях только с этими инструментами. Таким образом, «stupid» относится к отношению между тем, что всё ломается, и сложностью необходимого для этого ремонта.

- Разбивайте задачи на подзадачи которые не должны по вашему мнению длиться более 4-12 часов написания кода
- Разбивайте задачу на множество более маленьких задач, каждая задача должна решаться одним или парой классов
- Сохраняйте ваши методы маленькими. Каждый метод должен состоять не более чем из 30-40 строк. Каждый метод должен решать одну маленькую задачу, а не множество случаев. Если в вашем методе множество условий, разбейте его на несколько. Это повысит читаемость, позволит легче поддерживать код и быстрее находить ошибки в нём. Вы полюбите улучшать код.
- Сохраняйте ваши классы маленькими. Здесь применяется та же техника что и с методами.
- Не бойтесь избавляться от кода. Изменение старого кода и написание нового решения два очень важных момента. Если вы столкнулись с новыми требованиями, или не были оповещены о них ранее, тогда порой лучше придумать новое более изящное решение решающее и старые и новые задачи.
