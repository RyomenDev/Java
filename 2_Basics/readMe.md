using **Java 21+ (JDK 21 or 22)**, where implicitly declared classes (like writing code directly without a class or method) are part of a preview feature called unnamed classes. These are not enabled by default.

### ✅ Option 1: Use a normal Java class (Recommended for learning)

```java
public class Main {
    public static void main(String[] args) {
        int age = 20;
        System.out.println("Name: " + name);
    }
}
```

### 🧪 Option 2: Use the preview feature (not recommended for beginners)

```bash
javac --enable-preview --release 21 1_Variables.java
java --enable-preview 1_Variables
```
