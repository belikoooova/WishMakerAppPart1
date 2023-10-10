# WishMakerAppPart1
Question: What issues prevent us from using storyboards in real projects?

Более медленная скорость работы
Работа только на последних версиях OS
Более тяжелый поиск ошибок
Question: What does the code on lines 25 and 29 do? 25: отключает автоматический ресайзинг элементов, чтобы мы могли задать кастомный 29: добавляет один view на другой - это позволяет делать ресайзинг объектов и вообще отображает добавленный view

Question: What is a safe area layout guide? Обозначает границы, которые не будут залезать на челку, Status Bar и Home Indicator

Question: What is weak self on line 23 and why is it important? Если оставить self, то создастся сильная ссылка на объект, вызывающий метод, и при выходе из метода она не будет удалена, что приведет к утечке памяти. Поэтому мы создаем слабую ссылку.

Question: What does clipsToBounds mean? Это означает, что subView, которые добавлены на данный view, будут ограничены границами view

Question: What is the valueChanged type? What is Void and what is Double? Тип - функция, принимающая Double (число с плавающей точкой) и ничего не возвращающая (т.е. Void) (то есть, это своего рода делегат)
