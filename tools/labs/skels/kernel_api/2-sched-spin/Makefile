KDIR = /lib/modules/`uname -r`/build
CONFIG_MODULE_SIG=n

kbuild:
	make -C $(KDIR) M=`pwd`

clean:
	make -C $(KDIR) M=`pwd` clean
