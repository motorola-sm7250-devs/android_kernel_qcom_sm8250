<<<<<<< HEAD
# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_SENSORS_SSC)	+= sensors_ssc.o
=======
all: modules

modules:
	$(MAKE) -C $(KERNEL_SRC) M=$(M) modules $(KBUILD_OPTIONS)

modules_install:
	$(MAKE) INSTALL_MOD_STRIP=1 -C $(KERNEL_SRC) M=$(M) modules_install

%:
	$(MAKE) -C $(KERNEL_SRC) M=$(M) $@ $(KBUILD_OPTIONS)

clean:
	rm -f *.o *.ko *.mod.c *.mod.o *~ .*.cmd Module.symvers
	rm -rf .tmp_versions
>>>>>>> 66413f72dcda05cd32f5e5ed639d78ad617533ba
