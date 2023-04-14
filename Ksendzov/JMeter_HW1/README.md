## JMeter HW_1

Сделать сценарий с перечисленными эндпоинтами.

Дать нагрузку на 50, 250, 500 потоков. Результаты прогонов загрузить в CSV. Настройки Jmeter, файл .jmx выгружаем на гит.

http://162.55.220.72:5005

1) http://162.55.220.72:5005/get_method
- GET
- name: str
- age: int

2) http://162.55.220.72:5005/user_info_2
- POST
- name: str
- age: int
- salary: int

3) http://162.55.220.72:5005/user_info_3
- POST
- name: str
- age: int
- salary: int

4) http://162.55.220.72:5005/object_info_1
- GET
- name: str
- age: int
- weight: int

5) http://162.55.220.72:5005/object_info_2
- GET
- name: str
age: int
salary: int

6) http://162.55.220.72:5005/object_info_3
- GET
- name: str
- age: int
- salary: int

7) http://162.55.220.72:5005/object_info_4
- GET
- name: str
- age: int
- salary: int
