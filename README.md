# North-West-Corner--NWC-
 A method for solving Transportation Problem

North-West Corner Method (NWCM) Steps (Rule)
Step-1:	Select the upper left corner cell of the transportation matrix and allocate min(s1, d1).
Step-2:
	a. Subtract this value from supply and demand of respective row and column.
	b. If the supply is 0, then cross (strike) that row and move down to the next cell.
	c. If the demand is 0, then cross (strike) that column and move right to the next cell.
	d. If supply and demand both are 0, then cross (strike) both row & column and move diagonally to the next cell.
Step-3:	Repeact this steps until all supply and demand values are 0.

Source: https://cbom.atozmath.com/example/CBOM/Transportation.aspx?he=e&q=nwcm&ex=0
