# OpenGlTutorials

https://habr.com/ru/articles/310790
https://learnopengl.com

# Установка VcPkg
- Скачать VcPkg (git clone https://github.com/microsoft/vcpkg.git)
- Запустить bootstrap-vcpkg (cd vcpkg; .\bootstrap-vcpkg.bat)
- Дальше надо установить переменную среды VCPKG_ROOT
- Добавить VCPKG_ROOT в PATH

# Сборка проекта
```
cmake . --preset=default -G "Visual Studio 17 2022" -A x64 -B build
cmake --build build
```
- Этот пример для системы сборки MsBuild, для других необходимо поменять генератор -G "Visual Studio 17 2022"
