# Filtering by Discipline

## Problem
Given a list of artist profiles, return only artists that match a selected discipline.

## Example Input
artists = [
  {"name": "Ana", "discipline": "Musician"},
  {"name": "Leo", "discipline": "Actor"},
  {"name": "Maya", "discipline": "Musician"}
]

Selected discipline:
"Musician"

## Expected Output
[
  {"name": "Ana", "discipline": "Musician"},
  {"name": "Maya", "discipline": "Musician"}
]

## Solution (Python)
profiles = [
  {"name": "Ana", "discipline": "Musician"},
  {"name":"Leo", "discipline": "Actor"},
  {"name": "Maya", "discipline": "Musician"}
  ]
selected_filter = input("search for a discipline...")

filtered_profiles = []

for profile in profiles:
  if profile["discipline"] == selected_filter:
    filtered_profiles.append(profile)

## Time Complexity
The algorithm is iterating through the list of profiles once and performs a constant time comparison for each profile.
Time complexity is O(n)
