sublime-syntax-fixes
====================

Syntax Fixes for Sublime Editor

####Java
```java
public class Foo {
    public void bar(@Baz(value = 123) val) {}
}
```

####JavaScript
```javascript
var x = 10
      / 2;
alert(x);
```

####Shell Script (Bash)

```bash
echo ${FOO:+default}
echo ${FOO:-"default"}
echo ${FOO:-${BAR}}
echo ${FOO:+"${BAR:+"${BAZ}"}"}
```
