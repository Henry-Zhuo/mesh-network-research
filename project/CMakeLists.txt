build_lib_example(
  NAME mesh-modified
  SOURCE_FILES mesh-modified.cc
  LIBRARIES_TO_LINK
    ${libinternet}
    ${libmobility}
    ${libwifi}
    ${libmesh}
    ${libapplications}
    ${libbuildings}
)
