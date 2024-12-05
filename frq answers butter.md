### Pre-FRQ Practice

## Identify the Algorithm present in the JavaScript Files.

### Aspects of Algorithm

Sequencing
Selection
Iteration

### Question 1

Programs accept input to achieve their intended functionality. **Describe at least one valid input to your program and what your program does with that input.**

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

> there is one button that you can click that will reset your history. it gets rid of any quote that is currently displayed in the history i guess, and look in the quoteCurrent array for stored arrays. if there is a current quote, it recreates all current quotes in the quote array.

---

### Question 2

Refer to your Personalized Project Reference when answering this question.

#### Part (a):

Consider the first iteration statement included in the Procedure section of your Personalized Project Reference. **Describe what is being accomplished by the code in the body of the iteration statement.**

```js
for (let i = 0; i < quoteCurrent.length; i++) {
  const quote = quoteCurrent[i];
  createQuoteCard(quote);
}
```

> for all the current quotes, create a card with all quotes stored in the quoteCurrent array

#### Part (b):

Consider the procedure identified in part (i) of the Procedure section of your Personalized Project Reference.

- Write two calls to your procedure that each cause a different code segment in the procedure to execute.

```js
retrieveFeelingQuote(alone);
```

would cause for api to call for lonely quotes, the quote and log it, store the objects in the quote, and put this quote into quote history.
quote current is set to 0, and creates a card with the quote.

```js
categorySet();
```

> checks for valueUserFeeling, and depending on the value, sets category to matching category.

but technically, there are no things that can be called other than retrievefeelingquote, as everything is chained within other functions later

- Describe the expected behavior of each call. If it is not possible for two calls to your procedure to cause different code segments to execute, explain why this is the case for your procedure.

#### Part (c):

Suppose another programmer provides you with a procedure called `checkValidity(value)` that:

- Returns `true` if a value passed as an argument is considered valid by the other programmer.
- Returns `false` otherwise.

Using the list identified in the List section of your Personalized Project Reference, **explain in detailed steps an algorithm that uses `checkValidity` to check whether all elements in your list are considered valid by the other programmer.** Your explanation must be detailed enough for someone else to write the program code for the algorithm that uses `checkValidity`.

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

> i don't think it's physically possible

---

### End of Exam

```

```

```

```
