obj-m +=  timer_test.o

export KROOT=/db/psp_git/users/a0393758/upstream/omap-kernel/

all:
	  @$(MAKE) ARCH=arm CROSS_COMPILE=arm-arago-linux-gnueabi- -C $(KROOT) M=$(PWD) modules
clean:
	  rm -rf   Module.symvers modules.order *.o *.ko

distclean: clean
