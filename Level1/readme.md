# 10진수 => n진수
```
def solution(nums,n):
    answer = ''
    while nums > 0:
        nums,r = divmod(nums,n)
        answer += str(r)
        
    return answer[::-1]
```
# n진수 => 10진수
```
int('n진수 값',n)
```

# rjust, ljust
```
'문자열'.rjust(n,'#')
``` 
