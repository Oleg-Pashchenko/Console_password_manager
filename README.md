# cli-password-drive
# How to install:
1) git clone https://github.com/Oleg-Pashchenko/cli-password-drive.git
2) chmod +x passwords
3) sudo ln -s $(pwd)/passwords /usr/local/bin/
4) sudo touch /usr/local/bin/passwords.json
5) sudo chmod 777 /usr/local/bin/passwords.json

# How to use:
1) passwords --add --site=ya.ru --login=test --password=hackme
2) passwords --query=ya.ru
