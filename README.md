# block4CT
import random
myList=[]


def mainProgram():
    while True:
          try:
              print("Hey there! Lets work with lists!")
              print("Choose one of the following options. Type a NUMBER ONLY!!")
              choice = input("""
1. Add to list,
2. Add a bunch of numbers,
3. Return the vaule at an index position,
4. sort list,
6. linear search
5. Random choice,
7. print lists
8. End Program   """)
              if choice == "1":
                  addtoList()
              elif choice == "2":
                  addtoList()
              elif choice == "3":
                  indexValues()
              elif choice == "4":
                  sortList(myList)
              elif choice == "5":
                  randomSearch()
              elif choice == "6":
                  linearSearch ()
              elif choice == "7":
                  printLists()
              else:
                  break
            except:
                print("an error occurred")

def addtoList():
    newItem = input("plaese type an intager!    ")
    myList.append(int(newItem))
    print(myList)

def addAbunch():
    print("we're going to add a BUNCH of numbers!")
    numtoAdd = input ("how many integers do you want to add?  ")
    numtoAdd = input ("and how high would you like these numbers to go? ")
    for x in range 90,int(numtoAdd))
        myList.append(random.randint(0,int(numRange)))
    print("Your list is noe complete!")


def sortList(myList):
    for x in myList:
        if x not in unique_list:
            unique_list.append(x)
        unique_list.sort()
        showMe = input("wanna see you new list? Y/N  ")
        if showMe.lower() == "y"
        print(unique_list)


def indexValue():
    indexpos =input("at what index postion would you like to look?   ")
    print(myList(int(index)])


def randomSearch():
    print("here's a random valuefrom your list!")
    print(myList[random.randint(0, len(myList)-1)])

def linearSearch():
    print("We're going to search through the list in the WORST WAY POSSIBLE! cause i want to :
          searchItem = input("what are you looking for? Number-wise   ")
          for x in range(len(myList)):
          if myList[x] == int(searchitem):
               print ("your item is at index {}".format(x))
    print(indexCount)

def recursiveBinarySearch(unique_list, low, mid, -1, x)
     if high >= low:
         mid  = (high + low) // 2


         if unique_list[mid] ==x:
             print("oh, your just a lucky dude aren't you? Your number is at position {}".formation(m:
        elif unique_list[mid] > x:  
             return recursiveBinarySearch(unique_list, low, mid, -1, x)
        else:
            return recusiveBinarySearch(unique_list, low, mid + 1, high, x)

        else:
            print("Your number isn't there!")

def printLists():
    if len(unique_list) == 0:
        print(myList)
    else:
        whichOne + input ("which list? Sorted or un-sorted?    ")
        print(unique_list)
    else:
        print(myList)


if __name__ == "__main__":
    mainProgram()
