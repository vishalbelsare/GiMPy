#============================================================================#
# This file is part of the GiMPy graph library                               #
#                                                                            #
# GiMPy is distributed under the Eclipse Public License as part of the       #
# COIN-OR repository (http://www.coin-or.org).                               #
#                                                                            #
# Authors: Ayukut Bulut, Lehigh University (ayb211@lehigh.edu)               #
#          Ted Ralphs, Lehigh University (ted@lehigh.edu)                    #
#                                                                            #
#                                                                            #
# Copyright (C) 2013, Lehigh University, Aykut Bulut, and Ted Ralphs         #
# All Rights Reserved.                                                       #
#============================================================================#

AUTOMAKE_OPTIONS = foreign

test: 
	PYTHONPATH=@abs_source_dir@/src:@abs_source_dir@/test \
	${PYTHON} @abs_source_dir@/test/test_algorithms.py

.PHONY: test

