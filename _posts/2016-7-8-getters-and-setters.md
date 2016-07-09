---
layout: post
title: Let's Go Fishing.
---

Encapsulation, the dark art of hiding data from other methods. So, what happens if that hidden data needs to be used...oh and by the way you can set data to be private in Java like so:

```java
private int example;
//a private variable called example, which is an integer
```

I'll take a test case of a bank account. No one wants their balance being seen by all and sundry, therefore being a private variable

```java
private int bank_balance;
```
This means if you withdraw money, the withdraw method will have to request for access to the value stored in ``` bank_balance ```.

Key word ```get``` sort of fetches the value of the private method or variable in the case where the program wants to debit your account. The key word ```set``` will give it a new public value that can be manipulated for the function. 

There is getters and setters dimistified!