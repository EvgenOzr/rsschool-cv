# Evgeny Akimov
## Russia Moscow
###Skills
*JS
*TS
*React
*Redux
*Css
*Sass
*TailwindCSS
*Git
###Discord nick: evgen_ozz

###Codewars solution
function findOutlier(integers){
  //your code here
	const odd = [],
		even = [];
	integers.forEach((elem) => {
		(elem % 2 === 0) ? even.push(elem) : odd.push(elem)
	})
	// console.log(odd, even);

	if(even.length < odd.length){
		return (even[0])
	} else {
		return(odd[0])
	}
}
