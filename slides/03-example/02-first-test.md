## اولین آزمایش

```
class TestInventor(unittest.TestCase):
   def test_init(self):
       kent = inventor.Inventor('TDD')
```

```
E
======================================================================
ERROR: test_init (__main__.TestInventor)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "inventor_test.py", line 7, in test_init
    kent = inventor.Inventor('TDD')
AttributeError: 'module' object has no attribute 'Inventor'

----------------------------------------------------------------------
Ran 1 test in 0.000s

FAILED (errors=1)
```
