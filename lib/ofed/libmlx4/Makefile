_spath=	${SRCTOP}/contrib/ofed/libmlx4
.PATH: ${_spath}

SHLIBDIR?=	/usr/lib
LIB=		mlx4
SHLIB_MAJOR=	1

SRCS= \
buf.c \
cq.c \
dbrec.c \
mlx4.c \
qp.c \
srq.c \
verbs.c

LIBADD=		ibverbs pthread
CFLAGS+=	-I${_spath}

.include <bsd.lib.mk>
