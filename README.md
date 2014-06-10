(Unofficial) Python API for HaveIBeenPwned Website.

This code has been developed to check compromised mails and is really easy to use: 

```python
from haveibeenpwnedAPI import haveibeenpwnedAPI
res = haveibeenpwnedAPI().is_compromised('test@test.com')
print res  # True

res = haveibeenpwnedAPI().is_compromised('test@myprivatecompany.com')
print res  # False
```