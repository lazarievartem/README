# README
A place where I experiment.

def fix_string_case(word: str) -> str:
    low = 0
    upp = 0
    for i in range(len(word)):
        if word[i].islower():
            low += 1
        elif word[i].isupper():
            upp += 1
    if low >= upp:
        return word.lower()
    else:
        return word.upper()
