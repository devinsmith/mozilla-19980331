#! gmake
# The contents of this file are subject to the Netscape Public License
# Version 1.0 (the "NPL"); you may not use this file except in
# compliance with the NPL.  You may obtain a copy of the NPL at
# http://www.mozilla.org/NPL/
#
# Software distributed under the NPL is distributed on an "AS IS" basis,
# WITHOUT WARRANTY OF ANY KIND, either express or implied. See the NPL
# for the specific language governing rights and limitations under the
# NPL.
#
# The Initial Developer of this code under the NPL is Netscape
# Communications Corporation.  Portions created by Netscape are
# Copyright (C) 1998 Netscape Communications Corporation.  All Rights
# Reserved.

DEPTH = ..

# Normally DIRS should contain all sub-dirs, but this
# directory was built to organize code rather than to
# reflect build order.
#
# Thus on the first pass we build the core classes and the
# top-level Makefile will control the order of subsequent
# directories by going directly into the specific directories
#
# The proper way to do this would be to introduce different
# stages into the java code build cycle, but that has the
# potential to introduce too many changes
#
# This is necessary to break circular dependencies the logical
# tree directory structure would otherwise introduce.
#
# See top-level makefile for details
#

DIRS = src jsj tests

include $(DEPTH)/config/rules.mk
