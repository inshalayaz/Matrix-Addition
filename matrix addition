no_col = 3
no_row = 2


def create_matrix(no_col,no_row):
    Matrix = []
    r=0
    while(r < no_row):
        Row = []
        c = 0
        while(c < no_col):
            a = float(input("Enter Value For matrix: "))
            Row.append(a)
            c+=1
        Matrix.append(Row)
        r +=1
    return Matrix

matrix_A = create_matrix(no_col,no_row)
matrix_B = create_matrix(3,2)



ans = []
r=0
while(r < no_row):
    Row = []
    c = 0
    while(c < no_col):
        a = matrix_A[r][c] + matrix_B[r][c]
        Row.append(a)
        c+=1
    ans.append(Row)
    r +=1
print(ans)
