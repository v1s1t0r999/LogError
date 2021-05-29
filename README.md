# LogError
Github repo for my `LogError` Package on PyPi. 

### Installation
```pip install LogError```
---
### Usage
```python
import LogError

try:
    # [Some codes that may or may not give errors]

except Exception as Any_Variable:
    LogError.handle(file="FileName.log", error=Any_Variable)
```

