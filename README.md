# JavaScript
What is JavaSript..???
/**************************IN 1996 JAVASCRIPT WAS CREATED ********************************8 */

//write a program to calculate leap yyear
// var year = 2020;
// if(year % 4 == 0){
//     if(year % 100 == 0 ){
//       if(year % 400 == 0){
//         console.log("The year " + year + " is a leap year");
//       }else{
//         console.log("The year " + year + "is not a leap year");
//       }
//     }else{
//     console.log("The year " + year + "is a leap year");
// }
// }
// else{
//     console.log("The year " + year + "is not a leap year");
// }

//what is truthy and fasly in javascript we have total 5 fasly values in javascript 0 , undefined ,null , NAN,false 
// if(score = 0){
//     console.log("You lose the game ");
// }else{
//     console.log("yay, we won the game");
// }       
  
//the tranary operator in javascript that takes three operands 5+ 20 5 and 20 is operand and + is operator

//var age = 17;
// if(age >= 18){
//     console.log("you are eligiable for the vote ");
// }
// else{
//     console.log("you are not  eligiable for the vote ");
// }

// var age = 17;
// console.log((age>= 18)? "You can Vote" : "You can't vote");

//Switch statement in javascript find the area of circle and triangle and rectangle 


// var area = circle;
// var PI = 3.12 , L=5 , b=4 , r=3;

// switch(area){
//     case 'circle':
//         consolelog("the area of the circle is " +   PI*r**2 );
//         break;
//     case 'triangle':
//         consolelog("the area of the Triangle is " + (L*b)/2);
//         break;
//     case 'rectangle':
//             consolelog("the area of the Rectangle is " + (L*b));
//             break;
//      default:
//         console.log("Plz enter a vaild data");      
// }

//write a program to print table
var num;

for(num=1;  num<=10; num++){
    var tableof = 8 ;
  console.log(tableof + " X "  + num  + " = " +  tableof*num);
} 


//functions in javascript
//A javascript function is a blocck of  code designed to pweform a particular task
//A function definition also called  a function declaration or function statement the name of function , 
function sum(a,b){
   var a = 10 , b=20;
   var total = a+b;
   console.log(total);
}
sum();

// why function ??
//we use  resuse the code once and use it many times .
//you can use thr same code many times with different arguments
// to produce different result
//A function is a group of resuable code which can  be called be anywhere in you program this  elmininates the need of writing  the same code again and agianfunction sum(a,b){
  function sum(a,b){
    var total = a+b;
    console.log(total);
 }
  var funExp = sum(5,15);
  
  
 //Return keyword in javascriipt
 //when javascript reaches a return statement, the function will stop executing functions often compute a return value the return value is retured back to the callerfunction sum(a,b){
//   function sum(a,b){
//     return total = a + b;
//  }
//   var funExp = sum(5,15);
//   console.log('the sum of two number is ' +funExp);

//What is Anonymous function 
//A function is similar to and  and has the same syntax as a function declaration one can define " named" function expressions where the name of the experssion might be used in the call stack for example or "annonymous function experssion" 
// the function without no name is called anoonymous function 
