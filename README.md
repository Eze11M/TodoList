# TodoList simple solidity contract

This repo presents a simple solidity array of structs practice contract featuring a todo list.

## The contract contains:

   1. A struct "Todo" composed by string "name" and bool "completed" fields.
   2. A public Todo array "todos" that stores different task information.
   3. An external "create(string)" function that pushes a new Todo struct into the array.
   4. An external "updateText(uint256, string)" function that updates the Todo text on a given index.
   5. An external "toggleCompleted(uint256)" function that toggles "completed" field from given Todo struct index.
   6. An external view "get(uint256)" function returning uint256, bool matching todo fields of given index structure stored in the array.
