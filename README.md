Machine Learning (CS 5710 (CRN: 22002)) Assignment - 1 Student Name: Vinay Kumar Camarushi Student 700#: 700740428

This repository contains the solution to Assignemnt - 1 of the course Machine Learning (CS 5710) at the University of Central Missouri.

Link to the video recording : https://drive.google.com/file/d/1QuBmS75VNiP5o1_pJxoug6G7xg5mUpOk/view?usp=sharing

Question – 1 The following is a list of 10 students ages: ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24] • Sort the list and find the min and max age  Here we have sorted the list using sorted() method and stored the sorted list in sorted_ages list.  We used min() method to get the minimum value of the list and max() method to get the maximum value of he list.  The we printed the list in the minimum, maximum values of the list along with the sorted list in Ascending order and Descending order.

• Add the min age and the max age again to the list  Here we used the append method to add the minimum and maximum values of the list to the sorted list sorted_ages.  We then printed the list to which the minimum and maximum values of the list are added.

• Find the median age (one middle item or two middle items divided by two)  Here we used a user defined method ‘median’ to calculate the median of the list.  The operations done inside the median method is  Sort the given list.  Find the length of the list.  Find the middle index of the list  To find out if there is one middle value or 2 middle values in the list.  If there is one middle value, it would be the median of the list.  If there are 2 middle values, then the average of the 2 middle values would be the mean.  And then call the method, get the median value, store it in a variable named median_ages and print the median values.

• Find the average age (sum of all items divided by their number)  Here we calculated the sum of the values of the list by using sum() method.  We calculated the number of elements of the list using len() method.  We divided the sum of the list with length of the list to get the Average of the list.  We then printed the Average of the list.

• Find the range of the ages (max minus min) Solution:  We used the maximum value and minimum values of the list which was calculated previously and subtracted the minimum value from the maximum value to get the range of the list and stored it in a variable named ranges_ages.  We then printed the range value.

Question – 2 • Create an empty dictionary called dog.  Here we are creating an empty dictionary named dog.

• Add name, color, breed, legs, age to the dog dictionary  Here we added the given attributes to the dictionary one by one using the assignment operator.  And then we printed the dictionary.

• Create a student dictionary and add first_name, last_name, gender, age, marital status, skills, country, city and address as keys for the dictionary  Here we are Initializing student Dictionary with given attributes  And then printing the dictionary.

• Get the length of the student dictionary  Here we got the length of the student Dictionary using the len() method.  • Get the value of skills and check the data type, it should be a list  Here we got the values of the dictionary using values() method.  To check the type of the values we used type() method.

• Modify the skills values by adding one or two skills  We used the extend method to add values to the skills key in the Student Dictionary.

• Get the dictionary keys as a list  We used the keys() method to get the keys and type casted it to a list.

• Get the dictionary values as a list  We used the values() method to get the values of the keys and type casted it to a list.

Question – 3 • Create a tuple containing names of your sisters and your brothers (imaginary siblings are fine)  We initialized brothers and sisters tuples with sample data.

• Join brothers and sisters tuples and assign it to siblings  We joined the brothers and sisters tuples using the + operator and stored it in siblings tuple.

• How many siblings do you have?  Calculated the number of siblings using len() method.

• Modify the siblings tuple and add the name of your father and mother and assign it to family_members  Father and Mother got added to the tuple using + operator and the resulting tuple is stored in the family_members tuple.

Question – 4 it_companies = {'Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon'} A = {19, 22, 24, 20, 25, 26} B = {19, 22, 20, 25, 26, 24, 28, 27} age = [22, 19, 24, 25, 26, 24, 25, 24]

• Find the length of the set it_companies  We found out the length of the set using len() method.

• Add 'Twitter' to it_companies  Twitter got added using the add() method.

• Insert multiple IT companies at once to the set it_companies  Multiple values are added to the tuple using update() method.

• Remove one of the companies from the set it_companies  One of the company is removed using remove() method.

• What is the difference between remove and discard ?  Both of the methods do the same work (i.e.), removes the element from the set only if the element is present in the set. the only difference is remove() method throws an error/exception if the element is not present in the set which is supposed to be removed and the discard method does not throw the exception. • Join A and B  The sets A & B are joined using the union operator ‘|’.

• Find A intersection B  Intersection of the 2 sets are done using the intersection() method.

• Is A subset of B  The above statement is verified by using issubset() method.

• Are A and B disjoint sets  2 sets are said to be disjoint if there are no common elements in the sets.  Here intersection is done for both the sets and if there are common elements, then not disjoint sets is printed or else, disjoint set is printed using an if loop.

• Join A with B and B with A  B is joined to A using the update() method and A is joined to B using the same method.

