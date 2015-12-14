# Created by: Martin Wilke <miwi@FreeBSD.org>
# $FreeBSD$

PORTNAME=	jaraco.itertools
PORTVERSION=	1.7
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	miwi@FreeBSD.org
COMMENT=	Fix ME

LICENSE=	MIT

BUILD_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pytest-runner>0:${PORTSDIR}/devel/py-pytest-runner \
		${PYTHON_PKGNAMEPREFIX}setuptools_scm>0:${PORTSDIR}/devel/py-setuptools_scm \
		${PYTHON_PKGNAMEPREFIX}more-itertools>0:${PORTSDIR}/devel/py-more-itertools

USES=		python
USE_PYTHON=	distutils autoplist
NO_ARCH=	yes

.include <bsd.port.mk>
