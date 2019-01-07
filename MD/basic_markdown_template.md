# Title

## Intro
> General info

## Chapter 1
> _**Lorem**_ `ipsum dolor` _sit_ **amet**, consectetur adipiscing elit. Fusce fermentum suscipit eros, eget bibendum augue. Ut viverra nec ex a dictum. Pellentesque pharetra erat eget luctus congue. Donec commodo quam sapien, ac sollicitudin augue ullamcorper a. Sed et mollis ligula, nec aliquam ipsum. Nunc blandit vulputate purus in tempus. Sed egestas volutpat nulla, iaculis vulputate ipsum malesuada vel. 

## Chapter 2
> _**Lorem**_ `ipsum dolor` _sit_ **amet**, consectetur adipiscing elit. Fusce fermentum suscipit eros, eget bibendum augue. Ut viverra nec ex a dictum. Pellentesque pharetra erat eget luctus congue. Donec commodo quam sapien, ac sollicitudin augue ullamcorper a. Sed et mollis ligula, nec aliquam ipsum. Nunc blandit vulputate purus in tempus. Sed egestas volutpat nulla, iaculis vulputate ipsum malesuada vel.

## Code snippets

```SQL
SELECT DISTINCT COUNT(ProductCollection.Product_ID) AS 'Unique figures'
FROM ProductCollection
WHERE Collection_ID = (SELECT Id FROM UserCollection WHERE CollectionName = 'TestCollection')
```

```Csharp
// an example class
Class Example {
    private static Example _Instance = new Example(123, "string");
    private int _SomeVar;
    private string _AnotherVar;

    private Example(int SomeVar, string AnotherVar) {
        _SomeVar = SomeVar;
        _AnotherVar = AnotherVar;
    }

    public static Example Instance {
        get {
            return _Instance;
        }
    }

    public int GetSomeVar {
        get {
            return _SomeVar;
        }
    }
}
```

## Some really big table

## Table name

|   abc   | some criteria | something else
-----------------|----------|-----------|
**def**     | info | some other info
**ghi**     | info | some other info
**jkl**     | info | some other info
**mno**     | info | some other info
**pqr**	    | info | some other info
**stu**     | info | some other info
**vwx**     | info | some other info
**yz!**     | info | some other info