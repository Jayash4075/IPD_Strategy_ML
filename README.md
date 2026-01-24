# IPD_Strategy_ML
This project focuses on designing a new strategy for the Iterated Prisoner’s Dilemma using machine learning and behavioural analysis. Behavioural patterns from existing strategies are analyzed to identify features that lead to high long-term payoffs.


## Project Overview
The Iterated Prisoner’s Dilemma (IPD) is a fundamental problem in game theory that models repeated interactions between rational agents.  
In each round, agents independently choose between cooperation and defection, and receive rewards based on a predefined payoff matrix.  
While short-term selfish behavior may yield immediate gains, long-term interactions require strategies that balance cooperation, retaliation, and forgiveness.
This project aims to design a new IPD strategy by leveraging machine learning techniques to analyze behavioral patterns of existing strategies and identify factors that lead to high long-term payoffs.


## 💫 Project Overview
This project focuses on designing a new optimized strategy for the Iterated Prisoner’s Dilemma (IPD) using machine learning and behavioral analysis.  
By analyzing historical performance and behavioral patterns of existing strategies, the goal is to construct a hybrid strategy that achieves high long-term payoff. The proposed strategy is evaluated through multi-round simulations against well-known IPD strategies.


## 📑 Problem Statement(E02)
The problem focuses on designing a robust, adaptive, and interpretable IPD strategy using machine learning insights that maximizes long-term payoffs across diverse opponents.
### - Long Term Strategy Optimization
Designing a strategy for the Iterated Prisoner’s Dilemma requires maximizing cumulative rewards over repeated interactions rather than short-term gains. The challenge lies in creating a strategy that performs consistently well across many rounds.
### - Trade-off Between Cooperation and Defection
Pure cooperation leads to exploitation, while constant defection prevents mutual benefit. The problem is to find a balance between cooperative behavior and defensive retaliation.
### - Identification of Successful Behaviourol patterns
Given multiple known IPD strategies with varying performance, it is difficult to manually identify which behavioral features lead to higher win rates. Data-driven analysis is required to extract these patterns.


## 📈 Dataset Description
The dataset used in this project consists of aggregate behavioral statistics collected from large-scale IPD tournaments.
Each row in the dataset represents a distinct strategy, while columns describe its behavior and performance characteristics, including:
- Overall cooperation rate  
- Overall defection rate  
- Probability of cooperation after being exploited  
- Probability of cooperation after exploiting the opponent  
- Probability of cooperation after mutual defection  
- Performance metrics such as win rate and median score  
This dataset enables analysis of how specific behavioral patterns influence long-term performance.


## 👥 Team Members & Responsibilities

**Heera Singh**
- Understanding and formalizing the project problem statement.
- Performing Exploratory Data Analysis (EDA) on the IPD strategy dataset.
- Feature analysis and selection based on behavioral patterns.
- Designing and training the machine learning model to learn optimal strategy traits.

**Jayash Mishra**
- Contributing to code organization and repository management.
- Interpreting model outputs to define a new hybrid IPD strategy.
- Documenting insights, results, and technical explanations.


## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib
