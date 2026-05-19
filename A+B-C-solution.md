# A + B - C

Nguồn PDF: `A + B - C - 300bàicode.vn - 300 Bài code thiếu nhi - Quyển bí kíp mà nhiều cao thủ có cơ duyên luyện qua!.pdf`

## Đề bài

Cho ba số nguyên `a`, `b`, `c`, hãy tính `a + b - c` và in kết quả ra màn hình.

## Input

- Dòng một: Một số nguyên `a`.
- Dòng hai: Hai số nguyên `b` và `c`, cách nhau bởi một dấu cách.

Với:

```text
-10 <= a, b, c <= 10
```

## Output

Một số nguyên duy nhất là kết quả của `a + b - c`.

## Ví dụ

### Input 1

```text
5
3 2
```

### Output 1

```text
6
```

### Input 2

```text
-2
4 -1
```

### Output 2

```text
3
```

## Giới hạn

- Giới hạn thời gian: 2.0s
- Giới hạn bộ nhớ: 64M

## Link trong PDF

```text
https://300baicode.vn/problem/0000
```

## Solution

### Ý tưởng

Đọc ba số nguyên `a`, `b`, `c`, sau đó tính trực tiếp biểu thức:

```text
a + b - c
```

Do chỉ có một phép tính đơn giản, độ phức tạp là `O(1)`.

### Code Python

```python
a = int(input())
b, c = map(int, input().split())

print(a + b - c)
```
