# Arrays and Maps

## What is an Array?
An array stores elements in order and allows access by index.

- Strengths:
  - Fast access by index
  - Simple structure
- Weaknesses:
  - Searching can be slow
  - Insertions/removals can be costly

## What is a Map (Dictionary)?
A map stores key–value pairs.

- Strengths:
  - Fast lookup by key
  - Useful for counting and grouping
- Weaknesses:
  - No guaranteed order (conceptually)
  - Slightly more memory usage

## When to Use Each
- Use an array when order matters or index access is needed.
- Use a map when fast lookup by key is required.

## Practice Problem
Given a list of artist disciplines, count how many times each discipline appears.

Example input:
["musician", "actor", "musician", "dancer", "actor"]

Example output:
musician: 2  
actor: 2  
dancer: 1

## Solution (Python)
arts = ["Musician, "Actor","Musician","Dancer","Actor]
counts = {}

for art in arts:
  if art in counts:
    counts[art] += 1
  else:
    counts[art] = 1
for art, count in counts.items():
  print(f"{art}: {count}")

- This solution works better than counters per variable due to its scalability (if new disciplines are added, there is no need to rewrite the code) and 
maintainability (its short and easy to debug)
  

## Time Complexity
The algorithm iterates through the list once. Each dictionary operation is constant time, so the overall time complexity is O(n).
