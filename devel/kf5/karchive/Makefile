# $OpenBSD: Makefile,v 1.4 2017/07/27 09:34:37 sthen Exp $

COMMENT =		Qt5-based API for manipulating file archives
DISTNAME =		karchive-${VERSION}

SHARED_LIBS =		KF5Archive		3.0

WANTLIB =		${COMPILER_LIBCXX} Qt5Core bz2 lzma m z

LIB_DEPENDS =		archivers/xz \
			archivers/bzip2

PORTHOME =	${WRKDIR}
.include <bsd.port.mk>
