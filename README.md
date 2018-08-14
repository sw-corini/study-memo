# Javascript 


- [data attribute and data](#index) - *2018-08-14*

___

## data attribute and data

### `html`

```html
<div class="test_div" data-call="test"></div>
```

### `js`

```js
var test = function(){
	alert(1);
}

var call = $('.test_div').data('call'); // get data-call="test"

// console.log(call); // return 'test'

$('.test_div').data('call', test); // set data
var call = $('.test_div').data('call'); // get $(target).data('call');

// console.log(call); // return function(){ alert(1) }; => test();

```