# friend-finder
Friend Finder is friend matching based on the user's responses to a ten question survey based loosely on Game of Thrones characters. 

The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). 

When the survey is submitted, an existing user record closest to the current user's responses is found and returned with a photo. 

The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.
