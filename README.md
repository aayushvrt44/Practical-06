# Practical-06

This repo consists of six tasks of object oriented programming with C++ .The tasks are follows under.

String related Questions in C++:

Task1: What happens if we add integer with a string, how the compiler would react to it?

       String str = "ABC";
       Int a = 1;
       String str2 = str + a;

Task2: Check the entered string is Palindrome or not?

       String str = "75457"
       Output: Yes it is a palindrome or No it is not a Palindrome. 

       (Use, getline(sin, str1) and reverse_iterator of string to check this)

Task3: Make a reverse of a string using reverse method and reverse_iterator of string class?

Task4: String Compare: Check if the strings are equal or not? (do not use str1.compare(str2), do it manually)

Task5: String Compare: Check the possible values string.compare() function will return?

            (Create cases in which compare function would return below values)

        X>0
        X<0
        X==0
        X = -4
        X = 5
        X = -2104040...


        Also check the ASCII difference between two characters?(use int type cast)

Task6: Check if string is mutable in C++ or not?
       String a = "Hello";
       Cout << &a;
       a[0] = 'J';
       Cout << &a;
       Cout << a;

       What is the output?
