# Summer Chores Callback Simulation

## Project Description

This project simulates completing a list of summer chores using JavaScript callbacks. Each chore takes arbitrarily selected time values (in milliseconds) used to simulate task duration. After each chore, aside from the first of the day, there is a chance the person may fall asleep. I have increased the probability after each chore to simulate real-world fatigue throughout the day. 

This project now includes a Promise-based implementation. The Promise version is located in `promiseVersion.js` and demonstrates Promise chaining and error handling using `.catch()`.

This project now includes an async/await implementation located in asyncAwaitVersion.js.


The project is an exercise in asynchronous JavaScript functions using `setTimeout()`, callbacks, and Promises.

---

## Concepts Practiced

- JavaScript callbacks and Promises
- Asynchronous programming
- setTimeout()
- Math.random()
- Conditional if/else logic
- Callback and Promise chaining
- resolve() and reject()
- Error handling with .catch() 
- Error handling with try/catch 
- async/await


---

## Tech Used
- JavaScript
- Node.js
- VS Code
- Git & GitHub

---

## How to Run

1. Clone the repository
2. Open project folder
3. a. (For Callback version) Run command:

```bash
node callbackVersion.js
```
b. (For Promise Version) Run Command:

```bash
node promiseVersion.js
```
c. (For async/await Version) Run Command:
``` bash
node asyncAwaitVersion.js
```
The program currently runs using a pre-appointed string literal name. You can change the name directly inside the doSummerChores() function call if you wish, just have fun. 🙃
