# iliyasq
my first project
from numpy import *
mat1 = random.randint(0, 10, (3, 4))
print(mat1)
t1 = shape(mat1)


def f(matrix):
    mat2 = ones((t1[1], t1[0]), dtype=int)

    for i in range(len(matrix)):
        for j in range(len(matrix)):
            mat2[i][j] = matrix[j][i]

    return mat2


print(f(mat1))
