# Coding Guideline

## Definitions
Access function – a public function that provides access control to private variables within a script. Ex: **public bool IsVar(){return var;}**

## General Coding Practices
Organizing scripts
- All variables, structs, enums, defines, etc. should be at the top of the class.
- All access functions follow
- The unity functions (**start, update, fixupdate**) should be next
- Then all the public functions follow
- Then all the private functions follow

Default to using **\[SerializeField\]** when you want a variable modifiable on the component menu. Only use **public** when the variable also needs to be read/write from another script.
