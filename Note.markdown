# SideNote

`flutter run -d chrome` // -d -> device

## Mindset

- flutter is widget inside widget
- widget use capital, augment use smaller case

## Types

```Demo
String name = 'XXX';
int number = 123;
double number2 = 123;
List myList = [1, 2, 3, 4];
Map<String, dynamic> myMap = {'key': value, 'string': 'Any Types'};
```

## Mouse over

`debugShowCheckedModeBanner: false,`

## Basic Layout

### Container

    height: double.infinity,
    width: double.infinity,
    padding: EdgeInsets.all(50.0),
    decoration: BoxDecoration(
      borderRadius: BorderRadius.circular(25.0),
      color: Colors.orange,
    ), 

`mainAxisAlignment: MainAxisAlignment.center,`
`crossAxisAlignment: CrossAxisAlignment.end,`

### Expanded

    Expanded(
      child: Container(
        ...
      ),
    ),

// Expanded 告訴 Column：這個子 widget（Container）應該填滿所有剩餘的垂直空間。
// 如果沒有 Expanded，那個 Container 只會佔據其內容所需的空間，不會自動拉伸。

