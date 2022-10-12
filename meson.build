project('GStreamerTest', 'cpp')
inc = include_directories('/usr/include/gstreamer-1.0',
'/usr/include/glib-2.0',
'/usr/include/libsoup-2.4',
'/usr/include/json-glib-1.0',
)

dep1 = dependency('glib-2.0')
dep2 = dependency('gstreamer-1.0')
dep3 = dependency('json-glib-1.0')
dep4 = dependency('libsoup-2.4')
dep5 = dependency('gstreamer-sdp-1.0')
dep6 = dependency('gstreamer-webrtc-1.0')


executable('GStreamerTest', 'GStreamerTest.cpp', include_directories : inc, dependencies : [dep1, dep2, dep3, dep4, dep5, dep6])

