# python

print("Do you have milk?")
a = input()
if a == "yes":
	a = True
else:
	a = False
print("Do you have cookies?")
b = input()
if b == "yes":
	b = True
else:
	b = False
print("Will you drink tea?")
c = a or b
if c == True:
	print("I will drink tea")
else:
	print("No, thanks.")
