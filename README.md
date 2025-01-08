# Russian Roulette Study
Have you ever wondered whether you should go first or second in "Russian Roulette" sequential firing? <br><br>
<img src="https://github.com/user-attachments/assets/5cb67238-0a40-460b-8b4d-d00b44d7d0cf" width="100%" alt="Squid Game">

## Overview & Control Variable
- In real life scenerio having factors like revolver bias, mechanical imperfections, or human error could introduce bias, but in this experiment assume a fair randomness
- In this experiment doing sequential firing (no re-spin)
- The revolver has 6 chambers and 1 bullet
- Test 1v1 against two player
- 10 Million time of simulation
<br>

## Hypothesis
P(k n) is a probability of survival k attemp in n chamber <br>
P(k n) = (n-k) / (n-k)+1 <br>

P(1 6) = (6-1)/(6-1)+1 = 5/6 ≈ 0.83333 ≈ 83.333% <br>
P(2 6) = (6-2)/(6-2)+1 = 4/5 ≈ 0.80000 ≈ 80.000% <br>
P(3 6) = (6-3)/(6-3)+1 = 3/4 ≈ 0.75000 ≈ 75.000% <br>
P(4 6) = (6-4)/(6-4)+1 = 2/3 ≈ 0.66667 ≈ 66.667% <br>
P(5 6) = (6-5)/(6-5)+1 = 1/2 ≈ 0.50000 ≈ 50.000% <br>
P(6 6) = (6-6)/(6-6)+1 = 1/1 ≈ 1.00000 ≈ 100.000% <br>
<br>


## Result from Simulation
### Probability of Death for Each Player in Russian Roulette Simulation
<img src="https://github.com/user-attachments/assets/f74b90b1-34dd-4a26-827c-ccef4da45547" width="100%" alt="Image 1">

### Distribution of Turns to Death in Russian Roulette Simulation
<img src="https://github.com/user-attachments/assets/7a218236-2a2d-4c94-acc4-4297d3679f8d" width="100%" alt="Image 1">
<br><br>

## Conclusion <br>
<img src="https://github.com/user-attachments/assets/989cd487-3bb9-408a-b21a-c14e01263a05" width="49%" alt="Seong Gi-hun"> 
<img src="https://github.com/user-attachments/assets/a0dbcf82-ea64-4e22-bc08-d7c86ac45e15" width="49%" alt="The Saleman"> <br><br>
"Russian Roulette" might not seem as a fair game becuase player who go first have 1/6 chance, then second player have 1/5 ... 1/4 1/3 1/2 1/1, but the result of this game is already predetermined after first spin of revolver. <br><br>

The probabilities of the bullet being in any given chamber are equal, that mean this game is a fair game. <br><br>
While this game is a fair game because the final outcome is set from the start, but the uncertainty and the changing probabilities create an illusion of fairness based on turn order. <br>

