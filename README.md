# persian
Some utilities for persian language in go

## Installation
```
go get github.com/mavihq/persian
```

## API
### .ToPersianDigits()
Converts all English digits in the string to Persian digits
```
persian.ToPersianDigits("123salam456")
=> "۱۲۳salam۴۵۶"
```

### .ToEnglishDigits()
Converts all Persian digits in the string to English digits
```
persian.ToEnglishDigits("۱۲۳salam۴۵۶")
=> "123salam456"
```