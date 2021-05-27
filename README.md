# Instances explanation
Pallet Building Problem Instances


# General explanation
This database contains 24  strongly  heterogeneous  instances originally presented in ***Solution of a Practical Pallet Building Problem with Visibility and Contiguity Constraints*** by  Iori  et  al. (2019), that  are  separated  into  4  groups,  each  containing  6  instances,  characterized  by different intervals in the number of distinct items. Table 1 summarizes the details of the instances, reporting an instance field and its respective value by row: ID number,  number  of  item  types,  number  of  families,  and  total  number  of  items. The respective instances are based on realistic cases, although some randomized values are included to preserve the company's privacy. 

|ID|n|N. of families|Max b_i|
|:---:|:---:|:---:|:---:|
|1|20|4|877|
|2||12|269|
|3|23|4|388|
|4||13|115|
|5|29|6|438|
|6||15|2103|
|7|34|7|698|
|8||17|1322|
|9|37|6|300|
|10||17|449|
|11|48|9|395|
|12||18|748|
|13|59|10|455|
|14||19|633|
|15|64|11|658|
|16||19|683|
|17|61|10|300|
|18||19|797|
|19|75|16|790|
|20||20|829|
|21|79|17|855|
|22||21|944|
|23|66|13|738|
|24||19|767|             

## Simple instances analysys
These instances are interesting to be solved because it allows us to carry a broad analysis of the algorithm performance for containing easy and hard cases. The  larger  the  number  of  item  types,  families  and  items  is,  the  more  complex becomes  the  instance  to  be  solved.  Specifically,  an  instance  in  that  database  is more complex when the number of item types is greater than or equal to 50; thenumber of families is grater than or equal to 15; the total of items is grater than or equal to 700.

# Instance description
7  	    //number of types of items
1000 	  //H 
1000 	  //W
1000 	  //L
10000 	//Weight capacity
0.75 	  //fill factor (will be in another file with parameters)

4     	    //Number of families
2; 5; 1; 10	//Stackability of each family

2;0		        //ITEM 1: Number of items of first type; Family number (start from 0)
268;198;187;7	//ITEM 1: h,w,l,weight
66;0          //ITEM 2: [...]
402;303;184;9
4;1
340;230;19;9
11;2
285;193;328;10
10;3
264;194;241;5
17;3
264;195;235;4
9;3
218;140;240;4
