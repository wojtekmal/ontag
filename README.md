# ONTAG

ONTAG is a library for creating olympic math problems from the fields of algebra and number theory.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ontag.

```bash
pip install ontag
```

## Usage

```python
import ontag.boolEval

# returns 'True'
ontag.boolEval.boolEval("forAll(a, 'integer', \"a * a >= 0\")")

# return 'False'
ontag.boolEval.boolEval("forAll(a, 'integer', \"a * a > 0\")")

# chlopacy
```
## License
[MIT](https://choosealicense.com/licenses/mit/)
