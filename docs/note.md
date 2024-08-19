### Bug en la pFrozenColumn en PrimeNG

Provoca que la tabla este muy lenta hace performace al hacer resize de mobile a desktop.

```html
<p-table [columns]="cols" [value]="cars" frozenColumns="1" [frozenValue]="cars"></p-table>
```
