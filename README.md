---
```python
class say_hello:

    def __init__(self, text) -> None:
        self.text = text

    def __str__(self) -> str:
        return self.text

    def __repr__(self) -> str:
        return self.__str__()

if __name__ == "__main__":
    print(say_hello("Hello there 👋, I'm Zek Wazaowsky, Nice to meet you all!"))
```
