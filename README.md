# Algorithm
알고리즘 팀노트

## 2차원 리스트 90도 회전
```python
def rotate_matrix_90(matrix):
  row = len(matrix)
  col = len(matrix[0])
  result = [[0]*row for _ in range(col)]
  for i in range(row):
    for j in range(col):
      result[j][row-i-1] = a[i][j]
  return result
```
