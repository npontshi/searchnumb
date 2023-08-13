# searchnumb
JS natural numbers below 10 that are multiples of 3 or 5
//the sum of the multiples is 23(3,5,6 and 9).

const result = num =>{
  let multiple = 0;
  for(let i = 0; i<num; i++){

    if(i%3==0 || i %5==0){
      multiple += i;
      //console.log(multiple += i);
      //console.log(i);
      //console.log('break');
      //console.log(multiple);
      }
    }
}
console.log(result(10));
    
 
