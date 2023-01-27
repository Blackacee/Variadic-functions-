# Variadic-functions-
 
function logSomeThings() {
 for (var i = 0; i < arguments.length; ++i) {
 console.log(arguments[i]);
 }
}
logSomeThings('hello', 'world');
// logs "hello"
// logs "world"
