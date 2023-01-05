# recruitement-test

https://www.codewars.com/kata/mumbling
solution : 
function accum(s) {
  const arr = []
	for (let i = 0; i<s.length; i++){
    arr.push(s[i].toLowerCase().repeat(i+1))

  } 
  for (let i = 0; i < arr.length; i++) {
  arr[i] = arr[i].charAt(0).toUpperCase() + arr[i].slice(1);

  }
  
   return(arr.join('-')) 
}
