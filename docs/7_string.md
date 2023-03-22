## String
* String is a text data type.
* To create a String, we can use single quotes or double quotes, then inside it contains the text value.
* Although String can use double quotes, it is recommended to use single quotes only


### ```string```
#### example code
```dart
String firstName = 'Faiz';

String lastName = "Hidayatulloh";

print(firstName);
print(lastName);
```

## String Interpolation
* Strings support expressions, where inside the expression we can retrieve data from other variables.
* To create an expression, we can use the ```${contentExpression}``` format, if it is simple we can directly use $contentExpression

#### example code
```dart
void main() {
  String firstName = 'Faiz';

  String lastName = "Hidayatulloh";

  var fullName = '$firstName ${lastName}';
  print(fullName);
}
```