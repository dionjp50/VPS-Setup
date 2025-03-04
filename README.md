# VPS-Setup
# I use VPS for Pentesting

1. sudo apt update && sudo apt upgrade -y
2. sudo apt install git
3. sudo apt install curl
4. sudo apt install wget
5. wget https://golang.org/dl/go1.23.0.linux-amd64.tar.gz
6. sudo tar -C /usr/local -xvzf go1.23.0.linux-amd64.tar.gz
7. nano ~/.profile
8. export PATH=$PATH:/usr/local/go/bin
9. nano ~/.bashrc
10. export PATH=$PATH:/usr/local/go/bin
11. source ~/.profile
12. source ~/.bashrc
13. go version (go version go1.23 linux/amd64)
#
after that i use tool from my great mentor RootBakar
you have to visit repository there are a lot of way to make you better in pentesting
https://github.com/rootbakar/bugbounty-toolkit
