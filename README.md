Download Link: https://assignmentchef.com/product/solved-homework-1-solution
<br>
<strong>Exercise 1</strong>

Governments and companies worldwide are becoming increasingly concerned with carbon footprints (annual releases of carbon dioxide into the atmosphere) from buildings burning various types of fuel for heat, vehicles burning fuels for power, and the like.

<ol>

 <li>Create 3 small classes unrelated by inheritance: Building, Car, and Bicycle</li>

 <li>Give each class the unique attributes and behaviors as specified in the class diagram in Figure 1 below. Create a single constructor for each class to allow consumers of the class to provide initial values for each attribute.</li>

 <li>Write an interface CarbonFootprint with a getCarbonFootprint</li>

 <li>Have each of your classes implement that interface so that its getCarbonFootprint method calculates the appropriate carbon footprint for that class, as specified below:

  <ol start="10">

   <li>Building footprint = ([monthly gas bill / 10.68] * 119.58 * 12) + ([monthly electric bill / 0.1188] * 1232 * 12)</li>

   <li>Car footprint = miles driven per year / miles per gallon * 19.82</li>

   <li>Bicycle footprint = miles traveled per month * 0.9</li>

  </ol></li>

 <li>Write an application that does the following:

  <ol>

   <li>Creates objects of each of the 3 classes</li>

   <li>Places references to those objects in an array of CarbonFootprint</li>

   <li>Iterates through the array, polymorphically invoking each object’s getCarbonFootprint method</li>

   <li>For each object, print identifying information, such as miles traveled or monthly bill amount, along with the object’s carbon footprint.</li>

  </ol></li>

</ol>




<strong>Exercise 2</strong>

Extend Exercise 1 by creating and demonstrating the use of an InvalidFootprintException class.

<ol>

 <li>Create the 4 constructors as discussed in this module/week’s presentations.</li>

 <li>Extend the appropriate superclass.</li>

 <li>Throw the InvalidFootprintException in the constructor of the Building, Car, and Bicycle classes if any of the provided parameter values are negative.</li>

 <li>Add code in your main method that handles the InvalidFootprintException, and write code that demonstrates that your handler works (i.e., write code that purposefully causes the InvalidFootprintException to be thrown, but then ensure that it does not crash your program). Instead of crashing, your main method must print a message to the error stream that an invalid footprint was detected.</li>

</ol>




Figure 1. Exercise 1 Class Diagram














