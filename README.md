HOMEWORK 1 Q 1

a = 100
b = 80
c = 10
d = 50
costa = 36.57
costb = 64.09
costc = 3.81
costd = 14.36
quarters = 0.25
dimes = 0.10
nickels = 0.5
pennies = 0.1
onebill = 1
fivebill = 5
tenbill = 10
twentybill = 20
fiftybill = 50 
onehundredbill = 100

changea = a-costa
changeb = b-costb
changec = c-costc
changed = d-costd


print ('change for a is', changea)
print ('change for b is', changeb)
print ('change for c is', changec)
print ('change for d is', changed)

x = (changea - fiftybill) 
print (x)
x2 = (x - tenbill)
print (x2)
x3 = (x2 - onebill * 3)
print (x3)
x4 = (x3 - quarters)
print (x4)
x5 = (x4 - dimes)
print (x5)

print ('we have all the change we need if x5 = 0.', x5)

y = (changeb - tenbill)
print (y)
y2 = (y - fivebill)
print (y2)
y3 = (y2 - quarters * 3)
print (y3)
y4 = (y3 - dimes)
print (y4)


print ('we have all of the change we need if y4 = 0.', y4)

z = (changec - fivebill)
print (z)
z2 = (z - onebill)
print (z2)
z3 = (z2 - dimes)
print (z3)

print ('we have all the change we need if z3 = 0.', z3)

m = (changed - twentybill)
print (m)
m2 = (m - tenbill)
print (m2)
m3 = (m2 - fivebill)
print (m3)
m4 = (m3 - quarters * 2)
print (m4)
m5 = (m4 - dimes)
print (m5)

print ('we have all the change we need if m5 = 0.', m5)

print ('yay we are done!')


HOMEWORK 1 Q 2
F = 98.6
K = 329.7
C = -60.9

C1 = 5/9*(F-32)
print ('The conversion is', C1)
F1 = 9/5*(K-273) + 32 
print ('The conversion is', F1)
K1 = C + 273
print ('The conversion is', K1)
