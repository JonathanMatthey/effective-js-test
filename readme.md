#### Chapter 1: Accustoming yourself to javascript

1. Know which Javascript you are using

2. Understand Javascript floating-point numbers

3. Beware of implicit coercions

4. Prefer primitives to object wrappers

5. Avoic using == with mixed types

6. Learn the limits of semicolon insertion

7. Think of strings as sequences of 16 bit code units


#### Chapter 2: Variable Scope

8. Mimize use of the global object

9. Always declare local variables

10. Avoid with

11. Get comfortable with closures

12. Understand variable hoisting

13. Use immediately invoked function expressions to create local scopes

14. Beware of unportable scoping of named function expressions

15. Beware of unportable scoping of block-local function declarations

16. Avoid creating local variables with eval

17. Prefer indirect eval to direct eval


#### Chapter 3: Working with functions

18. Understand the difference between function method and constructor calls

19. Get comfortable using higher-order functions

20. Use call to call methods with a custom receiver

21. use apply tocall functions with different numbers of arguments

22. use arguments to create variable functions

23. never modify the arguments object

24. use a variable to save a reference to arguments

25. use bind to extract methods with fixed receiver

26. use bind to curry functions

27. prefer closures to strings for encapsulating code

28. avoid relying on the toString method of functions

29. avoid nonstandard stack inspection properties


#### Chapter 4: Objects and Prototypes

30. Understand the difference between prototype, getPrototypeOf and __proto__

31. Prefer Object.getPrototypeOf to __proto__

32. Never modify __proto__

33. Make your constructors new-agnostic

34. Store methods on prototypes

35. Use closures to store private data

36. Store instance state only on instance objects

37. Recognize the implicit binding of this

38. Call superclass constructors from subclass constructors

39. Never reuse superclass property names

40. avoid inheriting from standard classes

41. treat prototypes as an implementation detail

42. avoid reckless money patching


#### Chapter 5: Arrays and Dictionaries 

43. Build lightweight dictionaries from direct instances of object

44. use null prototypes to prevent prototype pollution

45. use hasownproperty to protect against prototype pollution

46. Prefer arrays to dictionaries for ordered collections

47. Never add enumerable properties to object.prototype

48. Avoid modifying an object during enumeration

49. Prefer for Loops to for..in loops for array iteration

50. prefer iteration methods to loops

51. reuse generic array methods on array-like objects

52. prefer array litereals to the array constructor


#### Chapter 6: Library and API Design

53. Maintain consistent conventions

54. Treat undefined as "No Value"

55. Accept options objects for keyword arguments

56. Avoid unneccessary state

57. use structural typing for flexible interfaces

58. distinguish between array and array-like

59. avoid excessive coercion

60. support method chaining


#### Chapter 7: Concurrency

61. Don't block the event queue on I/O

62. use nested or named callbacks for asynchronous sequencing

63. be aware of dropped errors

64. use recursion for asynchronous 

65. Don't block the event queue on computation

66. Use a counter to perform concurrent operations

67. Never call asynchronous callbacks synchronously

68. Use promises for cleaner asynchronous logic



