# LOOP for
```js
let str = '';
let cnt = 0

for (let i = 0; i < 9; i++) {
    str = str +i;
    cnt+=i
}

console.log (str);
```
Оператор for создает цикл, включающий три необязательных выражения, заключенных в круглые скобки и разделенных точкой с запятой. За ними следует оператор (обычно блочный оператор), который выполняется в теле цикла. Следующий оператор for начинается с объявления переменной i и инициализации ее значением 0. Проверяется условие, что значение i меньше девяти, после чего выполняются два последующих оператора, и значение i увеличивается на 1 после каждого прохода цикла.

# LOOP while

```js
let n = 0;
let x = 0;

while (n<3) {
    n++;

x += n
}
console. log (n);
```
Цикл while создает цикл, который будет выполнять указанную инструкцию до тех пор, пока тестовое условие не станет истинным. Условие оценивается перед выполнением инструкции. Следующий цикл while будет продолжаться до тех пор, пока переменная n не будет меньше трех. Для досрочного завершения цикла до достижения значения true используйте оператор break.

# LOOP Do/while 

```js 
let result = '';
let i = 0;

do {
    i = i + 1;
    result = result + i;    
}
while (i < 5);

console.log (result);
```

Цикл, создаваемый инструкцией do...while, выполняет указанную команду до тех пор, пока проверочное условие не станет ложным. Проверка условия осуществляется после выполнения команды, гарантируя, что команда выполнится хотя бы один раз. В следующем примере цикл do...while повторяется минимум один раз и продолжает повторяться до тех пор, пока переменная i не достигнет значения 5 или более.

# CONDITION Switch statment

```js 
const expr = 'Papayas';

switch (expr) {
    case 'Orenges':
        console.log ('Orenges are $0.59 a pound.');
        break;
    case 'Papayas':
        console.log ('Mangoes and papayas are $ 2.79 a pound.');
        break;
    default:
        console.log ('Sorry, we are out of ${expr}.');

}
```
Оператор switch вычисляет
выражение, сопоставляя
его значение с рядом
предложений case, и выполняет
операторы после первого
предложения case с соответствующим значением,
пока
не будет найден оператор break. Предложение по умолчанию оператора
switch будет
заменено, если ни один регистр не соответствует значению
выражения.