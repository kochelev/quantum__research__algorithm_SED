# Определение существования решений
# Solution Existence Detection

**Исходная ссылка:** c36b67be8356e03f1c1aca68de880e2c

Схема определения существования хотя бы одного решения.

Описание состоит из трех статей:
- теоретическое обоснование [**SED_1_theory.ipynb**](https://github.com/kochelev/quantum__research__algorithm_SED/blob/master/SED_1_theory.ipynb);
- тестирование на удаленном симуляторе квантового компьютера IBM [**SED_2_tests.ipynb**](https://github.com/kochelev/quantum__research__algorithm_SED/blob/master/SED_2_tests.ipynb);
- грубая оценка применимости схемы + точки роста [**SED_3_scaling.ipynb**](https://github.com/kochelev/quantum__research__algorithm_SED/blob/master/SED_3_scaling.ipynb).

Для апробации на реальном квантовом компьютере необходимо зарегистрироваться в IBM Quantum, и затем в корневой папке проекта создать файл **ibm_token.py**, в который вписать строчку: **token = "Ваш токен от IBM Quantum"**.
