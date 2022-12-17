Висота початкового шару
====

### **Опис**

Цей параметр визначає товщину першого шару вашого друку.

![The initial layer is thicker than the rest of the layers](../images/layer_height_0.png)

### **Вплив**

Збільшення початкової товщини шару змушує сопло екструдувати більше матеріалу на таку ж відстань, що потребує додаткової сили, оскільки матеріал розповсюджується в сторони, щоб заповнити всю ширину лінії. Ця додаткова сила змушує матеріал краще прилипати до робочої поверхні столу. Крім того, товстіший шар усуне будь-які нерівності на поверхні. Якщо робоча поверхня злегка зігнута, ця мінливість буде поглинена товщиною першого шару, інакше сопло може зішкребти перший шар під час друку другого шару.

### **Використання**

Початковий шар зазвичай друкується товстішім, ніж решта, щоб створити міцніше зчеплення з робочим столом. За допомогою цього параметра товщину початкового шару можна збільшити без зменшення роздільної здатності решти друку.

Занадто товстий початковий шар призводить до того, що перший шар більше розтікається, що спричиняє появу «слонячої ноги». Налаштування [Горизонтальне розширення початкового шару](../shell/xy_offset_layer_0.md) може запобігти «слонячим ногам», через встановлення невеликого від’ємного значення.