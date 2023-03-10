# Methods in Java
- Methods are a subtasks within a class that are used to break a complex problem into small manageble pieces.
- It is a collection of code statements that perform a specific task.
- Methods perform a specific task and can help eliminate redundacy and code.
- Other programming language have different names for these such as **functions, or modules**. But in java it is known as methods
- We have already created a method in every program that we've written so far that is **main method**
```java
public static void main(String[] args){

}
```

- We have also made calls to other methods such as the ones in the **Scanner class to input data** and the ones in the **System class to output the data**.
- Consider this program code below:
<img width="368" alt="image" src="https://user-images.githubusercontent.com/63767834/214448724-78afce0d-d3c6-425d-9afd-974ff096944c.png">

- let's examine the parts of the method:
<img width="364" alt="image" src="https://user-images.githubusercontent.com/63767834/214448841-2174091d-e86f-4cd9-9c4d-9d2934253e68.png">

- The very first line of the method is called the header

<img width="363" alt="image" src="https://user-images.githubusercontent.com/63767834/214449128-49a3b5f9-6a94-417a-96bf-ae296e25de7e.png">

- The first word in a method is the access modifier.
- **Access modifiers** indicate who is allowed access to use this method.
- **Public** means any code from any class can use this method. 
- Having an access modifier is not required


---

- After the method's header comes the method body
![image](https://user-images.githubusercontent.com/63767834/214608375-5b1c3ef4-aeb1-404f-8650-96906af27d00.png)

- Method's body starts after the set of curly braces
```java
{
// Method's Body
//
//
}
```

- The body consists of zero or more statements that are to be executed, when the method is called
- If the method has specifies the a return type as anything as void, the method must include a return statement.
![image](https://user-images.githubusercontent.com/63767834/214612281-a6303b31-756d-4e4f-a3fc-494a286f328f.png)


- The return statement will return a value which matches the return type specified in the header.
- **Return** is a reserved word in Java.


#### This is the anatomy of the method
