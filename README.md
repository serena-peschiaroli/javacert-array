

- 1. 

Given the code fragment:

 

List names = new ArrayList<>();

names.add(“Joel“);

names.add(“Paul“);

names.remove(0);

names.remove(0);

System.out.println(names.isEmpty());

names.add(“Joel“);

names.add(“Paul“);

names.clear();

System.out.println(names.isEmpty());

 

What is the result?

The are 1 correct answers
FALSE TRUE
- [x] TRUE TRUE
FALSE FALSE
A runtime exception is thrown



_____________________________________________________________________

- 2. 

Which of the following are legal declarations?

The are 1 correct answers

float[] lion = new float[];
- [x] float[] tiger = new float[1];
float[] bear = new[] float;
float[] ohMy = new[1] float;
All of the above
None of the above

________________________________________________________________________

- 3. 

What happens when calling the following method with a non-null and non-empty array?


public static void addStationName(String[] names) {

  names[names.length] = “Times Square“;
}

The are 1 correct answers

It adds an element to the array the value of which isTimes Square.
It replaces the last element in the array with the valueTimes Square.
It does not compile.
- [x] It throws an exception.
None of the above.
It creates a new array with the same name and insert the value Time Square in it.


_______________________________________________________________________

- 4. 

Which line fails to compile first?

20: List list = Arrays.asList(‘a’, ‘b’, ‘c’);

21: Char letter1 = list.get(0);

22: char letter2 = list.get(0);

23: int letter3 = list.get(0);

24: Integer letter4 = list.get(0);

25: Object letter5 = list.get(0);

The are 1 correct answers

20
- [x] 21
22
23
24
25



_______________________________________________________________________-

- 5. 

Given the code fragment:


List fls = new ArrayList<>();

fls.add(“jasmine“);

fls.add(“rose“);

fls.add(“lotus“);

fls.remove(2);

fls.set(2, “lily“);

System.out.println(fls);


What is the result?

The are 1 correct answers
[jasmine, rose, lily]
- [x] A runtime exception is thrown
[jasmine, lily, lotus]
[jasmine, rose, lotus, lily]


__________________________________________________________________

- 6. 

How many lines does the following code output?


var days = new String[] { “Sunday“, “Monday“, “Tuesday“, “Wednesday“, “Thursday“, “Friday“, “Saturday“ };

for (int i = 1; i <= days.length; i++)
  System.out.println(days[i]);

The are 1 correct answers
 Six
Seven
The code does not compile.
- [x] The code compiles but throws an exception at runtime.
None of the above
The output is different every time .

________________________________________________________________________
- 7. 

Which of the following references the first and last elements in a nonempty array?

The are 1 correct answers
fruits[0] and fruits[fruits.length]
- [x] fruits[0] and fruits[fruits.length – 1]
fruits[1] and fruits[fruits.length]
fruits[1] and fruits[fruits.length – 1]
None of the above
All of the above


_______________________________________________________________________

- 8. 

Given the code:

public class Application {
  public static void main(String[] args) {
  int xx[] = null;
  for (int i : xx) {
  System.out.println(i);
  }
}
}

What is the result?

The are 1 correct answers
Nothing is printed
- [x] An exception is thrown at runtime
Compilation fails
null



______________________________________________________________________

- 9. 

Given the code fragment:

int [] num = new int [2];

num[0] = 10;

num[1] = 15;

List<Integer> lst = new ArrayList<Integer>(2);

lst.add(10);

lst.add(15);

num[1] = 20;

lst.add(20);

for (int x : num) { System.out.print(x + “ “); }

System.out.println(““);

for (int y : lst) { System.out.print(y + “ “); }

 

What is the result?

The are 1 correct answers
10 20
- [x] 10 20, 10 15 20
A runtime exception is thrown
10 15 20, 10 20
10 20, 10 20
A compilation error occurs






___________________________________________________________________________
- 10. 

Given the code fragment:

// line n1

num = new int[10];

