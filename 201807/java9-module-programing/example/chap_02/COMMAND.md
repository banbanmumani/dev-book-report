# 실습에서 사용한 명령어

```bash
mkdir -p code/java9/src/packt.addressbook/packt/addressbook
```

```bash
vi code/java9/src/packt.addressbook/module-info.java
```

```java
module packt.addressbook{
}
```
```bash
vi code/java9/src/packt.addressbook/packt/addressbook/Main.java
```

```java
package packt.addressbook

public class Main{
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}
```

```bash
cd code/java9
javac --module-source-path src -d out src/packt.addressbook/packt/addressbook/Main.java src/packt.addressbook/module-info.java
java --module-path out --module packt.addressbook/packt.addressbook.Main
```
