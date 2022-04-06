# iliyasq
my first project
from numpy import *
mat1 = random.randint(0, 10, (3, 4))
print(mat1)
t1 = shape(mat1)


def tr(array):
    mat2 = ones((t1[1], t1[0]), dtype=int)

    for i in range(len(array)):
        for j in range(len(array)):
            mat2[i][j] = array[j][i]

    return mat2


print(tr(mat1))
