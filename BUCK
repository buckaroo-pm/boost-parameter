include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'parameter', 
  header_only = True,
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  deps = BUCKAROO_DEPS,
  visibility = [
    'PUBLIC',
  ],
)
