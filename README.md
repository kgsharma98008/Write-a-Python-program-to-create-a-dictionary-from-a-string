# Write-a-Python-program-to-create-a-dictionary-from-a-string

string = 'w3resource'
d = {}
for char in string:
 if char in d:
 d[char] += 1
 else:
 d[char] = 1
print(d)
