# Championship-2025-2026-Football-Analytics-Intelligence-Report
# Objective

Analyze Championship 2025/2026 match data to evaluate:

team performance relative to bookmaker expectations
attacking efficiency
finishing inefficiency
match-winning performance indicators
tactical patterns associated with success

The goal was to transform raw football match data into actionable football business intelligence useful for clubs, analysts, recruiters, and betting markets.

# Data Used

Dataset: football-data.co.uk/England Championship 2025/2026 Match Data (E1.csv)

# Dataset Overview
552 matches
132 variables
Match-level football statistics
Key Variables Used
Category	Variables
Match Outcomes	FTR, FTHG, FTAG
Attacking Metrics	HS, AS, HST, AST
Discipline	HF, AF, HY, AY
Set Pieces	HC, AC
Betting Markets	B365H, B365D, B365A
# Tools & Technologies
Python
Pandas
NumPy
Matplotlib
# Key Findings
1. Millwall, Hull, and Coventry significantly outperformed bookmaker expectations
Team	Performance Gap
Millwall	+17.28
Hull	+15.72
Coventry	+13.32
Insight

These teams consistently earned more points than bookmaker-implied probabilities predicted, suggesting strong tactical efficiency and market undervaluation.

2. Leicester and West Brom were major underperformers
Team	Performance Gap
Leicester	-13.38
West Brom	-14.41
Insight

Both clubs failed to convert underlying performance levels into actual results consistently.

3. Coventry produced the league’s strongest attacking profile
Metric	Value
Goals	97
Shots	751
Goals per Game	2.11
Insight

Coventry successfully combined elite attacking volume with strong finishing efficiency.

4. West Brom and Watford showed major attacking inefficiency
Team	Conversion Rate
West Brom	7.8%
Watford	8.3%
Insight

Both teams generated attacking opportunities but converted chances poorly relative to league standards.

5. Shots on target were the strongest predictor of winning
Metric	Correlation With Winning
Shots on Target	0.375
Total Shots	0.071
Insight

Attacking efficiency and shot quality had a far stronger relationship with winning than raw shot volume.

# Visuals
1. Performance vs Bookmaker Expectation Bar Chart

Displays:

overperforming teams
underperforming teams
market inefficiencies
2. Shot Volume vs Conversion Rate Scatter Plot

Identifies:

clinical attacking teams
inefficient high-volume teams
3. Winning vs Non-Winning Match Metrics

Compares:

shots on target
shots
corners
fouls
between winning and non-winning teams.
4. Correlation Analysis

Highlights which in-game metrics most strongly influence match outcomes.

# Tactical Implications
Efficient Teams

Teams such as Coventry and Hull demonstrated:

effective shot selection
strong attacking structure
efficient final-third execution
Inefficient Teams

Teams such as West Brom and Watford showed:

poor finishing efficiency
low-quality shot selection
inability to maximize attacking volume
Winning Football Pattern

The analysis suggests:

shot quality matters more than shot quantity
efficient attacking execution is a stronger predictor of success than overall attacking volume
# Actionable Recommendations
For Coaching Staff
prioritize chance quality over raw shot volume
improve finishing efficiency through tactical shot selection
focus on creating central high-value opportunities
For Recruitment Teams

Target players who:

improve shot conversion
contribute to attacking efficiency
consistently generate shots on target
For Betting Analysts

Monitor:

teams overperforming bookmaker expectations
inefficient attacking teams likely to improve through regression
hidden market mispricing opportunities
Portfolio Positioning Statement

“I built a Championship football intelligence model combining bookmaker market evaluation, attacking efficiency analysis, finishing performance, and match-winning factor analysis to uncover tactical and business insights from the 2025/2026 season championship league.”
