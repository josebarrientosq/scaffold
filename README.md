[![Python application test with Github Actions](https://github.com/josebarrientosq/scaffold/actions/workflows/main.yml/badge.svg)](https://github.com/josebarrientosq/scaffold/actions/workflows/main.yml)

# scaffold

## Create ssh for github and paste
```
ssh-keygen –t rsa
cat /home/ec2-user/.ssh/id_rsa.pub
```

## Create directory
```
touch Makefile
touch hello.py
touch test_hello.py
touch requirements.txt
```


## Create a virtual enviroment
```
python3 -m venv ~/.scaffold
source ~/.scaffold/bin/activate
which python3
```

## write Makefile , then 
```
make install
make lint
make test
make all
```
## Github actions
Create template to test on github actions
[template](https://gist.github.com/josebarrientosq/b82b595e8a924ccee6b58a2a06a411df)


## Printscreen
![imagen](https://user-images.githubusercontent.com/35469345/134110310-55887a44-b0f6-439e-8b8c-3e116bcb8ac5.png)
