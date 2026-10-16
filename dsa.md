# 📘 Time vs Space Complexity — Quick Reference

| Code Element | ⏱️ Consider for Time? | 💾 Consider for Space? |
|:---|:---|:---|
| Primitive variables (`int`, `double`, `boolean`) | Yes, when operations execute | Yes, but each uses constant space |
| Variable assignments | Yes | Usually no additional space per assignment |
| `if` / `else` conditions | Yes | No additional space by themselves |
| `for` loops | Yes | Not automatically |
| `while` loops | Yes | Not automatically |
| Increment operations (`i++`) | Yes | No additional space per increment |
| Arrays | Yes, when accessing or processing them | Yes, based on their size |
| ArrayLists and other collections | Yes, when operating on them | Yes, based on their size |
| Objects created with `new` | Yes, creation takes time | Yes, memory is allocated |
| Recursion | Yes, across recursive calls | Yes, for the call stack |
| Nested loops | Usually, yes | Not automatically |
| Input size (`n`, `p`) | Helps determine the growth rate | Matters when it determines allocated memory |

---

## 💡 Remember

- **Time complexity:** Analyse how the number of operations grows with input size.
- **Space complexity:** Analyse how additional memory usage grows with input size.
- **Loops affect time, but do not automatically increase space.**
- **Arrays and collections:** Consider how much data they store.
- **Recursion:** Account for the memory used by active function calls.
