# daily-javascript-array
Daily JavaScript question
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Daily Question</title>
</head>

<body>

<script>
    var firstArray = ["Paul", "John", "Pete", "George"];
    var secondArray = firstArray;
    secondArray[2] = "Ringo";
    alert(firstArray);
</script>
</body>

</html>
```

What is the output when you run this script in the browser?

A. An alert box displaying the following: Paul, John, Pete, George

B. An alert box displaying the following:Paul, John, Ringo, George

C. An alert box displaying the following: Paul, John, George

D. An alert box displaying the following: John, Ringo, George

B

/*

	CORRECT! Well done!

	Both variables, firstArray and secondArray are pointing to the same array
	so doesn't matter which variable you use when modifying the item at index
	position 2, you are still modifying the original array.

	i.e. The array isn't copied/cloned automatically when assigned to an additional variable.
	
*/