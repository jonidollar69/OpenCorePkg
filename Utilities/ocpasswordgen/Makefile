## @file
# Copyright (c) 2020, Marvin Haeuser. All rights reserved.
# SPDX-License-Identifier: BSD-3-Clause
##

PROJECT = ocpasswordgen
PRODUCT = $(PROJECT)$(INFIX)$(SUFFIX)
OBJS    = $(PROJECT).o
#
# OcCryptoLib targets.
#
OBJS   += PasswordHash.o

VPATH   = ../../Library/OcCryptoLib
include ../../User/Makefile
