# branch-main.py
def suma(a, b):
    return a + b

def resta(c, d):
    return a - b

def multiplicacion(a, b):
    return a * b
    
git checkout Devs
# dev
def suma(a, b)
    return a - b

def resta(a, b):
    return a - b

def multiplicacion(a, b):
    return a + b


git checkout QA
 # test_main.py

import unittest
from main import suma, resta, multiplicacion, division

class TestMathOperations(unittest.TestCase):
    def test_suma(self):
        self.assertEqual(suma(1, 2), 3)  # Esta prueba fallará en la rama Devs
        self.assertEqual(suma(3, 0), 3)

    def test_resta(self):
        self.assertEqual(resta(3, 2), 1)
        self.assertEqual(resta(1, 1), 0)





