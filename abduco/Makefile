# $OpenBSD: Makefile,v 1.19 2019/07/12 20:47:49 sthen Exp $

COMMENT=		provides session management

V=				0.6
DISTNAME=		abduco-${V}
CATEGORIES=		misc
REVISION=		0

HOMEPAGE=		http://www.brain-dump.org/projects/abduco/

# MIT/X
PERMIT_PACKAGE=	Yes

WANTLIB += c curses util

MASTER_SITES=		${HOMEPAGE}

NO_TEST=     		Yes

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/abduco ${PREFIX}/bin
	${INSTALL_MAN} ${WRKSRC}/abduco.1 ${PREFIX}/man/man1

.include <bsd.port.mk>
