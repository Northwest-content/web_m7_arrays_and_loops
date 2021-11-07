Going back to our project, we will be using `arrays`, but arrays we seen only can be declared in advance 🤔

**❓ Question:**

> How can we add a new item?

**🤓 Answer:** 

> By using the `push()` method. Arrays have many already famous methods, we will use first `push()`It looks like this: 

```javascript
let students = []; // empty list
students.push(“Bob”);
```

**Inspector Implementation:**

![img](https://lh4.googleusercontent.com/P8viJZ7g2y9PJsjDcbRHJeU4wMEXYXEkFpr1a89Ri3EzFiQqwjGubN4Y7Oy8d-g-68hm2-FPmfDY1_87yWtqMtfl4dhGZdssM9GI6FhCSabbs1GGgX4UQWT-LM14WfSUq2HXBxsm)Now let's fix our code: 

1. Change `name` to `names`

   ![img](https://lh4.googleusercontent.com/Dd4u5-7FYC5qZTWPIAbTw6OeTacL5sDoWOPIwabt4ctEYuzDS5-bfrAZWhOT7h3rkSpGRmUspPklmdGcE2qGXuM4yOZfJTUDJzHHVm7_tuw9ULo8_PZOGgLS2iZvoroFd6DOlB0C)

2. `push` the input value into `names` by saying: 

   ````javascript
   names.push(document.querySelector("#input").value);
   ````

   ![img](https://lh6.googleusercontent.com/tHSxDcsKeNUmF22KlEUw8SxOqawxaBSkNyygPLdMOJIZTqL3b1g3ezCnq_qDfOKm2sEnPoxCXR56pTKToApMn9NGIjdvrASdDEjglF5uAHfrFXQhw0shYOhXCaJHcmNS0kI6YKhG)

3. Test it

   ![img](https://lh5.googleusercontent.com/3EE3Up9yS9jvU2WtnEVmQgAnK6qjhlixxwYSVkP38iKyoF3bGK9M-zfnTgFkyemod7loGuTWWS3Qp_ajDtGDnwKWigUFRa67dVSOREky-CzKca0ZyFH6o5bepNvYPKPXReNOTYA2)

It is still not working 🤔

**Trying 👀:**

>  let the `innerHTML = names` rather then `name`

![img](https://lh5.googleusercontent.com/gqJz7vIeVbGawhHzub83MOHgL0wZdISGpXqTREQJnzP0FC5ebYJLlaBykGif8oFiztG4feYJnUzAO6gBxdYGQqqs6dasf3wbWskuKUXecui72_hmmMyDPUl9oeYfAa1iwu5Am2zy)

We need to learn how to print `arrays` on the screen 👀

**Fix ⚠:**

>  `array` need to be declared outside of the `addStudent()` or else we are creating it with each click: 

![img](https://lh4.googleusercontent.com/GHq8PA6LdS7DYbC_RPbMqbp5QLZUUXDSzce2hb5Vr4LxsFYj57qaoGxyTZMdmpJpn1cojIT9Mz-8J-Wzv3DU9o-dOEVQUrw4FHG2H-nP_Mv0Ixe8aSrBUtc3XGQnAlqJgcMdJ3m2)

**Output:**

![img](https://lh4.googleusercontent.com/rm82YLNUjU2DE7BG3aZOJvv2R_4AD9FT8FB7gU649UMChjk3UPnlzb0g5EbHUMsi_YSUvfy0Bti86uYX1tilrnd_wc8cOKwX7WQpP59UeSVy6-cAQ3OzhAXzJoqP_R0tw7QDd3il)

**Fix ⚠:**

> Now to fix the look of the elements, we will be using ```` and `$` and `{}`This way: 

![img](https://lh6.googleusercontent.com/DFllHrcKojGS3GlJ1A9D9LM8z75jYDhHIIFXaLDcUOfe2kYU7erhvMxOw2tUK5IZfsPLSNPuV4bZZa1dH2VHHEyhBjNtOrGhuIk2tGqLbLXZgi5sQYYTqJ3aoSecd9bLHJYvVLih)Then adding `<h3>`:![img](https://lh3.googleusercontent.com/AqERAEatBByU3v4CTdiVD-b0oH_at8Fwh1bbsF4uKCIm7Uekmst2REgwgPrzU26lPmFRDQhdzqNCB4F2QqIB8wwk8wy3GcnkCfVNVReVcY70Je6F_EoUxtIQ8q4rECyRYsIyL43m)**Output:**

![img](https://lh4.googleusercontent.com/DLET7hu6aywrKN8WpLzMo-mijUSrCllTTQ_ylb9gP0NcT5JWSlgLnVMrqR4l-9ybXpBMEI0zJOPbG0MSSSzSDMGnvjrnNL-zFTpL0SJd6jz8YajhQfHirh8WXPhyIuTyQuf5AiNY)

