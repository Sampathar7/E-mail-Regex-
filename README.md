num=input()
import re
pattern=re.compile("[a-z]{4,}@[a-z]{4,}[.][a-z]{2,}")
print(pattern.findall(num))
