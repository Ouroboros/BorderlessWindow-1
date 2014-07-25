# BorderlessWindow for Qt
Native Qt borderless window for Windows OS (like Office 2013, Visual Studio 2012).

Creates a simple borderless winapi window, like this one URL. Then adds QWinWidget from QtWinMigrate and fills window with it.

### Difference from Qt:FramelessWindowHint
* Resizeable
* Draggable
* Minimize animation
* Aero snap support
* ALT+Space system menu works
* Shadow

### Issues
* Two event loops, one from WinApi window, one from QApplication.



Works with Qt4 and Qt5. 
If you use Visual Studio, you'll need to import BorderlessWindow.pro file (VS Main menu -> Qt -> open Qt Project file).




