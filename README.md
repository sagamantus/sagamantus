```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Student:

    def __init__(self):
        self.name = "Sagar Mankoti"
        self.role = "Student"
        self.language_spoken = ["en_IN", "hi_IN"]

    def say_hi(self):
        print("Hey! Thanks for dropping by, hope you find some of my work interesting.")


me = Student()
me.say_hi()
```
