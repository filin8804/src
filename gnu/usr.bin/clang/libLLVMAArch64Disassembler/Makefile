# $OpenBSD: Makefile,v 1.4 2020/08/03 14:45:24 patrick Exp $

LIB=	LLVMAArch64Disassembler
NOPROFILE=

CPPFLAGS+=	-I${.OBJDIR}/../include/llvm/AArch64 \
		-I${LLVM_SRCS}/lib/Target/AArch64

SRCS+=	AArch64Disassembler.cpp \
	AArch64ExternalSymbolizer.cpp

.PATH:	${.CURDIR}/../../../llvm/llvm/lib/Target/AArch64/Disassembler
