# Solicen.SEncrypt

#### Русский | [English](https://github.com/DenisSolicen/Solicen.SEncrypt/README-EN.md)

## На русском
* Класс для реализации простого шифрования файла
* Может как зашифровать файл, так и расшифровать файл, и передать его расшифровку в строку.

### Использование:
* Определить какое смещение вы будете использовать (смещение - это количество дополнительных нулевых байтов, для зашифровки файла)

* Для зашифровки: использовать метод `Encrypt(файл)` или `EncryptWithOffset(файл,смещение)`
* Для расшифровки: использовать метод `Decrypt(файл)` или `DecryptWithOffset(файл,смещение)`
  * Если создание файла не нужно, то `DecryptToStringWithOffset(файл,смещение)` это вернет вам расшифровку как строку.

#### Автор библиотек/классов - [Denis Solicen](https://github.com/DenisSolicen)
