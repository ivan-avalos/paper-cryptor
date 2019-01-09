# PaperCryptor

PaperCryptor is a symmetric encryption tool made on paper, written in C, that allows you to easily encrypt a file using another file as a key, and outputing the encrypted file. Using the same key, you can decrypt the file to see its contents.

## Why I made it?

I made this project in April 2018 in middle school, when I was really bored and had nothing to do. Maybe some absent teacher or simply not paying attention to the class, I can't remember why, but it took me about 50 minutes (an entire class) to finish it. I haven't tried to compile it to see if really works, but I think it does, maybe you could help me with that.

## How it works?

PaperCryptor uses a really fundamental logical component called: XOR. No complex algorithms, only a simple bitwise XOR operation. It applies the same operation for each byte between the file and the key. Applying the same operation again will result in the decrypted file.

<img src="img/xor.png">

## Why do I have many *Cryptors?

+ <a href="https://github.com/ivan-avalos/crackcryptor">Crack**Cryptor**</a> 
**2016** Graphical encryption tool made using Qt.
+ <a href="https://github.com/ivan-avalos/quick-cryptor">Quick**Cryptor**</a> 
**2018** Simple CLI encryption tool written in C.
+ <a href="https://github.com/ivan-avalos/g-quick-cryptor">gQuick**Cryptor**</a> 
**2018** GUI for QuickCryptor made using GTK+.
+ <a href="https://github.com/ivan-avalos/paper-cryptor">Paper**Cryptor**</a> 
**2018** Simple encryption tool made on paper.

Well, maybe because it's very easy and funny to create a symmetric encryption tool, emphasizing _funny_. I don't know much about cryptography, but creating programs like this makes me feel like at least I'm able to do something.

## License (GPL v3)

```
PaperCryptor – simple symmetric encryption made on paper.
Copyright (C) 2018, 2019  Iván Ávalos

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```