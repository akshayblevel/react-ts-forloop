# react-ts-forloop

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
