################################################################################
# Automatically-generated file. Do not edit!
################################################################################


RM := rm -rf

USER_OBJS :=

LIBS := 
PROJ := 

O_SRCS := 
C_SRCS := 
S_SRCS := 
S_UPPER_SRCS := 
OBJ_SRCS := 
ASM_SRCS := 
PREPROCESSING_SRCS := 
OBJS := 
OBJS_AS_ARGS := 
C_DEPS := 
C_DEPS_AS_ARGS := 
EXECUTABLES := 
LIB_AS_ARGS :=
OUTPUT_FILE_PATH :=
OUTPUT_FILE_PATH_AS_ARGS :=
HEX_FLASH_FILE_PATH :=
HEX_FLASH_FILE_PATH_AS_ARGS :=
HEX_EEPROM_FILE_PATH :=
HEX_EEPROM_FILE_PATH_AS_ARGS :=
LSS_FILE_PATH :=
LSS_FILE_PATH_AS_ARGS :=
MAP_FILE_PATH :=
MAP_FILE_PATH_AS_ARGS :=
AVR_APP_PATH :=C:/Program Files/Atmel/AVR Studio 5.0/AVR ToolChain/bin/
QUOTE := "
ADDITIONAL_DEPENDENCIES:=
OUTPUT_FILE_DEP:=

# Every subdirectory with source files must be described here
SUBDIRS :=  \
../src/ \
../src/asf/ \
../src/asf/common/ \
../src/asf/common/boards/ \
../src/asf/common/services/ \
../src/asf/common/services/clock/ \
../src/asf/common/services/clock/xmega/ \
../src/asf/common/services/gpio/ \
../src/asf/common/services/gpio/xmega_ioport/ \
../src/asf/common/utils/ \
../src/asf/common/utils/interrupt/ \
../src/asf/common/utils/make/ \
../src/asf/xmega/ \
../src/asf/xmega/boards/ \
../src/asf/xmega/boards/stk600/ \
../src/asf/xmega/boards/stk600/rc100x/ \
../src/asf/xmega/drivers/ \
../src/asf/xmega/drivers/cpu/ \
../src/asf/xmega/drivers/ioport/ \
../src/asf/xmega/utils/ \
../src/asf/xmega/utils/assembler/ \
../src/asf/xmega/utils/bit_handling/ \
../src/asf/xmega/utils/preprocessor/ \
../src/config/


# Add inputs and outputs from these tool invocations to the build variables 
C_SRCS +=  \
../src/asf/common/services/clock/xmega/sysclk.c \
../src/asf/xmega/boards/stk600/rc100x/init.c \
../src/asf/xmega/drivers/ioport/ioport.c \
../src/led_example.c


PREPROCESSING_SRCS +=  \
../src/asf/xmega/drivers/cpu/ccp.s


ASM_SRCS += 


OBJS +=  \
src/asf/common/services/clock/xmega/sysclk.o \
src/asf/xmega/boards/stk600/rc100x/init.o \
src/asf/xmega/drivers/cpu/ccp.o \
src/asf/xmega/drivers/ioport/ioport.o \
src/led_example.o


OBJS_AS_ARGS +=  \
src/asf/common/services/clock/xmega/sysclk.o \
src/asf/xmega/boards/stk600/rc100x/init.o \
src/asf/xmega/drivers/cpu/ccp.o \
src/asf/xmega/drivers/ioport/ioport.o \
src/led_example.o


C_DEPS +=  \
src/asf/common/services/clock/xmega/sysclk.d \
src/asf/xmega/boards/stk600/rc100x/init.d \
src/asf/xmega/drivers/ioport/ioport.d \
src/led_example.d


C_DEPS_AS_ARGS +=  \
src/asf/common/services/clock/xmega/sysclk.d \
src/asf/xmega/boards/stk600/rc100x/init.d \
src/asf/xmega/drivers/ioport/ioport.d \
src/led_example.d


OUTPUT_FILE_PATH +=LED_CHASER1.elf

OUTPUT_FILE_PATH_AS_ARGS +=LED_CHASER1.elf

HEX_FLASH_FILE_PATH +=LED_CHASER1.hex

HEX_FLASH_FILE_PATH_AS_ARGS +=LED_CHASER1.hex

HEX_EEPROM_FILE_PATH +=LED_CHASER1.eep

