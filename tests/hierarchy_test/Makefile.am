noinst_PROGRAMS += hierarchy_test

hierarchy_test_sources = %D%/main.cxx
hierarchy_test_SOURCES = $(hierarchy_test_sources)

hierarchy_test_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += hierarchy_testU
hierarchy_testU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
hierarchy_testU_SOURCES = $(hierarchy_test_sources)
hierarchy_testU_LDADD = $(liblog4cplusU_la_file)
endif
