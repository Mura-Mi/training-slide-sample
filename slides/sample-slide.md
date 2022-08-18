---
title: Sample Slide (meta data title)
description: An example slide deck created by Marp CLI
author: Takuya "Mura-Mi" Murakami
---

# サンプルスライド <!-- markdownlint-disable MD025 -->

---

## Java コードがきれいに表示できます

Marpを利用することで、Javaのコードがキレイにハイライトされます。

```java
public class SampleSlide {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

## Shell もきれいに表示できます

```bash
$ echo "Hello, World!"
$ javac SampleSlide.java
$ java SampleSlide
Hello, World!
```

---

## 箇条書きで説明を書きます

* このスライドは、Marp CLIで作成されたスライドです
* 箇条書きは、Markdownの `*` で記載すれば大丈夫
* もうPowerPointなんて要らないかも
