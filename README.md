# The NEW keyword

**When we make a function like**
`function Color(r, g, b) { this.r = r; this.g = g; this.b = b; }`

**And then call that function**
`var car1 = new Color(255, 40, 100)`

_// 1. Creates a blank, plain JavaScript object;_
_// 2. Links (sets the constructor of) this object to another object;_
_// 3. Passes the newly created object from Step 1 as the this context;_
_// 4. Returns this if the function doesn't return its own object._
