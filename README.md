# Primitive Datatypes Task
Utiliza la guía adjunta para familiarizarte con los comandos y los tipos de datos primitivos de Powershell
## · Task 1
~~~
Get-Help Get-ExecutionPolicy
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/1.PNG)
~~~
Get-Help Set-ExecutionPolicy
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.PNG)
~~~
Get-Help Get-Acl
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/3.PNG)
~~~
Get-Help Get-EtwTraceProvider
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/4.PNG)
~~~
Get-Help Set-InitiatorPort
~~~ 
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/5.PNG)
## · Task 2
~~~
Get-Help Get-ExecutionPolicy -examples
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.1.PNG)
~~~
Get-Help Set-ExecutionPolicy -examples
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.2.PNG)
~~~
Get-Help Get-Acl -examples
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.3.PNG)
~~~
Get-Help Get-EtwTraceProvider -examples
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.4.PNG)
~~~
Get-Help Set-InitiatorPort -examples
~~~ 
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/2.5.PNG)
## · Task 3
~~~
New-Item -Path C:\Users\Carles\Desktop\CARLES\FP_DAM_1º\SISTEMAS -Name PracticaPrimitive -ItemType Directory
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/3.1.PNG)
~~~
New-Item -Path C:\Users\Carles\Desktop\CARLES\FP_DAM_1º\SISTEMAS\PracticaPrimitive -Name TestFile.txt -ItemType File
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/3.2.PNG)
## · Task 4
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/4.1.PNG)
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/4.2.PNG)
## · Task 5
~~~
Get-Content -Path C:\Users\Carles\Desktop\CARLES\FP_DAM_1º\SISTEMAS\PracticaPrimitive\TestFile.txt | Get-Member
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/5.1.PNG)
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/5.2.PNG)
## · Task 6
~~~
Set-Content -Path C:\Users\Carles\Desktop\CARLES\FP_DAM_1º\SISTEMAS\PracticaPrimitive\Testfile.txt -Value "Aaaaaaaaaah"
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/6.PNG)
## · Task 7
~~~
Get-Service | Format-List
~~~
~~~
Set-ExecutionPolicy | Format-List
~~~
## · Task 8
~~~
Get-Command | Out-GridView
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/8.PNG)
## · Task 9
~~~
Get-ExecutionPolicy | Format-List
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/9.1.PNG)
~~~
Set-ExecutionPolicy | Out-GridView
~~~
~~~
Get-Acl | Out-GridView
~~~
![alt_text](https://github.com/carlosblancoj/Ejercicio3_Sistemas/blob/main/primitive_data/9.2.PNG)
~~~
Get-EtwTraceProvider | Out-GridView
~~~
~~~
Set-InitiatorPort | Out-GridView
~~~
## · Task 10
~~~
Start-Process "https://docs.microsoft.com/en-us/powershell/"
~~~