HEX_EEPROM_FILE_PATH_AS_ARGS +=LED_CHASER1.eep

LSS_FILE_PATH +=LED_CHASER1.lss

LSS_FILE_PATH_AS_ARGS +=LED_CHASER1.lss

MAP_FILE_PATH =LED_CHASER1.map

MAP_FILE_PATH_AS_ARGS =LED_CHASER1.map

LIB_AS_ARGS +=libLED_CHASER1.a

ADDITIONAL_DEPENDENCIES:= size

OUTPUT_FILE_DEP:= ./makedep.mk

# AVR/GNU C Compiler









src/asf/common/services/clock/xmega/%.o: ../src/asf/common/services/clock/xmega/%.c
	@echo Building file: $<
	@echo Invoking: AVR/GNU C Compiler
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -DBOARD=STK600_RC100X  -I"../src" -I"../src/asf/common/applications/led_chaser/atxmega128a1_stk600" -I"../src/asf/common/boards" -I"../src/asf/common/services/clock" -I"../src/asf/common/services/gpio" -I"../src/asf/common/utils" -I"../src/asf/xmega/boards" -I"../src/asf/xmega/boards/stk600/rc100x" -I"../src/asf/xmega/drivers/cpu" -I"../src/asf/xmega/drivers/ioport" -I"../src/asf/xmega/utils" -I"../src/asf/xmega/utils/preprocessor" -I"../src/config"  -O1 -fdata-sections -ffunction-sections -g3 -Wall -c -std=gnu99 -Wstrict-prototypes -Wmissing-prototypes -Werror-implicit-function-declaration -Wpointer-arith -mrelax  -mmcu=atxmega128a1   -MD -MP -MF"$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -o"$@" "$<"
	@echo Finished building: $<

src/asf/xmega/boards/stk600/rc100x/%.o: ../src/asf/xmega/boards/stk600/rc100x/%.c
	@echo Building file: $<
	@echo Invoking: AVR/GNU C Compiler
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -DBOARD=STK600_RC100X  -I"../src" -I"../src/asf/common/applications/led_chaser/atxmega128a1_stk600" -I"../src/asf/common/boards" -I"../src/asf/common/services/clock" -I"../src/asf/common/services/gpio" -I"../src/asf/common/utils" -I"../src/asf/xmega/boards" -I"../src/asf/xmega/boards/stk600/rc100x" -I"../src/asf/xmega/drivers/cpu" -I"../src/asf/xmega/drivers/ioport" -I"../src/asf/xmega/utils" -I"../src/asf/xmega/utils/preprocessor" -I"../src/config"  -O1 -fdata-sections -ffunction-sections -g3 -Wall -c -std=gnu99 -Wstrict-prototypes -Wmissing-prototypes -Werror-implicit-function-declaration -Wpointer-arith -mrelax  -mmcu=atxmega128a1   -MD -MP -MF"$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -o"$@" "$<"
	@echo Finished building: $<

src/asf/xmega/drivers/ioport/%.o: ../src/asf/xmega/drivers/ioport/%.c
	@echo Building file: $<
	@echo Invoking: AVR/GNU C Compiler
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -DBOARD=STK600_RC100X  -I"../src" -I"../src/asf/common/applications/led_chaser/atxmega128a1_stk600" -I"../src/asf/common/boards" -I"../src/asf/common/services/clock" -I"../src/asf/common/services/gpio" -I"../src/asf/common/utils" -I"../src/asf/xmega/boards" -I"../src/asf/xmega/boards/stk600/rc100x" -I"../src/asf/xmega/drivers/cpu" -I"../src/asf/xmega/drivers/ioport" -I"../src/asf/xmega/utils" -I"../src/asf/xmega/utils/preprocessor" -I"../src/config"  -O1 -fdata-sections -ffunction-sections -g3 -Wall -c -std=gnu99 -Wstrict-prototypes -Wmissing-prototypes -Werror-implicit-function-declaration -Wpointer-arith -mrelax  -mmcu=atxmega128a1   -MD -MP -MF"$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -o"$@" "$<"
	@echo Finished building: $<

