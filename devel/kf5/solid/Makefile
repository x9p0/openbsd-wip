# $OpenBSD: Makefile,v 1.5 2017/07/27 09:34:38 sthen Exp $

COMMENT =	KDE hardware abstraction layer
DISTNAME =	solid-${VERSION}

SHARED_LIBS =	KF5Solid		3.0

WANTLIB += ${COMPILER_LIBCXX} Qt5Core Qt5DBus Qt5Gui Qt5Network
WANTLIB += Qt5Qml Qt5Widgets Qt5Xml c m

BUILD_DEPENDS =	devel/bison

LIB_DEPENDS =	x11/qt5/qtdeclarative

.include <bsd.port.mk>
