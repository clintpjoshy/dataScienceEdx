#### R
* A freshly installed **r** language is called **base R**
* We can install packages or libraries to help us with many tasks
    ```Ex for installing a package
        install.packages("dslabs")
        #This will install a package called dslabs.
    ```
* We can load a package using **library**
    ``` Ex for a library
        library (dslabs)
    ```
* 
#### R Basics
* **Objects**
    * Solve quadratic equation (ax^2 + bx - 1 = 0)
        * For this `a <- 1, b <- 1 are the varible then the equation becomes x^2 + x - 1 = 0`
        * In ** R ** ` <- ` is the assignment operator. We can use (=) also
            ``` Ex:
                a <- 4
                a 
                #4
                print (a)
                #4
            ```
            In the ablve example variable a is assigned a value 4. This can be printed using ` print ` or just by typing ` a `
          * Objects are the stuff that are stored in R. Ojbects can be functions also.
          * Ojects are defined stored in the `workspace`. Variables saved in the workspace can be displayed using ` ls() ` function.
          ``` Ex:
                ls()
                # "a"
            ```
* **Functions**
   * Functions are not available in the workspace.
       ``` Ex:
           log(8)
       ```
       ```
       a <- 7
       log(a)
       ```
   * Functions can be nested. Meaning a function can be passed in as an argument (first class functions)
   * `help()` function can be used to get the manual / documentation of the command.
      ``` Ex:
          help(log)
      ```
  * help() function can also be replaced by `?`
      ``` Ex:
          ?log
      ```
  * Arguments
      * When an argument is assigned a value  in the function `=` is used instead of `<-`
        ``` Ex:
            log(8, 2)
            log (x = 8, base = 2)
            # If the documentation is checked we can see that log function is expecting 2 variables x and base.
        ```
  * Some functions do not need parenthesis to invoke the function.
    ``` Ex:
        3^2
    ```
  * Variable Names
    * Starts with a letter
    * Shouldn't have space
    * Avoid using already used or native names of R
* ** Data Types **
