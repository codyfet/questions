## Вопросы по технологиям

# JS

* Какие типы данных есть в js? :star:
* В чём разница между ```null``` и ```undefined```? :star:

* В чём разница между ```==``` и ```===```? :star:

* Как создать копию объекта? Как создать глубокую копию объекта? :star::star: 
* Что будет выведено в консоль? :star:
```
var user = {name: 'Вася'};
var admin = user;
admin.name = 'Петя';
console.log(user.name);
```
* Как произвести глубокое клонирование объекта?

* Каким типом данных являются массивы в js?
* В чем разница между методами ```Array.forEach()``` и ```Array.map()```? :star:
* Как определить является ли значение в переменной массивом или нет? :star::star:

* Объясните для чего используется ключевое слово ```this```? :star::star:
* Для чего используется метод ```bind```? Что является результатом выполнения этого метода? :star:

* Что такое замыкание? :star:
* В чём разница между объявлениями функций: ```function foo() {}``` и ```var foo = function() {}```? :star::star:
* В чём разница между понятиями *функция* и *функция-конструктор*? :star:
* Как в классах реализуются приватные поля? :star:
* Расскажите максимально подробно, что происходит когда мы вызываем функцию-конструктор с ключевым словом ```new```? :star::star:
* Для чего используется ключевое слово ```super```? :star:
* В чём разница между классическим наследованием и прототипным наследованием? :star::star:
* Приведите пример наследования между сущностями? Можно ли построить наследование Автомобиль -> Двигатель? :star:

# React

* Мгновенно ли срабатывает ```setState```? Если нет, то как выполнить код, который на 100% выполнится после того, как новый state будет установлен? :star:
* Что будет если вызвать ```this.setState``` в render методе компонента? :star:
* Что следует использовать в качестве значения для атрибута ```key``` при отрисовке набора компонентоа? Можно ли использовать index коллекции при отрисовке элементов в цикле? :star::star:
* Привидите несколько примеров применения редких методов ЖЦ компонентов? :star::star:
* Назовите какие вы знаете приёмы оптимизации react приложений? :star::star:
* Были ли в вашей практике ситуации, когда приходилось использовать метод ```forceUpdate```? :star::star:
* Как передать параметр в функцию-обработчик события в методе render? :star::star:
```
<tr onClick={this.handleClick(id)}...
```
* Что вам нравится в реакте? Что не нравится? :star::star:

## Redux

* Можно ли (и считается ли это нормальным) использовать локальный state компонента, если используется Redux? :star:

###### References
