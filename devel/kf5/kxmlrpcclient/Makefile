# $OpenBSD: Makefile,v 1.3 2017/07/27 09:34:38 sthen Exp $

COMMENT =	KDE XML-RPC client
DISTNAME =	kxmlrpcclient-${VERSION}

SHARED_LIBS =	KF5XmlRpcClient		2.0

WANTLIB += ${COMPILER_LIBCXX} KF5ConfigCore KF5CoreAddons KF5I18n
WANTLIB += KF5KIOCore KF5Service Qt5Core Qt5Xml

BUILD_DEPENDS =	devel/gettext-tools

LIB_DEPENDS =	devel/kf5/ki18n \
		devel/kf5/kio

.include <bsd.port.mk>
