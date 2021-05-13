# Лиейный поиск

```javascript
const array = [1,4,5,8,5,1,2,7,5,2,11]

const linearSearch = (array, item) => {
    for (let i = 0; i < array.length; i++) {
        if(array[i] == item){
            return i
        }        
    }
    return null
}
```
---

**Проходимся по каждому элементу массива , где i - индекс числа в массиве**

```javascript
 for (let i = 0; i < array.length; i++){}
```

---
**Срванивает элемент массива(array[i]) с полученным числом(item) ↓**
```javascript
    if(array[i] == item){
        return i
    } 
```

**Если они равно , то возвращает index , иначе null**