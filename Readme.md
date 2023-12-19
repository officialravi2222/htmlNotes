Warning !
Array elements can be deleted using the JavaScript operator delete.

Using delete leaves undefined holes in the array.

Use pop() or shift() instead.



```html
<!DOCTYPE html>
<html>
<body>
<h1>JavaScript Arrays</h1>
<h2>The delete Method</h2>

<p>Deleting elements leaves undefined holes in an array:</p>

<p id="demo1"></p>
<p id="demo2"></p>

<script>
const fruits = ["Banana", "Orange", "Apple", "Mango"];

document.getElementById("demo1").innerHTML =
"The first fruit is: " + fruits[0];

delete fruits[0];

document.getElementById("demo2").innerHTML =
"The first fruit is: " + fruits[0];
</script>

</body>
</html>
```


JavaScript Arrays
The delete Method
Deleting elements leaves undefined holes in an array:

The first fruit is: Banana

The first fruit is: undefined