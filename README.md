1 ПАРА БЭКЭНД

**ЛЯМБДА ФУНКЦИИ**
*Это анонимные функции, те функции без имени*
lambda <аргументы через запятую>: <возвращаемое выражение>

**КЛАССЫ**
*Класс* - шаблон для создания обьекта
Класс состоит из членов
Члены - это:
1) Метод - функции класса
2) Поля - переменные класса

students = {'Петя': [3,2, 3, ,5, 2],
            'Артем': [5, 4, 5, 5],
            'Илья':[3, 4, 5]}
def avg():
  for key, value in students.items():
    print(key, sum(value) / len(value))
    
ИЛИ

class Students:
  def __init__(self(сам обьект, с которым мы взаимодействуем), name:str, scores: list[int]) #конструктор, создающая класс:
    self.name = name
    self.scores = scores
  def avg(self) -> int:
    return sum(self.scores / len(self.scores)
  def print(self) -> None:
    print(f'{self.name}: {self.avg()}')
petya = Students('Петя', [3, 4, 2, 5])
petya.scores => оценки пети
students.print() => Петя: средняя оценка

**ООП***
*-Астракция 
-Инкапсуляция
-Наследование
-Полиморфизм*

**Абстракция** - представление реального обьекта, из кот. мы удалили ненужное
**Наследование** - ...
class GraduatedStudent(Student):
def __init__(self, name: str, score, date_of_graduation):
self.name = name
self.scores = scores
self.date_of_graduation = date_of_graduation
student = GraduatedStudent("Питер", [3, 2, 4, 5], "2025-06-25"
student.date_of_graduation => '2025-06-25'














 
(id - айдишный код обьекта)
