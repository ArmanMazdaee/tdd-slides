## آزمودن invention

```
class TestInventor(unittest.TestCase):

   def test_invention(self):
       expected_invation = 'TDD'
       kent = inventor.Inventor(expected_invation)
       current_invation = kent.invention
       self.assertEqual(expected_invation, current_invation)
```

```
.E
======================================================================
ERROR: test_invention (__main__.TestInventor)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "inventor_test.py", line 12, in test_invention
    current_invation = kent.invention
AttributeError: Inventor instance has no attribute 'invention'

----------------------------------------------------------------------
Ran 2 tests in 0.000s

FAILED (errors=1)
```
