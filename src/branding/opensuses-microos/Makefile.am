microosbrandingdir = $(datadir)/cockpit/branding/opensuse-microos

microosbranding_DATA = \
	src/branding/opensuse-microos/branding.css \
	$(NULL)

EXTRA_DIST += $(microosbranding_DATA)

install-data-hook::
	$(LN_S) -f /usr/share/wallpapers/default-1920x1200.jpg $(DESTDIR)$(microosbrandingdir)/default-1920x1200.jpg
	$(LN_S) -f /usr/share/pixmaps/distribution-logos/square-hicolor.svg $(DESTDIR)$(microosbrandingdir)/square-hicolor.svg
