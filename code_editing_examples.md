# 代码编辑实例

OpenAI的[edits](https://openai.com/blog/gpt-3-edit-insert/)端点对于编辑代码特别有用。

与补全不同，edits需要两个输入：要编辑的文本和一条指令。

例如，如果你想编辑一个Python函数，你可以提供该函数的文本和一个指令，如 "add a docstring"。

输入`code-davinci-edit-001`的文本示例。

```python
def tribonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    elif n == 2:
        return 1
    elif n == 3:
        return 2
    else:
        return tribonacci(n-1) + tribonacci(n-2) + tribonacci(n-3)
```

示例指令输入:

```text
add a docstring
```

```text
Add typing, using Python 3.9 conventions
```

```text
improved the runtime
```

```text
Add a test.
```

```text
Translate to JavaScript (or Rust or Lisp or any language you like)
```

改进运行时间并翻译成JavaScript后的输出示例:

```JavaScript
function tribonacci(n) {
  let a = 0;
  let b = 1;
  let c = 1;
  for (let i = 0; i < n; i++) {
    [a, b, c] = [b, c, a + b + c];
  }
  return a;
}
```

正如你所看到的，`code-davinci-edit-001`能够成功地将函数的运行时间从指数级降低到线性，以及从Python转换到JavaScript。

在 [OpenAI Playground](https://beta.openai.com/playground?mode=edit&model=code-davinci-edit-001) 中使用 `code-davinci-edit-001` 进行代码编辑实验。