# $FreeBSD$

PORTNAME=        vlc
PORTVERSION=     3.0.6108
CATEGORIES=      python
PKGNAMEPREFIX=   ${PYTHON_PKGNAMEPREFIX}

USE_GITHUB=      yes
GH_ACCOUNT=      oaubert 
GH_PROJECT=      python-vlc
GH_TAGNAME=      fff0541

MAINTAINER=      hukadan@protonmail.com
COMMENT=         ctypes-based bindings for the native libvlc API of the VLC video player. 
LICENSE=         LGPL21+ 

NO_ARCH=         yes
USES=            python
USE_PYTHON=      autoplist concurrent distutils allflavors

WRKSRC_SUBDIR=          generated/3.0/
PYDISTUTILS_PKGNAME=    python-vlc

.include <bsd.port.mk>
