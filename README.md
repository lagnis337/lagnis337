# Chirag Singal

Senior Data Scientist based in Bangalore. Since 2022 I've built machine-learning and analytics systems in fintech and ride-hailing: an adaptive payment router, a multilingual safety classifier that decides how drivers are treated on a ride-hailing platform, and an LLM (large language model) analyst that answers a team's data questions from its own wiki.

**Portfolio with case studies: [lagnis337.github.io](https://lagnis337.github.io)**

## Work projects

The code is proprietary, so each link opens a write-up of the method. Some numbers come from a simulation and some from a before-and-after comparison with no control group; each write-up says which.

| Project | What it does | Where |
|---|---|---|
| [Adaptive payment-gateway router](https://lagnis337.github.io/projects/adaptive-gateway-router.html) | Picks a gateway per transaction and learns from every outcome, using an upper confidence bound (UCB) bandit with drift detection and a safety floor. A PPO policy was pre-trained on a simulator but is not in the decision path. On live traffic, payment success ran about 30% above the control; 96.0% against a threshold router's 42.7% in the 10M-transaction simulation that preceded the rollout. | Razorpay |
| [Driver churn prediction](https://lagnis337.github.io/projects/driver-churn.html) | Scores roughly 150,000 drivers every morning, averaging XGBoost and a random forest over 36 features, and hands ops a ranked call list. Against a randomised holdout, called drivers churned 30 percentage points less. | Namma Yatri |
| [Driver safety enforcement](https://lagnis337.github.io/projects/driver-safety-enforcement.html) | Translates rider feedback with the Sarvam API, sorts it into five severity groups, then either drops the driver's matching priority or sends a block to a person to confirm. Safety complaints fell by about half. | Namma Yatri |
| [Slack-native AI analyst](https://lagnis337.github.io/projects/text-to-sql-analyst.html) | 2,000 documents compiled into one approved data wiki. A model-agnostic Slack agent reads the index, opens only what it needs, and runs read-only SQL. 96% of answers earned a thumbs-up, and about 40% of a 127-person team asked something daily. | Razorpay |
| [Voice AI support agent](https://lagnis337.github.io/projects/voice-ai-support-agent.html) | Answers the driver support calls that repeat every day, in Hindi, English or Kannada, on Gemini Live with the Sarvam models behind it. Resolution time fell 75%. | Namma Yatri |
| Real-time payment fraud detection | Scores every transaction as it happens, blocks and reverses the clearest cases, and sends the rest to a much shorter review queue. Review turnaround fell from about four days to hours. No write-up: publishing the design of a live fraud model would help the people it blocks. | Razorpay |
| Offer-propensity ranking | Scores how likely a customer is to take an offer, weighing type, timing and product, for Uber's Asia-Pacific ads and promotions business. Net revenue per outlet tripled. | Uber |

## Personal pursuits

| Project | What it does | Code |
|---|---|---|
| [Fantasy Premier League player models](https://lagnis337.github.io/projects/fpl-player-models.html) | Predicts points for the coming gameweek from 79 pre-deadline features, tested with a 75-gameweek walk-forward backtest. Two data problems turned up: a column carrying post-match information, and an availability feature that did not help. | [fpl-player-models](https://github.com/lagnis337/fpl-player-models) |
| [Linear algebra for machine learning](https://lagnis337.github.io/foundations.html) | UC San Diego Extended Studies, grade A+. Face-image compression with principal component analysis, and gradient descent against the normal equation. | [linear-algebra-for-ml-coursework](https://github.com/lagnis337/linear-algebra-for-ml-coursework) |
| Log Ingestor | Takes log records in JSON, writes them into PostgreSQL, and searches them across 11 filters. | [logs_ingestor](https://github.com/lagnis337/logs_ingestor) |
| Lift Simulator | A browser simulation of the lifts in a building: two dispatch rules, random traffic, and the wait times that follow. [Live demo](https://lagnis337.github.io/Lift_Simulator/) | [Lift_Simulator](https://github.com/lagnis337/Lift_Simulator) |

## Contact

chiragsingal337@gmail.com · [linkedin.com/in/chiragsingal](https://www.linkedin.com/in/chiragsingal)
