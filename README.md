# Google Code Jams

This repository contains:

- My solutions with python code to the problems from the [Google Code Jams](https://codingcompetitions.withgoogle.com/codejam)
- Resources to learn and prepare the challenges
- A scrapper to download information from the languages used by the participants in the challenges

The goal is to improve my algorithmic skills and to see if python can be a competitive language.
The statistics so far so that the best competitors use mainly C++.

The strategy will be to always write a working solution for every problem I try to solve. I might
look into the analysis section if needed but I should always write a working solution. If I only
read the analysis but not write a solution I will not learn anything.

## Testing the solutions

```bash
# run the script with input data
cat input.txt | python code.py
# run the script with input data and compare the output with the expected output
cat input.txt | python code.py > pred.txt ; echo "Script output is: "; cat pred.txt; echo "Comparison with required output"; diff output.txt pred.txt; rm pred.txt
```

## Python dependencies

The known python dependencies are: `numpy, scipy`

## Resources

- [Google Code Jam — How To Prepare by Konopka Kodes](https://konopkakodes.medium.com/google-code-jam-study-guide-a8c58baf6397)
- [▶️ Dynamic Programming - Learn to Solve Algorithmic Problems & Coding Challenges](https://www.youtube.com/watch?v=oBt53YbR9Kk&t=1638s)

### Dynamic programming

[Dynamic programming by favtutor](https://favtutor.com/blogs/dynamic-programming)

Toy problems:

- Fibonacci
- Grid traveler
- Can sum, how sum and best sum

Sample problems:

- [Spiralling into control](https://codingcompetitions.withgoogle.com/codejam/round/00000000008778ec/0000000000b15a74)

## 2023 New year Resolutions

The following table summarizes what was needed on 2022 to pass the rounds.

| Round         | Participants | Requirements to pass round |
|---------------|--------------|----------------------------|
| Qualification | ∞            | 30                         |
| 1             | ∞            | 34/100 @ 1:51              |
| 2             | 4500         | 25/100 @ 1:19              |
| 3             | 1001         | 71/100 @ 1:28              |
| Finals        | 26           |                            |

- 2023 resolution: get to round 3. This might be achieved by solving 2 problems each round
- 2024 resolution: get to final round. To achieve this I should be able to solve 3 problems in 2.5 hours.
  Thus I need to be fast, experienced and to have good templates.

To be able to achieve this goals I should do one challenge per week.
