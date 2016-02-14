# Created by: John Chen <johnpupu@gmail.com>
# $FreeBSD$

PORTNAME=	APCu
PORTVERSION=	5.1.3
CATEGORIES=	devel
MASTER_SITES=	http://pecl.php.net/get/
PKGNAMEPREFIX=	pecl-
PKGNAMESUFFIX=	-php7
DISTNAME=	${PORTNAME:tl}-${PORTVERSION}
DIST_SUBDIR=	PECL

MAINTAINER=	johnpupu@gmail.com
COMMENT=	APC User Caching

LICENSE=	PHP301

CONFLICTS=	pecl-APC-[0-9]*

CFLAGS+=	-I${LOCALBASE}/include
USE_PHP=	yes
USE_PHP_BUILD=	yes
USE_PHPIZE=	yes
USE_PHPEXT=	yes
USES=		tar:tgz
IGNORE_WITH_PHP=	55 56
PHP_MODNAME=	${PORTNAME:tl}
WRKSRC=		${WRKDIR}/${PORTNAME:tl}-${PORTVERSION}

.include <bsd.port.mk>
