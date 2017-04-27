macos_sources = [
  'lib/RemoteryMetal.mm',
]

cxx_library(
  name = 'remotery',
  header_namespace = '',
  exported_headers = {
    'Remotery.h': 'lib/Remotery.h',
  },
  srcs = [
    'lib/Remotery.c',
  ],
  platform_srcs = [
    ('^macos.*', macos_sources),
  ],
  visibility = [
    'PUBLIC',
  ],
)
