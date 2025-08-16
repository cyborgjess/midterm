[midterm1task.txt](https://github.com/user-attachments/files/21809030/midterm1task.txt)# midterm

1.[Usection .data
    var1 dd 10        ; example value
    var2 dd 3         ; example value
    var3 dd 7         ; example value
    result dd 0
    fmt db "Result: %d", 10, 0

section .bss

section .text
    extern printf
    global main

main:
    
    mov eax, [var1]       ; EAX = var1
    add eax, 2            ; EAX = var1 + 2

    mov ebx, [var3]       ; EBX = var3
    sub ebx, [var2]       ; EBX = var3 - var2

    
    xor edx, edx          

   
    div ebx               

   
    mov [result], eax

    
    push eax              
    push fmt              
    call printf
    add esp, 8            

  
    mov eax, 0
    ret
ploading midterm1task.txt…]()

2. ![midterm1](https://github.com/user-attachments/assets/8bc31771-2a97-4ab0-80f5-1e416de54499)
   ![mid2](https://github.com/user-attachments/assets/91f906d3-e655-4b07-bb50-9e8011026c20)
   ![table](https://github.com/user-attachments/assets/01339059-5fec-4d56-8997-c5b55ab83f2c)


3. K-map
![20250722_224628](https://github.com/user-attachments/assets/5fbbd97c-8a95-42e2-bfea-a390c7387e8b)

4. Write a code that identifies an odd or an even number
   ![mid4](https://github.com/user-attachments/assets/7736f0be-f16d-4242-96ca-bae99e2e073e)
![midterm3](https://github.com/user-attachments/assets/4569c528-2631-440a-9d9b-ee279ff73156)

