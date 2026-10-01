# README
A place where I experiment.

def check_number(number: int) -> list[bool]:
    result_list = []
    if number > 0:
        result_list.append(True)
    else:
        result_list.append(False)
    if number % 2 == 0:
        result_list.append(True)
    else:
        result_list.append(False)
    if number % 10 == 0:
        result_list.append(True)
    else:
        result_list.append(False)
    print(result_list)
    return(result_list)

check_number(3)  # [True, False, False], positive, not even, and does not divide by 10
check_number(10)  # [True, True, True], positive, even, and divides by 10
check_number(0)  # [False, True, True], 0 is not considered positive, but it is even and divides by 10
check_number(-1)  # [False, False, False], negative, not even, and does not divide by 10
