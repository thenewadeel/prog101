# Mathematics

## Set Theory

### Set

A collection of **unique** objects / elements

### Function

An operation that maps elements of set A onto another set B
e.g isOdd() maps  (indirectly, since it is a boolean function) elements from the set of Natural Nos to the set of Odd nos; directly mapping to the *Assertion* set  {True, False}

### Domain

The stuff on which the function operates is it's domain (The set A as per the def of functions)

### Range

All possible results of a function are called it's Range (The set B as per the def of functions)


### Appl in Programming

once you declare a variable, you are telling the compiler about the set that will hold your values. E.g int a; means you are working on N ( The set of Natural Nos)

### Student asks...:

#### Arrays

* [] universal programming lang identifier for arrays
* Common operations
	* define	-	declare
	type name = [ ]
	type name = [el,el2,el4]
	int i= [1,2];
	bool results = [1,0,0];

	* add stuff	-	push
	arrayName.push(newElement);
	i.push(12)
	int i=[1,2,3,4,5];
	i[3] = 23;// in C you change already allocated numbers.....at beginner level
	* get stuff	-	pop
	arrayName.pop() // will return the last el of the array and remove it from the array
	* traverse the array	-	iterate
	Loops
	for(int i=0; i < array.length; i++){
		// do something with the element i.e. arrayName[i]
		}
	arrayName.forEach( el in arrayName){
		// do something with the element i.e el
		}
	advanced tenhniques to iterate an array include search algos
