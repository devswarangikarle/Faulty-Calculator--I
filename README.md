# Faulty-Calculator--I

def faulty_calculator(A, B):
    result = A + B
    result_with_3 = int(str(result) + '3')
    return result_with_3

# Input
A, B = map(int, input().split())

# Output
print(faulty_calculator(A, B))
