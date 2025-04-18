# 👾Conway's Game of Life /// Google Sheets port

![image](https://github.com/user-attachments/assets/765cd2fe-c62e-4009-8382-aed6734158c5)

---
---
---

# 🕹Play /// Fork

### Open https://docs.google.com/spreadsheets/d/1d-GBZnzR8wV8ZAmCunNPO-PCWJZXAikKwakJuxtmlyU

- Sign in to your Google account
- File > Make a copy

## Control the whole game with 2 switches

- 🟨 RESET [B7] Check and uncheck to restart
- 🟩 RUN [B13] Click on it, and HOLD SPACEBAR until GAME OVER message

## Draw your pattern instead of the automatic random one with this 3rd switch below

- ☑️ SEED MODE [B85] You can copy your favorite or high-score seeds to the [Saved seeds] sheet

---
---
---

# 🎞️Video showing features

[<img src="https://github.com/user-attachments/assets/870dcf17-b9f4-4354-a3e2-2f575c1b41d8" width="100%">](https://youtu.be/Za2HlAjVzag)

## v1 published on 2024-02-04

2024-02-04 https://x.com/VincentBounce/status/1753906987287327084 \
2024-02-13 https://youtu.be/Za2HlAjVzag

---
---
---

# ⚖️Rules
	
## Goal

The goal is to keep your cells moving the longer you can until a repeating pattern appears.
The pattern cycle detection is limited to one of up to 16 periods. Don't use bigger oscillators.
The more new generations are created, the more your score is increased.
Alternative goal: obtaining the highest generations count until ALL cells DIE.
	
## Rules

Each new generation of cells on the grid is calculated from the previous one with 4 basic rules:
1. Any live cell with fewer than 2 neighbors dies, as if by underpopulation.
2. Any live cell with more than 3 live neighbors dies, as if by overpopulation.
3. Any live cell with 2 or 3 live neighbors lives on to the next generation.
4. Any dead cell with exactly 3 live neighbors becomes a live cell, as if by reproduction.
	
## Deterministic & unpredictable

- Deterministic: the same initial pattern always produces the same generations.
- Unpredictable: forecasting the 100th gen without computing each intermediate one is impossible.

- There are 2⁵⁷⁴ possible games, it's 10¹⁰⁰ times more than the atom quantity in the universe!
- No one can certify that the highest score has been reached.

<img width="726" src="https://github.com/user-attachments/assets/757f3fa1-f39e-45f3-86f3-220f7d847e98" />

---
---
---

# 🧬Seed mode

## 🎲Random seed

You can select the target density of the generated population.
Then scroll up, tick Reset 2 times and Run.

![image](https://github.com/user-attachments/assets/71925905-51a0-48e2-bd37-a9d87c680315)

## ✍️Custom seed

You can tick every cell, so you can draw the pattern you want.
Then scroll up, tick Reset 2 times and Run.

![image](https://github.com/user-attachments/assets/587f9b0c-2e43-4509-8529-fac170e52802)
