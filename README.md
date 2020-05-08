# answer.js

setting and swapping

var myNumber = 42;
var myName = 'chaya';
var temp = myNumber;
myNumber = myName;
myName = temp;

print -52 to 1066

for(i = -52; i <= 1066; i++){
  console.log(i);
  }
  
don't worry be happy

 function beCheerful(){
  console.log("good morning!");
  }
  
  for(var i = 0; i < 98; i++){
    beCheerful();
  }


multiples of three - but not all

for( i = - 300; i <= 0; i ++){
  if(i%3==0){
    if(i=== -3 || i === -6){
      continue;
    }
      console.log(i);
   
  }
}


printing integers with while

var i = 2000;
while(i <= 5280){
  console.log(i);
   i += 1;
  }
  
  
 you say it's your birthday 
  
var chayasBirthMonth = 5;
var chayasBirthDay = 2;
function birthday(day, month, a, b){
if(day === a && month === b || day === b && month ===a){
    console.log("How did you know?");
}
  else{
    console.log("Just another day...")
  }
}

leap year

function leap_year(year){
  if(year%100 === 0){
     if(year % 400 === 0){
       return true;
     }
    else{
     return false;
    }
  }
  else{
     if(year%4 === 0){
       return true;
     }
    else{
      return false;
    }
  }
}
console.log(leap_year(2020));


 print and count
 
var arr = [];
for(i = 512; i <= 4096; i++){
   if(i % 5 ===0){
     arr.push(i);
   }
}
console.log(arr);
console.log(arr.length);

multiples of six

var i = 6;
while(i <= 60000){
  if(i % 6 === 0){
    console.log(i);
      i += 6;
  }
}

counting, the dojo way!

for(var i = 1; i <= 100; i++){
  if(i % 5 === 0){
    console.log('coding');
  }
  else{
    console.log(i);
  }
  if(i % 10 === 0){
        console.log('dojo');
  }  
}

what do you know?

function what_do_you_know(incoming){
  console.log(incoming);
}

whoa, that sucker's huge
(spoiler alert my attempt did NOT work)

var arr = [];
var i = -300000;
while(i <= 300000){
  if(i%2 === !0){
    arr.push(i);
    i += 1;
  }
  else{
    continue;
  }
  console.log(arr);
}

countdown by fours

var fours = 2016;
while(fours > 0){
  console.log(fours);
  fours-=4;
}

flexible countdown

function flexible_countdown(lowNum, highNum, mult){
  for(var i = highNum; i > lowNum; i -= 1){
    if(i%mult === 0){
      console.log(i);
    }
  }
}
flexible_countdown(2, 9, 3);

the final countdown

function the_final_countdown(param1, param2, param3, param4) {
  var i = param2;
   while(i <= param3) {
       if(i%param1 === 0) {
         if(i !== param4){
           console.log(i);
         }
       }
     i++;
   }
}
the_final_countdown(3,5,17,9);
