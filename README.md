# partitioning-a-disk-to-clean-it-for-OS
commands to partition a disk or clean it to install and operating system

commands:
diskpart
list disk
select disk "X"
format fs=fat32 quick
clean
exit
