#-*- coding:utf-8 -*-
def iteration(number):
    a= 0
    while number != 1:
        if number % 2 == 0:
            number = number / 2
            a = a +1
            print a,':',number
        else:
            number = number * 3 + 1
            a = a + 1
            print a,':' , number
    return number

input_number = int(input())
iteration(input_number)
