# 30 Days of Algorithms

One problem a day for 30 days. Every problem is wrapped in a **real-life scenario** (payments, logistics,
banking, e-commerce, telecom) and difficulty climbs from **Day 1: Three Sum** up to a **Sudoku-solver
capstone**.

Topics covered: Big O notation, hashing and hash maps, algorithms, time and space complexity, recursion,
backtracking, divide and conquer, memoization, dynamic programming, greedy algorithms.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## How a day works

1. Open `day_XX_name/README.md`. Read the scenario and the task.
2. Write your code in `day_XX_name/solution.py` (it starts as a stub that raises `NotImplementedError`).
3. Run the tests:
   ```bash
   python check.py 1          # run one day
   python check.py            # run every day and print a scoreboard
   ```
4. When green, add a comment with your complexity analysis, commit, and move on.

> Run one day at a time (`python check.py N` or `pytest day_XX_name`). Every day uses the same file names,
> so pytest can't run two days in a single process.

## Rules that make it worth it

- **Try for 30 to 45 minutes before opening a hint.** Hints are in collapsed sections for a reason.
- **Don't open `_solutions/` until your tests pass** (or until you've tried for a full hour). Then compare approaches.
- Tests include **performance checks**. A correct but slow answer will fail on purpose. That's the Big O lesson.
- Read failing tests. Names like `test_random_against_brute_force` tell you what class of bug you have.

## The 30 days