• What is the symmetric difference between A and B  Symmetric difference is calculated using the symmetric_difference() method.

• Delete the sets completely  Both the sets are deleted using the del method.

• Convert the ages to a set and compare the length of the list and the set  The length of the set and list are calculated using the len() method.

Question – 5 The radius of a circle is 30 meters. • Calculate the area of a circle and assign the value to a variable name of area_of_circle  Here the area of the circle is calculated using pirr and the value is stored in the variable area_of_circle.

• Calculate the circumference of a circle and assign the value to a variable name of circum_of_circle  Here the perimeter of the circle is calculated using 2pir and the value is stored in the variable circum _of_circle.

• Take radius as user input and calculate the area.  Here the radius is taken as a user input and the area of the circle is calculated.

Question – 6 “I am a teacher and I love to inspire and teach people” • How many unique words have been used in the sentence? Use the split methods and set to get the unique words.  Here the string is divided at spaces using split() method and the resulting list is converted to a set to get the unique values of the string and len() method is used to get the number of unique words.

Question – 7 Use a tab escape sequence to get the following lines. Name Age Country City Asabeneh 250 Finland Helsinki  Here \t is used for a tab and \n is used for new line in the print statement.

Question – 8 Use the string formatting method to display the following: radius = 10 area = 3.14 * radius ** 2 • “The area of a circle with radius 10 is 314 meters square.  .format() method is used to get the desired output.

Question – 9 Write a program, which reads weights (lbs.) of N students into a list and convert these weights to kilograms in a separate list using Loop. N: No of students (Read input from user) Ex: L1: [150, 155, 145, 148] Output: [68.03, 70.3, 65.77, 67.13]  Here 2 empty lists are initialized to store the weights in lbs and kgs.  The number of weights are taken as user input.  Then the values of user input weights in lbs is added to the lbs list.  Then using a for loop the values in lbs are converted to kgs and gets added to list of kgs.

Question - 10 The diagram below shows a dataset with 2 classes and 8 data points, each with only one feature value, labeled f. Note that there are two data points with the same feature value of 6. These are shown as two x’s one above the other. Provide stepwise mathematical solution, do not write code for it.

Divide this data equally into two parts. Use first part as training and second part as testing. Using KNN classifier, for K=3, what would be the predicted outputs for the test samples? Show how you arrived at your answer. Solution As per the given data, let’s assume that 0 represents a dot and 1 represents a cross. So the data points would be (1, 0), (2, 1), (3, 1), (6, 1), (6, 1), (7, 0), (10, 0), (11, 0). By dividing the dataset into equal parts randomly we get, The training set to be (2, 1), (6, 1), (7, 0), (11, 0). The test set to be (1, 0), (3, 1), (6, 1), (10, 0). Now by calculating the distances of each test point from each of the train set, we would get the following table. Here we would consider 3 nearest points from the 4 training points and predict the y co-ordinate value of test data point with majority value in the y co-ordinate of the training points. As we see for the first test point, we have two 1’s and one 0 in the nearest 3 points of the training set, hence we predicted the y co-ordinate value of test point to be 1. Similarly for the second test point, we have two 1’s and one 0 in the nearest 3 points of the training set, hence we predicted the y co-ordinate value of test point to be 1. Similarly for the third test point, we have two 1’s and one 0 in the nearest 3 points of the training set, hence we predicted the y co-ordinate value of test point to be 1. Similarly for the fourth test point, we have two 0’s and one 1 in the nearest 3 points of the training set, hence we predicted the y co-ordinate value of test point to be 0.
Train Set

Test Set (2, 1) (6, 1) (7, 0) (11, 0) KNN classifier, for K=3 (predicted output) Actual Output (1, 0) 1.414 5.099 6.0 10 1 0 (3, 1) 1.0 3.1 5.099 9.055 1 1 (6, 1) 4.0 0.0 1.414 5.099 1 1 (10, 0) 8.06 4.123 3 4 0 0

( Note: The distances between the points is calculated by the Euclidean Formula The distance between the points (x1,y1) and (x2,y2) is distance = ((x1 - x2)^2 + (y1 - y2)^2)^0.5 )

Compute the confusion matrix for this and calculate accuracy, sensitivity and specificity values Solution:
As per the above table, the confusion matrix is [1 1] [0 2]  TP = 2  TN = 1  FP = 1  FN = 0 Accuracy: Accuracy = (TP+TN)/(P+N) = ¾ = 0.75 % Sensitivity: Sensitivity = TP/(TP+FN) = TP/P = 2/(2+0) = 100 % Specificity: Specificity = TN/(FP+TN) = TN/N = 1/(2) = 50 %
