Чи можу я в методі onChange для типу поля checkbox переробити логіку визначення значення в залежності від event.target.type == "checkbox"? 
Це нормальна практика?

```javascript
this,setState((prevState, prevProps) => (newState))
```
це теж саме, що?
```javascript
this,setState((prevState, prevProps) => { return newState; })
