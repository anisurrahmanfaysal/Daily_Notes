# Welcome To My Notes
### I'm Anisur rahman Faysal.

<br>
<p>As a Software developer I should maintain alaways github and I'm gonna notedown my learning topic here.</p>
<hr>

## Topics

- Operating Systems
  - [Linux Mint](#linuxmint)

<br>
<hr>

- Programming Languages
  - [C](#c)
  - [C#](#c#)
  - [JavaScript](#javascript)
  - [PHP](#php)

<br>
<hr>

- Framework
  - [Laravel](#laravel)

<br>
<br>
<br>
<br>
<br>
<hr>

# Operating Systems
## Linux Mint <a name="linuxmint"></a> 
 - [C# Project Create using VS Code](#c#create)
 - [C# Code Run using VS Code](#c#run)

### Installition
 - [Install XAMPP](#xampp)


<br>
<hr>

### Prerequisites for C# Code in VS Code <a name="c#prerequisites"></a>
- Visual Studio Code with the C# extension installed. For information about how to install extensions on Visual Studio Code, see VS Code Extension Marketplace.
- The .NET 7 SDK.

  - #### Install
    ```
      sudo apt install dotnet-sdk-7.0
    ```
  - #### Remove
    ```
      sudo apt-get remove dotnet-sdk-7.0
    ```
### C# Project Create using VS Code <a name="c#create"></a>
```
  dotnet new console --framework net7.0
```
### C# Code Run using VS Code <a name="c#run"></a>
```
  dotnet run
```
- [Prerequisites for coding C# in VS Code](#c#prerequisites)

<br>
<hr>

### Install XAMPP <a name="xampp"></a>
   #### Prerequisites

   #### Step-1: XAMPP requires the “net-tools” package to be installed on your system. This package can be installed by running the following command in the terminal:
   ```
     sudo apt install net-tools
   ```

   #### Step-2: Downloading XAMPP via the Internet:

       https://www.apachefriends.org/download.html

   #### Step-3: Making the Downloaded File Executable:
     ```
       sudo chmod 755 xampp-linux-x64-7.2.34-0-installer.run      
     ```

   #### Step-4: Installing XAMPP on Linux:
     ```
       sudo ./xampp-linux-x64-7.2.34-0-installer.run
     ```
   #### Step-5:
<br>
<hr>

# Programming Languages
## C <a name="c"></a> 
## C# <a name="c#"></a>
 - [C# Introduction](#introduction)
 - [C# Output](#output)
 - [C# Variables](#variables)
 - [C# DataType](#datatype)

<br>
<hr>

### C# Introduction <a name="introduction"></a>
<p>C# is pronounced "C-Sharp".

It is an object-oriented programming language created by Microsoft that runs on the .NET Framework.

C# has roots from the C family, and the language is close to other popular languages like C++ and Java.

The first version was released in year 2002. The latest version, C# 11, was released in November 2022.

C# is used for:</p>

    - Mobile applications
    - Desktop applications
    - Web applications
    - Web services
    - Web sites
    - Games
    - VR
    - Database applications
    - And much, much more!

<br>
<hr>
  
### C# Output<a name="output"></a>
<p>To output values or print text in C#, you can use the WriteLine() method:</p>
   
   ```
       Console.WriteLine("Hello World!");
   ```
   ```
       Console.WriteLine(3 + 3);
   ```
   ```
       Console.Write("Hello World! ");
   ```     
   
<br>
<hr>

### C# Variables <a name="variables"></a>

<p>Variables are containers for storing data values.

In C#, there are different types of variables (defined with different keywords), for example:</p>

- int - stores integers (whole numbers), without decimals, such as 123 or -123
- double - stores floating point numbers, with decimals, such as 19.99 or -19.99
- char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
- string - stores text, such as "Hello World". String values are surrounded by double quotes
- bool - stores values with two states: true or false

<b><p>type variableName = value;</p></b>


```C#
  int myNum = 5;
  double myDoubleNum = 5.99D;
  char myLetter = 'D';
  bool myBool = true;
  string myText = "Hello";
```

<p>This will declare the variable as "constant", which means unchangeable and read-only:</p>

```C#
  const int myNum = 15;
  myNum = 20; // error
```

<p>Note: You cannot declare a constant variable without assigning the value. If you do, an error will occur: A const field requires a value to be provided.</p>

<br>
<hr>

### C# DataType <a name="datatype"></a>

<p> A data type specifies the size and type of variable values. It is important to use the correct data type for the corresponding variable </p>

 <img src="images/0001.jpg">
 <img src="images/0002.jpg">

    

   


<br>
<hr>
   


    

## JavaScript <a name="javascript"></a> 
## PHP <a name="php"></a> 

# Framework
## Laravel <a name="laravel"></a>
  - [Mastering](#mastering)
  - [CRUD](#crud)
  - [Auth](#auth)
  - [Multi User Dashboard](#validation)
  - [Middleware](#validation)
  - [Eloquent ORM](#validation)
  - [Query Builden](#validation)
  - [API](#validation)
  - [Mailing](#validation)
  - [October CRM](#validation)


<br>
<hr>

<hr>
<br>




```php

public function store(Request $request){
  dd($request->all());
  return view('index');
}
```

```bash
php artisan make:request StoreRequest
```
