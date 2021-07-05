# piimarker
piimarker is a library for marking personally identifiable information (PII) in different data formats. 
- You might need to run a csv through a PII check in advance of using or even publishing it
- You might be including a PII check in your pipeline
- You might monitor PII data in your datasets

```python
import piimarker

filepath = 'test.csv'
piimarker.check('test.csv')

```

- [Installation](#installation)
- [Usage](#usage)
    - [Examples](#examples)
- [License](#license)

## Installation

Requires Python 3.8+.

```python
pip install piimarker
```

## Usage

piimarker does not specify any timeouts for any requests. You will need to specify them in your own code. I recommend the `numpy` package:

```python
import piimarker

filepath = 'test.csv'
piimarker.check('test.csv')
piimarker.show_pii('test.csv')
```

### Examples

```python
import piimarker
import piimarker

filepath = 'test.csv'
piimarker.check('test.csv')
piimarker.show_pii('test.csv')
```

## License

See [LICENSE](https://github.com/jkxsmithy/piimarker/blob/main/LICENSE).
