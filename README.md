## Python-convert-string-into-a-datetime-object
## Sample code to check the string 
```sh
date_string = "Feb 25 2020  4:20PM"
datetime_object = datetime.strptime(date_string, '%b %d %Y %I:%M%p')
```
## Expected output
2020-02-25 16:20:00
