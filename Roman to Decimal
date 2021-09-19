roman = {
    'I': 1,
    'V': 5,
    'X': 10,
    'L': 50,
    'C': 100,
    'D': 500,
    'M': 1000,

}
romannumbers=str(input('Enter your roman Numeral: '))
result=0
print(romannumbers)
for index in range(len(romannumbers) - 1): #we subtract 1 so that we don't exceed the string limit
    previous = romannumbers[index] #to know the first symbol
    nextSymbol = romannumbers[index + 1] # to know the symbol that followed it.
    previousNumber=roman[previous] #to know the numeric value when converted
    nextNumber=roman[nextSymbol] #to know the numeric value when converted

    if  previousNumber< nextNumber : # to check if the first value is less than the second one
        result -= previousNumber # add negative to the number if true
    else:
        result += previousNumber # add the number positively.
lastSymbol=romannumbers[-1] # to get the last symbols.
lastNumber=roman[lastSymbol] # to get the converted value of the last symbol
result+=lastNumber # add the last number to the summation
print(result)
