# Лиейный поиск

**Просто сравнивает элемент массива с искомым числом и если он его нашел то возвращает индекс , иначе null**

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