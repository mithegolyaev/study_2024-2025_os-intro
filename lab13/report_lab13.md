
# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until

# Лабораторная работа №13

Студент: Щеголяев Максим Ильич  
Группа: НБИбд-02-25  
Студенческий билет: 1032256490  

## Цель работы
Изучить основы программирования в оболочке UNIX, включая использование ветвлений, циклов и обработки аргументов командной строки.

## Теоретическая часть

Командный процессор UNIX (shell) представляет собой мощный инструмент...
(расширенный текст)

### Команда getopts
Команда getopts используется для обработки аргументов командной строки...

### Команда grep
grep — утилита поиска текста...

### Управляющие конструкции
if, case, while, until...

## Практическая часть

### Задание 1
```bash
#!/bin/bash
while getopts "i:o:p:Cn" opt; do
 case $opt in
  i) input=$OPTARG ;;
  o) output=$OPTARG ;;
  p) pattern=$OPTARG ;;
  C) flag="-i" ;;
  n) num="-n" ;;
 esac
done

grep $flag $num "$pattern" "$input" > "$output"
```

### Задание 2
```c
#include <stdio.h>
#include <stdlib.h>
int main() {
 int x;
 scanf("%d",&x);
 if(x>0) exit(1);
 if(x<0) exit(2);
 exit(0);
}
```

### Задание 3
```bash
for ((i=1;i<=$1;i++)); do
 touch "$i.tmp"
done
```

### Задание 4
```bash
find . -mtime -7 -type f -print | tar -czf archive.tar.gz -T -
```

## Результаты
Программы успешно работают...

## Выводы
Были изучены...

## Ответы на контрольные вопросы
1. getopts — обработка аргументов
2. Метасимволы используются...
3. if, case, while
4. break, continue
5. true/false — логика
6. проверка файла
7. while vs until
