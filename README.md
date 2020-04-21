# react-iq
react js interview questions answers

<h2>What is Virtual DOM</h2>
<p>The virtual DOM (VDOM) is an in-memory representation of Real DOM. The representation of a UI is kept in memory and synced with the “real” DOM. It’s a step that happens between the render function being called and the displaying of elements on the screen. This entire process is called reconciliation.

</p>
<h2>What is the difference between state and props?</h2>
<p>Both props and state are plain JavaScript objects. While both of them hold information that influences the output of render, they are different in their functionality with respect to component. i.e,</p>
<ul>
  <li>Props get passed to the component similar to function parameters</li>
  <li>state is managed within the component similar to variables declared within a function.</li>
</ul>
<h2>What are Higher-Order components</h2>
<p>A higher-order component (HOC) is a function that takes a component and returns a new component. Basically, it’s a pattern that is derived from React’s compositional nature
We call them as “pure’ components” because they can accept any dynamically provided child component but they won’t modify or copy any behavior from their input components.</p>

<code>const EnhancedComponent = higherOrderComponent(WrappedComponent);</code>

<h4>HOC can be used for many use cases as below,</h4>
<ol>
<li>Code reuse, logic and bootstrap abstraction</li>
<li>Render High jacking</li>
<li>State abstraction and manipulation</li>
<li>Props manipulation</li>
</ol>

<h4>Redux Reducer</h4>
<p>how we specify our app state chnages in response to certain actions to stores/context</p>
