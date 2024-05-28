# A function that finds the HCF
def compute_hcf(x, y):
    if x > y:
        smaller = y
    else:
        smaller = x
    for i in range(1, smaller + 1):
        if x % i == 0 and y % i == 0:
            hcf = i
    return hcf


# Example run
n1 = 81
n2 = 36
print(f"The H.C.F. between {n1} and {n2} is {compute_hcf(81, 36)}")
