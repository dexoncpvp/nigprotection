# NigProt Obfuscator

**Professional Java Obfuscation for Maximum Protection**

## What is NigProt?

NigProt is a state-of-the-art Java obfuscator that protects your code from:
- Decompilers (CFR, Fernflower, Procyon)
- Bytecode editors (Recaf)
- String analysis
- Debugging

## Features

| Feature | Description |
|---------|-------------|
| **Name Obfuscation** | Classes, methods renamed to unreadable characters |
| **ZKM-Style String Encryption** | Multi-layer encryption |
| **InvokeDynamic** | Hidden method calls |
| **Native Transpilation** | Convert to C code (JNIC-style) |
| **Watermark** | ASCII art branding |

## Demo

This repository contains a before/after comparison:

```
demo/
├── snakegame-original.jar      # Before obfuscation
└── snakegame-obfuscated.jar    # After obfuscation
```

### Run the games:
```bash
java -jar snakegame-original.jar
java -jar snakegame-obfuscated.jar
```

Both work identically - but try decompiling them!

## Obfuscation Stats

```
╔══════════════════════════════════════════╗
║              OBFUSCATION STATS           ║
╠══════════════════════════════════════════╣
║  Classes obfuscated:         6            ║
║  Methods obfuscated:         4            ║
║  Strings encrypted:          2            ║
╚══════════════════════════════════════════╝
```

## Before vs After

### Before (Original)
```java
public class SnakeGame {
    private int score = 0;
    
    public void startGame() {
        System.out.println("Game Started!");
    }
}
```

### After (Obfuscated)
```java
public class l {
    private int o = 0;
    
    public void O() {
        System.out.println(new StringBuilder()
            .append((char)(42^97^13))
            .append((char)(55^103^26))
            ...);
    }
}
```

## Contact

- GitHub: [@dexoncpvp](https://github.com/dexoncpvp)

---

**2026 NigProt - Your Code, Protected.**
