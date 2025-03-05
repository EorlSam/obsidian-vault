* **Abstract class** defines methods but doesn't implement them
* A class with at least one unimplemented method must be declared abstract `abstract class myClass()`

* Unlike Java, where you overwrite a method by typing `@Override`, in Scala you declare it before the function: `override def toString`
* You can also override attributes
* If you don't want a method/attribute/class to be overwritten you must declare it `final`

* Super-class constructors can be called with `extends` (like in C#)

### Operators
- Lists:
	- `::` joins an element to the beggining of a list `val listaConPrepend = 0 :: lista`
	- `:+` joins an element to the end of the list
	- `++` joins 2 lists