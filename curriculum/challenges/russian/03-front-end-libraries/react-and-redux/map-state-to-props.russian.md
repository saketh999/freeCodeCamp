---
id: 5a24c314108439a4d4036145
title: Map State to Props
challengeType: 6
isRequired: false
videoUrl: ''
localeTitle: Состояние карты для реквизита
---

## Description
<section id="description"> Компонент <code>Provider</code> позволяет вам предоставлять <code>state</code> и <code>dispatch</code> ваши компоненты React, но вы должны точно указать, какое состояние и действия вы хотите. Таким образом, вы убедитесь, что каждый компонент имеет доступ только к состоянию, в котором он нуждается. Вы достигаете этого, создавая две функции: <code>mapStateToProps()</code> и <code>mapDispatchToProps()</code> . В этих функциях вы объявляете, какие части состояния вы хотите иметь доступ и какие создатели действий вы должны иметь возможность отправлять. После того, как эти функции находятся в месте, вы увидите , как использовать Реагировать Redux <code>connect</code> метод , чтобы соединить их к компонентам в другом вызове. <strong>Примечание.</strong> За кулисами React Redux использует метод <code>store.subscribe()</code> для реализации <code>mapStateToProps()</code> . </section>

## Instructions
<section id="instructions"> Создайте функцию <code>mapStateToProps()</code> . Эта функция должна принимать <code>state</code> как аргумент, а затем возвращать объект, который отображает это состояние в имена конкретных свойств. Эти свойства станут доступными для вашего компонента через <code>props</code> . Поскольку этот пример поддерживает все состояние приложения в одном массиве, вы можете передать это целое состояние вашему компоненту. Создайте <code>messages</code> свойств в возвращаемом объекте и установите его <code>state</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Конст <code>state</code> должно быть пустым массивом.
    testString: 'assert(Array.isArray(state) && state.length === 0, "The const <code>state</code> should be an empty array.");'
  - text: <code>mapStateToProps</code> должна быть функцией.
    testString: 'assert(typeof mapStateToProps === "function", "<code>mapStateToProps</code> should be a function.");'
  - text: <code>mapStateToProps</code> должен возвращать объект.
    testString: 'assert(typeof mapStateToProps() === "object", "<code>mapStateToProps</code> should return an object.");'
  - text: 'Передача массива как состояния в <code>mapStateToProps</code> должна вернуть этот массив, назначенный для ключа <code>messages</code> .'
    testString: 'assert(mapStateToProps(["messages"]).messages.pop() === "messages", "Passing an array as state to <code>mapStateToProps</code> should return this array assigned to a key of <code>messages</code>.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='jsx-seed'>

```jsx
const state = [];

// change code below this line

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
