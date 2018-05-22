inital:

Using var
variables are hoisted.
same variables can be declared within the scope.
No block scope

ES6 has the following keywords.

let const -- 

let -- for mutalble reference variable 
const for immutable refernce variable


var let const not used then JS assumes it as a variable.


variables should not be used.

Self - executable function // IIFE pattern.


--> Static fn binding.

Functions are not binded to any instances, mandatory to bind with instance or object or it goes for type error


----> Dynamic Binding

functions --- call , apply --- bind as well as invoke once,.
 bind --- bind and save for later invocation.

 Function invocation:

1) Function-invocation -- without obj
'this' ==> undefined (Strict mode) || Window(non-strict)
2) method-invocatoin(Static binding)
'this'==> invocation obj
3) call/apply/bind invocation(Dynamic binding)
'this' => arg-object

Arrow functions are always are binded to the invocation objects or creators


(q) =>{
    console.log(this.name+"anusering"+q);
}


