---
layout: page
title: College Football Rankings
permalink: lrmc-rankings/
---
This page holds up-to-date team rankings based on my implementation of the logistic regression/Markov chain (LRMC) model originally described by [Kvam and Sokol](https://onlinelibrary.wiley.com/doi/10.1002/nav.20170) and adapted for college football by [Kolbush and Sokol](https://sciendo.com/article/10.1515/ijcss-2017-0014).

The LRMC Rating represents the probability that a team is truly the best in the nation.

### Week 9 Rankings

| Rank | Team (Record)                             | LRMC Rating |
|------|------------------------------------------|-------------|
| 1    | **Indiana** (_7-0_)                        | 0.92%       |
| 2    | **Ohio State** (_7-0_)                     | 0.86%       |
| 3    | **Notre Dame** (_5-2_)                     | 0.78%       |
| 4    | **Texas Tech** (_6-1_)                     | 0.73%       |
| 5    | **Oregon** (_6-1_)                         | 0.73%       |
| 6    | **Utah** (_5-2_)                           | 0.71%       |
| 7    | **Alabama** (_6-1_)                        | 0.71%       |
| 8    | **Texas A&M** (_7-0_)                      | 0.67%       |
| 9    | **USC** (_5-2_)                            | 0.66%       |
| 10   | **Georgia** (_6-1_)                        | 0.65%       |
| 11   | **Miami** (_5-1_)                          | 0.61%       |
| 12   | **Texas** (_5-2_)                          | 0.61%       |
| 13   | **BYU** (_7-0_)                            | 0.59%       |
| 14   | **Vanderbilt** (_6-1_)                     | 0.58%       |
| 15   | **Oklahoma** (_6-1_)                       | 0.58%       |
| 16   | **South Florida** (_6-1_)                  | 0.58%       |
| 17   | **Florida State** (_3-4_)                  | 0.57%       |
| 18   | **Michigan** (_5-2_)                        | 0.57%       |
| 19   | **Iowa** (_5-2_)                           | 0.55%       |
| 20   | **Virginia** (_6-1_)                        | 0.55%       |
| 21   | **Pittsburgh** (_5-2_)                      | 0.55%       |
| 22   | **Ole Miss** (_6-1_)                        | 0.55%       |
| 23   | **Missouri** (_6-1_)                        | 0.55%       |
| 24   | **Washington** (_5-2_)                      | 0.53%       |
| 25   | **Illinois** (_5-2_)                         | 0.53%       |
| 26   | **LSU** (_5-2_)                             | 0.53%       |
| 27   | **Tennessee** (_5-2_)                        | 0.51%       |
| 28   | **Auburn** (_3-4_)                          | 0.50%       |
| 29   | **Louisville** (_5-1_)                       | 0.50%       |
| 30   | **Florida** (_3-4_)                          | 0.50%       |
| 31   | **North Texas** (_6-1_)                       | 0.50%       |
| 32   | **Cincinnati** (_6-1_)                        | 0.49%       |
| 33   | **Iowa State** (_5-2_)                         | 0.49%       |
| 34   | **Georgia Tech** (_7-0_)                       | 0.49%       |
| 35   | **Penn State** (_3-4_)                          | 0.49%       |

Note: This model is calibrated using an alternative measure of margin of victory that counts the number of possessions, or scores, a team wins by. Here, a touchdown and 2-point conversion together are worth 1 score, and a field goal is worth half a score. For example, a 27-point victory is converted into a 3.5 score win (3 TDs and 1 FG). This is to ensure that margins of victory are consistent with how far the opponent was held from winning.
