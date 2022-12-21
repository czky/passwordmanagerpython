# Password Manager made with Python

- Project created with the help of [Tech with Tim's video](https://www.youtube.com/watch?v=DLn3jOsNRVE).

## How to use

- Download the project, unzip the file, place the main.py in a folder.
- Open command prompt / terminal and do 
```bash pip install cryptography```
- Create a file called "key.key" and place it in the same folder as main.py
- Use this command in order to generate the key file: ```bash python -c "from cryptography.fernet import Fernet; FERNET_KEY = Fernet.generate_key().decode()```
- The command prompt / terminal will output a key, copy it and paste it in the key.key file.
- Create a passwords.txt file and place it in the same folder as main.py
- Run the main.py file and you're good to go!


