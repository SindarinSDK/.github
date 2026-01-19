# ✨ What is Sindarin?

**Sindarin (Sn)** is a statically-typed procedural programming language that compiles to C. It combines modern developer experience with native performance, featuring clean arrow-based syntax, powerful string interpolation, and built-in array operations.

```
.sn source → Sn Compiler → C code → GCC/Clang → executable
```

### 🎯 Key Features

| Feature | Description |
|---------|-------------|
| 🔒 **Static Typing** | Explicit type annotations for safety and clarity |
| ➡️ **Arrow Syntax** | Clean `=>` blocks for readable code |
| 💬 **String Interpolation** | Embed expressions with `$"Hello {name}!"` |
| 📦 **Built-in Arrays** | Native operations: push, pop, slice, join, and more |
| 🏗️ **Structs** | Structured data with C library interop |
| 📂 **File I/O** | TextFile and BinaryFile types |
| 🧵 **Threading** | Built-in spawn and sync for parallelism |
| 🔗 **C Interop** | Native functions, pointers, and callbacks |
| 🧠 **Arena Memory** | Shared/private scopes with copy semantics |

### 📝 Example

```sn
fn is_prime(n: int): bool =>
  if n <= 1 =>
    return false
  var i: int = 2
  while i * i <= n =>
    if n % i == 0 =>
      return false
    i = i + 1
  return true

fn main(): void =>
  var primes: int[] = {}
  for var n: int = 2; n <= 50; n++ =>
    if is_prime(n) =>
      primes.push(n)
  print($"Primes: {primes.join(\", \")}\n")
```

---

## 📚 Repositories

| Repository | Description |
|------------|-------------|
| 🛠️ [**sindarin-compiler**](https://github.com/SindarinSDK/sindarin-compiler) | The Sindarin compiler - converts `.sn` files to native executables |

---

## 🚀 Quick Start

### Installation

**Linux (Debian/Ubuntu)**
```bash
sudo dpkg -i sindarin_*.deb
```

**Linux (Fedora/RHEL)**
```bash
sudo rpm -i sindarin-*.rpm
```

**macOS (Homebrew)**
```bash
curl -LO https://github.com/SindarinSDK/sindarin-compiler/releases/latest/download/sindarin.rb
brew install --formula ./sindarin.rb
```

**Windows (Winget)**
```powershell
Expand-Archive winget-manifests.zip -DestinationPath winget-manifests
winget install --manifest ./winget-manifests
```

### Compile & Run

```bash
# Compile a program
sn hello.sn -o hello
./hello

# Or emit C code only
sn hello.sn --emit-c -o hello.c
```

---

## 📖 Documentation

Full documentation is available in the [sindarin-compiler docs](https://github.com/SindarinSDK/sindarin-compiler/tree/main/docs):

- 📘 [Language Overview](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/readme.md)
- 🔤 [Strings & Interpolation](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/strings.md)
- 📊 [Arrays & Slicing](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/arrays.md)
- 🏛️ [Structs & C Interop](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/structs.md)
- 🧠 [Memory Management](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/memory.md)
- 🧵 [Threading](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/threading.md)
- 📦 [SDK Modules](https://github.com/SindarinSDK/sindarin-compiler/blob/main/docs/sdk/readme.md)

---

## 🤝 Contributing

We welcome contributions! Here's how to get involved:

1. 🍴 Fork the [sindarin-compiler](https://github.com/SindarinSDK/sindarin-compiler) repository
2. 🌿 Create a feature branch
3. ✅ Run tests with `make test`
4. 📬 Submit a pull request

Check out the [contribution guidelines](https://github.com/SindarinSDK/sindarin-compiler#contributing) for more details.

---

## 📄 License

All SindarinSDK projects are released under the **MIT License** - feel free to use, modify, and distribute!

---

<p align="center">
  <i>🧝 Named after the Elvish language from Tolkien's legendarium</i>
</p>
