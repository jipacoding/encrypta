**Prefere Português? [Clique aqui](docs/pt-br/README.md) para ler nessa língua maravilhsosa.**

## Goals
- Supports all alphabets and symbols
- Bi-directional encryption

## Installation & Usage
Encrypta is in various programming languages. Visit [this link](docs/en-us/Install-Encrypta) and see available languages.

## Algorithm
Encrypta is based on the [Caesar's Chipher](https://en.wikipedia.org/wiki/Caesar_cipher), but her standard mode is not safe 😓.

* ### What's the difference?
  * ### Random Shift
    Instead of using a plain-alphabet for the displacement (abcde...), Encrypta uses a list of 65 characters. You can generate another at any time. This list is called Kutter.

  * ### Support all alphabets and symbols
    EncryptaEngine uses the base64 encoding method. It converts the characters into text-mode representations. That is, EncryptaEngine supports Chinese language, Russian language, emojis etc.

  * ### Rotation
    You can set the rotation index by changing the order of Kutter. This option does not make much difference 🤷‍♂️

  * ### Extra Security
    The first step is to encrypt the string with the Kutter set. With `steps = 2`, there is a second encryption, but using the reverse Kutter/String.




## Contributing
You can help making this project better by reporting bugs or submitting pull requests.
