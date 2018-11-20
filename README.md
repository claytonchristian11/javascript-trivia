# javascript-trivia
null -> object. typeof bar === 'object'

a = b = 3; -> b = 3; var a = b; 
b is defined as global, a is defined as var

easy str manipulation for palindrome (str == str.split('').reverse().join(''));

array manipulation modifies original ie:
var arr1 = "john".split('');
var arr2 = arr1.reverse();
var arr3 = "jones".split('');
arr2.push(arr3);
# ['n','h','o','j', ['j','o','n','e','s'] ]
