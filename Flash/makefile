################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := c:/ti/ccsv6/tools/compiler/c2000_6.2.8

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./Sin256Q15.obj" \
"./VoiceModule.obj" \
"C:/ti/controlSUITE/development_kits/C2000_LaunchPad/f2802x_headers/cmd/F2802x_Headers_nonBIOS.cmd" \
"C:/ti/controlSUITE/development_kits/C2000_LaunchPad/f2802x_common/lib/driverlib.lib" \
-l"C:/ti/controlSUITE/development_kits/C2000_LaunchPad/f2802x_examples/C2kLaunchPadDemo/../../f2802x_common/cmd/F28027.cmd" \
-l"rts2800_ml.lib" \
-l"IQmath.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
VoiceModule.out \

EXE_OUTPUTS__QUOTED += \
"VoiceModule.out" \

BIN_OUTPUTS += \
VoiceModule.hex \

BIN_OUTPUTS__QUOTED += \
"VoiceModule.hex" \


# All Target
all: VoiceModule.out

# Tool invocations
VoiceModule.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: C2000 Linker'
	"c:/ti/ccsv6/tools/compiler/c2000_6.2.8/bin/cl2000" -v28 -ml -mt -O0 -g --define="_FLASH" --define=NDEBUG --define="_DEBUG" --define="LARGE_MODEL" --quiet --verbose_diagnostics --diag_warning=225 --gen_func_subsections=on --output_all_syms --cdebug_asm_data -z -m"VoiceModule.map" --heap_size=0x200 --stack_size=0x300 --warn_sections -i"c:/ti/ccsv6/tools/compiler/c2000_6.2.8/lib" -i"c:/ti/ccsv6/tools/compiler/c2000_6.2.8/include" -i"C:/Users/Edward/Documents/CodeComposerWorkspace_v6_0/VoiceModule" -i"C:/ti/controlSUITE/development_kits/C2000_LaunchPad/F2802x_common/lib" --reread_libs --verbose_diagnostics --issue_remarks --xml_link_info="VoiceModule_linkInfo.xml" --entry_point=code_start --rom_model -o "VoiceModule.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

VoiceModule.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: C2000 Hex Utility'
	"c:/ti/ccsv6/tools/compiler/c2000_6.2.8/bin/hex2000"  -o "VoiceModule.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "Sin256Q15.pp" "VoiceModule.pp" 
	-$(RM) "Sin256Q15.obj" "VoiceModule.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

