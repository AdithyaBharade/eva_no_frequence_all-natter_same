from collections import Counter
def min_magicstring(s):
    frequency=Counter(s)
    max_freq=max(frequency.values())
    min_step=len(s)-max_freq
    return min_step
s='aaabbbccccccddddddd'
print(min_magicstring(s))
