# Message Encryption and Decryption
____________________________  
This project is a desktop application that allows encrypting and decrypting messages using symmetric cryptographic algorithms. It is developed in Python using the Kivy framework for the graphical user interface (GUI).
## Previous Author
Santiago Cano Ocampo


## Current authors
____________________________  
- Anderson Monsalve Monsalve  
- Juan Felipe Ruiz Yepes  

## Description
____________________________  
The application allows users to encrypt and decrypt messages using a cryptographic key. The available algorithms for encryption are: Twofish, Serpent, AES (Rijndael), Camellia, Salsa20, ChaCha20, Blowfish, CAST5, Kuznyechik, RC4, DES, 3DES, Skipjack, Safer, and IDEA.

## Requirements
____________________________  
- Python 3.9.13  
- Kivy 2.3.0  

  ```bash
  pip install pycryptodome
  ```

- Install Kivy:

  ```bash
  pip install kivy
  ```

- Install `cryptography`:

  ```bash
  pip install cryptography
  ```

- Run the encryption module:

  ```bash
  python aes_encryption.py
  ```

## Installation
____________________________  
1. Clone this repository or download the source code.  
2. Make sure you have Python 3.9.13 installed on your system.  
3. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   ```

   For Windows:

   ```bash
   venv\Scripts\activate
   ```

   For Linux/Mac:

   ```bash
   source venv/bin/activate
   ```

## GUI Execution
____________________________  
1. Install `pycryptodome`:

   ```bash
   pip install pycryptodome
   ```

2. Run the main module:

   ```bash
   python app.py
   ```

## Steps to run the code by cmd
- For the console we use
```bash
python src/view/app.py
```
- To run all tests in the test folder, use this command, it will find and run all test files
  ```bash
  python -m unittest discover -s test

   ```
```bash
test_BD.py
```
 ```bash
 test_crypto.py,
```
## use this to add your database

```bash
src/controller/SecretConfig.py

   ```
-si vas a utilizar por interfaz sería

  ```bash
python src/view/criptop.py

   ```

## base de datos
# instalar las siguientes librerias:
- psycopg2
- sys
- os
- ryptography
- base64


## coloca tus datos de tu base de datos en la carpeta secretconfig:
PGHOST='******
PGDATABASE=*****
PGUSER=****
PGPASSWORD=****

## ejecucion

una vez echo lo anterior ejecutar el modulo app.py 
ya sea desde el cmd o visual code 
si es desde el cmd se recomienda ponerla en escritorio y acceder a la carpeta con el comando cd 

una vez echo lo anterior ejecutar el modulo app.py 
ya sea desde el cmd o visual code 
si es desde el cmd se recomienda ponerla en escritorio y acceder a la carpeta con el comando cd 

