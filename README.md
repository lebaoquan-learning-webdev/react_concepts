# REACT CONCEPTS 

## Components 
- reusable 
- is a Javascript function that returns a markup - JSX - Javascript XML 

## JSX 
- note: use camelCase style i.e. onClick instead of click

```
import React from 'react';

const Button = () => {
  return (
    <button onClick={() => alert('Button clicked!')}>
      Click Me
    </button>
  );
};

export default Button;
  
```
- dynamic javascrips value --> use curly brace {} 
```
const text = "world!" 
<div>
    Hello {text}
<div>
```

## Fragments
- one component can only RETURN ONE value 
```
<>
    <Header />
    <Main />
</>
```
## Props
