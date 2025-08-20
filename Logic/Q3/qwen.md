We are given a logic puzzle about the finishing order of five people eating apples: A, B, C, D, and E.

We need to determine the **order** in which they finished, based on the following clues:

1. **A finished before B**, but  
2. **A finished behind C**.  
3. **D finished before E**, but  
4. **D finished behind B**.

Let’s break this down step by step.

---

### Step 1: Analyze the clues

#### Clue 1 & 2: A finished before B, but behind C.

So:
- C < A < B  
  (in terms of finishing time — "before" means earlier, so lower number if we think of order)

So the order is: **C came before A**, and **A came before B**

So:  
**C → A → B**

#### Clue 3 & 4: D finished before E, but behind B.

So:
- B < D < E  
  (B finished before D, D before E)

So:  
**B → D → E**

---

### Step 2: Combine the sequences

From above:
- C → A → B
- B → D → E

Now chain them together:

**C → A → B → D → E**

This satisfies all the conditions:

- A before B? ✅ (A → B)
- A behind C? ✅ (C → A)
- D before E? ✅ (D → E)
- D behind B? ✅ (B → D)

All five people are included, and the order is fully determined.

---

### ✅ Final Answer: The finishing order is  
**C, A, B, D, E**
