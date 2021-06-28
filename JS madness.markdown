## Bind | Call | Apply

### *Bind*
Метод bind может быть вызван на любой js функции. bind (*создает и возвращает новую функцию*) позволяет нам указать js-пту [на что должно указывать ключевое слово this] (https://youtu.be/Pv9flm-80vM?t=980).
**Не забывай** bind возвращает новую функцию и привязаным контекстом, поэтому её нужно вызывать. Поэтому если требуется сразу испольнить функцию используется метод **call** вместо bind. Других отличий у них нет.

#### Call 

Работает так же как и bind. Принципиальное различие в том, что *call* вызывается сразу в отличии от bind.

#### Apply

Работает так же как и bind.  Принципиальное различие в том, что как и *call* вызывается сразу. Отличается от *call* тем, что в аргументах передается массив, когда как в *call* передается список аргументов через запятую.


## Falsy values

![image](https://user-images.githubusercontent.com/39916816/123404864-f5851780-d5b1-11eb-8c26-e1d5edb98b0c.png)


## Type checking 

#### Checking if argument is a string
```javascript
function A(x) {
  return (typeof x == 'string') || (x instanceof String)
}
```

#### Checking if argument is a number

![image](https://user-images.githubusercontent.com/39916816/123618508-f1a30080-d810-11eb-8e74-eaff6265a47d.png)

## *Lexical scope* 

Lexical scope defines how variable names are resolved in nested functions. Nested (child) funtions have access to variable defined in there parents and global scope.

## Object methods

#### Сравнение через Object.is

![image](https://user-images.githubusercontent.com/39916816/123559963-f089b900-d7a7-11eb-85d4-cfb1b0f3e5b8.png)

## Array methods

![image](https://user-images.githubusercontent.com/39916816/123619325-bd7c0f80-d811-11eb-868b-95992cc797e7.png)
