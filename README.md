a = input("entre canditate name\n")

b = input("entre the date of joing\n")
c = input("letter sign date\n")
letter = '''dear ,  NAME
YOU ARE SELECTED FOR THE POAST OF SD2 IN AMAZON
YOUR JOING DATE IS  AS 

      DATE = DS'''

letter = letter.replace("NAME",a)
letter = letter.replace("AS",b)
letter = letter.replace("DS",c)
print(letter)
