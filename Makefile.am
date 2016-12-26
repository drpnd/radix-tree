#
# Copyright (c) 2016 Hirochika Asai.
# All rights reserved.
#
# Authors:
#      Hirochika Asai  <asai@jar.jp>
#

bin_PROGRAMS = radix_test_basic
radix_test_basic_SOURCES = tests/basic.c radix.c radix.h

CLEANFILES = *~

test: all
	@echo "Testing all..."
	$(top_builddir)/radix_test_basic
