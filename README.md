# computational-thinking-
#  - Assignment P1

## Task 1: Identity Investigation

In this task, we used the id() function in Python to check the memory location of variables.

We observed that:
- For immutable data types like integers and strings, a new memory location is created when the value is changed.
- For mutable data types like lists, the memory location remains the same when we modify the list using methods like append().

This shows how Python handles memory differently for mutable and immutable objects.


## Task 2: Git Commit Immutability

In this task, we created multiple commits (Version 1 and Version 2).

We observed that:
- The new commit does not replace the old one.
- Both commits exist in the repository history.

This proves that Git uses an immutable storage model, where each commit is preserved and cannot be changed.


## Task 3: Nested List Copy

We created a nested list and copied it using:
update_data = list(data)

After modifying an inner element:
update_data[1][1] = 99

We observed that the original list also changed.

Reason:
- This is a shallow copy.
- Inner lists are shared between original and copied list.

This shows that changes in nested elements affect both lists.


## Task 4: Commit Hash Change

We created a commit and noted its hash using git log.

Then we modified the commit message using:
git commit --amend

After that, we observed that:
- The commit hash changed.

Reason:
- Git does not modify an existing commit.
- It creates a new commit with a new hash.

This proves that commits in Git are immutable.