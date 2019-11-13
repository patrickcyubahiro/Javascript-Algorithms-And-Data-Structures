//Only change code below this line
function countdown(myArray, n){
  if(n <= 0){
    return;
  }
  else{
    myArray.push(n);
    countdown(myArray, n - 1);
  }
}