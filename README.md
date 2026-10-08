# README
A place where I experiment.

def weekday_order(weekday: str) -> int:
    if weekday == "Monday":
        return 0
    if weekday == "Tuesday":
        return 1
    if weekday == "Wednesday":
        return 2
    if weekday == "Thursday":
        return 3
    if weekday == "Friday":
        return 4
    if weekday == "Saturday":
        return 5
    if weekday == "Sunday":
        return 6

def sort_weekdays(weekdays: list) -> list:
    sorted_weekdays = sorted(weekdays, key=weekday_order)
    return sorted_weekdays

sort_weekdays(["Monday"]) # ["Monday"]
sort_weekdays(["Saturday", "Wednesday"]) # ["Wednesday", "Saturday"]

