Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/28VDv2cD5Hsx4VepNtMReevWsY02Jh

Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/Zivwi4JB1r8uP7ecBnVxF7G2tvRT26

Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/w1ypwTFJAH0DHFIwYjCCf4wtxaOuWj

Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/0ssnFSSc22qPxnB61prjSQj7EHak2r
