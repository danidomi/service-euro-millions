
# Backend Interviews: EuroMillions Problem-Solving

## Introduction

EuroMillions is one of the most popular lottery games in Europe. In this game, players choose 5 numbers from a pool of 1 to 50 and 2 "Lucky Star" numbers from a pool of 1 to 12. The goal is to match as many of these numbers as possible with the drawn numbers in order to win a prize. EuroMillions offers a wide range of prizes, including a massive jackpot.

We will explore three backend interview assignments related to EuroMillions:

### Assignment 1: Model EuroMillions and Import Data

The first task is to model EuroMillions and import the [CSV file](euromillion.csv)

### Assignment 2: Generating a Random EuroMillions Combination

The second task is to create a API that generates a random EuroMillion combination. This combination should consist of 5 random numbers between 1 and 50 (inclusive) and 2  "Lucky Star" numbers between 1 and 12 (inclusive).

Here's the [API Definition](swagger.yaml)

```http request
/api/v1/euro-millions/random
```
You can use this function to generate random EuroMillions combinations for testing or any other purposes.

### Assignment 3: Finding Possible Combinations for Given Numbers

The third task is to create an API that finds all possible EuroMillions combinations that contain a specified set of numbers and stars, if none all results should be returned.
For example, given a set of 3 numbers and 1 star (e.g., [22, 7, 1] and [9]), the function should find all EuroMillions combinations that include those specific numbers and stars.

Here's the [API Definition](swagger.yaml)

```http request
/api/v1/euro-millions?query=numbers:22,7,1|stars:9
```
This API generates all possible EuroMillions combinations and then filters them to find the ones that contain the specified numbers and stars.

These three assignments should help candidates demonstrate their problem-solving skills and backend development capabilities in the context of the EuroMillions lottery game.

## Slack

if you have any doubts or wanna join the discussion over slack, please join us [here](https://twolazyworkspace.slack.com/archives/C05TCKKBABS)
