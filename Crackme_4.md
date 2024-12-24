Crackme_4

Run on x32dbg

![c4 2](https://github.com/user-attachments/assets/a31f03b4-73ab-4a46-afa3-3877c1673352)

![c4 3](https://github.com/user-attachments/assets/e09861d5-f994-4381-ba8f-ab38aadc6d17)

And we see it paused

![c4 4](https://github.com/user-attachments/assets/abb9da33-158f-4d68-ba6d-36c7f0844054)

Open Tab Call stack and locate the call instructions that cause the program to open the window, focusing on the comments labeled "crackme4."
Pay attention to the ones triggered by the user. This will guide you to the relevant code, and by examining the area above it, you can find some useful code.

![c4 5](https://github.com/user-attachments/assets/645dd46f-438c-4551-a681-818653569f48)

![c4 6](https://github.com/user-attachments/assets/c136092a-bbda-497d-b970-c64d54a73413)

That ecx has value 1E also in hexa, eax maybe 0 then ecx – eax and we got the 16 in decimal and it’s the value shown in windown above.

![c4 7](https://github.com/user-attachments/assets/b5c1e3d6-4435-4960-9819-896cb671bc51)

Increase the value of ecx, here I change to ff and click OK so that it will make it beyond 30 day

![c4 8](https://github.com/user-attachments/assets/424b0e77-adb5-4c91-bf3e-055f8ff6d12b)

And it will beyond 30 day

![c4 10](https://github.com/user-attachments/assets/52b4cc60-6c6e-420e-b2fd-1e5cf3947260)
