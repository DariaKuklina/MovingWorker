## 🚦 Процесс работы системы

### 1. Инициализация
    - Тележка находится в стартовой позиции
    - Рабочий в состоянии ожидания 
    - Компонент расположен на рабочем столе

### 2. Запуск системы
    - Пользователь нажимает клавишу `Z`
    - Тележка начинает движение по сплайновому пути

### 3. Взаимодействие с рабочим
    - При достижении триггерной зоны:
        * Тележка автоматически останавливается
        * Запускается State Machine рабочего
        * Последовательное выполнение анимаций:
            1. Поднятие компонента
            2. Перенос на телегу
            3. Возврат на рабочее место

### 4. Продолжение движения
    - После завершения анимаций:
        * Компонент фиксируется на телеге
        * Тележка возобновляет движение
       
