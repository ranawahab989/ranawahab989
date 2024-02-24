


// =========================== Q No 01 ====================//


let num = +prompt("Enter Your Number");


if(num%6 == 0){
    document.write("Your number is Multiple of 6")
}
else{document.write("Your number is Not multiple of 6")
}





// =========================== Q No 02 ====================//


let score = +prompt("Enter Your Percentage");
let grade;

if(score >=90 && score <=100){
        console.log("A+");}
else if(score >=70 && score <=89){
    console.log("A");}
    else if(score >=50 && score <=69){
        console.log("B");}
        else if(score >=0 && score <=49){
            console.log("Fail");}



            
// =========================== Q No 03 ====================//

var name = prompt("name")
var eng = prompt("eng")
var urdu = prompt("urd")
var phy = prompt("phy")
var chem = prompt("chem")
var bio = prompt("bio")
var total = eng + urdu + phy + chem + bio;
var Percentage = (total / 500) * 100;


if (Percentage >= 90 && Percentage <= 100){
    console.log(name + "Your Grade is A+" + Percentage+"%");
}else if (Percentage >= 70 && Percentage <= 89){
    console.log(name + "Your Grade is A" + Percentage+"%")}
    else if (Percentage >= 50 && Percentage <= 69){
        console.log(name + "Your Grade is B" + Percentage+"%")}
    else if (Percentage >= 0 && Percentage <= 49){
        console.log(name + "Your Grade is fail" + Percentage+"%")}
    else{ console.log("Invalid Number");
    }
