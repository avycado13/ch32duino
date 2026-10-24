CH32FUN_DIR ?= ../ch32fun

TARGET := main
TARGET_MCU := CH32V203
TARGET_MCU_PACKAGE := CH32V203C8T6

.PHONY: all flash clean
all: build

include $(CH32FUN_DIR)/ch32fun/ch32fun.mk

flash: cv_flash
clean: cv_clean
