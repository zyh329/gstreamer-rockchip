plugin_LTLIBRARIES = libeglgles.la

libeglgles_la_SOURCES =				\
	gsteglglessink.c			\
	gstegladaptation.c			\
	gstegladaptation_egl.c			\
	video_platform_wrapper.c		\
	egl.c					\
	$(NULL)

libeglgles_la_CFLAGS =				\
	$(X11_CFLAGS)				\
	$(ARMMALI_CFLAGS)			\
	$(GST_PLUGINS_BASE_CFLAGS)		\
	$(GST_BASE_CFLAGS)			\
	$(GST_VIDEO_CFLAGS)			\
	$(GST_ALLOCATORS_CFLAGS)                \
	$(GST_CFLAGS)				\
	$(NULL)

libeglgles_la_LIBADD =				\
	$(X11_LIBS)				\
	$(ARMMALI_LIBS)				\
	$(GST_PLUGINS_BASE_LIBS)		\
	$(GST_BASE_LIBS)			\
	$(GST_VIDEO_LIBS)                       \
	$(GST_ALLOCATORS_LIBS)                  \
	$(GST_LIBS)				\
	$(NULL)

libeglgles_la_LDFLAGS =				\
	$(GST_PLUGIN_LDFLAGS)			\
	$(NULL)
