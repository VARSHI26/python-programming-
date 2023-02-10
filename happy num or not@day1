n=int(input("enter a number"))
def is_Happy_num(n):
  past = set()
  while n != 1:
        n = sum(int(i)**2 for i in str(n))
        if n in past:
            print("number is not happy")
            return 0
        past.add(n)
  print("number is happy")
  return 0

print(is_Happy_num(n))
