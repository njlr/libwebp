cxx_library(
  name = 'imageio',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('imageio', '*.h'),
  ]),
  srcs = glob([
    'imageio/*.c',
  ]),
)

cxx_library(
  name = 'libwebp',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.c',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = [
    ':imageio',
  ],
)
