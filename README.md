# 🛡️ NigProt Obfuscator

**Professional Java Obfuscation for Maximum Protection**

## 🎯 What is NigProt?

NigProt is a state-of-the-art Java obfuscator that protects your code from:
- 🔓 Decompilers (CFR, Fernflower, Procyon)
- ✏️ Bytecode editors (Recaf)
- 🔍 String analysis
- 🐛 Debugging

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **Name Obfuscation** | Classes, methods renamed to `ӀОl`, `о0I` |
| **ZKM-Style String Encryption** | Multi-layer encryption |
| **InvokeDynamic** | Hidden method calls |
| **Native Transpilation** | Convert to C code (JNIC-style) |
| **Watermark** | ASCII art branding |

## 📦 Demo

This repository contains a before/after comparison:

```
demo/
├── snakegame-original.jar      # Before obfuscation
└── snakegame-obfuscated.jar    # After obfuscation
```

### Run the games:
```bash
java -jar demo/snakegame-original.jar
java -jar demo/snakegame-obfuscated.jar
```

Both work identically - but try decompiling them! 👀

## 📊 Obfuscation Stats

```
╔══════════════════════════════════════════╗
║              OBFUSCATION STATS           ║
╠══════════════════════════════════════════╣
║  Classes obfuscated:         7            ║
║  Methods obfuscated:         4            ║
║  Strings encrypted:          3            ║
╚══════════════════════════════════════════╝
```

## 🔥 Before vs After

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
public class ӀОl {
    private int о0l = 0;
    
    public void Оo1() {
        /* ZKM-encrypted string */
        System.out.println(new StringBuilder()
            .append((char)(42^97^13))
            .append((char)(55^103^26))
            ...);
    }
}
```

## 💰 Pricing

Contact for enterprise licensing.

## 📧 Contact

- Discord: `dexon.cpvp`
- GitHub: [@dexoncpvp](https://github.com/dexoncpvp)

---

**© 2024 NigProt - Your Code, Protected.**
