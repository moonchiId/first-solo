# first-solo

def collect_data(number_of_digits):
    list = []
    for i in range(number_of_digits):
        list.append(int(input("Type a number: ")))
    return list

def even(number):
    if number%2 == 0:
        return "True"
    else:
        return "False"

how_many = int(input("Enter number of digits your list should have:"))
print(collect_data(how_many))
list = collect_data(how_many)
for i in list:
    print(even(i))
