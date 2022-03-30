# Troubleshoot_PM2
Problem and could solve it with re-creating the startup script. Try the following steps:

delete current process
pm2 delete nameOfProcess
unload current startup script
pm2 unstartup systemd
update pm2
pm2 update
enable startup script
pm2 startup //copy paste the output
start process again
pm2 start nameOfProcess
save current config
pm2 save
