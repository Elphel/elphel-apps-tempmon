PROGS      =
PHPCLI     =
CONFIGS    =

SRCS = imgsrv.py
OBJS =

INSTALL    = install
INSTMODE   = 0755
INSTDOCS   = 0644

OWN = -o root -g root

CFLAGS     =

SYSCONFDIR = /etc
BINDIR     = /usr/bin
WWW_PAGES  = /www/pages

all:

install:
	$(INSTALL) $(OWN) -d $(DESTDIR)$(BINDIR)
	$(INSTALL) $(OWN) -m $(INSTMODE) $(SRCS)   $(DESTDIR)$(BINDIR)

clean:
	@echo "Nothing to clean"