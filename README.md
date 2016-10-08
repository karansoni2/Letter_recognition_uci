# Letter_recognition_uci
A basic mini-project using the UCI letter recognition Dataset.

Data Set Information:
The objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15. We typically train on the first 16000 items and then use the resulting model to predict the letter category for the remaining 4000.

Possible problem statement 1:
=> Every hand written letter in enlish can correspond to one of the 26 letters(Capitals), each character will have certain dimeansions and based on 15 attributes the letter will be mapped, the objective is to implement a working system that can recognize the hand written letter correctly. We have 16,000 values with its corresponding alphabet, using this as a reference we need to use the remainig 4,000 datasets to map its corresponding alphabet and find out if the dataset is accurate and this system of data recognition works.

possible problem statement 2:
==> Everyperson has a differnt handwriting style, this could be read by anyother person; but if we were to have these documents scanned and have them digitally stored in a computer, The computer cannot understand what is written; Our goal is to use data mining techniques and methods so that written or printed words can be scanned and saved in a computer in the form of text.


Attribute Information:

1.	lettr	capital letter	(26 values from A to Z) 
2.	x-box	horizontal position of box	(integer) 
3.	y-box	vertical position of box	(integer) 
4.	width	width of box	(integer) 
5.	high height of box	(integer) 
6.	onpix	total # on pixels	(integer) 
7.	x-bar	mean x of on pixels in box	(integer) 
8.	y-bar	mean y of on pixels in box	(integer) 
9.	x2bar	mean x variance	(integer) 
10.	y2bar	mean y variance	(integer) 
11.	xybar	mean x y correlation	(integer) 
12.	x2ybr	mean of x * x * y	(integer) 
13.	xy2br	mean of x * y * y	(integer) 
14.	x-ege	mean edge count left to right	(integer) 
15.	xegvy	correlation of x-ege with y	(integer) 
16.	y-ege	mean edge count bottom to top	(integer) 
17.	yegvx	correlation of y-ege with x	(integer)

Result attribute

prediction - Possible values- 0=NO 1=YES

Error Calculation:
Based on Result attribute generated.
