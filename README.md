goit-nodejs-hw-01

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
![list](https://github.com/StanislavPoponia/goit-nodejs-hw-01/assets/127778439/802e60d3-3472-491e-be07-23ba14ae0bc8)

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
![byID](https://github.com/StanislavPoponia/goit-nodejs-hw-01/assets/127778439/602f1acc-5607-4144-b5c8-fb5bf9435990)

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
![add](https://github.com/StanislavPoponia/goit-nodejs-hw-01/assets/127778439/0f62c08c-46e9-466b-a860-0467884592bf)

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
![remove](https://github.com/StanislavPoponia/goit-nodejs-hw-01/assets/127778439/54afbe3e-1722-452c-93c8-d6eba51e14dd)
