ADD_SUBDIRECTORY(F77)
ADD_SUBDIRECTORY(F90)

SET(CUR_EXTRA_DIST CMakeLists.txt Makefile.am)
ADD_EXTRA_DIST("${CUR_EXTRA_DIST}")
