# Cookie-Cats-Mobile-Game_ABTesting

ntroduction: Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level.

Problem statement:
As players progress through the game, they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention and game rounds.

Methodology and Analysis used: 
1. A/B Testing
2. Shapiro test
3. ttest
4. levene test

Programming language:
Python (Pandas)

A/B Testing

Assumptions:

1. Check normality
2. If Normal Distribution, check homogeneity

Steps:

1. Split & Define Control Group & Test Group
2. Apply Shapiro Test for normality
3. If parametric apply Levene Test for homogeneity of variances
4. If Parametric + homogeneity of variances apply T-Test
5. If Parametric - homogeneity of variances apply Welch Test
6. If Non-parametric apply Mann Whitney U Test directly
