## Code

```python
def convertToUpper(string1):

	convertedString = string1.upper()

	return convertedString

def addTwoInteger(int1,int2):

	return int1+int2
```

## Unit Test
```python
import unittest

import codetest


class TestMethods(unittest.TestCase):

	def test_convertToUpper(self):
		self.assertEqual("TEST",codetest.convertToUpper("test"))
		self.assertNotEqual("abTEST",codetest.convertToUpper("abtest"))

	def test_addTwoInteger(self):
		self.assertEqual(11,codetest.addTwoInteger(10,1))
		self.assertNotEqual(10,codetest.addTwoInteger(10,4))

if __name__ == "__main__":

unittest.main()

```