# $FreeBSD$

PORTNAME=        vlc
PORTVERSION=     3.0.6108
CATEGORIES=      python
PKGNAMEPREFIX=   ${PYTHON_PKGNAMEPREFIX}

MAINTAINER=      hukadan@protonmail.com
COMMENT=         VLC bindings for python

LICENSE=         LGPL21+
LICENSE_FILE=    ${WRKSRC}/COPYING

USES=            python
USE_PYTHON=      autoplist concurrent distutils allflavors
USE_GITHUB=      yes
GH_ACCOUNT=      oaubert
GH_PROJECT=      python-vlc
GH_TAGNAME=      fff0541

NO_ARCH=         yes

WRKSRC_SUBDIR=          generated/3.0/
PYDISTUTILS_PKGNAME=    python-vlc

.include <bsd.port.mk>
