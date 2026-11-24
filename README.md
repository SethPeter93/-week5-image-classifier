# Seth Pearson
# Week 5 - Image Classifier
I chose the coin group, and my classes were Pennies, Dimes, and Nickels 
| Condition | Description |
|---|---|
| Where I was | my bed roon |
| Lighting | over head led with curtain open |
| Background | brown wooden desk |
| Distance | 5 inches from coins |
| Angles | mostly straight on with a few from side views |
| Whose objects | my coins |


| Object | Predictions | Total |
|---|---:|---:|
| Dime | [5 ] | 5 |
| Nickel| [5 ] | 5 |
| Pennie | [ 4] | 5 |

Overall is was 93 percent confident
with a 
**Accuracy:** [14] / 15 or 93 percent 



I do not believe these results since the test photos were so close to the training ones. Which could give the model a way higher score then it really was.


| Test | Accuracy | Worst Failure |
|---|---:|---:|
| Different Place | 26%| The Nickel |
| Different Light | 53%| The Pennie |
| Different Distance |66%| The Pennie |
| Someone Else's Objects | 53% | The dime |
Total of 49 percent accuracy.
**Which test hurt the most?**
The worst test was different distances, and I believe this happened since my model was only rembering the background, so when it changed that messed up the whole thing.



### 4.1 Form a Hypothesis

It is using the brown desk since when I changed that the results became a lot worse.

### 4.2 Change One Thing and Retrain

I changed the background to match the first one to hopefully inprove the score. 

I retrained the model and it did not change at all it instaed got worse and only got 20 percent  correct. I think this happened since the new desk was still not close enough to the old one.



<img width="1680" height="907" alt="Screenshot 2026-11-23 203235" src="https://github.com/user-attachments/assets/fd5af394-b0ac-4ec4-a19b-d5f6753837a5" />
<img width="1392" height="949" alt="Screenshot 2026-11-23 204236" src="https://github.com/user-attachments/assets/01b36913-b1da-4cd9-942c-41612d1a6ee8" />


