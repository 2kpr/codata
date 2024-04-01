# codata

Go library of all the CODATA <i>(2018, up to date)</i> recommended values for physical constants.

## Go Get
`go get github.com/2kpr/codata`

## Example Use
```go
package main

import (
	"fmt"
	"github.com/2kpr/codata"
)

func main() {
	mass := codata.ElectronMass
	fmt.Println(mass)
}
```

### Links
https://physics.nist.gov/cuu/Constants/index.html<br />
http://physics.nist.gov/cuu/Constants/Table/allascii.txt
