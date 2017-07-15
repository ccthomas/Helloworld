# Simple Style Guide

## Header
Always import the specific item you want, NEVER use '\*' while importing
```
package main.mypackage;

import path.to.javafile;

/**
 * @author      First Last <github.com/username>
 * @version     #.#.#
 */
 ```

## Spacing
> Tabs equals 4 spaces

> No White space characters at the end of the line

> Spaces between operators, after commas, and statements like if, else, try, while, ect...
```
int x = myVariable - anotherVariable;
```
```
callingAMethid("Param", x);
```
```
while (x < 0) {
    // Code
}
```

## Comment
Javadoc Comments before every Class, Method, Global Variable Declaration, or Block of Complicated Code
```
/**
 * General Statement of what is happening
 * <p>
 * More information if needed
 * And more
 * <p>
 * @param x describe parameter
 * @return describe What will be returned
 */
```
Template
```
/**
 * TODO: Main Description
 * <p>
 * TODO: More detailed description
 * <p>
 * @param parameterName <description...>
 * @return <description...>
 */
public void methodName() {

}
```

## Brackets
Always include brackets when you use for loops or if statements.
```
if (x < y) {
    // Single line of code
}
else {
    // Code
}
```
