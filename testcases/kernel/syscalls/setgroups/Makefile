# SPDX-License-Identifier: GPL-2.0-or-later
# Copyright (c) International Business Machines  Corp., 2001

top_srcdir		?= ../../../..

# Remove after rewriting setgroups04.c to the new API.
USE_LEGACY_COMPAT_16_H := 1

include $(top_srcdir)/include/mk/testcases.mk
include $(abs_srcdir)/../utils/compat_16.mk
include $(top_srcdir)/include/mk/generic_leaf_target.mk
