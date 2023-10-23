# Криптографічні перетворення S-блоку та P-блоку

Цей репозиторій містить приклад Java-коду, який демонструє роботу криптографічних перетворень з використанням S-блоку та P-блоку.

## Вміст репозиторію

1. `Main.java`: Головний файл, який містить реалізацію алгоритмів S-блоку та P-блоку.
2. `README.md`: Цей файл, що надає опис та інструкції щодо використання коду.

## Як використовувати код

1. Склонуйте репозиторій на ваш комп'ютер:

    ```sh
    git clone https://github.com/yourusername/crypto-algorithms.git
    ```

2. Відкрийте проект у вашій улюбленій Java розробковій середовищі.

3. Відкрийте файл `Main.java` і ознайомтесь з кодом. У ньому містяться реалізації S-блоку, P-блоку, а також функції для шифрування та розшифрування.

4. Запустіть код у ваший Java-середовищі (наприклад, за допомогою `main` методу).

5. Ви побачите результати шифрування та розшифрування для заданого вхідного тексту (plaintext).

## Приклад використання

```java
public static void main(String[] args) {
    int plaintext = 0x53; // Вхідний текст
    System.out.println("Plaintext: 0x" + Integer.toHexString(plaintext));

    // Шифрування
    int ciphertext = encrypt(plaintext);
    System.out.println("Ciphertext: 0x" + Integer.toHexString(ciphertext));

    // Розшифрування
    int decryptedText = decrypt(ciphertext);
    System.out.println("Decrypted text: 0x" + Integer.toHexString(decryptedText));
}
