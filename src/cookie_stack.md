```python
class CookieStack(object):
    """ A stack of cookies."""
    def __init__(self):
        self.cookie_list = []

    def eat(self):
        """Eat a cookie!"""
        return self.cookie_list.pop()

    def bake(self, cookie):
        """Bake a cookie and add it to the stack"""
        return self.cookie_list.append(cookie)
```