PORTNAME=	octopkg-tui
DISTVERSION=	0.1.0
CATEGORIES=	ports-mgmt

MAINTAINER=	cleber@cloudbsd.com.br
COMMENT=	Terminal UI for pkg(8), companion of OctoPkg
WWW=		https://github.com/cleberalves40/octopkg-tui

LICENSE=	GPLv2+
LICENSE_FILE=	${WRKSRC}/LICENSE

BUILD_DEPENDS=	ftxui>=6.1.9:devel/ftxui
LIB_DEPENDS=	libftxui-component.so:devel/ftxui

USES=		cmake:ninja compiler:c++17-lang
USE_GITHUB=	yes
GH_ACCOUNT=	cleberalves40
GH_PROJECT=	octopkg-tui
GH_TAGNAME=	v0.1.0

.include <bsd.port.mk>
