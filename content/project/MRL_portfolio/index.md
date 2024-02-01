---
title: Multi-Agent Reinforcment Learning for Financial Portfolio Management with Transformers
summary: An example of using the in-built project page.
tags:
  - Deep Learning
  - Reinforcment Learning
date: '2023-10-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Created using Stability AI
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This project delves into the realm of financial portfolio management through an advanced approach: Multi-Agent Policy-Driven Reinforcement Learning. The focus is on leveraging transformers to model policy functions, steering away from conventional value-driven models to embrace a policy-driven multi-agent framework. This innovative shift allows for diversified investment strategies across multiple agents, each striving to maximize individual portfolio profitability.

The problem setup frames portfolio management as a Markov Decision Process (MDP), emphasizing states, allowable actions, and rewards. In the multi-agent scenario, the goal is to determine the optimal joint policy across all participating agents, aiming for cumulative reward maximization. The training dataset, spanning two decades, comprises the opening and closing prices of the top 30 stocks from the Dow Jones Industrial Average index.

The proposed method employs Multi-Agent Policy-Driven Reinforcement Learning with Proximal Policy Optimization (PPO) and introduces transformers to model policy functions. The framework's architecture encompasses individual transformer networks for each agent, fostering maximum diversity and individual reward maximization. Two key evaluation metrics, Return and Sharpe ratio, gauge the profitability of the method.

The project's codebase is implemented within FINRL, an open-source library dedicated to financial reinforcement learning, incorporating three layers: market environments, DRL agents, and applications.