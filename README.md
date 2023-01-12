# javascript
All my Javascript code and practice that I have done is available here with the output.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>javascript</title>
    <script> 
    console.log("hello, world");
    // assigning a varibale 
    var a;
    var b= 2;
    console.log(b)
    a=7;
    b=a;
    console.log(b)
    //use of  backslash
    var myString ="firstline\n\t\\secondline\n"
    console.log(myString)
    //concatinating a string
    var myname ="my first name"+" my second name"
    console.log(myname )
    //Another way to concatinate
    var name="hey call me vaishnav"
    name+= " but my surname is singh"
    console.log("name :"+ name)
    //find the length of the character
    var firstnamelength =   0;
    var firstname="vaishnav singh";
    firstnamelength =firstname.length;
    
    firstnamelength =firstname[0]
    console.log(firstnamelength)
    var lastname="vishu singh"
     var letterlastname=lastname[lastname.length-2];
    console.log(lastname.length-1);
    //representation of a multidimensional array
    var ourarray=[["vaishnav",34],["vishu", 16]]//2-d  array
    //finding the position of given array
    var array=[10,20,30];
    var ourdata= array[1];
    var ourdata = array[1];//20 is not showing in the output section
    var ourdata= array[2];
    console.log(ourdata);
    //replace an array with another array
    var newarray=[11,20,230];
    newarray[2]=30;
    console.log(newarray);
    newarray[0]=10;
    console.log(newarray);
    // find an array in an multidimensional array
    var arrayvalue =[[1,2,3],[4,5,6],[7,8,9],[[10,11,12],13,14]];
    var datahigh=arrayvalue[3][0][1];
    console.log(datahigh);
    //push and pop of an array
    var ourarray =  ["jhonny", "yespapa", "sugar"];
    ourarray.push(["nojhonny", "nopapa","nosugar"]);
    console.log(ourarray);
    ourarray.pop();
    console.log(ourarray);
    //shift and unshift function in array for javascript
    var array =["vaishnav","vishu","bhote"];
 console.log(array);
    array.shift();
    array.unshift("ansh");
    console.log(array);    
    //functions with arguments
    function args(a,b) {
        console.log(a-b);
        console.log(a+b);
        console.log(a*b);
        console.log(a/b);

    }
    args(10,2);
    //scope of a function
     function mylocalscope(){
        var myvar=5;
        console.log(myvar);
    
     }
    //local variable took precedence over global variable
    var outerwear =" t-shirt";  
    function outfit(){
      var outerwear= "sweater"
      return outerwear; 
    }
    console.log(outerwear); 
    console.log(outfit());
    //function use
    function minus(num){
      return num-7;

    }
    console.log(minus(7));
    var sum=0;
    function add(){
       sum+=5
    }
    console.log(add);
    function addfuntion(){
      sum+=10;

    }
   // console.log(addfunction);
    var changed =0;
    function change(num){
      return (num+5)/2;

    }
     changed=change(10);
     var processed=0;
     function process(num){
      return (num+3)/5;
      
     }
     processed=process(10);
       
        console.log(processed)
        console.log(changed)
       
       //string in line
       //json.stringyfy is used to convert an array into a string
       function nextInLine(array, item){
        array.push();
        return array.shift();

       }
       var testarray=[1,2,3,4,5];
       console.log("before"+ JSON.stringify(testarray))

       console.log(nextInLine(testarray,6))

       console.log("after" +JSON.stringify(testarray))
       //if statements
      
       function trueorfalse(isittrue){
        if(isittrue){
          return "yes,its true";

        }
        return "no,its false buddy";
       }
       console.log(trueorfalse(true));
        
       function teststrict(val){
        if(val===7){
          return "the value is strictly equal to seven"


        }
        return " the value is not equal to seven"

       }   
       
       console.log(teststrict(7));
 
  // == this check equaltiy
  // === this check whether it is strictly equal or not
  // comparison with the strictly inequality operator(!==)
  // test two logic at one time
  function testlogicalvalue(val){
    if(val<=20&& val>=10){
      return "you are right";

    }
   return " oops! you are wrong ";
  }
  console.log(testlogicalvalue(15));
  
 //switch case
 function switchcase(val){
  var answer="";
  switch(val){
    case 1:
    answer="alpha";
    break;
    case 2:
      answer="beta";
      break;
      case 3:
        answer="gamma";
        break;
        case 4:
          answer="delta";
          break;
          default :
          answer="stuff";
          break;
           

  }
return answer;

 }
 console.log(switchcase(3));
 // returning a boolean value
 function isless(a,b){
  return a<b;


 }  
 console.log(isless(2,4));

//objects
var testobject={
        "hat": "topi",
        "bat": "cricketer",
        "shoes slippers": "woodland"
};
 var hatvalue= testobject.hat;
 var shoesvalue = testobject["shoes slippers"];
 console.log(hatvalue); 
 console.log(shoesvalue);
 var name={
14: "vaishnav",
15: "rohan",
16: "ansh",
17: "shree ram"
 };
 var playernumber= 16;
 var player= playernumber[16];
 console.log();

</script>
</head>
<body>  
    
</body>
</html>
