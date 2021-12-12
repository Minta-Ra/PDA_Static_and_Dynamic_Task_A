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
    # If statement should be comparing, so needs to be == 1
    if card.value = 1:
      return True
    # Missing colon at the end of else
    else
      return False
   

  # Misspelled dif, to define new function should be def
  # Passed in variables in () needs to be separated using comma
  dif highest_card(self, card1 card2):
  # If and else statements (4 lines below) needs to be indented to be inside of "highest_card" function
  if card1.value > card2.value:
    # Card does not exist, needs to be card1
    return card
  else:
    return card2
    # Missing comparisment if cards would be equal
  

# Method indented incorrectly, needs to be inside of the class
def cards_total(self, cards):
  # Missing assignment to total, such as total = 0
  total
  for card in cards:
    total += card.value
    # Return is not indented properly, it needs to be outside of for loop
    # Total should be passed in as {value} and formated string is needed
    return "You have a total of" + total
  
```