src/%.o: ../src/%.c
	@echo Building file: $<
	@echo Invoking: AVR/GNU C Compiler
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -DBOARD=STK600_RC100X  -I"../src" -I"../src/asf/common/applications/led_chaser/atxmega128a1_stk600" -I"../src/asf/common/boards" -I"../src/asf/common/services/clock" -I"../src/asf/common/services/gpio" -I"../src/asf/common/utils" -I"../src/asf/xmega/boards" -I"../src/asf/xmega/boards/stk600/rc100x" -I"../src/asf/xmega/drivers/cpu" -I"../src/asf/xmega/drivers/ioport" -I"../src/asf/xmega/utils" -I"../src/asf/xmega/utils/preprocessor" -I"../src/config"  -O1 -fdata-sections -ffunction-sections -g3 -Wall -c -std=gnu99 -Wstrict-prototypes -Wmissing-prototypes -Werror-implicit-function-declaration -Wpointer-arith -mrelax  -mmcu=atxmega128a1   -MD -MP -MF"$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -o"$@" "$<"
	@echo Finished building: $<



# AVR/GNU Assembler

src/asf/xmega/drivers/cpu/%.o: ../src/asf/xmega/drivers/cpu/%.s
	@echo Building file: $<
	@echo Invoking: AVR/GNU Assembler
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -Wa,-gdwarf2 -x assembler-with-cpp -c -mrelax -I "../src" -I "../src/asf/common/applications/led_chaser/atxmega128a1_stk600" -I "../src/asf/common/boards" -I "../src/asf/common/services/clock" -I "../src/asf/common/services/gpio" -I "../src/asf/common/utils" -I "../src/asf/xmega/boards" -I "../src/asf/xmega/boards/stk600/rc100x" -I "../src/asf/xmega/drivers/cpu" -I "../src/asf/xmega/drivers/ioport" -I "../src/asf/xmega/utils" -I "../src/asf/xmega/utils/preprocessor" -I "../src/config"   -mmcu=atxmega128a1   -o"$@" "$<"
	@echo Finished building: $<




ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: $(OUTPUT_FILE_PATH) $(ADDITIONAL_DEPENDENCIES)

# AVR/GNU C/C++ Linker
$(OUTPUT_FILE_PATH): $(OBJS) $(USER_OBJS) $(OUTPUT_FILE_DEP)
	@echo Building target: $@
	@echo Invoking: AVR/GNU C/C++ Linker
	$(QUOTE)$(AVR_APP_PATH)avr-gcc.exe$(QUOTE) -Wl,--gc-sections -mrelax -Wl,--relax  -mmcu=atxmega128a1   -o$(OUTPUT_FILE_PATH_AS_ARGS) $(OBJS_AS_ARGS) $(USER_OBJS) $(LIBS)
	@echo Finished building target: $@



$(HEX_FLASH_FILE_PATH): $(OUTPUT_FILE_PATH)
	$(QUOTE)$(AVR_APP_PATH)avr-objcopy.exe$(QUOTE) -O ihex -R .eeprom -R .fuse -R .lock -R .signature  $(QUOTE)$<$(QUOTE) $(QUOTE)$@$(QUOTE)

$(HEX_EEPROM_FILE_PATH): $(OUTPUT_FILE_PATH)
	-$(QUOTE)$(AVR_APP_PATH)avr-objcopy.exe$(QUOTE) -j .eeprom --set-section-flags=.eeprom=alloc,load --change-section-lma .eeprom=0 --no-change-warnings -O ihex $(QUOTE)$<$(QUOTE) $(QUOTE)$@$(QUOTE) || exit 0

$(LSS_FILE_PATH): $(OUTPUT_FILE_PATH)
	$(QUOTE)$(AVR_APP_PATH)avr-objdump.exe$(QUOTE) -h -S $(QUOTE)$<$(QUOTE) > $(QUOTE)$@$(QUOTE)

size: $(OUTPUT_FILE_PATH)
	@$(QUOTE)$(AVR_APP_PATH)avr-size.exe$(QUOTE) -C --mcu=atxmega128a1 $(OUTPUT_FILE_PATH_AS_ARGS)

# Other Targets
clean:
	-$(RM) $(OBJS_AS_ARGS)$(C_DEPS_AS_ARGS) $(EXECUTABLES) $(LIB_AS_ARGS) $(HEX_FLASH_FILE_PATH_AS_ARGS) $(HEX_EEPROM_FILE_PATH_AS_ARGS) $(LSS_FILE_PATH_AS_ARGS) $(MAP_FILE_PATH_AS_ARGS)

