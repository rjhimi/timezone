sudo timedatectl set-timezone Africa,Tunis
sudo yum install chrony -y
vi /etc/chrony.conf
add pool 196.203.249.241 iburst
systemctl daemon-reload
systemctl restart chronyd
timedatectl
