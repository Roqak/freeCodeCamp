---
id: 5900f50b1000cf542c51001d
challengeType: 5
title: 'Problem 414: Kaprekar constant'
videoUrl: ''
localeTitle: 'Задача 414: постоянная подписи'
---

## Description
<section id="description"> 6174 - замечательное число; если мы сортируем его цифры в порядке возрастания и вычитаем это число из числа, которое вы получаете, когда сортируете цифры в порядке убывания, получаем 7641-1467 = 6174. Еще более примечательно то, что если мы начнем с любого 4-значного числа и повторим этот процесс сортировки и вычитания, то в конечном итоге мы получим 6174 или сразу с 0, если все цифры равны. Это также работает с числами, которые имеют менее 4 цифр, если мы поместим число с ведущими нулями, пока у нас не будет 4 цифры. Например, давайте начнем с номера 0837: 8730-0378 = 8352 8532-2358 = 6174 <p> 6174 называется константой Капрекара. Процесс сортировки и вычитания и повторения этого значения до достижения 0 или константы Капрекара называется рутиной Капрекара. </p><p> Мы можем рассмотреть рутину Капрекара для других баз и числа цифр. К сожалению, не гарантируется постоянная Капрекара во всех случаях; либо подпрограмма может закончиться в цикле для некоторых номеров ввода, либо константа, по которой выполняется обычная процедура, может быть разной для разных номеров ввода. Однако можно показать, что для 5 цифр и основания b = 6t + 3 ≠ 9 существует константа Капрекара. Например, основание 15: (10,4,14,9,5) 15 основание 21: (14,6,20,13,7) 21 </p><p> Определите Cb как константу Капрекара в базе b для 5 цифр. Определите функцию sb (i) равной 0, если i = Cb, или если i, записанная в базе b, состоит из 5 одинаковых цифр, число итераций, которые требуется для процедуры Kaprekar в базе b, чтобы прибыть на Cb, в противном случае </p><p> Заметим, что мы можем определить sb (i) для всех целых чисел i &lt;b5. Если я записал в базе b, занимает менее 5 цифр, число заполняется нулевыми цифрами до тех пор, пока у нас не будет 5 цифр перед применением процедуры Kaprekar. </p><p> Определим S (b) как сумму sb (i) при 0 &lt;i &lt;b5. Например, S (15) = 5274369 S (111) = 400668930299 </p><p> Найдите сумму S (6k + 3) для 2 ≤ k ≤ 300. Дайте последние 18 цифр в качестве вашего ответа. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler414()</code> должен вернуть 552506775824935500.
    testString: 'assert.strictEqual(euler414(), 552506775824935500, "<code>euler414()</code> should return 552506775824935500.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler414() {
  // Good luck!
  return true;
}

euler414();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>