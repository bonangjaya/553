# masuk putty
# 
# cd /tmp
# wget --no-check-certificate wget https://github.com/bonangjaya/flash/blob/main/pw553.bin
# tunggu proses wget selesai
# setelah proses wget selesai, ketik :
  cd /tmp && mtd -e linux -r write pw553.bin linux
# tunggu sampai proses selesai dan router akan reboot otomatis
# selesai
