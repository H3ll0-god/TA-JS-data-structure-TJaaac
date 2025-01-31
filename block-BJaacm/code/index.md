```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` //True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason
- `user === newUser;` // True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.name === newUser.name;`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.name == newUser.name;`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.sibling == newUser.sibling;`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.sibling === newUser.sibling;`// // True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.sibling == allBrothers;`//// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.sibling === allBrothers;`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy === allBrothers;`// False because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy == allBrothers;`//// False because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy == user.sibling;`// False because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy === user.sibling;`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy[0] === user.sibling[0];`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `brothersCopy[1] === user.sibling[1];`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
- `user.sibling[1] === newUser.sibling[1];`// True because the values of user are not changed and again stored in a new variable called newUser which is a call by value  output and reason === is also true because no values are changed in the place called user
