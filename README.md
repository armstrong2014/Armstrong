Armstrong
=========
<img src="http://chicagoagentmagazine.com/wp-content/uploads/2012/11/real-estate-numbers-game-trulia-jed-kolko-asking-prices-housing-patterns.jpg"/></img>
Domain Specific Language (DSL) for describing recreational numbers 

Most programmers of our generation has written a program for finding the Armstrong numbers. 
Armstrong numbers are a special kind of number where each digit raise to the power of three 
and added together generates the same number. 153 is an armstrong number. 

Mathematicians are not always great programmers. That's ok. Thanks to functional programming techniques. 
We can create 

"Armstrong" is an external DSL for describing such numbers in almost plain English like syntax.  
For example consider these 

                      Armstrong (DSL for Number Theory) Code
		------------------------------------------------------------------
		//Definition of "Armstrong Number" is 
			Sum of the cube of the digits of the number is the number itself.
		//Definition of "Dudeney Number" is 
			Cube of the sum of the digits of the number is the number itself.
	        //Definition of "Sum-Product-Number" is 
			Sum of the digits of the number * product of the digits of the number is the number itself.
		//Definition of "Factorions" is 
			Sum of the factorial of the digits of the number is the number itself.
		----------------------------------------------------------------------------

The provided "Armstrong Console" is where 
