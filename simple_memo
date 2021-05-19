# 간단한 메모장 만들기
'''
필요한 기능은?
메모 추가하기, 메모 조회하기
입력 받는 값은?
메모 내용, 프로그램 실행 옵션
출력하는 값은?
memo.txt
'''

import sys

option = sys.argv[1]

if option == '-a':
    memo = sys.argv[2]
    f = open('memo.txt','a')
    f.write(memo)
    f.write('\n')
    f.close()
elif option == '-v':
    f = open('memo.txt')
    memo = f.read()
    f.close()
    print(memo)
