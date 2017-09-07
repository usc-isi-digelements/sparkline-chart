# sparkline-chart
A Polymer Element that displays a spark line chart.

### Example

```js
var testPoints = [
  {"date": new Date(2017, 01, 02) , "count": 0},
  {"date": new Date(2017, 01, 09) , "count": 3},
  {"date": new Date(2017, 01, 16) , "count": 5},
  {"date": new Date(2017, 01, 23) , "count": 3},
  {"date": new Date(2017, 01, 30) , "count": 9},
  {"date": new Date(2017, 02, 06) , "count": 1},
  {"date": new Date(2017, 02, 13) , "count": 9},
  {"date": new Date(2017, 02, 20) , "count": 7},
  {"date": new Date(2017, 02, 27) , "count": 1}
];
```

```html
<sparkline-chart
  points="[[testPoints]]"
  x-prop="date"
  y-prop="count">
</sparkline-chart>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct