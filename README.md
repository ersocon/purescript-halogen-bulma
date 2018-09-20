# purescript-halogen-bulma
Bulma styles classes for Halogen


The classes can be used as follows:

```

import Halogen.Themes.Bulma as B

render :: State -> H.ComponentHTML Query
  render state =
    HH.button
      [ HP.class_ B.button ]
      [ HH.text label ]

```
        
