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

