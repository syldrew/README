### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

function whatToDoForLunch (hungry, availableTime){ 
  if (hungry === true && availableTime < 20) {
    console.log('Pick a snack! or grab something from your house')
  } else if (hungry === true && availableTime >= 20 && availableTime < 30) {
    console.log('You deserve a break! Cook a tasty meal!!!')
  } else if (hungry === true && availableTime >= 30) {
    console.log('You should eat something!')
  } else {
    console.log('No need to eat if you are not hungry! You can eat later on.')
  }
}
whatToDoForLunch(false, 20)


```function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```
