This test determines whether Odd or Even number with if/else if
====
var isEven = function(number) {

if(number % 2 === 0  ) {
    //console.log("The first number is even");
    return true;
} else if(isNaN(number)){
    return "The input is not even a number."
}
    else {
    //console.log("The first number is odd");
    return false;
}

};

isEven(12);
