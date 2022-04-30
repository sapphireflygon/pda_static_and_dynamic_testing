### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: # This line should have double equals == to equate card.value and 1
      return True
    else # Need a colon : at the end of this line
      return False
   

  dif highest_card(self, card1 card2): # Should be def to define a new function, not dif. Also needs a comma between the two parameters card1 and card2.
  if card1.value > card2.value: # If-else statment needs to be indented to be part of the function
    return card # Should be card1
  else:
    return card2
  


def cards_total(self, cards): # Not indented to be a part of the class; entire function needs to move over one tab space
  total # Variable not defined; should be set as total = 0
  for card in cards:
    total += card.value
    return "You have a total of" + total # Return statement should not be a part of the for loop, need to fix indentation. Also string concatenation cannot join a str with an int, need to convert total to a string, or use an fstring instead of concatenation.
  
```
