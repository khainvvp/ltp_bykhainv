# SPDX-License-Identifier: GPL-2.0-or-later
# Copyright (c) 2017 Linux Test Project

top_srcdir		?= ../../../..

include $(top_srcdir)/include/mk/testcases.mk

CFLAGS			+= -D_GNU_SOURCE -pthread
read_all: LDLIBS+=-lrt

include $(top_srcdir)/include/mk/generic_leaf_target.mk
