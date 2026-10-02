# README
A place where I experiment.

def get_century(year: int) -> int:
    if year == 0:
        year = 1
    if year > 0:
        return((year + 99) // 100)
    return get_century

