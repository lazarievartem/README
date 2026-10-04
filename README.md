# README
A place where I experiment.

import random

def generate_random_list(min_value: int, max_value: int, length: int) -> list:
    final_list = []
    for i in range(length):
        number = random.randint(min_value, max_value)
        final_list.append(number)
    print(final_list)
    return final_list

