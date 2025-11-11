# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END

```

## OUTPUT
<img width="1280" height="626" alt="image" src="https://github.com/user-attachments/assets/7053b4d9-1d60-4167-9f91-2cc0e56ee73a" />
<img width="1600" height="1595" alt="image" src="https://github.com/user-attachments/assets/41955998-2a69-4b95-956b-fc91c51d92ad" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```
## OUTPUT
<img width="1173" height="758" alt="image" src="https://github.com/user-attachments/assets/ed480164-922a-4d58-82db-248cbe18d03c" />
<img width="916" height="1359" alt="image" src="https://github.com/user-attachments/assets/85a47ed0-1949-4ba6-8ff2-845a050e37ca" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
