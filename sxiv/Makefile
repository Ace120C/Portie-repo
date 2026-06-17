PORTNAME =					sxiv
COMMENT =						Simple X Image Viewer  
VERSION =						master
DISTNAME =					${PORTNAME}-${VERSION}
REVISION =					0

REPO = 							https://github.com/explosion-mental/sxiv
MAINTAINER =				Ace120C <vegetotownley@proton.me>

# GPL-2.0
PERMIT_PACKAGE =		Yes

GH_ACCOUNT =				explosion-mental
GH_PROJECT =				sxiv
GH_COMMIT  =				155c60beffdd8788fb480d7ac3a8e1967b49b988

fetch:
	curl -L ${REPO}/archive/${GH_COMMIT}.tar.gz -o ${DISTNAME}-${GH_COMMIT}.tar.gz
install:
	mkdir -p src
	tar -xf ${DISTNAME}-${GH_COMMIT}.tar.gz -C src --strip-components=1
