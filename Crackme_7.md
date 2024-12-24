Crackme_7

![c7 1](https://github.com/user-attachments/assets/c328f336-5096-4b80-97de-b1f9eb85f263)

Analyse the code:

When the program runs, it assigns the same value to both the `eax` and `ecx` registers and then performs a subtraction between them.

Next, a `test` instruction is called, which compares the values of `eax` and `ecx` after the subtraction. The `test` instruction works like an `AND` operation, and if either value is 0, the result will be 0, leading to a "bad" message: "Unregistered."

![c7 2](https://github.com/user-attachments/assets/d1e55b16-df84-4f64-9fe2-a5009190ac82)


Our goal here is to ensure that the `test` result is not 0. To do this, we need to change the value of either `eax` or `ecx` so that the subtraction result is not 0. This way, the two `je` (jump if equal) instructions will not be triggered.

In this case, I changed the value of `ecx` to 3, so the subtraction result is no longer 0, and the program displays the "good" message: "Registered."

![c7 3](https://github.com/user-attachments/assets/9005f1a6-cbef-444c-ae66-0befb746ed28)

The result is:

![c7 4](https://github.com/user-attachments/assets/a9ef8f76-085f-44b3-b9b8-22fc6f08df87)