| Day | Problem | Difficulty | Topics |
|-----|---------|------------|--------|
| 01 | [Ledger Zero-Sum Triplets](day_01_three_sum/README.md) | Medium | Hashing, Big O Notation, Two Pointers |
| 02 | [Sales Windows That Hit Target](day_02_subarray_sum/README.md) | Medium | Hashing, Prefix Sums, Time Complexity |
| 03 | [Longest Unique Browsing Streak](day_03_unique_session/README.md) | Medium | Hashing, Sliding Window, Big O |
| 04 | [Trending Search Terms](day_04_top_search_terms/README.md) | Medium | Hash Maps, Heaps, Time Complexity |
| 05 | [Longest Login Streak](day_05_login_streak/README.md) | Medium | Hash Sets, Time Complexity (beat O(n log n)) |
| 06 | [Branch Impact Multipliers](day_06_product_except_self/README.md) | Medium | Time & Space Complexity, Prefix/Suffix Products |
| 07 | [Valid Template Nesting](day_07_generate_parentheses/README.md) | Medium | Recursion, Backtracking-lite, Combinatorics |
| 08 | [Search a Rotated Log](day_08_rotated_log_search/README.md) | Medium | Divide and Conquer, Binary Search, Big O (log n) |
| 09 | [The Fuel-Stop Delivery Loop](day_09_delivery_route/README.md) | Medium | Greedy Algorithms, Time Complexity |
| 10 | [Exact-Change Combinations](day_10_exact_change/README.md) | Medium | Backtracking, Recursion, Pruning |
| 11 | [Cooldown Job Scheduler](day_11_job_scheduler/README.md) | Medium | Greedy Algorithms, Hashing (counting) |
| 12 | [Account Balance Cache](day_12_lru_cache/README.md) | Medium | Hash Maps, Data-Structure Design, O(1) operations |
| 13 | [Decode the Mobile-Money SMS](day_13_decode_sms/README.md) | Medium | Memoization, Recursion, Dynamic Programming |
| 14 | [ATM Fewest-Notes Payout](day_14_atm_notes/README.md) | Medium | Dynamic Programming (unbounded knapsack) |
| 15 | [Warehouse Label Scanner](day_15_warehouse_scan/README.md) | Medium | Backtracking, Recursion, Pruning |
| 16 | [Longest Growth Chain](day_16_growth_chain/README.md) | Medium-Hard | Dynamic Programming, Binary Search, Time Complexity |
| 17 | [Hashtag Splitter](day_17_hashtag_splitter/README.md) | Medium-Hard | Memoization, Backtracking, Recursion |
| 18 | [Dispatch Rider's Bag](day_18_rider_bag/README.md) | Medium-Hard | Dynamic Programming (0/1 knapsack) |
| 19 | [Ranking Disagreement Score](day_19_ranking_disagreement/README.md) | Hard | Divide and Conquer (merge sort), Time Complexity |
| 20 | [KYC Name Matching](day_20_kyc_name_match/README.md) | Hard | Dynamic Programming (2-D), Time & Space Complexity |
| 21 | [Credit / Debit Assignment](day_21_credit_debit_assignment/README.md) | Hard | Memoization, Dynamic Programming (counting) |
| 22 | [Lagos-to-Kano Refuel Plan](day_22_refuel_stops/README.md) | Hard | Greedy Algorithms, Heaps |
| 23 | [K-th Highest Transaction](day_23_kth_largest/README.md) | Hard | Divide and Conquer (quickselect), Time Complexity |
| 24 | [Cell-Tower Placement](day_24_cell_towers/README.md) | Hard | Backtracking, Pruning with Sets |
| 25 | [Fair Split Between Two Riders](day_25_fair_split/README.md) | Hard | Dynamic Programming (subset sum), Space Optimization |
| 26 | [Transaction Narration Filter](day_26_narration_filter/README.md) | Hard | Dynamic Programming (2-D), Pattern Matching |
| 27 | [Limited-Trades FX Strategy](day_27_fx_trading/README.md) | Hard | Dynamic Programming (state machine), Space Optimization |
| 28 | [Lagos Island Skyline](day_28_skyline/README.md) | Very Hard | Divide and Conquer (merge), Sweep Line |
| 29 | [Branch Closure Revenue Planner](day_29_branch_closures/README.md) | Very Hard | Dynamic Programming (interval DP), Recursion + Memoization |
| 30 | [Capstone: Exam-Hall Seating Solver](day_30_exam_seating/README.md) | Very Hard | Backtracking, Pruning (constraint propagation), Bitmasks |

## Progress tracker

- [ ] Day 01: Ledger Zero-Sum Triplets
- [ ] Day 02: Sales Windows That Hit Target
- [ ] Day 03: Longest Unique Browsing Streak
- [ ] Day 04: Trending Search Terms
- [ ] Day 05: Longest Login Streak
- [ ] Day 06: Branch Impact Multipliers
- [ ] Day 07: Valid Template Nesting
- [ ] Day 08: Search a Rotated Log
- [ ] Day 09: The Fuel-Stop Delivery Loop
- [ ] Day 10: Exact-Change Combinations
- [ ] Day 11: Cooldown Job Scheduler
- [ ] Day 12: Account Balance Cache
- [ ] Day 13: Decode the Mobile-Money SMS
- [ ] Day 14: ATM Fewest-Notes Payout
- [ ] Day 15: Warehouse Label Scanner
- [ ] Day 16: Longest Growth Chain
- [ ] Day 17: Hashtag Splitter
- [ ] Day 18: Dispatch Rider's Bag
- [ ] Day 19: Ranking Disagreement Score
- [ ] Day 20: KYC Name Matching
- [ ] Day 21: Credit / Debit Assignment
- [ ] Day 22: Lagos-to-Kano Refuel Plan
- [ ] Day 23: K-th Highest Transaction
- [ ] Day 24: Cell-Tower Placement
- [ ] Day 25: Fair Split Between Two Riders
- [ ] Day 26: Transaction Narration Filter
- [ ] Day 27: Limited-Trades FX Strategy
- [ ] Day 28: Lagos Island Skyline
- [ ] Day 29: Branch Closure Revenue Planner
- [ ] Day 30: Capstone: Exam-Hall Seating Solver

## Big O cheat sheet

| Complexity | Name | Feels like |
|------------|------|------------|
| O(1) | constant | dict lookup, array index |
| O(log n) | logarithmic | binary search, halving the problem |
| O(n) | linear | one pass over the data |
| O(n log n) | linearithmic | good sorting, merge sort, heap-based top-k |
| O(n^2) | quadratic | nested loops over the same data |
| O(n^3) | cubic | interval DP, triple loops |
| O(2^n) | exponential | trying every subset or sign pattern |
| O(n!) | factorial | trying every ordering |

Rule of thumb for Python in tests: about 10^7 simple operations per second. `n = 10^5` needs roughly
`O(n log n)` or better. `n = 3000` allows `O(n^2)`. `n <= 20` allows `O(2^n)`.

## Techniques at a glance

- **Hashing:** trade memory for O(1) lookups. "Have I seen this before?" Days 1 to 6, 12.
- **Recursion and backtracking:** build a solution one choice at a time, undo, try the next. Days 7, 10, 15, 24, 30.
- **Divide and conquer:** split, solve halves, combine. Days 8, 19, 23, 28.
- **Memoization and DP:** overlapping subproblems means cache them. Days 13, 14, 16 to 18, 20, 21, 25 to 27, 29.
- **Greedy:** a locally best choice that provably stays optimal. Days 9, 11, 22.
# 30_days_of_coding
