################################################################################
# Automatically-generated file. Do not edit!
################################################################################

### Toolchain: yocto--arm-poky-linux-gnueabi--opt-poky-n6x-203 ###
CC=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-gcc --sysroot=/opt/poky/n6x/203/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi -mfloat-abi=hard 
STRIP=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-strip
CPP=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-cpp --sysroot=/opt/poky/n6x/203/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi -mfloat-abi=hard 
CXX=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-g++ --sysroot=/opt/poky/n6x/203/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi -mfloat-abi=hard 
RANLIB=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-ranlib
CXXFILT=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-c++filt
DEBUGGER=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-gdb
AR=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-ar
AS=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-as
OBJCOPY=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-objcopy
OBJDUMP=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-objdump
LD=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-ld --sysroot=/opt/poky/n6x/203/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi -mfloat-abi=hard 
ADDR2LINE=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-addr2line
NM=/opt/poky/n6x/203/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-nm

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: libTest3_cshared.so

# Tool invocations
libTest3_cshared.so: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GCC C Linker'
	$(CC) -shared -o "libTest3_cshared.so" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(LIBRARIES)$(OBJS)$(C_DEPS) libTest3_cshared.so
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
