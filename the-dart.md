<h1 style="padding-top:150px" class="text-center">The Dartlang</h1>
<p class="text-center"><strong>Andy Ai</strong></p>

---

# Dart: A structured web programming language

- Object oriented
- For better performance
- Class-based single inheritance
- Interfaces with default implementation
- Optional static types
- Generics
- Real lexical scoping
- Single-threaded
- Modular

---

# Run in all modrn browsers

![](https://raw.githubusercontent.com/aiyanbo/dart-training/master/images/temp-code-example.png)

---

# Dart execution

![](https://raw.githubusercontent.com/aiyanbo/dart-training/master/images/dart-execution.png)

---

# Variables

```dart

var x = 10;

final name = 'Andy';

const PI = 3.1415976;
```

---

# Static types

- Numbers
  - num
  - int
  - double
- Strings
  - String
- Booleans
  - bool

---

# Collections

- List

```dart
var names = new List<String>();
names.addAll(['Andy', 'Bob']);
```

- Set
```dart
Set<String> topic = new Set<String>();
topic.addAll(['News', 'Techs']);
topic.remove('Techs');
```

- Map
```dart
var map = {'key' : 'Value'};
assert(map['key'] == 'One')
```

---

# Function

```dart
printNumber(num number) => print(number);

String name({bool enabledFullName: false}) {
	if(enabledFullName) {
		return 'Andy Ai';
	}
	return 'Andy';
}
```

---

# main() function

- Web app

```dart
import 'dart:html'

void main(){
	querySelector('#div').innerHTML = 'Hello, Dart';
}
```

- Server

```dart
void main(List<String> args){
	print(args);
}
```

---

# Class

```dart
Class Person{
	String name;
	int age;

	Person({String name, int age: 18} {
		this.name = name;
		this.age = age;
	}
}

var person = new Person('Andy');

assert(person.age == 18)
```

---

# Demo

[AiShell](https://github.com/aiyanbo/aishell)

- Testing
- Debug

---

# Articles

- [Dart Style Guide](https://www.dartlang.org/articles/style-guide/)
- [Html & Css Style Guide](http://codeguide.bootcss.com/)

---

<h1 style="padding-top:150px" class="text-center">Thanks</h1>

<div class="text-center">
  <img style="width:400px; height:400px" src="http://api.qrserver.com/v1/create-qr-code/?color=000000&amp;bgcolor=FFFFFF&amp;data=http%3A%2F%2Fweibo.com%2Faiyboo&amp;qzone=1&amp;margin=0&amp;size=400x400&amp;ecc=L" alt="qr code" />
<div>