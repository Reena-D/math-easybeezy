math-easybeezy is a simple package to perform increment, decrement operation.

math-easybeezy can be used in both node.js and in the browser.

Install math-easybeezy using npm:

npm install math-easybeezy

Example usage:

import { useCounter, Button } from 'math-easybeezy'


const App = () => {
  const {count, increment, decrement} = useCounter();

  return (
    <>
     <Button onClick={increment}>Increment</Button>
     <h1>{count}</h1>
     <Button onClick={decrement}>Decrement</Button>
    </>
  )
}

export default App