_.delay(func, wait, [args])
[Ⓢ](https://github.com/lodash/lodash/blob/4.17.21/lodash.js#L10538 "View in source") [Ⓝ](https://www.npmjs.com/package/lodash.delay "See the npm package") [Ⓣ][1]
Invokes func after wait milliseconds. Any additional arguments are provided to func when it's invoked.

Since
0.1.0

Arguments
func (Function): The function to delay.
wait (number): The number of milliseconds to delay invocation.
[args] (...*): The arguments to invoke func with.
Returns
(number): Returns the timer id.

Example
_.delay(function(text) {
  console.log(text);
}, 1000, 'later');
// => Logs 'later' after one second.
