# Object-and-class
14.Object 

Object Oriented Programming is a programming style that is intended to make thinking about programming closer to thinking about the real world.

Attributes  -  characteristics of object
The following three dimensions describe any object in object oriented programming: identity, attributes, behavior.

15.Class

Objects are created using classes. The class describes what the object will be, but is separate from the object itself.
In other words, a class can be described as an object's blueprint, description, or definition.
You can use the same class as a blueprint for creating multiple different objects.

Each class has a name, and describes attributes and behavior.
In programming, the term type is used to refer to a class name: We're creating an object of a particular type.

Method -  is another term for a class' behavior. A method is basically a function that belongs to a class.

For example, if we are creating a banking program, we can give our class the following characteristics:
name: BankAccount
attributes: accountNumber, balance, dateOpened
behavior: open(), close(), deposit()

The class only provides a definition.
Once we've written the class, we can move on to create objects that are based on that class.
Each object is called an instance of a class. 
The process of creating objects is called instantiation.


16.Syntax of Class

Creating a Class

Let's create a class with one public method, and have it print out "Hi".

Class BankAccount {
public :        // Access specifier : public (accessed by everyone ) or private
void sayHi () 
{
cout << “Hi “ << endl;
}
}  ;

// The next step is to instantiate an object of our BankAccount class, in the same way we define variables of a type, the difference being that our object's type will be BankAccount.

int main()
{
BankAccount test; // test - object
test.sayHi();
}
