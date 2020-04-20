# What-I-learned-in-week-13




![](https://thumbs.dreamstime.com/z/i-hate-my-computer-14456531.jpg=250x)

**Week 13** was riddled with _panic attack inducing works_, brain scrambling tests, and above all interesting new topics.
 
 __<u>I learned that :</u>__
- if the order of the parameters changes in the original class that a subsequent that it is inheriting from said class, you can modify it again in the function’s `super`
- *Super* kind of does it's own thing, whereas a *Constructor* follows the rules.
 - ---
- **Arrow _(styled)_ Functions** /es6
   -the curly brackets are optional.
   - whatever is behind the arrow gets `returned`
   - when you have one parameter, you don't need parentheses 
   - They treat `".this"` differently
  ---
Javascript works in _“Stacks"_


**Stacks vs queues**


`stack.peek()` shows what’s on top

`queue.peek()` shows what’s on the bottom 

*Get in on the back, then get to the front, then leave from the front*


- stack can be `.push()`
- queue  can be `.pop()`
  - ---
  - when stacking, you don’t want to grab for functions before they’re supposed to be called.


- giving every programmer on our app
to have a queue that line to 
 


`Head 
|
|
|
v
| 3 | = | == > | 5 | = | ==> | 8 | = | ==> null`

`this.head.next. next = 8`
**as long as there a  ’next’ keep going**
to add something to the end of this list :`

`Head                                                        Tail
|                                                                  |
|                                                                  |           
|                                                                  |
v                                                                 v
| 10 | = | ==> | 20  | = | ==> | 3| = | ==> | 8 |
`

`Const tail = newNode;
oldTail.next = newNode;`


`Const head = thing2 ;`

`Const thing1 = {
Value : 20,
Next :{},
}`

`Const thing2 ={
Value: 10}`

**Linked list pros:**
- With an array, we have to hit every single thing if we add or subtract from the start

 - If you DON'T have a link to the tail, you still have to to do that with a linked list

- Null is a keyword, not a string, i.e. undefined, NaN
