# Beating the Demon Lord
#Trying to learn python and practicing for my upcoming university coding class. I would like my program to keep asking "Come again?" UNTIL #either option a or b is typed by the user. However, after typing anything other than those options to purposefully trigger the "Come #again?" loop, I tried typing one of the options, a or b. It still asks me "Come again?" why is that?
#The code in question is:

n = input("You are in the Lost Forest. Go left or right?")
while n == "right" :
    n = input("You are in the Lost Forest. Go left or right?")
while n == "left":
    n = input( "You got out of the Lost Forest!Where do you want to go now?")

while n == "Demon Lord's Castle":
    n = input("Are you sure? It's going to be a tough fight!!")  
    if n == "Yes, I'm sure! Let's do this!!":
        print("To be continued...") 
    elif n == "Nah I'd rather chill a bit more":
        print("Whatever you say boss")
    else: 
        n = input("Come again?")
        a = "Yes, I'm sure! Let's do this!!"
        b = "Nah I'd rather chill a bit more"
        while n is not a or b:
            n = input("Come again?")

