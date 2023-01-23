# lab_4_Glass_classes_and_objects
Create a class called Glass. Upon initialization, it will not receive any parameters. You must create an instance attribute called content which should be equal to 0. You should also create a class attribute called capacity which should be 250 ml. Create 3 instance methods:
-	fill(ml) - fills the glass with the given milliliters if there is enough space in it and returns "Glass filled with {ml} ml", otherwise returns "Cannot add {ml} ml"
-	empty() - empties the glass and returns "Glass is now empty" 
-	info() - returns info about the glass in the format "{space_left} ml left"

Test Code

glass = Glass()
print(glass.fill(100))
print(glass.fill(200))
print(glass.empty())
print(glass.fill(200))
print(glass.info())


Output

Glass filled with 100 ml
Cannot add 200 ml
Glass is now empty
Glass filled with 200 ml
50 ml left
