# Usage
gcc lab1.c -o lab1  
./lab1


# lab1
LAB1 labzhynskyi UNIX KPI КПИ ЛАБЖ ЛАБЖИНСКИЙ ЛАБА1 ЛАБ1 
# Контрольні запитання

Які типи границь існують в операційній системі?
В чому полягає різниця між функціями pathconf і fpathconf?

# Індивідуальні завдання
Написати програму, яка виводить значення всіх границь, що не пов'язані з файловою системою (функція sysconf), та значення всіх границь, що пов'язані з файловою системою (функція pathconf), приблизно у такий спосіб (по одній границі в кожному рядку):

Значення границі <ім’я_границі> дорівнює <значення_границі>.

Символьні імена границь для функцій sysconf, pathconf і fpathconf наведені у відповідних розділах довідкового посібника. Як перший аргумент функції pathconf доцільно взяти “/” (кореневий каталог) або “.” (поточний каталог).

SYSCONF
PATHCONF
fpathconf
