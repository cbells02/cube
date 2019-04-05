# cube
# a cubing function

ex = int(input("give me a number"))
xe = int(input("give me another number"))


def cube(num, nums):
    return num**nums


print(cube(ex, xe))


def super_cube(exp, exps):
    return exp**exps**exp


print(super_cube(ex, xe))
