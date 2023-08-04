#JavaScript LoopChallenges

// Challenge 1:Print odds 1-20
for (var i = 1; i < 21; i++) {
    if(i % 2 === 1){
        console.log(i);
    }
}

// Challenge 2:Decreasing Multiples of 3
for (var i = 100; i > 0; i--) {
    if(i % 3 === 0){
        console.log(i);
    }
}


// Challenge 3:Print the sequence
const values = [-0.5, 4, -3.5, 1, 2.5, -2];
var ordered = [];
    for (var i = 0; i < values.length; i ++) {
        ordered.push(values[i]);
    }
    console.log(values);
    console.log("Ordered is",ordered.sort((a, b) => b - a));


// Challenge 4:Sigma
var sum = 0;
    for (var i = 1; i < 101; i ++) {
        sum += i;
    }
    console.log(sum); //output 5050

// Challenge 5:Factorial
var sum = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12];
var value = 1;
for( var i = 0; i <sum.length; i++){
    value *= sum[i];
}
console.log(sum);
console.log('Factorial value is',value); //output 479001600