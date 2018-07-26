## Coding Exercises No. 05

1. Create a new file called ```exercise_1.rb``` and fill in the following line:

```ruby
dictionary = { :one => "ichi", :two => "ni", :three => "san" }
```

Add a code so that it prints out the following:

```
San
```
**Note:** There’s a method that upcases the first letter of a string. Consult the ruby String documenation or start googling for "```ruby string upcase first letter```"
&nbsp;

2. There is a method on hashes that allows to check if a certain key is defined on the hash. Find said method by googling for "```ruby hash key defined```".

Experiment with said method in ```irb``` by creating a ruby hash example below 

```ruby
dictionary = { :one => "ichi", :two => "ni", :three => "san" }
```

then calling the method and passing keys like :one, :two, :three and :five.

**Tip:** Aside from using google, you can also consult the [ruby Hash documentation](https://ruby-doc.org/core-2.4.1/Hash.html).
&nbsp;

3. There is a method on ruby hashes that flips keys and values. Find said method in the [ruby Hash documentation](https://ruby-doc.org/core-2.4.1/Hash.html). Create a new file called ```exercise_03.rb```, and fill in the following line of code:

```ruby
dictionary = { :one => "ichi", :two => "ni", :three => "san" }
# your code goes here...
```
	
This should then output
	
```ruby	
{ "ichi" => :one, "ni" => :two, "san" => :three }
```	
&nbsp;

4. Create a new file called ```exercise_04.rb```. In this ruby program, write a method greet that takes a name, prepends "```Hello ```", and appends an exclamation mark "```!```":	

```ruby	
def greet(name)
  # your code goes here...
end

puts greet("Kristine")  
```	
	
This should print out 

```
Hello Kristine!
```
&nbsp;

5. Copy the above file and name it ```exercise_05.rb```.  Now change your method so that instead of always using "```Hello ```", it picks a random string from the array 

```ruby
["Hello", "Hi", "Ohai", "ZOMG"]
```

Every time you run the program it should print out either "```Hello Kristine!```", "```Hi Kristine!```", "```Ohai Kristine!```", or "```ZOMG Kristine!```".

**Tip:** The method ```shuffle``` on [ruby Arrays](https://ruby-doc.org/core-2.4.1/Array.html#method-i-shuffle) does, well, shuffle the array :) That means it changes the order of the elements in the array in a random way.
&nbsp;

6. Create a new file and name it ```exercise_06.rb```. In this ruby program, write a method that converts a distance (a number) from miles to kilometers:

```ruby
def miles_to_kilometers(miles)
  # your code goes here...
end

puts miles_to_kilometers(25)
```

This should print out

```
40.2336
```	
&nbsp;

7. Create a new file and name it ```exercise_07.rb```. In this ruby program, write a method leap_year? that takes a year (a number), and calculates if it is a leap year.

```ruby
def leap_year?(year)
  # your code goes here
end

puts leap_year?(2012)
puts leap_year?(2015)
```

This should print out

```
true
false	
```

**Tip:** The ruby operator ```%``` or [modulo](https://www.quora.com/In-Ruby-what-is-modulo-rather-what-does-it-do) returns the remainder division, e.g. ```14 % 3``` returns ```2```.

**Bonus:** Also make it so that the method returns ```true``` for the year 2000 and 
```false``` for 1900. Because that’s really the definition of leap years.
&nbsp;

8. Create a new file and name it ```exercise_08.rb```, and fill in the following line of codes:

```ruby
words = ["one", "two", "three", "four", "five"]
# your code goes here...
puts words.inspect
```

So that you get the following output

```ruby	
["one", "three", "five"]	
```
&nbsp;

9. Copy ```exercise_08.rb``` and name it ```exercise_09.rb```. Now change your code so that you get the following output:

```ruby
["One", "Three", "Five"]
```

**Note:** Consult the [ruby String documentation](https://ruby-doc.org/core-2.4.1/String.html) for a method or function that would uppercase first letter of a string.
&nbsp;

10. Copy ```exercise_09.rb``` and name it ```exercise_10.rb```. Now change your code so that you get the following output:

```ruby
["One <3", "Three <3", "Five <3"]
```
&nbsp;
