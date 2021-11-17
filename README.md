#Setting the TOTAL value
total = 0
#Setting the Y value
y = "Yes!"
#Setting the N value
n = "No:("
#Setting the C value
c = "+1"
#Setting the W value
w = "+0"

#Making the text of the questions
questions = ["Whats my nickname?", "How old am I?", "Whats my bestie's name?"]

#Setting the first question with input
question1 = input(questions[0])

#Making the if statement
if question1 == "3faze" or question1 == "3Faze":
    print(y)
    print(c)
    total = total + 1
else:
    print(n)
    print(w)

#Setting the second question with input
question2 = input(questions[1])

#Making the if statement
if question2 == "?":
    print(y)
    print(c)
    total = total + 1
else:
    print(n)
    print(w)

#Setting the second question with input
question3 = input(questions[2])

#Making the if statement
if question3 == "Santiago" or question3 == "santiago" or question3 == "Santi" or question3 == "santi":
    print(y)
    print(c)
    total = total + 1
else:
    print(n)
    print(w)

#Printing the score
print("Your score was " + str(total) + "/3")
#Giving credits
print("Made by @3faze")
