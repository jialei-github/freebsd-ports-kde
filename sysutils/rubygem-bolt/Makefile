# $FreeBSD$

PORTNAME=	bolt
PORTVERSION=	2.31.0
CATEGORIES=	sysutils rubygems
MASTER_SITES=	RG

MAINTAINER=	puppet@FreeBSD.org
COMMENT=	Execute commands remotely over SSH and WinRM

LICENSE=	APACHE20

RUN_DEPENDS=	puppet:sysutils/puppet6 \
		r10k:sysutils/rubygem-r10k \
		rubygem-addressable>=2.5:www/rubygem-addressable \
		rubygem-aws-sdk-ec2>1:devel/rubygem-aws-sdk-ec2 \
		rubygem-CFPropertyList>=2.2:devel/rubygem-CFPropertyList \
		rubygem-concurrent-ruby>=1.0:devel/rubygem-concurrent-ruby \
		rubygem-hiera-eyaml>=3:sysutils/rubygem-hiera-eyaml \
		rubygem-jwt>=2.2:www/rubygem-jwt \
		rubygem-logging>=2.2:devel/rubygem-logging \
		rubygem-net-scp>=1.2:security/rubygem-net-scp \
		rubygem-net-ssh>=4.0:security/rubygem-net-ssh \
		rubygem-net-ssh-krb>=0.5:security/rubygem-net-ssh-krb \
		rubygem-orchestrator_client>=0.4:net/rubygem-orchestrator_client \
		rubygem-paint>=2.2:devel/rubygem-paint \
		rubygem-puppet-resource_api>=1.8.1:devel/rubygem-puppet-resource_api \
		rubygem-puppet-strings>=2.3:textproc/rubygem-puppet-strings \
		rubygem-puppetfile-resolver>=0.1:sysutils/rubygem-puppetfile-resolver \
		rubygem-ruby_smb>=1.0:net/rubygem-ruby_smb \
		rubygem-terminal-table>=1.8:textproc/rubygem-terminal-table \
		rubygem-winrm-fs>=1.3:sysutils/rubygem-winrm-fs \
		rubygem-winrm>=2.0:sysutils/rubygem-winrm

USES=		gem shebangfix
USE_RUBY=	yes

ruby_OLD_CMD+=	/opt/puppetlabs/puppet/bin/ruby
SHEBANG_FILES=	libexec/*

PLIST_FILES=	bin/bolt

.include <bsd.port.mk>
