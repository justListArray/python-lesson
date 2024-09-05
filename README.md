# python-lesson
no
REUIREMENTS:

Use all the variables given in the code cell to produce the multiline string given under 'OUTPUT'.
You can use 'if' or 'if-else'
Use methods like split(), istitle(), title(), replace(), len(), lower(), etc. to produce the multiline string.
Do not use replace() function more than once
Use string methods to get the 'C' from the name variable
Use len() function to calculate the total characters in the final text to produce the '508' number
Do not use any methods or tricks that we have not yet covered in the lecture yet
After your code successfully prints the 'output_text', compare it with the test_text. If everything goes well, the two text strings will match.
OUTPUT:

A Brief Profile of C. Dickens in 508 characters.

Hello. My name is Charles Dickens. I am an English novelist. I was born on February 7, 1812, in Portsmouth, England. I am most famous as a writer of the Victorian era. I married Catherine Hogarth in 1836. We have ten children. Some of my most famous works include "A Christmas Carol," "Oliver Twist," "David Copperfield," and "Great Expectations." Besides being a writer, my other talent was doing dramatic public readings of my work. I died on June 9, 1870, at my home in Gad's Hill Place, Kent, England.

name = "CHARLES DICKENS"
dob = "February 7, 1812"
birthplace = "portsmouth, England"
famous_for = "A writer of the Victorian era"
married_to = "Catherine Hogarth"
year_of_marriage = "1836"
number_of_children = "ten"
famous_works = '"A Christmas Carol", "Oliver Twist", "David Copperfield", and "Great Expectations"'
other_talent = "doing DRAMATIC public readings of my work"
death_date = "June 9, 1870"
place_of_death = "Gad's Hill Place, Kent, England"

#Use the different methods that are given under 'REQUIREMENTS' to complete the code.





title = # The title of the output text should be stored in this variable

output_text = # Your final output text should be stored in this variable, which will also include the 'title'.

print(output_text)

test_text = f'''A Brief Profile of C. Dickens in 505 characters.

Hello. My name is Charles Dickens.
I am an English novelist. I was born on February 7, 1812, in Portsmouth, England.
I am most famous as a writer of the Victorian era.
I married Catherine Hogarth in 1836. We have ten children.
Some of my most famous works include "A Christmas Carol", "Oliver Twist", "David Copperfield", and "Great Expectations".
Besides being a writer, my other talent was doing dramatic public readings of my work.
I died on June 9, 1870, at my home in Gad's Hill Place, Kent, England.'''

if output_text == test_text:
    print("SUCCESS! Yes, your output text matches the test text.")
else:
    print("OOPS!!! Sorry, your output text does not match the test text.")
