# gugudan


# 구구단 1단부터 9단까지 출력
for x in range(1, 10):  # 1단부터 9단까지
    for y in range(1, 10):  # 각 단에 대한 곱셈
        print(f"{x} x {y} = {x*y}")
    print("")  # 단마다 한 줄씩 띄어서 출력

--------------------------------
gugudan = lambda n: [print(f"{n} x {i} = {n*i}") for i in range(1, 10)]

# 구구단 2단부터 9단까지 출력
for n in range(2, 10):
    gugudan(n)
    print('')  # 단마다 빈 줄을 출력하여 구분
