
lib_LTLIBRARIES = libgstinferencebaseoverlay-@GST_API_VERSION@.la

libgstinferencebaseoverlay_@GST_API_VERSION@_la_SOURCES=	\
	gstinferencebaseoverlay.cc

libgstinferencebaseoverlay_@GST_API_VERSION@_la_CFLAGS=	\
	$(GST_CFLAGS)				\
	$(GST_BASE_CFLAGS)			\
	$(GST_PLUGINS_BASE_CFLAGS)		\
	$(OPENCV_CFLAGS)			\
	$(R2INFERENCE_CFLAGS)

libgstinferencebaseoverlay_@GST_API_VERSION@_la_CXXFLAGS=	\
	$(GST_CFLAGS)				\
	$(GST_BASE_CFLAGS)			\
	$(GST_PLUGINS_BASE_CFLAGS)		\
	$(OPENCV_CFLAGS)			\
	$(R2INFERENCE_CFLAGS)			\
	-std=c++11

libgstinferencebaseoverlay_@GST_API_VERSION@_la_LIBADD=	\
	$(GST_LIBS)				\
	$(GST_BASE_LIBS)			\
	-lgstvideo-@GST_API_VERSION@		\
	$(GST_PLUGINS_BASE_LIBS)		\
	$(OPENCV_LIBS)			\
	$(R2INFERENCE_LIBS)

gstinferencebaseoverlayincludedir=@includedir@/gstreamer-@GST_API_VERSION@/gst/opencv/

gstinferencebaseoverlayinclude_HEADERS=	\
	gstinferencebaseoverlay.h
