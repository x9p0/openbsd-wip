# $OpenBSD: Makefile,v 1.5 2017/07/27 09:34:37 sthen Exp $

COMMENT =		Qt wrapper for BlueZ 5 DBus API
DISTNAME =		bluez-qt-${VERSION}

SHARED_LIBS =		KF5BluezQt		3.0

WANTLIB = ${COMPILER_LIBCXX} Qt5Core Qt5DBus Qt5Network Qt5Qml m

LIB_DEPENDS =		x11/qt5/qtdeclarative

TEST_IS_INTERACTIVE =	X11

.include <bsd.port.mk>
