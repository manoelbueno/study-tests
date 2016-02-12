def binary_search(n, my_list=[]):

    while True:

        middle_list = len(my_list) / 2

        if n == my_list[middle_list]:
          return True
        elif n < my_list[middle_list]:
            my_list = my_list[:middle_list]
        elif n > my_list[middle_list]:
            my_list = my_list[middle_list:]
        if len(my_list) == 1:
            return False

l = [-5, 0, 1, 4, 6, 7, 10, 12]
print binary_search(8, l)
print binary_search(-10, l)
print binary_search(12, l)
print binary_search(0, l)
