*It is Pune based co-op marketing and monetisation startup*
More info, click this 👉🏼 (https://yourstory.com/2020/12/startup-funding-onlinesalesai-pre-series-b-round-ivycap-ventures-core91/amp)

I did well in R1 interview, but in 2nd round I was asked various question:
1. Architechture:- how UI/UX of home page of amazon.in works?
2. Redux: How Redux plays a pivotal role here ?
3. Lastly gave a code challenge, which I did almost 70% but not able to complete that.
  Question:
 `Write a function that takes two parameters as array (arr) and number(k), where you need to find unique pair among the array where the combination of any two number is a K.`
 Ex: 
 ```
 var arr = [1,3,5,5,7,9];
 var k = 10;
findUniquePair(a,k)  
[1,9], [3,7], [5,5]   \\output

\\Sol:

const findUniquePair=(arr, k)=>{
	let returnedArr=[];
	for (let i=0; i < arr.length; i++){
		for (let j=i+1; j< arr.length; j++){
			if (arr[i] + arr[j] == k){
				returnedArr.push([arr[i], arr[j]])
			}
		}
	}
  return returnedArr;
} 
```

Result: **Rejected**
