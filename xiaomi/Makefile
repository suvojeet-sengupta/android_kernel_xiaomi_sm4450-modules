KBUILD_OPTIONS += MODNAME=xiaomi

modules modules_install clean:
	$(MAKE) -C $(KERNEL_SRC) M=$(M) $@ $(KBUILD_OPTIONS)
