# Created by:	marcus@FreeBSD.org
# $FreeBSD: head/www/mod_php56/Makefile 367268 2014-09-04 14:24:25Z ale $

CATEGORIES=	www devel
PKGNAMEPREFIX=	mod_

MAINTAINER=	miwi@FreeBSD.org

PHP_PORT=	lang/php70
MASTERDIR=	${.CURDIR}/../../${PHP_PORT}

OPTIONS_DEFINE=	AP2FILTER
AP2FILTER_DESC=	Use Apache 2.x filter interface (experimental)
OPTIONS_EXCLUDE=	CGI CLI FPM EMBED

.include "${MASTERDIR}/Makefile"
