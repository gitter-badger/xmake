# preifx
include $(PRO_DIR)/prefix.mak

# module name
NAMES 											= demo

# type
demo_TYPE 										= BIN

# files
demo_C_FILES 									+= xmake

# packages
demo_PKGS-$(TBOX)  								+= tbox 
demo_PKGS-$(LUAJIT)  							+= luajit 
demo_PKGS-$(BASE)  								+= base 

# others
demo_LIBS 										+= xmake$(DTYPE)
demo_INC_DIRS 									+= ../
demo_LIB_DIRS 									+= ../xmake
demo_CXFLAGS 									+= -D__tb_prefix__=\"xmake\"

# suffix
include $(PRO_DIR)/suffix.mak

