#  Poker Flush Probability Simulator in R  
This R script simulates Texas Hold'em scenarios to estimate flush probabilities at different stages (hole, flop, turn, river) using Monte Carlo simulations. It generates a standard deck, deals cards randomly, and calculates probabilities. Ideal for poker enthusiasts and probability analysis.
Your **README.md** should provide an overview of your project, installation steps, usage instructions, and other relevant details. Here’s a well-structured README for your project:  


# Poker Flush Probability Simulator in R  

## Overview  
This R script simulates Texas Hold'em poker scenarios to estimate the probability of forming a flush at different stages of the game (hole cards, flop, turn, and river). Using Monte Carlo simulations, it calculates the likelihood of achieving a flush, helping poker players and data enthusiasts analyze probabilities.  

## Features  
- Generates a standard 52-card deck  
- Simulates Texas Hold'em dealing (hole, flop, turn, and river)  
- Calculates the probability of forming a flush at each stage  
- Runs Monte Carlo simulations for more accurate probability estimation  

## Installation  
1. Ensure you have R installed on your system. You can download it from [CRAN](https://cran.r-project.org/).  
2. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/poker-flush-simulator.git
   ```
3. Open R and set the working directory to the project folder.  

## Usage  
Run the script in R:  
```r
source("poker_flush_simulator.R")
main()
```  
The output will display:  
- Your **hole cards**  
- The probability of forming a **flush** after each stage (hole, flop, turn, river)  
- The community cards dealt at each stage  

## Example Output  
```
Hole Cards: 10 Hearts, 6 Hearts  
Probability of Flush after Hole Cards: 0.1523  

Flop Cards: 3 Hearts, Q Hearts, 8 Clubs  
Probability of Flush after Flop: 0.3245  

Turn Card: K Hearts  
Probability of Flush after Turn: 0.6128  

River Card: 2 Diamonds  
Probability of Flush after River: 0.6891  
```  

## Customization  
You can adjust the number of Monte Carlo simulations by modifying:  
```r
calculate_probabilities(deck, simulations = 100000)  # Increase for more accuracy
```  

