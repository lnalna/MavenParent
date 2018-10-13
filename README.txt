https://o7planning.org/ru/10259/build-a-multiple-module-project-with-maven

Простой проект многомодульный Maven . Состоит из двух модулей и родительского проекта.

В MathLibrary описан метод суммы двух чисел, вызывается этот метод на странице index.jsp в
проекте MathWebApp.

Проект рабочий. Для запуска необходимо выполнить цель : install в проекте MavenParent.

После можно попробовать развернуть на Tomcat MathWebApp.war. Все должно работать.
