# strings
most_frequent(string):
d =dic()
for key in string:
  if key not in d:
      d[key] = 1
  else:
       d[key] += 1
 return d
 print most_frequent('aabbcc')
 
 
 returning
 {'a':2
 'c':1
 'b':3}
