**<font size=5 color=000000>2023年7月 KUG（深圳、贵州、武汉）联合线上趣味问答活动完整题库</font>**

## 题库

| 题号 | 问题                                                         | 答案                              | 回答者QQ   | 回答者群昵称   |
| ---- | ------------------------------------------------------------ | --------------------------------- | ---------- | -------------- |
| 1    | [JetBrains 在中国上海成立公司，中文名叫什么？（三个字）](#1) | 捷并思                            | 1524176441 | CSC            |
| 2    | [Kotlin 的命名来源于一个岛屿，这个岛屿位于哪个国家？](#2)    | 俄罗斯                            | 863350375  | val Int ＝true |
| 3    | [截至目前 (2023年7月)， 中国一共有多少个 KUG (Kotlin User Group) 组织？](#3) | 17                                | 316762827  | 不二先森       |
| 4    | [在 Kotlin 内置函数 let、also、apply、run 中，返回值为调用者本身的函数是？](#4) | also、apply                       | 1034557712 | imknown        |
| 5    | [修改String](#修改String)                                    | FFF                               | 1524176441 | CSC            |
| 6    | [协程](#协程)                                                | CB                                | 2453793562 | (⊙_⊙)          |
| 7    | [Android 每一个版本的代号都是按照字母顺序的甜点名，那么Android 14 (U) 的代号是哪一种甜点呢？](#7) | 翻转蛋糕(Upside Down Cake)        | 1034557712 | imknown        |
| 8    | [Kotlin 的空安全机制机制，能够有效的降低应用的空指针异常，那么空指针异常 NullPointerException (NPE) 他在哪一个包下面？](#8) | java.lang                         | 2457968197 | 下一个小廖     |
| 9    | [它叫什么名字？](#Kotlin吉祥物)                              | Kodee                             | 2457968197 | 下一个小廖     |
| 10   | [方法描述符](#方法描述符)                                    | (FB)I                             | 929698601  | 深海鱼🐟YY.     |
| 11   | [方法描述符常量](#方法描述符常量)                            | 2                                 | 2457968197 | 下一个小廖     |
| 12   | [JVM重载](#JVM重载)                                          | 5                                 | 1524176441 | CSC            |
| 13   | [ 仅当对象为非 null 时，____ 运算符才允许你调用方法](#运算符) | ?:                                | 1034557712 | imknown        |
| 14   | [以下哪个是 Kotlin 1.9.0 版本发布的稳定的范围运算符？](#..<运算符) | ..<                               | 2457968197 | 下一个小廖     |
| 15   | [在 Kotlin 中，可见性修饰符用于控制类、函数、属性和其他声明的可见范围。Kotlin 中的可见性修饰符按照可见度从高到低的顺序排序是？](#15) | public>internal>protected>private | 316762827  | 不二先森       |



**最后获得奖励的参与者是[2457968197, 1524176441, 1034557712] **

`下一个小廖`  `CSC`  `imknown`

###   <font face="微软雅黑" size=5 color=2B2B2B>第 1 题</font><a name="1"></a>

<font face="微软雅黑" size=5 color=2B2B2B>JetBrains 在中国上海成立公司，中文名叫什么？（三个字）</font>





### <font face="微软雅黑" size=5 color=2B2B2B>第 2 题</font> <a name="2"></a>

<font face="微软雅黑" size=5 color=2B2B2B>Kotlin 的命名来源于一个岛屿，这个岛屿位于哪个国家？ </font> 





### <font face="微软雅黑" size=5 color=2B2B2B>第 3 题</font> <a name="3"></a>

<font face="微软雅黑" size=5 color=2B2B2B>截至目前 (2023年7月)， 中国一共有多少个 KUG (Kotlin User Group) 组织？ </font> 

 

 

### <font face="微软雅黑" size=5 color=2B2B2B>第 4 题</font> <a name="4"></a>

<font face="微软雅黑" size=5 color=2B2B2B>在 Kotlin 内置函数 let、also、apply、run 中，返回值为调用者本身的函数是？ </font> 





### <font face="微软雅黑" size=5 color=2B2B2B>第 5 题: </font><a name="修改String"></a>

<font face="微软雅黑" size=5 color=2B2B2B> 阅读代码，回答输出结果</font>

- 以下代码运行于 JDK8 环境
- JDK8 以上环境，请添加虚拟机参数  `--add-opens java.base/java.lang=ALL-UNNAMED --add-exports java.base/jdk.internal.module=ALL-UNNAMED`

```kotlin
const val first = "A"
const val second = "A"

fun main() {
    with(String::class.java.getDeclaredField("value")) {
        isAccessible = true
        set(first, "F".toByteArray())
    }
    print(first)
    print(second)
    println("A")
}
```





### <font face="微软雅黑" size=5 color=2B2B2B>第 6 题</font><a name="协程"></a>

<font face="微软雅黑" size=5 color=2B2B2B> 阅读代码，回答输出结果</font>

```kotlin
fun main() {
    GlobalScope.launch {
        launch {
            delay(3000)
            print("A")
        }
        launch {
            delay(1000)
            print("B")
        }
    }
    print("C")
    Thread.sleep(2000)
}
```





### <font face="微软雅黑" size=5 color=2B2B2B>第 7 题</font><a name="7"></a>

<font face="微软雅黑" size=5 color=2B2B2B>Android 每一个版本的代号都是按照字母顺序的甜点名，那么Android 14 (U) 的代号是哪一种甜点呢？</font>





### <font face="微软雅黑" size=5 color=2B2B2B>第 8 题</font><a name="8"></a>

<font face="微软雅黑" size=5 color=2B2B2B> Kotlin 的空安全机制，能够有效的降低程序的空指针异常，那么空指针异常 NullPointerException (NPE) 他在 JDK 的哪一个包下面？</font>

- A: java.io
- B: java.lang
- C: java.util
- D: java.security

 

### <font face="微软雅黑" size=5 color=2B2B2B>第 9 题</font><a name = "Kotlin吉祥物"></a>

<font face="微软雅黑" size=5 color=2B2B2B> 它叫什么名字？</font>

![Kotlin吉祥物](https://blog.jetbrains.com/wp-content/uploads/2023/04/DSGN-16174-Blog-post-banner-and-promo-materials-for-post-about-Kotlin-mascot_3.png)

![Kotlin吉祥物](https://blog.jetbrains.com/wp-content/uploads/2023/04/DSGN-16174-Blog-post-banner-and-promo-materials-for-post-about-Kotlin-mascot_4-copy.png)

![Kotlin吉祥物](https://blog.jetbrains.com/wp-content/uploads/2023/04/DSGN-16174-Blog-post-banner-and-promo-materials-for-post-about-Kotlin-mascot_3-copy-2.png)





### <font face="微软雅黑" size=5 color=2B2B2B>第 10 题</font><a name="方法描述符"></a>

<font face="微软雅黑" size=5 color=2B2B2B>请写出以下方法的 方法描述符 [method descriptor]</font>

```kotlin
fun method(first: Float, second: Byte): Int {
    return 0
}
```



### <font face="微软雅黑" size=5 color=2B2B2B>第 11 题</font><a name="方法描述符2"></a>

<font face="微软雅黑" size=5 color=2B2B2B>以下Class中的 4 个方法，将产生几个方法描述符常量</font>

```kotlin
class G3Q1 {
    fun a(text: String?): Int? = 0

    fun b(text: String?): Int = 0

    fun c(text: String): Int? = 0

    fun d(text: String): Int = 0
}
```





### <font face="微软雅黑" size=5 color=2B2B2B>第 12 题</font><a name="JVM重载"></a>

<font face="微软雅黑" size=5 color=2B2B2B> 以下 Test3 类中将产生几个方法名为 func 方法？</font>

```kotlin
class Test3() {
    @JvmOverloads
    fun func(
        a: String? = null,
        b: String? = null,
        c: String? = null,
        d: String? = null
    ) {
        // TODO
    }
}
```





### <font face="微软雅黑" size=5 color=2B2B2B>第 13 题<a name="运算符"></a></font>

<font face="微软雅黑" size=5 color=2B2B2B> 仅当对象为非 null 时，____ 运算符才允许你调用方法</font>

- A：`.`
- B：`!!` 
- C：`?:`
- D：`?.` 





### <font face="微软雅黑" size=5 color=2B2B2B>第 14 题</font><a name="..<运算符"></a>

<font face="微软雅黑" size=5 color=2B2B2B> 以下哪个是 Kotlin 1.9.0 版本发布的稳定的范围运算符？</font>

- A：`..`

- B：`..<` 

- C：`>..`

- D：`downTo`

- E：`until` 





### <font face="微软雅黑" size=5 color=2B2B2B>第 15 题<a name="15"></a></font>

<font face="微软雅黑" size=5 color=2B2B2B>在 Kotlin 中，可见性修饰符用于控制类、函数、属性和其他声明的可见范围。Kotlin 中的可见性修饰符按照可见度从高到低的顺序排序是？</font>

- A：`internal`>`public`>`protected`>`private`
- B：`public`>`internal`>`protected`>`private`
- C：`public`>`protected`>`internal`>`private`
- D：`public`>`protected`>`private`>`internal`
