# program-to-predict-future-AADT-volume-in-a-township-for-a-relationship-Use-python-math-module.

#program to predict future AADT volume in a township, for a relationship:
#Future AADT = (preasent AADT)growthfactor . Given, present traffic 1100 AADT,
#and growth factor 1.08. Use python math module. (hints: use math.pow(x,y) method)

import math

def calculation(present_AADT, growth_factor):
    AADT = math.pow(present_AADT, growth_factor)
    return AADT

output = calculation(present_AADT = 1100, growth_factor = 1.08)
output = round(output)

print("Future AADT of the township  = ", output)
