# Rendering List and Conditional Content Exercise Hints

## Exercise 1: Create and Show Todo List
1. Hint 1: It is totally same with the lesion, you just need to change products to todo.
2. Hint 2: Because Todo have two properties: *name and description", so that you need use object to contains Todo, example

```js
data() {
  return {
    todos: [{name: 'my todo', description: 'todo desc'}],
  };
}
```

## Exercise 2: show message when todo list is empty
1. Hint 1: you *v-if* to check and show the message.
2. Hint 2: it is so easy, no hint 2.

## Exercise 3: Delete TODO

1. Hint 1: When user click on a TODO, use even binding to call a method to delete todo.
2. Use *array.splice(start, deleteCount)* to delete a element. Start should be the index of the element that you want to delete and deleteCount should be 1.
