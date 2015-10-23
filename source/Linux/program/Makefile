all: BUILD_32 BUILD_64

BUILD_64:
	$(MAKE) -f Makefile.64bit
BUILD_32:
	$(MAKE) -f Makefile.32bit
clean:
	$(MAKE) -f Makefile.32bit clean
	$(MAKE) -f Makefile.64bit clean
clean_all:
	$(MAKE) -f Makefile.32bit clean_all
	$(MAKE) -f Makefile.64bit clean_all
