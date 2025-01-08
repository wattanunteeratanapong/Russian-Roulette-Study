# Russian Roulette Study
Have you ever wondered whether you should go first or second in "Russian Roulette" sequential firing? <br><br>
<img src="https://github.com/user-attachments/assets/5cb67238-0a40-460b-8b4d-d00b44d7d0cf" width="100%" alt="Squid Game">

## Overview & Control Variable
- In this experiment doing sequential firing (no re-spin)
- When we pulled the marble out of the bag, we just put it back in, so that it could be an Independent Trial
- P(success) every trial is constant (because we put marble back in the bag)
- 10 Million time of simulation
<br>

## Hypothesis
P(k n) is a probability of success k time in n trial (order doesn't matter)<br>
P(k n) = nCk × pᵏ × (1-p)ⁿ⁻ᵏ <br>

### First Player
<img src="https://github.com/user-attachments/assets/989cd487-3bb9-408a-b21a-c14e01263a05" width="400" alt="Seong Gi-hun"> <br>

Bag : Red Green Green <br>
Success(k) is when drawing Red Marbel <br>
P(0 10) &nbsp;&nbsp;= 10C0 (1/3)⁰(2/3)¹⁰ &nbsp;           ≈ 0.01734153 &nbsp;(1.734153%)<br>
P(1 10) &nbsp;&nbsp;= 10C1 (1/3)¹(2/3)⁹ &nbsp;&nbsp;&nbsp;≈ 0.08670765 &nbsp;(8.670765%)<br>
P(2 10) &nbsp;&nbsp;= 10C2 (1/3)²(2/3)⁸ &nbsp;&nbsp;&nbsp;≈ 0.19509221 &nbsp;(19.509221%)<br>
P(3 10) &nbsp;&nbsp;= 10C3 (1/3)³(2/3)⁷ &nbsp;&nbsp;&nbsp;≈ 0.26012295 &nbsp;(26.012295%)<br>
P(4 10) &nbsp;&nbsp;= 10C4 (1/3)⁴(2/3)⁶ &nbsp;&nbsp;&nbsp;≈ 0.22760758 &nbsp;(22.760758%)<br>
P(5 10) &nbsp;&nbsp;= 10C5 (1/3)⁵(2/3)⁵ &nbsp;&nbsp;&nbsp;≈ 0.13656455 &nbsp;(13.656455%)<br>
P(6 10) &nbsp;&nbsp;= 10C6 (1/3)⁶(2/3)⁴ &nbsp;&nbsp;&nbsp;≈ 0.05690190 &nbsp;(5.690190%)<br>
P(7 10) &nbsp;&nbsp;= 10C7 (1/3)⁷(2/3)³ &nbsp;&nbsp;&nbsp;≈ 0.01625768 &nbsp;(1.625768%)<br>
P(8 10) &nbsp;&nbsp;= 10C8 (1/3)⁸(2/3)² &nbsp;&nbsp;&nbsp;≈ 0.00304832 &nbsp;(0.304832%)<br>
P(9 10) &nbsp;&nbsp;= 10C9 (1/3)⁹(2/3)¹ &nbsp;&nbsp;&nbsp;≈ 0.00033870 &nbsp;(0.033870%)<br>
P(10 10) = 10C10 (1/3)¹⁰(2/3)⁰                            ≈ 0.00001694 &nbsp;(0.001694%)<br>

### Second Player
<img src="https://github.com/user-attachments/assets/a0dbcf82-ea64-4e22-bc08-d7c86ac45e15" width="400" alt="The Saleman"> <br>

Bag : Red Green Green <br>
Success(k) is when drawing Red Marbel <br>
P(0 10) &nbsp;&nbsp;= 10C0 (1/3)⁰(2/3)¹⁰ &nbsp;           ≈ 0.01734153 &nbsp;(1.734153%)<br>
P(1 10) &nbsp;&nbsp;= 10C1 (1/3)¹(2/3)⁹ &nbsp;&nbsp;&nbsp;≈ 0.08670765 &nbsp;(8.670765%)<br>
P(2 10) &nbsp;&nbsp;= 10C2 (1/3)²(2/3)⁸ &nbsp;&nbsp;&nbsp;≈ 0.19509221 &nbsp;(19.509221%)<br>
P(3 10) &nbsp;&nbsp;= 10C3 (1/3)³(2/3)⁷ &nbsp;&nbsp;&nbsp;≈ 0.26012295 &nbsp;(26.012295%)<br>
P(4 10) &nbsp;&nbsp;= 10C4 (1/3)⁴(2/3)⁶ &nbsp;&nbsp;&nbsp;≈ 0.22760758 &nbsp;(22.760758%)<br>
P(5 10) &nbsp;&nbsp;= 10C5 (1/3)⁵(2/3)⁵ &nbsp;&nbsp;&nbsp;≈ 0.13656455 &nbsp;(13.656455%)<br>
P(6 10) &nbsp;&nbsp;= 10C6 (1/3)⁶(2/3)⁴ &nbsp;&nbsp;&nbsp;≈ 0.05690190 &nbsp;(5.690190%)<br>
P(7 10) &nbsp;&nbsp;= 10C7 (1/3)⁷(2/3)³ &nbsp;&nbsp;&nbsp;≈ 0.01625768 &nbsp;(1.625768%)<br>
P(8 10) &nbsp;&nbsp;= 10C8 (1/3)⁸(2/3)² &nbsp;&nbsp;&nbsp;≈ 0.00304832 &nbsp;(0.304832%)<br>
P(9 10) &nbsp;&nbsp;= 10C9 (1/3)⁹(2/3)¹ &nbsp;&nbsp;&nbsp;≈ 0.00033870 &nbsp;(0.033870%)<br>
P(10 10) = 10C10 (1/3)¹⁰(2/3)⁰                            ≈ 0.00001694 &nbsp;(0.001694%)<br>

## Result from Simulation
### First Scenerio
<img src="https://github.com/user-attachments/assets/5f9f731e-3ee7-4859-b954-17ea49e2ef93" width="35%" height="300" alt="Image 1">
<img src="https://github.com/user-attachments/assets/508043df-37b1-411c-87e7-6da7190bbf29" width="35%" height="300" alt="Image 2">
<img src="https://github.com/user-attachments/assets/c4d55467-7a35-49f4-bd20-1abc596d2f8f" width="20%" height="300" alt="Image 3">

### Second Scenerio
<img src="https://github.com/user-attachments/assets/61883594-d729-412e-b2cb-6d3e5717e0ec" width="35%" height="300" alt="Image 1">
<img src="https://github.com/user-attachments/assets/67c941ed-f4c4-4ebb-96e1-48223afa92ca" width="35%" height="300" alt="Image 2">
<img src="https://github.com/user-attachments/assets/2c8ca9f6-d791-40ed-a188-1dd5cb5adc38" width="20%" height="300" alt="Image 3">
<br><br>

## Conclusion <br>
<img src="https://github.com/user-attachments/assets/989cd487-3bb9-408a-b21a-c14e01263a05" width="49%" alt="Seong Gi-hun"> 
<img src="https://github.com/user-attachments/assets/a0dbcf82-ea64-4e22-bc08-d7c86ac45e15" width="49%" alt="The Saleman"> <br><br>
"Russian Roulette" might not seem as a fair game becuase player who go first have 1/6 chance, then second player have 1/5 ... 1/4 1/3 1/2 1/1, but the result of this game is already predetermined after first spin of revolver. <br><br>
While the final outcome is set from the start, the uncertainty and the changing probabilities create an illusion of fairness based on turn order. <br>

