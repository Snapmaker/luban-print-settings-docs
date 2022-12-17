Прискорення друку початкового шару
====

### **Опис**

Цей параметр контролює швидкість прискорення сопла в різних напрямках під час подачі матеріалу в першому шарі.

### **Вплив**

Друк із високими темпами прискорення може спричинити вібрацію принтера. Зокрема, ці вібрації можуть спричинити вібрацію робочого столу вгору та вниз, що негативно впливає на зчеплення моделі з робочим столом. Зменшення прискорення для першого шару може зменшити вібрацію під час цієї критичної частини процесу друку. Однак для друку знадобиться більше часу, а надто велике зниження швидкості прискорення може спричинити нерівномірне видавлювання в кутах, що також негативно впливає на зчеплення з робочим столом.

### **Використання**

Для прискорення під час друку першого шару можна встановити іншу швидкість, ніж для решти друку. Прискорення руху робочої головки під час екструзії можна встановити іншим, ніж прискорення під час переміщення без друку.

Хоча стінки, елементи зчеплення з робочим столом, низ, опори та заповнення можуть мати різні швидкості прискорення, під час друку першого шару вони будуть зроблені однаковими. Прискорення початкового шару буде перекривати швидкості прискорення окремих структур. Налаштування [Прискорення спідниці/поля](acceleration_skirt_brim.md) замінює початкове прискорення друку шару.