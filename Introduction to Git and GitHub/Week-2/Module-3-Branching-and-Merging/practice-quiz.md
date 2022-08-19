# Practice Quiz: Branching & Merging

__To pass__ 80% or Higher

__Total points__ 5

1. When we merge two branches, one of two algorithms is used. If the branches have diverged, which algorithm is used? _(point 1)_
- [x] three-way merge
- [ ] fast-forward merge
- [ ] merge conflict
- [ ] orphan-creating merge

2. The following code snippet represents the result of a merge conflict. Edit the code to fix the conflict and keep the version represented by the current branch. _(point 1)_

```python
<<<<<<< HEAD                    # delete 
print("Keep me!")
=======                         # delete
print("No, keep me instead!")   # delete
>>>>>>> brancho-cucamonga       # delete
```

3. What command would we use to throw away a merge, and start over? _(point 1)_
- [ ] git checkout -b <branch>
- [x] git merge --abort
- [ ] git log --graph --oneline
- [ ] git branch -D <name>

4. How do we display a summarized view of the commit history for a repo, showing one line per commit? _(point 1)_
- [ ] git log --format=short 
- [ ] git branch -D <name>
- [x] git log --graph --oneline 
- [ ] git checkout -b <branch>

5. The following script contains the result of a merge conflict. Edit the code to fix the conflict, so that both versions are included. _(point 1)_

```python
def main():
<<<<<<< HEAD                                # delete
    print("Start of program>>>>>>>")
=======                                     # delete
    print("End of program!")
>>>>>>> improvement-to-the-code             # delete

main()
```