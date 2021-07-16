# masuk putty
# 
# ketik cd /tmp
# ketik wget https://github.com/bonangjaya/flash/blob/main/pw553.bin
# tunggu proses wget selesai
# setelah proses wget selesai, ketik :
  cd /tmp && mtd -e linux -r write 553.bin linux
# tunggu sampai proses selesai dan router akan reboot otomatis
# selesai
