all: BUILD_LIB BUILD_DOXYGEN
	@cd program        && $(MAKE)
BUILD_LIB:
	@cd SiSTouchIO817 && $(MAKE)
	@cd SiSTouch       && $(MAKE)
CLEAN_LIB:
	@cd SiSTouchIO817 && $(MAKE) clean
	@cd SiSTouch       && $(MAKE) clean
BUILD_DOXYGEN:
#doxygen
clean:CLEAN_LIB
	@cd program        && $(MAKE) clean
CLEAN_LIB_ALL:
	@cd SiSTouchIO817 && $(MAKE) clean_all
	@cd SiSTouch       && $(MAKE) clean_all
clean_all:CLEAN_LIB_ALL
	@cd program        && $(MAKE) clean_all
	@rm -vfr bin lib ../../doc/Linux_Android_FWConsole_Tool
