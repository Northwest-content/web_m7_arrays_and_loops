I bet you miss preparing your environment 😉. This time the project `HTML` and `CSS` are here, we just want your powerful `JavaScript` knowledge to complete it together. We will build a student list: ![img](https://lh4.googleusercontent.com/VisUw_8KdMIf6Dqx-kA5SH7D4t8dW2CL6Qr4lvmu81p4jZ7_6AfQHQjmjwiHUIKTIewbPLrzbHC9kTrVMaAs4EGWWovRZDdzNOOtrfIztQwupm9uzWTEIEEp_j5csC3Dt6bHNjE5)We will be doing the following:

- Activating the buttons
- Displaying names in the `#list` `<div>`

Let's start 🔥

1. **Creating `addStudent` function**

   **![img](https://lh6.googleusercontent.com/9M1p5dy2Z8QqHnCuIdHygMBlUG52T5InP7FxglQDM7cPbJ02nQ3XTyXfCgAPXs3lwUQGdkanUOqf75MouT7zyAnZxy6APjHoQzxL3wxmmLPhHPgUeipQP01kXCx-R01R5zwZLQnb)**

2. **Linking `addStudent()` with the submit button `onClick`**

   **![img](https://lh6.googleusercontent.com/bQfJi8AmsvKcMtqXLFn5VDokNfy5OnBc4xXbdbVS14qBsH6NpDjV2QXSlsJ8rPhcBzjFM2Ay6Hq3ZqSnWxvfGNr9pF2Jj0RhaRHJrB9cdFjiPwlmg7vKDwXAoFIfOhj3T63dx3rF)**

3. **Writing inside the `addStudent()` function:**

   - **Getting `input`**

     **![img](https://lh3.googleusercontent.com/6PaK6kghZu3TjLmBTWUfvX8N0qJ9zmYE8U3yqb59S4cTWmjCtVmWpoqxT70pxwC-1OxxJKIFtMuKBc3c7-XBYHsrvtpwd2mKHnqqoTKytUNaS00R79QGs-UyFdBj8TwBPDgUxA8x)**

   - **Display input**

     **![img](https://lh6.googleusercontent.com/5R2DKhprnQdZxy3nnrMct2gpBcZOsu0WhAcmBBHrgrbxrQGFZ8qVmW-sU7M2xcYKt0EQIoyd1ONBVBaRf1cHJr6uoIhpNsMb_3WPi-oSiaKwNbMgRrTwh2kbW5O5QQclqI7brgAa)**

**Output:**

![img](https://lh4.googleusercontent.com/iXojBDYGFypINBttWjVqu8YoUFNwThjg4NMA9sIkq7-MF6lM-prlelj9v_eIId920kpNzSwmPSCjhjray0id5r4mK77w1r6HMTxjzNqAj72WVEX8fbgJzH9HbR7PitdDJhXthSpB)

```javascript
function addStudent() {
  let name = document.querySelector("#input").value;
  document.querySelector("#list").innerHTML = name;
}
```

Ammmmmm, only one name🤔 we are facing `overwritten` values . Let's continue and we will get back to this later 👀

4. **Create `deleteName` function**

   **![img](https://lh3.googleusercontent.com/ubEep7RGHLvlZERELWlpFOTYM2xxPadnczfnueyv46DxJJpQbz7T9DxflzKKym11jco7mYXUfxf27xcBWwwtbE-nSlpmfCjOd-bZLlNzO9lQ4MTTE-iZ0OKVZAcdfhj2qriTXChz)**

5. **Linking `deleteName()` with the `Delete a name` button**

   **![img](https://lh3.googleusercontent.com/lvFsRpHKFOPKpdKY3kYz-4TcCgjYnm9kMKmG4-pk66OvKAVBIJa7pQo_DbYDVgiM4d-fDX3B-te_CSQHucHNfWLXW5t6kFTpvbH6Ppytyq_vrusr0Ug7rfm_YeKOvnM6OKrgvbUf)**

6. **Writing inside the `deleteName()` function:**

   - **Remove the name displayed from the list** **![img](https://lh6.googleusercontent.com/ZMeK_ycimkHYToY6QX9RuSxo_C5Q3ED5Wunu6eWv2t8dEE-MIQS7C7Qx-hV910JZ4gaXF4j_VWU3B_QJigRctMZKuU4MEvHWuIabI-3547XTqDcRAUXEeKwzCHcNU0CoXyBYKObs)**Output:\*\*

     **![img](https://lh3.googleusercontent.com/UqOwoW25446qK9HSqhlgeNZwnqr662oEUMQw8zXa2qZuoeSiFrsZ7HFbrgqcDk--K1pbum-G0CuXu5Dg3JqggCes_WxsBVDXb5f8CK9jFBPtU54kYuljCM_Hn_qCAj8vmebzWjhW)**

     Now only two things left to fix:

     1. Benign able to add multiple students to the list

     2. Deleting able to delete one name only rather then deleting the whole list

        To be able to do both we need to learn something new called `Arrays` 🔥
