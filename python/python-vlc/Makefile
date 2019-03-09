# $FreeBSD$

PORTNAME=        python-vlc
PORTVERSION=     3.0.6108
CATEGORIES=      python

USE_GITHUB=      yes
GH_ACCOUNT=      oaubert 
GH_PROJECT=      python-vlc
GH_TAGNAME=      fff0541

MAINTAINER=      hukadan@protonmail.com
COMMENT=         ctypes-based bindings for the native libvlc API of the VLC video player. 
LICENCE=         LGPL21+ 

NO_ARCH=         yes
USES=            python
USE_PYTHON=      autoplist distutils flavors

.if ${FLAVOR:Upy27}
PYSETUP=         generated/2.2/setup.py
.else
PYSETUP=         generated/3.0/setup.py
.endif

.include <bsd.port.mk>
