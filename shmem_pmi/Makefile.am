# -*- Makefile -*-
#
# Copyright 2011 Sandia Corporation. Under the terms of Contract
# DE-AC04-94AL85000 with Sandia Corporation, the U.S.  Government
# retains certain rights in this software.
# 
# Copyright (c) 2015 Intel Corporation. All rights reserved.
#
# This file is part of the Sandia OpenSHMEM software package. For license
# information, see the LICENSE file in the top level directory of the
# distribution.
#

ACLOCAL_AMFLAGS = -I config

AM_CPPFLAGS= -I$(top_srcdir)/shmem_pmi

lib_LTLIBRARIES = libshmem_pmi.la
libshmem_pmi_la_SOURCES = \
	simple_pmi.c \
	simple_pmiutil.c \
	simple_pmiutil.h \
	pmi.h
