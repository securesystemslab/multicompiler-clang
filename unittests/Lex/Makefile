##===- unittests/Lex/Makefile ------------------------------*- Makefile -*-===##
#
#                     The LLVM Compiler Infrastructure
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
##===----------------------------------------------------------------------===##

CLANG_LEVEL = ../..
TESTNAME = Lex
LINK_COMPONENTS := $(TARGETS_TO_BUILD) asmparser bitreader support mc mcparser multicompiler option
USEDLIBS = clangParse.a clangSema.a clangAnalysis.a clangEdit.a \
	clangSerialization.a clangAST.a clangLex.a clangBasic.a 

include $(CLANG_LEVEL)/unittests/Makefile
