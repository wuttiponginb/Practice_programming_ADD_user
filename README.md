def say_hello(name):
    print("Hello " + name)

print("""---Add user---""")
customer_list = []
round = int(input())
for i in range(round):
    customer_list.append(input("name of user" + str(i) + ":"))
print(customer_list)
for data in customer_list:
    say_hello(data)
