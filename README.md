# README
A place where I experiment.

def get_order(order: str) -> str:
    menu = [
        "burger",
        "fries",
        "chicken",
        "pizza",
        "sandwich",
        "onionrings",
        "milkshake",
        "coke"
    ]
    result = []
    for i in menu:
        count = order.count(i)
        for _ in range(count):
            result.append(i.capitalize())
    return " ".join(result).

