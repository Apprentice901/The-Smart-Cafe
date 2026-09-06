# The Smart Cafe

Phase 1 (Journal):
- "Function Declaration" is a "stand alone" statement that defines a function with a name and parameters.
- "Function Expression" is a function created and assigned to a variable.


Phase 2 (Journal):
- When I tried to log "defaultTaxRate" constant variable outside of the "calculateStoreTax" Function, it displayed an error because "defaultTaxRate" variable was not defined in the global scope of the script.


Phase 3 (Journal):
- Arrow functions offer "shorter" syntax & simpler bindings while standard function expressions are more flexible for different situations issued and called separately.
- Concise implicit returns makes code easier to read but takes away the standard function expression of "{}" and "return" keywords which will have pro's and con's.


Phase 4 (Journal):
- The role of "applyDiscount" is considered a higher-order function because it acts a main discount function for other functions that use it.
- The role that both "studentDiscount" and "seniorDiscount" functions played were the acting discount functions that displays the differences of 2 separate discounts.
- If I wanted to apply no discounts, id write a standardPriceValue function with 1 parameter (price) within it and use a Callback function before logging it in a print statement.


Phase 5 (Journal):
- Breaking the order process into small, single-purpose functions made writing "calculateFinalBill" function easier because it uses previous created called on discount functions into 1 function that runs through several steps in 1 place as long as the smaller function exist verses writing every function into 1 long block of code that creates a big landfill of code chaos which is difficult to read and map out where everything is.
