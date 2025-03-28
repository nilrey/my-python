
# 📚 Урок 1: Переменные и типы данных  

## 🎯 Цель урока  
Познакомиться с переменными и основными типами данных в Python.  

---  

## 📖 Теория  

### 🔹 Переменные  
Переменная — это имя, которое присваивается значению в программе. В Python для создания переменной достаточно просто присвоить значение:  

```python
x = 10
name = "Alice"
```

- Имя переменной должно начинаться с буквы или символа подчеркивания (`_`).
- Имя переменной не может начинаться с цифры.
- Переменные чувствительны к регистру (например, `age` и `Age` — это разные переменные).

### 🔹 Типы данных  
В Python есть несколько встроенных типов данных. Вот самые распространённые:  

- **int** (целые числа): `10`, `-5`, `0`
- **float** (числа с плавающей запятой): `3.14`, `-2.5`, `0.0`
- **str** (строки): `"Hello"`, `'Python'`
- **bool** (булевы значения): `True`, `False`

Пример:  
```python
x = 10          # int
y = 3.14        # float
name = "Alice"  # str
is_valid = True  # bool
```

### 🔹 Преобразование типов  
В Python можно преобразовывать типы данных, используя функции преобразования, например:  

- `int()`: преобразует в целое число
- `float()`: преобразует в число с плавающей запятой
- `str()`: преобразует в строку
- `bool()`: преобразует в булев тип

Пример:  
```python
x = "5"
y = int(x)  # Преобразуем строку в целое число
print(y + 3)  # 8
```

---  

## 📝 Практика  

### ✅ **Задание 1: Переменные и типы данных**  
Создайте переменные для хранения своего возраста, роста, имени и статуса. Присвойте им значения и выведите их.  

📌 **Пример работы**:  
```
Возраст: 25  
Рост: 1.75  
Имя: Alice  
Статус: True  
```  

---  

### ✅ **Дополнительное задание**  
1. Преобразуйте строку с числом в тип `int` и посчитайте результат умножения на 2.
2. Преобразуйте целое число в строку и выведите его на экран.

---  

🚀 **Добавьте этот файл в `basics/lesson_1_variables_and_data_types.md`, коммитните и запушьте!**  
Как только зальешь, напиши, и я подготовлю следующий урок. 😊  
