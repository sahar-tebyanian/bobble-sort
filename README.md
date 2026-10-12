# bobble-sort
data = [23, 3, 2, 5, 14, 63, 89]

for i in range(len(data)):
    for j in range(0, len(data) - i - 1):
        if data[j] > data[j + 1\]:
            data[j], data[j + 1] = data[j + 1], data[j]

print("Sorted array:", data) 
