@echo off
color 0a
mode 50,10
:loop
set /p user= "user_name : 
echo.
set /p pass= "new_passw : 
echo.
net user %user% %passw%
echo.
echo --PRESS ENTER--
cls
goto loop
