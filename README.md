# twine
1. Добавление раздела [[Аоеорш      оьхшв олжгньир]]
2. Добавление картинки персонажа <img src="https://github.com/topqwi9416/twine/blob/main/user.png?raw=true" width="450" height="450">
```
<img src="https://github.com/topqwi9416/twine/blob/main/user.png?raw=true" width="450" height="450">
```
3. Добавление фона
```
tw-story {
background-image: url("https://github.com/topqwi9416/twine/blob/main/fon.jpg?raw=true");
  background-size: cover
}
```
4. Добавление подложки у текста
```
#passages {
  position: relative;
}

.passage {
  position: relative;
}

.text-box {
  position: fixed;
  left: 50%;
  margin-top: 10px;
  bottom: 20px;
  border-radius: 10px;
  transform: translateX(-50%);
  max-width: 800px;  
  padding: 10px; 
  color: white;
  border-radius: 10px;
  z-index: 1000;
 
  }
```
