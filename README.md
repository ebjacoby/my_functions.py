# my_functions.py
functions exercise
# custom-functions/my_functions.py

# TODO: define temperature conversion function here

# TODO: define gradebook function here

def numeric_to_letter_grade(n):
    if n < 60:
        return "F"
    elif n < 70:
        return "D"
    elif n < 80:
        return "C"
    elif n < 90:
        return "B"
    else: 
        return "A"

if __name__ == "__main__":

    print("--------------------")
    print("CUSTOM FUNCTIONS EXERCISE...")

#print("--------------------")
#c=10
#print("THE CELSIUS TEMP IS: ", c, "DEGREES")
#def celsius_to_fahrenheit(c):
#    return ((c * 1.8) + 32)
#f = celsius_to_fahrenheit(c)
#print("THE FAHRENHEIT EQUIVELANT IS: ", f, "DEGREES")

    score = input("Please input a numeric letter grade (from 0 to 100): ")
    print(type(score)) #>str
    score= float(score)
    print("--------------------")
    print("THE NUMERIC SCORE IS:", score)
    grade = numeric_to_letter_grade(score)
    print("THE LETTER-GRADE EQUIVALENT IS:", grade)
