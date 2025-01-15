# FractalBitcoin

Бот для генерации Bitcoin-адресов на основе симметричных узоров 16x16. Каждый узор преобразуется в 256-битный ключ, который используется для создания Bitcoin-адреса.

## Как это работает?

1. Бот создаёт симметричный узор 16x16 с использованием математических функций.
2. Узор преобразуется в 256-битный ключ.
3. На основе ключа генерируется приватный ключ и Bitcoin-адрес.
4. Бот проверяет баланс адреса через API.
5. Если баланс ненулевой, бот отправляет информацию вам в личные сообщения. Если баланс нулевой, информация публикуется в канале.

## Пример работы

```plaintext
Число: 29
Узор:
🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩
🟩🟩🟩🟩🟩⬜️⬜️⬜️⬜️⬜️⬜️🟩🟩🟩🟩🟩
🟩🟩🟩⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️🟩🟩🟩
🟩🟩⬜️⬜️⬜️🟩🟩🟩🟩🟩🟩⬜️⬜️⬜️🟩🟩
🟩🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩🟩
🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩
🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩
🟩⬜️⬜️🟩🟩🟩🟩⬜️⬜️🟩🟩🟩🟩⬜️⬜️🟩
🟩⬜️⬜️🟩🟩🟩🟩⬜️⬜️🟩🟩🟩🟩⬜️⬜️🟩
🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩
🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩
🟩🟩⬜️⬜️🟩🟩🟩🟩🟩🟩🟩🟩⬜️⬜️🟩🟩
🟩🟩⬜️⬜️⬜️🟩🟩🟩🟩🟩🟩⬜️⬜️⬜️🟩🟩
🟩🟩🟩⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️⬜️🟩🟩🟩
🟩🟩🟩🟩🟩⬜️⬜️⬜️⬜️⬜️⬜️🟩🟩🟩🟩🟩
🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩

Приватный ключ: 32274494ea2844c3f8e91b959639e960dace983b24f251962e672b171df95e58
Адрес Bitcoin: 1KPQwHK4pQ6PPGsmeRdsBDzqWJtzYV4GxY
Баланс Bitcoin: 0 сатоши
Количество транзакций Bitcoin: 0
Баланс Bitcoin Cash: 0 сатоши
