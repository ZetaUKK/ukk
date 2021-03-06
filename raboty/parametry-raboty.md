# Параметры работы

## Общие параметры

Для каждой работы независимо от ее вида в системе Zeta УКК предусмотрено обязательное введение и сохранение следующих параметров:

1. **Наименование работы** - участвует в расшифровках и других формах
2. **Группа** - работы можно группировать
3. \*\*\*\*[**Контрагент**](../klienty/)\*\*\*\*
4. \*\*\*\*[**Договор контрагента**](../klienty/dogovor-s-klientom.md)\*\*\*\*
5. [**Вид работы**](vidy-rabot.md)\*\*\*\*
6. **Вид затрат** - рассмотрено в соответствующем разделе [Виды затрат](../zatraty/vidy-zatrat.md)
7. **Периодичность** - в зависимости от указанного параметра будут автоматически создаваться заказы покупателя на новый период
8. **Ответственный** - ответственный сотрудник со стороны нашей компании за работу. Поле носит информационный характер, при необходимости можно задействовать в бизнес-логике
9. **Ответственное лицо клиента** - ответственный сотрудник со стороны клиента эту работу. Поле носит информационный характер, при необходимости можно задействовать в бизнес-логике
10. **Состояние** - два состояния: открыта и закрыта. Закрытые работы имеют свою подсветку и скрываются в списке работ
11. **Дата закрытия работы** - поле носит информационный характер, при необходимости можно задействовать в бизнес-логике

![&#x424;&#x43E;&#x440;&#x43C;&#x430; &#x440;&#x430;&#x431;&#x43E;&#x442;&#x44B; &#x43A;&#x43B;&#x438;&#x435;&#x43D;&#x442;&#x430; &#x423;&#x41A;&#x41A;](../.gitbook/assets/image%20%2817%29.png)

### Описание работы

На вкладке "Описание" можно добавить произвольный комментарий к работе.

![](../.gitbook/assets/image%20%2873%29.png)

Поле носит информационный характер, при необходимости может использоваться в отчетах и формах.

### Заказы по работе

На вкладке "Заказы" отображаются все заказы покупателя, созданные по выбранной работе.

![](../.gitbook/assets/image%20%2825%29.png)

## Параметры по видам работ

### Для бюджетных работ

![](../.gitbook/assets/image%20%2810%29.png)

* **Номенклатура** - выбрать номенклатуры для заказа покупателя и акта
* **Бюджет** - сумма работы в валюте договора
* **Количество часов** в рамках установленного бюджета - возможность указать количество часов, которое планируется затратить в рамках работы. Носит информационный характер

### Для почасовых работ

![](../.gitbook/assets/image%20%2816%29.png)

* **Специальная цена** - возможность установить на работу другой вид цен, отличный от цены, указанной в договоре
* **Скидка** - скидка в % к виду цен, указанному в договоре
* **Периодичность** - в случае указания периодичности на каждый период будет создаваться новый заказ покупателя

### Для тарифного плана

![](../.gitbook/assets/image%20%2848%29.png)

* **Специальная цена** - возможность установить другой вид цены для выбранной работы, отличной от вида цены, указанного в договоре
* **Тарифный план** - заполняется автоматически из договора
* **Количество документов и часов** в рамках установленного тарифного плана - возможность указать согласованное в рамках тарифного плана количество документов и часов. Превышения по тарифу будут рассчитываться по цене из договора или по специальной цене, указанной в работе
* **Периодичность** - в соответствии с выбранной периодичностью будут создаваться новые заказы покупателя



