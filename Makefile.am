#
# aide, Advanced Intrusion Detection Environment
# 
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; see the file COPYING.  If not, write to
# the Free Software Foundation, 59 Temple Place - Suite 330,
# Boston, MA 02111-1307, USA.
#

SUBDIRS = include src doc

datadir = @datadir@
localedir = $(datadir)/locale
DEFS = -DLOCALEDIR=\"$(localedir)\" @DEFS@

CLEANFILES = *~

EXTRA_DIST = version.m4 AUTHORS ChangeLog INSTALL README Todo \
	contrib/bzip2.sh contrib/gpg2_check.sh contrib/gpg2_update.sh \
	contrib/gpg_check.sh contrib/gpg_update.sh contrib/sshaide.sh \
	contrib/aide-attributes.sh

