[<==Back](README.md)

## Things I want to know more about

# What is a ‘Controlled Component’?

An input form element whose value is controlled by React in t way that it renders the form and also controls what happens in that form on subsequent user input.

# Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.


"The handleChange runs on every keystroke to update the react state" so I'm thinking this means it automatically updates as typed. I'm really not sure what the answer to this one it though I couldnt find it.

# How do we target what the user is entering if we have an event handler on an input field?





``` javascript

handleInpoutChange(event) {
  const target = event.target;
  const value = target.type === 'checkbox' ? target.checked : target.value;
  const name = target.name;

  this.setState({
    [name]: value
  });
}

```



# Why would we use a ternary operator?



  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  condition ? (x===y) value if true :  if false