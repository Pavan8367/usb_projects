obj-m += bot_driver.o

bot_driver-objs := bot_probe.o scsi_cmds.o bbb_transport.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
