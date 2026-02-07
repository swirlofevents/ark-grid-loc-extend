# Ark Grid Calculator

A lightweight web tool to optimize Ark Passive Core gem layouts using your inventory.


## How It Works

The calculator simulates all valid gem combinations for 3 cores, based on:

- Your available gems (Class / General astrogem inventory)
- Core rarity (Legendary / Relic / Ancient)
- Willpower limits per core
- Target point goals (Auto or Manual)

It then selects the best possible combination by:

- Prioritizing reaching target points
- Minimizing wasted points (over-target)
- Maximizing total points
- Using the least willpower when ties occur


## How to Use

### 1. Enter Your Ark Grid Page
- Fill in the quantity of each gem you own.
- Class and General astrogems are calculated separately.

### 2. Configure Cores
- Choose **Legendary / Relic / Ancient** for each core.
- **Auto Target (recommended):**
  - Legendary → 14 pts  
  - Relic / Ancient → 17 pts
- Or disable Auto Target and set targets manually.

### 3. Calculate
- Click **Calculate** to optimize one side.
- Or **Calculate Both** to optimize Class and General at the same time.

### 4. Read Results
For each core you will see:
- Used astrogems
- Willpower used
- Points vs target
- Progress bar
- Remaining unused astrogems

### 5. Add / Craft Suggestion (Reach All Targets)
If your current inventory **cannot fully reach all target points**, the calculator will show an additional section:

**Add / Craft Suggestion (reach all targets)**

This feature:
- Automatically checks what happens if you **add or craft extra gems**
- Finds the **minimum number of additional gems** needed
- Suggests a gem type (or types) that guarantee **all cores reach their targets**
- Searches up to **8 extra gems** using a minimal-add strategy

The suggestion represents:
- The **worst-case safe option**
- Adding the shown gem(s) will ensure all targets are reached, even if other options might also work

Example:
- `A × 1` means crafting or adding **one A-tier gem** is sufficient to reach all targets.


## Notes
- Results always respect your inventory limits.
- If inventory is insufficient, the calculator shows the best achievable result below the target.
- Manual targets affect priority order between cores.
- Add / Craft suggestions do **not** modify your inventory — they are informational only.
- The site may continue to receive updates and improvements over time.


## Credits
Original template and inspiration by **u/skyhawkx3 (Reddit & GitHub)** and **u/azizcanv/ (Reddit & GitHub)**.
