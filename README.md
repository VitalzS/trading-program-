## Overview:

This project analyzes trading activity to identify potentially bad traders based on their historical performance and behavior. It processes trade records, evaluates trader statistics, and applies rule‑based logic to flag traders who may be underperforming or exhibiting risky patterns.

The core logic is implemented in C++ and is designed for speed, clarity, and easy extension.

## Features:
-Parse and store trade data (e.g., trader ID, profit/loss, trade count).

-Compute performance metrics such as:

-Total profit/loss

-Number of trades

-Average trade performance

-Identify traders who meet “bad trader” criteria, such as:

-Consistently negative performance

-Excessive losses

-High trade volume with poor outcomes

-Output a clean list of flagged traders.
