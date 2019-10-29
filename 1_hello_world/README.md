# Run command

- Hello world! の表示

```bash
% gradle -q hello
```

- hoge,fuga,piyoと数字の表示

```bash
% gradle -q hoge
```

- カウンターの表示

```bash
% gradle -q counter
```

- 依存関係の記述

```bash
% gradle -q unlockDoor
% gradle -q enterMyRoom
% gradle -q relax
# 別記法
% gradle -q unlockDoor2
% gradle -q enterMyRoom2
% gradle -q relax2
```

- taskの前後に処理を差し込む

```bash
% gradle -q samplebf
```

# Errors

## `<<` でエラーが発生

```
Could not find method leftShift() for arguments
```

> `<<` による記法は Gradle 3.2 で非推奨となり、Gradle 5.0 で廃止になったようです。
https://teratail.com/questions/187565

---

# References

[1] Androidのビルドについて（Gradle）
http://mixi-inc.github.io/AndroidTraining/introductions/1.05.how-to-build-for-gradle.html