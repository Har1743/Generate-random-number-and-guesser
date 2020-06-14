import random

n1 = int(input("Enter the lower limit :"))
n2 = int(input("Enter the upper limit :"))

chance = 1

r_no = int(random.randint(n1,n2))
print(r_no)

print("\nYou have three chance to guess the no beween the range ",n1 , " - ",n2)

while ( chance <=3 ):
    guess = int(input("\nEnter the no that you have guessed : "))
    
    if ( guess == r_no):
        print("CONGRATS\n",
              "You have guessed the right no in ",chance,"ATTEMPT")
        break
    else:
        if ( chance <= 2 ):
            if ( guess < r_no):
                print("\nSoory you have guessed the wrong no try again\n",
                      "Your guess is low : Think a higher no ")
            else:
                 print("\nSoory you have guessed the wrong no try again\n",
                      "Your guess is high : Think a lower no ")
        else:
            print("\n\nSorry your chances are over\n",
                  "YOUR CHOICE IS NOT CORRECT",
                  "BETTER LUCK NEXT TIME")
        
    chance += 1
