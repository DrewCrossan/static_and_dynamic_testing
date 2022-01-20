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
    if card.value = 1: # should be a "==" rather than a single "="
      return True
    else # missing a colon at the end of "else"
      return False
   

  dif highest_card(self, card1 card2): # spelling error, should start with def not dif. Missing a comma after card1.
  if card1.value > card2.value: # not indented correctly
    return card # should be card1, not card
  else:
    return card2
  


def cards_total(self, cards): # whole method needs indenting
  total # Total not defined
  for card in cards:
    total += card.value
    return "You have a total of" + total # needs to be indented to the left. Can't concatenate a string and int, need to stringify total to concatenate.
  
```
