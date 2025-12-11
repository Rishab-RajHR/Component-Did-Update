componentDidUpdate() is a lifecycle method in class components that runs after every re-render.

It receives previous props and previous state as arguments (prevProps, prevState).

Useful for performing DOM updates, making API calls, or reacting to state/prop changes.

Must be used carefully to avoid infinite loops—wrap state updates inside conditions.

Ideal for comparing previous and current values to trigger actions.

Not called during the initial render; only after updates.

Replace with useEffect in functional components.
