.PATH:		${.CURDIR}/..

PROG=		login_otp
SRCS=		login_otp.c login_passwd.c
MAN=		login_otp.8

LDADD=		-lutil
DPADD=		${LIBUTIL}

BINDIR=		/usr/libexec/auth

LINKS=		${BINDIR}/${PROG} ${BINDIR}/login_totp \
		${BINDIR}/${PROG} ${BINDIR}/login_hotp \
		${BINDIR}/${PROG} ${BINDIR}/login_otp_only \
		${BINDIR}/${PROG} ${BINDIR}/login_totp_only \
		${BINDIR}/${PROG} ${BINDIR}/login_hotp_only

.include <bsd.prog.mk>
