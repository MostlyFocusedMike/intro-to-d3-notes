# D3 Notes

- the `.select` `.selectAll` d3 methods select elements via selectors.
- They have bonus d3 filtering methods on them, and can be chained (chained off the selection will only select its children, just like you'd expect)


## Data binding

- d3 adds a `__data__` attribute to the dom element in its selection to show what literal data is bound to it

look up the `enter` phase of d3