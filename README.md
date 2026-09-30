<div align="center">

# 🧠 Brainfuck Interpreter

### A Brainfuck interpreter built from scratch with Python

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-Brainfuck-181717?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Working-00C853?style=for-the-badge" />
</p>

<p>
  A small interpreter built as a challenge to understand how an extremely minimal
  programming language can be parsed and executed.
</p>

</div>

<br />

<div align="center">

## ⚡ The Challenge

</div>

Brainfuck has only **eight commands**:

<div align="center">

```text
>  <  +  -  .  ,  [  ]
```

</div>

Despite having such a small instruction set, writing and debugging Brainfuck programs
is surprisingly challenging. This project was built from scratch to understand the
logic behind executing those instructions, managing memory, moving pointers, and
handling loops.

<br />

<div align="center">

## 🧪 First Successful Test

</div>

One of the first tests was the classic **Hello World** program:

```brainfuck
++++++++++[>+++++++>++++++++++>+++>+<<<<-]
>++.>+.+++++++..+++.>++.<<+++++++++++++++.
>.+++.------.--------.>+.>.
```

Output:

```text
Hello World!
```

<br />

<div align="center">

## 🚀 Usage

</div>

Run a Brainfuck source file:

```bash
python brainfuck.py yourcode.bf
```

The interpreter can also be used as a Python module:

```python
import brainfuck

brainfuck.evaluate(sourcecode)
```

<br />

<div align="center">

## 🛠 Built With

<img src="https://skillicons.dev/icons?i=python" height="60" />

**Python**

</div>

<br />

<div align="center">

## 📚 What I Explored

<table>
  <tr>
    <td align="center">🧠<br /><strong>Interpreters</strong></td>
    <td align="center">💾<br /><strong>Memory</strong></td>
    <td align="center">👉<br /><strong>Pointers</strong></td>
    <td align="center">🔄<br /><strong>Loops</strong></td>
    <td align="center">⚙️<br /><strong>Execution</strong></td>
  </tr>
</table>

</div>

<br />

<div align="center">

## 📌 About

This project started as a simple experiment and became a hands-on way to understand
how source code can be interpreted instruction by instruction.

**Built from scratch. Built to learn.**

<br />

<a href="https://github.com/Abdurahman-Abdella/BrainFuck">
  <img src="https://img.shields.io/badge/View%20Source-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>
