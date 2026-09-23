# README
A place where I experiment.

def disemvowel_trolls(sentence: str) -> str:
    vowels = "aeiouAEIOU"
    result = ""
    for letter in sentence:
        if letter not in vowels:
            result += letter
    return result


disemvowel_trolls("Delete all vowels!") == "Dlt ll vwls!"
disemvowel_trolls("QWERTY") == "QWRTY"
