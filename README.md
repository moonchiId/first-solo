# first-solo

def collect_data(number_of_digits):
    list = []
    for i in range(number_of_digits):
        list.append(int(input("Type a number: ")))
    return list

how_many = int(input("Enter number of digits your list should have:"))
print(collect_data(how_many))
