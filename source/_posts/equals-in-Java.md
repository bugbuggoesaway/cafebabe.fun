---
title: Equals in Java
date: 2024-11-26 11:00:20
tags: [Java]
---

这是一道比较常见的 Java 面试题，考察的是候选人 Java 基础是否足够扎实。
看下大家的功底：
<!-- more -->

```Java
public class EqualsInJava {
    public static void main(String[] args) {
        String s1 = new String("Hello");
        String s2 = new String("Hello");
        System.out.println(s1.equals(s2)); // true
        System.out.println(s1 == s2); // false

        String s3 = "Hello";
        String s4 = "Hello";
        System.out.println(s3.equals(s4)); // true
        System.out.println(s3 == s4); // true
        
        Integer i1 = new Integer(100);
        Integer i2 = new Integer(100);
        System.out.println(i1.equals(i2)); // true
        System.out.println(i1 == i2); // false
        
        Integer i3 = 100;
        Integer i4 = 100;
        System.out.println(i3.equals(i4)); // true
        System.out.println(i3 == i4); // true
        
        Integer i5 = 200;
        Integer i6 = 200;
        System.out.println(i5.equals(i6)); // true
        System.out.println(i5 == i6); // false
    }
}
```

如果你都答对了，那么给你点个赞，你的 Java 基础功底还是不错的。
如果你对某些结果感到困惑，那么请持续关注我的博客，我会详细解释这些结果。
