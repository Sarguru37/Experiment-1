# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
```python
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```

## Output
### Psitive Numbers:
![Screenshot 2025-03-20 104202](https://github.com/user-attachments/assets/a574caeb-1acf-4d19-9c48-b1e8fbbd3ff3)
### Negative Numbers:
![Screenshot 2025-03-20 104240](https://github.com/user-attachments/assets/b97f052c-db85-42da-8898-3982bc38e49d)
### Character and String input
![Screenshot 2025-03-20 104314](https://github.com/user-attachments/assets/b353e6a0-59a8-4706-9a55-535805ea886a)
### Null Input:
![Screenshot 2025-03-20 104329](https://github.com/user-attachments/assets/93d0a4ad-7936-4c89-8fd7-90cd44ba8d00)






## Result
Thus to write a python program for do…while with possible test cases was executed successfully



