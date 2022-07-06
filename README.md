#수박수박수박수박수박수?

def solution(n):
    answer = ''
    if n == 1:
        return '수'
    elif n % 2 == 0:
        answer = '수박' * (n // 2)
    else:
        answer = '수박' * (n // 2) + '수'

    return answer

#print(solution(3))
#ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

def water_melon(n):
    s = "수박" * n
    return s[:n]
