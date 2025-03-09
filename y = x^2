# 손실 함수: y = x^2 (최소값을 찾아야 할 함수)
def loss_function(x):
    return x**2

# 손실 함수의 미분 (기울기): y' = 2x
def gradient(x):
    return 2 * x

# 초기값 설정
x = 10  # 초기 값
learning_rate = 0.1  # 학습률
iterations = 100  # 반복 횟수

# 경사 하강법 실행
for i in range(iterations):
    grad = gradient(x)  # 기울기 계산
    x = x - learning_rate * grad  # 경사 하강법으로 x 업데이트
    print(f"Iteration {i+1}: x = {x}, Loss = {loss_function(x)}")

print(f"최소값을 찾은 x: {x}, Loss: {loss_function(x)}")
