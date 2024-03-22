# gugudan


# 구구단 1단부터 9단까지 출력
for i in range(1, 10):  # 1단부터 9단까지
    for j in range(1, 10):  # 각 단에 대한 곱셈
        print(f"{i} x {j} = {i*j}")
    print("")  # 단마다 한 줄씩 띄어서 출력
