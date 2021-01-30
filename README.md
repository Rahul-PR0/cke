def max(*args):
    result=args[0]
    for i in args:
        if i>result:
            result=i
    return result
print(max(4,5,6,8,78,5,7))
