# Passo a passo para criar venv(versionamento de ambiente)  

--------------------------------------------------------------
***Versionamento de Deploy***    

[![img1.png](https://i.postimg.cc/W4c0sZgx/img1.png)](https://postimg.cc/68z80yHh)  
 
 
Imagem acima: lado esquerdo ambiente Linux e lado direito Windows  

-------------------------------------------------------------

***Versionamento BD***  

Inserindo biblioteca:  
$ source ./venv/Scripts/activate  
$ pip3 install sqlite-utils  
$ pip freeze > requirements.txt  

-------------------------------------------------------------  

Sequência completa no Gitbash:  

$ pwd (aparece o caminho completo do diretório)  
$ python3 -m venv <caminho completo do diretório>/venv  ***(em alguns casos no lugar do python3 colocar apenas python)***  
$ source ./venv/Scripts/activate  
$ pip install sqlite-utils  
$ pip freeze > requirements.txt

Fonte: material de apoio Professor Thiago Kuma  

[![impacta.png](https://i.postimg.cc/0QVbLK8g/impacta.png)](https://postimg.cc/FdJrSRdG)  

-------------------------------------------------------------

Mais informações : https://virtualenv.pypa.io/en/latest/
