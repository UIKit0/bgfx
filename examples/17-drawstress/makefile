#
# Copyright 2011-2014 Branimir Karadzic. All rights reserved.
# License: http://www.opensource.org/licenses/BSD-2-Clause
#

include ../../premake/shader-embeded.mk

rebuild:
	@make -s --no-print-directory clean all
	@bin2c -c --name s_droidSansTtf ../runtime/font/droidsans.ttf > droidsans.ttf.h
