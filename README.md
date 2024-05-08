Щоб порівняти алгоритми сортування за їхньою ефективністю, виконаймо тестування на різних наборах даних, 
включаючи відсортовані, випадкові та зворотно відсортовані масиви. 
Для цього я скористалася модулем timeit для заміру часу виконання кожного алгоритму.

Код можна побачити у файлі task1

Після виконання коду ми отримаємо час виконання кожного алгоритму на різних розмірах даних. 
Використовуючи ці дані, ми можемо провести аналіз ефективності кожного алгоритму.

Звісно, очікується, що Timsort буде набагато швидшим, оскільки він комбінує в собі переваги обох підходів: злиття та вставки. 
Таким чином, його швидкодія буде показником оптимальності його реалізації. 
Результати допоможуть підтвердити цю гіпотезу та проілюструвати переваги використання вбудованих алгоритмів сортування в Python над власноручним кодуванням.

На основі результатів тестування можна зробити висновок, що для багатьох випадків сортування вбудованими функціями Python є оптимальним вибором, 
оскільки вони використовують ефективний алгоритм Timsort. Це зменшує необхідність вручну реалізовувати сортування та забезпечує швидку та надійну реалізацію.