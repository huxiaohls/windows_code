obj-m += my_rc522.o

KDIR := /home/rty/iTop4412_Kernel_3.0

PWD := $(shell pwd) 

all:  
	$(MAKE) -C $(KDIR) M=$(PWD) modules  
	
clean:  
	rm *.mod.c *.o *.ko  modules.* Module.*
