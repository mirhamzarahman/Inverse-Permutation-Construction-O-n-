# Presents — Inverse Permutation Construction

## 📌 Problem

Each friend gives exactly one present to another friend.

Given the recipient of every friend's gift, determine who gave a gift to each friend.

## 💡 Approach

The input represents a permutation.

For every friend `i`:

- If friend `i` gives a gift to friend `p[i]`,
- Then the answer for friend `p[i]` is `i`.

This directly constructs the inverse permutation.

## ✅ Complexity

- **Time:** O(n)
- **Space:** O(n)

## 📖 Concepts Used

- Arrays
- Permutations
- Inverse Mapping
- Simulation

## 🚀 Key Idea

Instead of searching for every recipient, directly place each giver into the recipient's position, producing the inverse permutation in a single pass.
