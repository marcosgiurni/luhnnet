# LuhnNet

![.NET Core](https://github.com/marcosgiurni/LuhnNet/workflows/.NET%20Core/badge.svg?branch=master)

## Usage
### Check if a number is valid
```c#
  var isValid = Luhn.IsValid("5555666677778884");
```

### Calculate the check digit
```c#
  var checkDigit = Luhn.CalculateCheckDigit("555566667777888");
```
