include $(top_srcdir)/Makefile.tool.am

noinst_PROGRAMS = 
if VGCONF_PLATFORMS_INCLUDE_X86_LINUX
noinst_PROGRAMS += lackey-x86-linux
endif
if VGCONF_PLATFORMS_INCLUDE_AMD64_LINUX
noinst_PROGRAMS += lackey-amd64-linux
endif
if VGCONF_PLATFORMS_INCLUDE_PPC32_LINUX
noinst_PROGRAMS += lackey-ppc32-linux
endif
if VGCONF_PLATFORMS_INCLUDE_PPC64_LINUX
noinst_PROGRAMS += lackey-ppc64-linux
endif
if VGCONF_PLATFORMS_INCLUDE_PPC32_AIX5
noinst_PROGRAMS += lackey-ppc32-aix5
endif
if VGCONF_PLATFORMS_INCLUDE_PPC64_AIX5
noinst_PROGRAMS += lackey-ppc64-aix5
endif
if VGCONF_PLATFORMS_INCLUDE_X86_DARWIN
noinst_PROGRAMS += lackey-x86-darwin
endif
if VGCONF_PLATFORMS_INCLUDE_AMD64_DARWIN
noinst_PROGRAMS += lackey-amd64-darwin
endif

LACKEY_SOURCES_COMMON = lk_main.c

lackey_x86_linux_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_x86_linux_CPPFLAGS     = $(AM_CPPFLAGS_X86_LINUX)
lackey_x86_linux_CFLAGS       = $(AM_CFLAGS_X86_LINUX)
lackey_x86_linux_DEPENDENCIES = $(COREGRIND_LIBS_X86_LINUX)
lackey_x86_linux_LDADD        = $(TOOL_LDADD_X86_LINUX)
lackey_x86_linux_LDFLAGS      = $(TOOL_LDFLAGS_X86_LINUX)

lackey_amd64_linux_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_amd64_linux_CPPFLAGS     = $(AM_CPPFLAGS_AMD64_LINUX)
lackey_amd64_linux_CFLAGS       = $(AM_CFLAGS_AMD64_LINUX)
lackey_amd64_linux_DEPENDENCIES = $(COREGRIND_LIBS_AMD64_LINUX)
lackey_amd64_linux_LDADD        = $(TOOL_LDADD_AMD64_LINUX)
lackey_amd64_linux_LDFLAGS      = $(TOOL_LDFLAGS_AMD64_LINUX)

lackey_ppc32_linux_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_ppc32_linux_CPPFLAGS     = $(AM_CPPFLAGS_PPC32_LINUX)
lackey_ppc32_linux_CFLAGS       = $(AM_CFLAGS_PPC32_LINUX)
lackey_ppc32_linux_DEPENDENCIES = $(COREGRIND_LIBS_PPC32_LINUX)
lackey_ppc32_linux_LDADD        = $(TOOL_LDADD_PPC32_LINUX)
lackey_ppc32_linux_LDFLAGS      = $(TOOL_LDFLAGS_PPC32_LINUX)

lackey_ppc64_linux_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_ppc64_linux_CPPFLAGS     = $(AM_CPPFLAGS_PPC64_LINUX)
lackey_ppc64_linux_CFLAGS       = $(AM_CFLAGS_PPC64_LINUX)
lackey_ppc64_linux_DEPENDENCIES = $(COREGRIND_LIBS_PPC64_LINUX)
lackey_ppc64_linux_LDADD        = $(TOOL_LDADD_PPC64_LINUX)
lackey_ppc64_linux_LDFLAGS      = $(TOOL_LDFLAGS_PPC64_LINUX)

lackey_ppc32_aix5_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_ppc32_aix5_CPPFLAGS     = $(AM_CPPFLAGS_PPC32_AIX5)
lackey_ppc32_aix5_CFLAGS       = $(AM_CFLAGS_PPC32_AIX5)
lackey_ppc32_aix5_DEPENDENCIES = $(COREGRIND_LIBS_PPC32_AIX5)
lackey_ppc32_aix5_LDADD        = $(TOOL_LDADD_PPC32_AIX5)
lackey_ppc32_aix5_LDFLAGS      = $(TOOL_LDFLAGS_PPC32_AIX5)

lackey_ppc64_aix5_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_ppc64_aix5_CPPFLAGS     = $(AM_CPPFLAGS_PPC64_AIX5)
lackey_ppc64_aix5_CFLAGS       = $(AM_CFLAGS_PPC64_AIX5)
lackey_ppc64_aix5_DEPENDENCIES = $(COREGRIND_LIBS_PPC64_AIX5)
lackey_ppc64_aix5_LDADD        = $(TOOL_LDADD_PPC64_AIX5)
lackey_ppc64_aix5_LDFLAGS      = $(TOOL_LDFLAGS_PPC64_AIX5)

lackey_x86_darwin_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_x86_darwin_CPPFLAGS     = $(AM_CPPFLAGS_X86_DARWIN)
lackey_x86_darwin_CFLAGS       = $(AM_CFLAGS_X86_DARWIN)
lackey_x86_darwin_DEPENDENCIES = $(COREGRIND_LIBS_X86_DARWIN)
lackey_x86_darwin_LDADD        = $(TOOL_LDADD_X86_DARWIN)
lackey_x86_darwin_LDFLAGS      = $(TOOL_LDFLAGS_X86_DARWIN)

lackey_amd64_darwin_SOURCES      = $(LACKEY_SOURCES_COMMON)
lackey_amd64_darwin_CPPFLAGS     = $(AM_CPPFLAGS_AMD64_DARWIN)
lackey_amd64_darwin_CFLAGS       = $(AM_CFLAGS_AMD64_DARWIN)
lackey_amd64_darwin_DEPENDENCIES = $(COREGRIND_LIBS_AMD64_DARWIN)
lackey_amd64_darwin_LDADD        = $(TOOL_LDADD_AMD64_DARWIN)
lackey_amd64_darwin_LDFLAGS      = $(TOOL_LDFLAGS_AMD64_DARWIN)
