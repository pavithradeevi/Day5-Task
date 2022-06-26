**1.Print odd numbers in an array**
  var a=[1,2,3,4,5,6]
  if(a%2)!=0;
  {
  console.log("its odd",+a)
  };
  else
  {
  console.log("its even")};

**********************************************
  
var a = [1,2,3,4,5,6,7,8,9,10,11,12]

let odd = a.filter(n => n%2)

console.log(odd)
  
  
  **2.Convert all the strings to title caps in a string array**
  
  function title(str){
  return str.toLowerCase().split(" ").map(function(words){
    return (words.charAt(0).toUpperCase() +words.slice(1));
  }).join(" ");
}
console.log(title("we are strong"));

*************************************************

var a = ['Pavi', 'asu', 'real', 'vivan'];

const b = a.map(name => name.toUpperCase());

console.log(b);


3.Sum of all numbers in an array

var a=[1,2,3,4]
var sum=0;
for(var i=0;i<a.length;i++)
{
  sum=sum+a[i]}  
console.log(sum)

************************************

var a=[1,2,3,4]
var sum=0;
a.forEach(b=>{
sum=sum+b;
});
console.log(sum);


4.Return all the prime numbers in an array


function sort(num){
  var num1=[];
  var num2=[];
  for(var i=0;i<=num;i++){
    num2.push(true);
  }
  for(var i=2;i<=num;i++)
  {
    if(num2[i]){
      num1.push(i);
      for(var j=0;i*j<=num;j++){
        num2[i*j]=false;
      }}}
      
      return num1;
}

console.log(sort(10))


5.Return all the palindrome in an array

var str="mom";
var strreverse=str.split("").reverse().join("");

if (str===strreverse)
{
  console.log("the string is palindrome");
}
else
{
  console.log("not")
}


6.Remove duplicate from an array

var a=['a','b','c','a','d','a','b']
var b=[...new Set(a)];

console.log(b)





  
