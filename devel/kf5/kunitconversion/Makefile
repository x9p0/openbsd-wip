# $OpenBSD: Makefile,v 1.4 2017/07/27 09:34:38 sthen Exp $

COMMENT =	KDE framework for converting physical units
DISTNAME =	kunitconversion-${VERSION}

SHARED_LIBS =	KF5UnitConversion	3.0

WANTLIB += ${COMPILER_LIBCXX} KF5I18n Qt5Core Qt5Network Qt5Xml
WANTLIB += m

BUILD_DEPENDS =	devel/gettext-tools

LIB_DEPENDS =	devel/kf5/ki18n

# for tests
PORTHOME =	${WRKDIR}

.include <bsd.port.mk>
