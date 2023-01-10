### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  if(hungry == true && availableTime < 20) {
    console.log('Pick a snack or grab something we have ready at home')
  }
  else if(hungry == true && availableTime > 20 && availableTime < 30) {
    console.log('Take a break and cook a tasty meal')
  }
  else if(hungry == true && availableTime > 30) {
    console.log('We will take our break later as we have to do some work first')
  } 
  else {
      console.log('We will take a break later when we are hungry')
  }
 
}
```