# BEGIN COPYRIGHT BLOCK
# Copyright (C) 2005 Red Hat, Inc.
# All rights reserved.
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation version
# 2.1 of the License.
#
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
#
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
# END COPYRIGHT BLOCK

# Process this file with automake to create Makefile.in.

SUBDIRS = src/libckyapplet src/coolkey 

if BUILD_PK11INSTALL
SUBDIRS += src/install
endif

ACLOCAL_AMFLAGS = -I m4

EXTRA_DIST = cookey.spec LICENSE

DISTCLEANFILES = 

AUTOMAKE_OPTIONS = foreign


