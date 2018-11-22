# patterns_node
```shallow copy an array

const names = [ 'Jon', 'Jacob', 'Jeff' ]

const copy1 = names.slice()
const copy2 = [].concat(names)
const copy3 = Object.values(names)
const copy4 = [...names]
const copy5 = Array.of(...names)
const copy6 = JSON.parse(JSON.stringify(names))
const copy7 = names.map(i => i)
const copy8 = Object.assign([], names)
```
