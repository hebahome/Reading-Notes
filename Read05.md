 Expressions and operators

## Operators

### JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

 ##  1.Assignment operators



| Name | Shorthand operator| Meaning |
|----------|:-------------:|------:|
| Assignment | x = y |x = y|
| Addition assignment |  x += y  | x = x + y  |

| Exponentiation assignment | x **= y|x = x ** y |


   ## 2. Comparison operators


 

|          Operator     |     Description   | Examples returning true    |  
|----------|:-------------|--------------------------------------------------:|
| Equal (==) |Returns true if the operands are equal | 3 == var1     "3" == var1    3 == '3'|




## 3. Arithmetic operators
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity). For example:

1 / 2; // 0.5
1 / 2 == 1.0 / 2.0; // this is true



## 4. Bitwise operators




|     Operator	     |         	Usage	|    	Description      |
|----------|:-------------:|------: |
| Bitwise AND	a & b	Returns a one in each bit position for which the corresponding bits of both operands are ones.   |  a & b |Returns a one in each bit position for which the corresponding bits of both operands are ones.         |
|         Bitwise XOR	a ^ b	Returns a zero in each bit position for which the corresponding bits are the same.
|Bitwise XOR       |    	a ^ b         |  Returns a zero in each bit position for which the corresponding bits are the same.|
        



# Loops and iteration

- Loops offer a quick and easy way to do something repeatedly
You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

   
   
   
## Some statements for loops provided in JavaScript are:

for statement
do...while statement
while statement




* Example
In the example below, the function contains a for statement that counts the number of selected options in a scrolling list (a <select> element that allows multiple selections). The for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the <select> element, performs the succeeding if statement, and increments i by after each pass through the loop.

<form name="selectForm">
  <p>
    <label for="musicTypes">Choose some music types, then click the button below:</label>
    <select id="musicTypes" name="musicTypes" multiple="multiple">
      <option selected="selected">R&B</option>
      <option>Jazz</option>
      <option>Blues</option>
      <option>New Age</option>
      <option>Classical</option>
      <option>Opera</option>
    </select>
  </p>
  <p><input id="btn" type="button" value="How many are selected?" /></p>
</form>

<script>
function howMany(selectObject) {
  let numberSelected = 0;
  for (let i = 0; i < selectObject.options.length; i++) {
    if (selectObject.options[i].selected) {
      numberSelected++;
    }
  }
  return numberSelected;
}

let btn = document.getElementById('btn');
btn.addEventListener('click', function() {
  alert('Number of options selected: ' + howMany(document.selectForm.musicTypes));
});
</script>

  
  
*  do...while statement
  
  Example
In the following example, the do loop iterates at least once and reiterates until i is no longer less than 5.

let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);
