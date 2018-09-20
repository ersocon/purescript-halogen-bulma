# purescript-halogen-bulma
Bulma styles classes for Halogen

[![Build Status](https://travis-ci.org/ersocon/purescript-halogen-bulma.svg?branch=master)](https://travis-ci.org/ersocon/purescript-halogen-bulma)


The classes can be used as follows:

```purescript
import Halogen.Themes.Bulma as B

render :: State -> H.ComponentHTML Query
  render state =
    HH.button
      [ HP.class_ B.button ]
      [ HH.text label ]

```