Which code fragment can be inserted at line n1 to enable the code to compile?

The are 1 correct answers
new int num[];
- [x] int[] num;
int[10] num;
int num[10];


_____________________________________________________________________


- 11. 

Given the code fragment:

 

List names = new ArrayList<>();

names.add(“Julia“);

names.add(“Peter“);

for (Iterator itr = names.iterator(); itr.hasNext();)
System.out.println(itr.next());

 

What is the result?

The are 1 correct answers
A compilation error occurs
A runtime exception is thrown
Julia
- [x] Julia, Peter
Peter
Peter, Julia



_________________________________________________________________________


- 12. 

Why ArryList is also know as dynamic array?

The are 1 correct answers
Because its size is fixed
- [x] Because its size can change as per requirement
Because it uses less memory
Because elements cannot be inserted its declared
All of the above
None of the above



____________________________________________________________________
- 13. 

What is the output of the following?


List sites = new ArrayList<>(1);

sites.add(“Eiffel Tower“);

sites.add(“Statue of Liberty“);

sites.add(“Louvre“);

sites.remove(2);

System.out.println(sites);

The are 1 correct answers
- [x] [Eiffel Tower, Statue of Liberty]
[Eiffel Tower, Statue of Liberty, Louvre]
The code does not compile.
The code compiles but throws an exception at runtime.
None of the above
All of the above


________________________________________________________________________
- 14. 

Which is not a true statement about an array?

The are 1 correct answers

- [x] An array expands automatically when it is full.
An array is allowed to contain duplicate values.
An array understands the concept of ordered elements.
An array uses a zero index to reference the first element.
None of the above
All of the above


_________________________________________________________________________
- 15. 

How many lines does the following code output?

 

var days = new String[] { “Sunday“, “Monday“, “Tuesday“, “Wednesday“, “Thursday“, “Friday“, “Saturday“ };

for (int i = 0; i < days.length; i++)
  System.out.println(days[i]);

 

The are 1 correct answers

6
- [x] 7
The code does not compile.
The code compiles but throws an exception at runtime.
1
This goes into an infinte loop.



_________________________________________________________________________________________________________
- 16. 

Given the code fragment:

 

int num[] = new int[3];

num[1] = 10;

num[2] = 15;

List lst = new ArrayList<>(3);

lst.add(10);

lst.add(15);

System.out.println(num);

System.out.println(lst);

 

What is the result?

The are 1 correct answers
a memory address1 in hexadecimal number format, a memory address2 in hexadecimal number format
10, 15 ,[10, 15]
0, 10, 15 , [10, 15, null]
- [x] a memory address in hexadecimal number format, [10, 15]


_______________________________________________________________________________________________
- 17. 

What is the output of the following?


20: List chars = new ArrayList<>();

21: chars.add(‘a‘);

22: chars.add(‘b‘);

23: chars.clear();

24: chars.remove(0);

25: System.out.print(chars.isEmpty()

+ “ “ + chars.length());

The are 1 correct answers

false 0
true 1
2
- [x]  The code does not compile.
The code throws an exception at runtime.
None of the above



_______________________________________________________________________________________

- 18. 

What is the result of the following when called as java Binary.java? (Choose two.)


1: import java.util.*;

2: public class Binary {

3:

4: public static void main(String[] args) {

5:   Arrays.sort(args);

6:   System.out.println(Arrays.toString(args));

7:   System.out.println(args[0]);

8: }
}

The are 2 correct answers

null
- [x] []
Binary
- [x] The code throws an ArrayIndexOutOfBoundsException.
The code throws a NullPointerException.
The code does not compile
_____________________________________________________________________________________________
- 19. 

Given the code fragment:

 

int[] arr1 = {1,2,3};

int[] arr2 = new int[2];

arr2[0] = 10;

System.out.print(arr1.length + “ : “ + arr2.length);

 

What is the result?

The are 1 correct answers
3 : 1
- [x] 3 : 2
0 : 1
2 : 0