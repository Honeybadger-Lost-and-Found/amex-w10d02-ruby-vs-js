# amex-w10d02-ruby-vs-js

![](https://zurich.impacthub.ch/wp-content/uploads/2016/01/55955100.jpg)

based on you reading last night can you convert these JS into Ruby ? 

```

const sayHi = (name) => { 
  console.log("Hi " + name );
}

const rectangleArea = (length, width) => { 
  return length * width ;
}



sayHi("Ghadeer")
Rectangle(2, 3)


// flatt an array remember !! 

// Abdulrab solution 

const arr = [1,[2,3,null,4],[null],5 , 1 , 2];
const result = [];

const flat =(element) => {
    if ( element != null && result.indexOf(element) < 0 ){
        result.push(element)
        return element
    };
};

const arr2 = arr.reduce((accumulator, currentValue) => accumulator.concat(currentValue),[]);
arr2.filter(el => flat(el));

console.log(result);


``
