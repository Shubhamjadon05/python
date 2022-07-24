from typing import List

def removeItems(fullList, toRemove):
    for i in toRemove:
        index = fullList.index(i)
        fullList.pop(index)
    return fullList

ListNumber = ["iphone","Moto","redmi","apple","Lenovo","Windoes"]

itemsToRemove = ["Lenovo" , "apple","iphone " ]


result  = removeItems(ListNumber, itemsToRemove)
print(result)

