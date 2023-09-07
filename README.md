def fibonacci(n):
    fib_seq = [0, 1]
    for i in range(2, n):
        next_num = fib_seq[i - 1] + fib_seq[i - 2]
        fib_seq.append(next_num)
    return fib_seq

numero_termos = 10
sequencia = fibonacci(numero_termos)
print(f'Sequência de Fibonacci com {numero_termos} termos: {sequencia}')
