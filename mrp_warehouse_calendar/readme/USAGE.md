When a manufacturing order is created out of a procurement evaluation
(from an orderpoint, MTO,...) the calendar is considered in the
computation of the planned start date of the manufacturing order.

For example, if it takes 1 day to manufacture a product and it is
required for Monday:
![Replenish](../static/description/replenish.png)

the manufacturing order will be created with
planned start date on the previous Friday, if the warehouse operates
under a Mo-Fri working calendar.
![Manufacturing Order](../static/description/manufacturing_order.png)

Manual changes to the start or end date of a manufacturing order will
also respect the lead time and the warehouse calendar's working days.
![Manual change day](../static/description/change_day.gif)
