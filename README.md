//bai 1 
function findOppositeNumber(a,b) {
for (let i = 4; i < 20; i++) {
    if (b <= a/2) { 
     if  (a - 1 - i + b == i - b + 1) {
        return i
    } 
    } if (b > a/2) {
     if (a - 1 - b + i == b - i + 1) {
         return i
     }   
    }
}
}

//bai2 
let s1 = ["abc"]
let s2 = [123]
var str1 = s1.split("") 
var str2 = s2.split("")
let x = str1[1] + str2[1] 
var full = arr.concat (str1[1] + str2[1])
console.log(x)
