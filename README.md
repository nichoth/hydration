# hydration

https://www.jameshill.dev/articles/partial-hydration/

## `hydration`

This function provides a kind of "soft" render, where the library does a quick comparison with whatever it might be expecting, and if all is well, simply attaches event listeners and runs the component's lifecycle methods, including **hooks**.

This way, we bypass the work needed to render this component on the client, but still make use of the interactive methods that the component might provide.


