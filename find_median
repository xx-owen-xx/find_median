# Owen Fissel
# ENG 103
# 5A
# Find the median


def find_median(numbers):
    """
    returns the median of a list of numbers
    """

    if not numbers:
        raise ValueError('Cant find median')
    sorted_numbers = sorted(numbers)
    n = len(sorted_numbers)
    
    if n % 2 == 1:
        return sorted_numbers[n // 2]
    else:
        mid1 = sorted_numbers[n //2 - 1]
        mid2 = sorted_numbers[n // 2]
        return (mid1 + mid2) / 2
    
