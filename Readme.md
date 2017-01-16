# Functional programming in the batcave

## Here are 100 things that you need to know about Functional programming.
___

1. Functions should just return values
2. Named vs anonymous functions
    ```
    function fun(){
      return "this is funny";
    }

    var anonfun =function(){
      return "this is an anonymous function"
    }
    ```
3. Scope - what variables do I have access to at a given time?
4. Functions are Objects
5. Functions have built in methods:
    - __defineGetter__
    - __defineSetter__
    - __loopupGetter__
    - __lookupSetter__
    - bind
    - call - say.call(null,"Morgan","I like cookies");
    - caller
    - constructor
    - hasOwnProperty
    - isPrototypeOf
    - length
    - name
    - propertyIsEnumerable
    - prototype
    - toLocaleString
    - toString
    - valueOf
6. Convert your code from imperative (tell the computer what to do step by step) to declarative (functional style, let the computer do the work for you. Don't repeat yourself DRY)
