# millionaire_game
questions = [["Q1. who is Shah Rukh Khan?" ,"WWE resler","Actor","Sumo","Driver",2 ],
             
            ["Q2. India ki rajdhani kya hai?","Mumbai","Chennai","New Delhi" ,"Kolkata",3],

             ["Q3. Bharat ka rashtriya pakshi kaun sa hai?","Kabutur","kova","Mor","Hans",3],

             ["Q4. Which planet is known as red planet?","Earth","Mars","Pluto","jupyter",2],

           ["Q5. what is largest animal?","Lion","Horse","Pig","elephant",4]
]

prizes=[10000,30000,50000,70000,100000]
i=0
for question in questions:
    print(question[0])
    print(f"a. {question[1]}")
    print(f"b. {question[2]}")
    print(f"c. {question[3]}")
    print(f"d. {question[4]}")

    a=int(input("enter your answer: 1 for a,2 for b, 3 for c,4 for d\n"))

    if(question[5]==a):
        print("correct answer")
    else:
        print(f"incorrect, the correct answer is : {question[5]}")
        print("Better luck next time")
        break
    print(f"you won {prizes[i]}")
    i +=1
    
