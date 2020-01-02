# bagging
Bagging is a technique used to improve the effeciency of the predictive model.Here we generate multiple decision trees based on different 
data set.Once we obtain all the data set we aggregate the obtained result to arrive at a correct prediction with with least error rate.
In the present program we have considered 3 data sets with data points 15,13 and 12 (in1.txt,in2.txt,in3.txt)respectively.

Once we get the data set ,we generate three different graphs for each of the data set by redirecting the output to the dot file.the output
btained are out1.txt,out2.txt,out3.txt.The graphs hence generated are graph1.png,graph2.png,graph3.png.

Now the predictive model is trained with the help the trainning data set.We test it by givin a random data point.Here the case considered is
body_temperatue-0(cold),gives_birth-0(no),aerial-0(no),aquatic-1(yes),has_legs-0(no),hibernates-0(no).The prection made by each of the three
models is present int the text files result1.txt,result2.txt,result3.txt which are later concatenated into a single file result.txt.

In bagging if it is a regression model then the result of prediction would be the average of the values obtained by the predictive models,
but in classsification model majority vote is considered.
By clear observation we can make out that the class predicted by three models is "fish".So the class of the data point which was given to
predict is "fish".

Therefore with the help of bagging we can arrive at a most accurate result.
