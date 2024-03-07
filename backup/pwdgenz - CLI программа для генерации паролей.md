Моей первой сделанной программой на Rust была pwdgenz. Была крутая задумка с реализацией псевдослучайных символов во благо того что бы пароли можно было легче запоминать, так же можно генерить стразу несколько паролей и так же сохранять в буфер обмена. Легкое управление:

```
Usage: pwdgenz [OPTIONS]

Options:
  -l, --length <LENGTH>  Password length [default: 16]
  -a, --amount <AMOUNT>  Amount of passwords [default: 1]
  -c, --clipboard        Save the last value to the clipboard
  -h, --help             Print help
  -V, --version          Print version
```

Если кому-то интересно вот страничка на [github](https://github.com/KerbsOpenSource/pwdgenz), там есть [сборки на Linux и Windows](https://github.com/KerbsOpenSource/pwdgenz/releases).