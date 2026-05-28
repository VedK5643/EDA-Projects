# IPL Data Analysis (2008–2024)

Exploratory data analysis on IPL match and ball-by-ball data covering 16 seasons, 1000+ matches, and 260,000+ deliveries.

## Dataset
- **Source:** [Kaggle — IPL Complete Dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- **Files:** `matches.csv` + `deliveries.csv` merged on match ID
- **Size:** 260,920 rows after merge

## Questions Explored
| # | Question |
|---|----------|
| 1 | Which team has won the most IPL matches? |
| 2 | Which team has the best win rate (wins/matches played)? |
| 3 | Does winning the toss affect match outcome? |
| 4 | Which venues favor batting first? |
| 5 | Who are the top 10 run scorers in IPL history? |
| 6 | Who are the top 10 wicket takers? |
| 7 | Which bowlers have the best economy rate (min 100 overs)? |
| 8 | How has IPL scoring changed across seasons? |
| 9 | Head-to-head record between all teams |
| 10 | Season-wise win rate for every team |

## Key Findings
- Mumbai Indians and CSK are the two undisputed dynasties
- Toss winner wins only 44% of matches — toss has no meaningful advantage
- MA Chidambaram Stadium heavily favors batting first (60%+ win rate)
- Spin bowlers dominate economy rates — Narine and Rashid Khan most economical
- IPL scoring has increased 40%+ from 2008 to 2024

## Tech Stack
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter Notebook`

## How to Run
1. Download dataset from [Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
2. Place `matches.csv` and `deliveries.csv` in the same folder as the notebook
3. Run all cells