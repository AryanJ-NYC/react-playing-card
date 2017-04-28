# React Playing Card

A material design playing card React component.

## Installation

`npm install react-playing-card --save`

## Usage

A Card component must be passed a rank and a suit as properties:

```javascript
import Card from 'react-playing-card'
<Card rank="A" suit="S" />
```

A suit must be an element in the set { S, H, C, D }, which stands for spades, hearts, clubs and diamonds, respectively.

A rank must be an eleent in the set { A, 2, 3, 4, 5, 6, 7, 8, 9, T, J, Q, K }, which stands for ace, two, three, four, five, six, seven, eight, nine, ten, jack, queen, king, respectively.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

The design for the playing card was created by [Jasper](http://codepen.io/jboeijenga/) as a [CodePen project](http://codepen.io/jboeijenga/pen/EadGdj).
