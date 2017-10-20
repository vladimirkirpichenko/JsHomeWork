## 1 задание

Определите результат и тип переменных в следующих случаях:

```javascript
var r = '9' + 0;    // '90'

var r = 9 + '0';    // '90'

var r = 4 + 9;      // 13

var r = null + 7;   // 7

var r = '6' + null; // '6null'

var r = '6' + [];   // '6'

var r = '6' + null; // '6null' (баян)
```

## 2 задание

Будет ли верным  выражение:

```javascript
2/3 + 1 + 1/3 == 2
```
Опишите почему да или нет?

Нет. Потому что, складываются бесконечные дроби,
которые в силу огранчиения выделенной памяти под них обрезаются.
В итоге сумма не получится целым числом.


## 3 задание

Определите результат в следующих случаях:

```javascript
var r = 6 && 0 && 7;       //   0

var r = -9 && -8;          //   -8

var r = 6 && 0 && 7;       //   0  (баян)

var r = "string" && 0;     //   0

var r = [] && {} && 7;     //   7

var r = [] || 7;           //   []

var r = {} || 0;           //   {}

var r = false || true;     //   true

var r = "2" > "3";         //   false

var r = "ab" <= "fg";      //   true

var r = "2k" <= "8l";      //   true

var r = "2" != 2;          //   false

var r = "2" !== 2;         //   true

var r = ++2 + 2;           //   5, если учитывать, что цыфры здесь представляют собой переменные с данными значениями

var r = ++2 + 2--;         //   5

var r = 1++ - 2--;         //   0
```

