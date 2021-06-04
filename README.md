# Database explanation
The database contains 24 strongly heterogeneous instances originally presented in Iori et al. (2020) and later used in Calzavara et al. (2021). The instances are separated into four groups, each containing six instances, characterized by different ranges for the number of items. Table 1 summarizes the details of the instances, reporting: ID number, number of item types, number of families, and total number of items. The instances have been created fropm a real-world database, although some randomized values have been included to preserve the company's privacy.

|ID|n|N. of families|Max b_i|
|:---:|:---:|:---:|:---:|
|1|20|4|877|
|2|20|12|269|
|3|23|4|388|
|4|23|13|115|
|5|29|6|438|
|6|29|15|2103|
|7|34|7|698|
|8|34|17|1322|
|9|37|6|300|
|10|37|17|449|
|11|48|9|395|
|12|48|18|748|
|13|59|10|455|
|14|59|19|633|
|15|64|11|658|
|16|64|19|683|
|17|61|10|300|
|18|61|19|797|
|19|75|16|790|
|20|75|20|829|
|21|79|17|855|
|22|79|21|944|
|23|66|13|738|
|24|66|19|767|             

## References
 - [Iori M, Locatelli M, Moreira MCO, Silveira T, “Solution of a Practical Pallet Building Problem with Visibility and Contiguity Constraints”, Proceedings of the 22nd International Conference on Enterprise Information Systems – Volume 1: ICEIS, 327-338 (2020)](https://www.scitepress.org/Link.aspx?doi=10.5220/0009351703270338)
 - [Calzavara G, Iori M, Locatelli M, Moreira MCO, Silveira T, “Mathematical Models and Heuristic Algorithms for Pallet Building Problems with Practical Constraints”, submitted technical report (2021)]()

# Instance description
```
7       //number of types of items
1000    //H (pallet)
1000    //W (pallet)
1000    //L (pallet)
10000   //Weight capacity (pallet)
0.75    //required fill factor

4           //Number of families
2; 5; 1; 10 //Stackability of each family

2;0           //ITEM 1: number of items of first type; family number (start from 0)
268;198;187;7 //ITEM 1: h,w,l,weight
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
```
