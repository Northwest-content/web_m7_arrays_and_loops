 Arrays can say that they are lists of variables, where you can save multiple values inside one variable. 

**❓ Question:**

>  Hoooowwww can one variable have multiple values? Will they be overwritten? 

**🤓 Answer:** 

> No, les see how the array sees the variables: 

Rather then: 

````javascript
let student1 = “Bob”;
let student2 = “Sam”;
let student3 = “Kim”;
````

````javascript
// We can say: 
let students = [“Bob” , “Sam” , “Kim”];
````

How beautiful 😍

**Inspector Implementation:**

![img](https://lh6.googleusercontent.com/mhvmA2660NccBwAKvJIa5NRUcPQD_ZlcqFDaI2WFbp7Hjy54nrnl6lQhY2LlaRzWwPmcXjPA2tB4SDCO7kpXYM49EpzwE54WMxkoC4bl6TY4WjhK-yCCpJeZMoX3F6s-KHKLrYhm)

How does it look with the printing: 

![img](https://lh6.googleusercontent.com/AVP9CZOa9RbqFWXFNqXADfl-j8q1P_FfmP4Ita7-nfRRaBGKuJk3BTBh5CQuX6DB3tMxMEeVVtfv2dZ_M9BKV9ZU_fBKh4oyFADKKytAwjWtui_5-5VY3rCxKvr029hdANyAFwNm)

**❓ Question:**

>  Can we print one element from the list?

**🤓 Answer:** 

> Yes we can, to do so we must know where the element is located.

![img](https://lh3.googleusercontent.com/8ngmH9X8c2ioY9EZtJFPj7O1PlvIfJRW1vimtCPR2VSapwjmby8POjC0kLlppjGT_OkI2jo8-Sw_jk3urTm6v0IHCvZz-3DCRNIbdLW6MUWLoSxAzUkTqEHCjvlsoC2H-BIMbJjw)

**Note 📝:**

> Arrays always start from zero location Now to call it, since `arrays` use `[ ]` then even while calling one element we use them like this: 

````javascript
Students[0] // will give Bob
Students[1] // will give Sam
Students[2] // will give Kim
````

**Inspector Implementation:**
![img](https://lh5.googleusercontent.com/1YfR3-TlAfAMl38iULZWbN-R9GC_lElqlDoFoCvl-fGxp4fFJ75tbxh1eY0O-KLy1sVmA8eDz0G-n9MJVfXhRHa8F11qYLoESF_gir-nKGkAUWbAqtHIrjenx_sCnhWLkY1L_JJ2)

