# DevOps
git clone git@github.com:Podrepny/DevOps.git

cd DevOps/

git status

ls -la

git add test_file.txt

git status

git commit -m "Added 'test_file.txt'."

git config --global user.email "no@mail.here"

git config --global user.name "Alexey"

git commit -m "Added 'test_file.txt'."

git push

git status

git pull

git status

git diff

git add .

git status

git commit -m "Added 'test_file2.txt'."

git push


git clone ...


nginx -t

service nginx restart

netstat -nlp

tail -f /var/log/nginx/* &

tcpdump -nni ens33 icmp

tcpdump -nni ens32

iptables -t nat

iptables -t nat -nvL

cat openssl.cnf | grep -v "^[[:space:]]*#" | grep -v "^$"
