# Cryptology
This is a project that helps you to encrpt and decrypt some information.

一、Funtion：

The project implements five encryption algorithms,include DES,affine,rc4,rsa,LFSR+JK.You can choose a file that need to be encryted and
choose a encryption algorithm to encrypt this file.After this file is encrypted,you also can choose the same encryption algorithm to decrypt
this ciphertext.

二、Project Architecture

![image](https://github.com/Alexlingl/Cryptology/blob/master/images/project_arch.png)

1、The "src" file folder has java source codes,includes "BuutonListen.java"-monitor class,"Config.java"-a interface that defines some parameters,"MessageWindows.java"-The main UI class and "PlayerMain.java"-The choose file UI class.

2、The "lib" file folder has five *.jar file,corresponding to five encryption algorithms.The five files are "des.jar","fangshe.jar",
"lfsrjk.jar","rc4.jar" and "rsa.jar".But you couldn't open the five files.If you want to see the java codes of five encrptology 
algorithms,you can open the "libs" file folder.

3、The "libs" file folder has five *.java file,corresponding to five encryption algorithms.You can see the specific java implements 
of five encryption algorithms.

三、The main UI

![image](https://github.com/Alexlingl/Cryptology/blob/master/images/Main_UI.png)

1、"选择文件"
You can click "选择文件" button to choose the file that you want to encrypt.You can see the specific information in the choosen file on the
left TextArea.

![image](https://github.com/Alexlingl/Cryptology/blob/master/images/choose_file.png)

2、drop down list
The drop down list includes "仿射","流密码RC4","流密码LFSRJK","DES" and "RSA".You can choose one encryption algorithm to encrypt or decrypt
the ciphertext.

3、"加密"
After you choose a file and a encryption algorithm,you can click the "加密" button.And this file will be encrypted with the encryption
algorithm.You can see the ciphertext on the right TextArea.

4、"解密"
The "解密" button is the same as "加密" Button.The most important things is that you must choose the right decription algorithm!

