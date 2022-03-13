### Where

1. Create a function that returns a `List` of `int`:

```dart
void main() {

}

List<int> filterVisitors(){

}
```

2. Our functions takes two arguments, one of type `List` of `int` and one of type `int`:

```dart
void main() {

}

List<int> filterVisitors(List<int> visitors,int age){

}
```

3. To filter a `List`, we use the `where` method, that takes an arrow function:

```dart
void main() {

}

List<int> filterVisitors(List<int> visitors,int age){
    visitors.where((visitor)=>);
}
```

4. Our condition is that the `visitor` age is more that the provided `age`:

```dart
void main() {

}

List<int> filterVisitors(List<int> visitors,int age){
    visitors.where((visitor)=>visitor>age);
}
```

5. Return the result and remember to convert it from an iterable to a list again:

```dart
void main() {

}

List<int> filterVisitors(List<int> visitors,int age){
    return visitors.where((visitor)=>visitor>age).toList();
}
```

### FirstWhere

1. Create a function names `odd` that returns an `int`:

```dart
void main() {

}

int odd(){

}
```

2. Our function takes a `List` of `int` argument:

```dart
void main() {

}

int odd(List<int> numbers){

}
```

3. To find something in a `List` we use the `firstWhere` function that takes an arrow function:

```dart
void main() {

}

int odd(List<int> numbers){
    numbers.firstWhere((number)=>);
}
```

4. To find if a number is `odd`, we we'll use the `modulo` operator:

```dart
void main() {

}

int odd(List<int> numbers){
    numbers.firstWhere((number)=>number % 2 != 0);
}
```

5. Return the result:

```dart
void main() {

}

int odd(List<int> numbers){
    return numbers.firstWhere((number)=>number % 2 != 0);
}
```
