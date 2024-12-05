### Question 1

Programs accept input to achieve their intended functionality. **Describe at least one valid input to your program and what your program does with that input.**

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

## ANSWER:

```js
DOMSelect.submit.addEventListener("click", function () {
  insertText(DOMSelect.input.childNodes), "paste";
});
```

> the input is a button click. when input is triggered, the insertText function is triggered to take the array that was summoned and for each item in the array, put it in as paragraph of text. i think it is also supposed to take type as "paste", but because it's not wrapped in the function, it's not going to take the text content

---

### Question 2

Refer to your Personalized Project Reference when answering this question.

#### Part (a):

Consider the first iteration statement included in the Procedure section of your Personalized Project Reference. **Describe what is being accomplished by the code in the body of the iteration statement.**

> checks to see what type of content was being taken in, and depending on the tyle, if it was a file, it wuold be put onto screen as just an item, or else the content inside would just be put inside

#### Part (b):

Consider the procedure identified in part (i) of the Procedure section of your Personalized Project Reference.

- Write two calls to your procedure that each cause a different code segment in the procedure to execute.
  ` insertText(thing, "file");`
  and
  `insertText(thing2, "notfile");`
- Describe the expected behavior of each call. If it is not possible for two calls to your procedure to cause different code segments to execute, explain why this is the case for your procedure.
  > first call: insert into reslts on the html the item, howevr, the secondthing would take the words inside of the thing2, and put it on the page

#### Part (c):

Suppose another programmer provides you with a procedure called `checkValidity(value)` that:

```
content.forEach(function (value) =>
let something = checkValidity(value);
if something === true
return something;)
```

- Returns `true` if a value passed as an argument is considered valid by the other programmer.
- Returns `false` otherwise.

Using the list identified in the List section of your Personalized Project Reference, **explain in detailed steps an algorithm that uses `checkValidity` to check whether all elements in your list are considered valid by the other programmer.** Your explanation must be detailed enough for someone else to write the program code for the algorithm that uses `checkValidity`.

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

```

```
