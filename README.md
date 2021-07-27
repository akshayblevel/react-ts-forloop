# react-ts-forloop

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/react-ts-1xsyu3)

```js
import React from 'react';

function App() {
  const names = ['Panth', 'Akshay', 'Patel'];

  return (
    <div>
      {names.map(o => {
        return <div>Name: {o}</div>;
      })}
    </div>
  );
}

export default App;

```
