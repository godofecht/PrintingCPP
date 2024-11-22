# Automatically generated makefile, created by the Projucer
# Don't edit this file! Your changes will be overwritten when you re-save the Projucer project!

# build with "V=1" for verbose builds
ifeq ($(V), 1)
V_AT =
else
V_AT = @
endif

# (this disables dependency generation if multiple architectures are set)
DEPFLAGS := $(if $(word 2, $(TARGET_ARCH)), , -MMD)

ifndef PKG_CONFIG
  PKG_CONFIG=pkg-config
endif

ifndef STRIP
  STRIP=strip
endif

ifndef AR
  AR=ar
endif

ifndef CONFIG
  CONFIG=Debug
endif

JUCE_ARCH_LABEL := $(shell uname -m)

ifeq ($(CONFIG),Debug)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Debug
  JUCE_OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := 
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) "-DLINUX=1" "-DDEBUG=1" "-D_DEBUG=1" "-DJUCE_DISPLAY_SPLASH_SCREEN=1" "-DJUCE_USE_DARK_SPLASH_SCREEN=1" "-DJUCE_PROJUCER_VERSION=0x70003" "-DJUCE_MODULE_AVAILABLE_juce_core=1" "-DJUCE_MODULE_AVAILABLE_juce_data_structures=1" "-DJUCE_MODULE_AVAILABLE_juce_events=1" "-DJUCE_MODULE_AVAILABLE_juce_graphics=1" "-DJUCE_MODULE_AVAILABLE_juce_gui_basics=1" "-DJUCE_GLOBAL_MODULE_SETTINGS_INCLUDED=1" "-DJUCE_STRICT_REFCOUNTEDPOINTER=1" "-DJUCE_STANDALONE_APPLICATION=1" "-DJUCER_LINUX_MAKE_6D53C8B4=1" "-DJUCE_APP_VERSION=1.0.0" "-DJUCE_APP_VERSION_HEX=0x10000" $(shell $(PKG_CONFIG) --cflags freetype2 libcurl pappl) -pthread -I../../JuceLibraryCode -I$(HOME)/JUCE/modules -IC:/Users/abhis/properbadger2/Builds/VisualStudio2022/packages/libpappl1_native.1.2.1/build/native/include $(CPPFLAGS)
  JUCE_CPPFLAGS_APP :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=0" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0" "-DJucePlugin_Build_LV2=0"
  JUCE_TARGET_APP := radger

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -g -ggdb -O0 $(CFLAGS)
  JUCE_CXXFLAGS += $(JUCE_CFLAGS) -std=c++17 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) -LC:\Users\abhis\properbadger2\Builds\VisualStudio2022\packages\libpappl1_native.1.2.1\build\native\lib\x64\Debug\ $(shell $(PKG_CONFIG) --libs freetype2 libcurl pappl) -fvisibility=hidden -lrt -ldl -lpthread $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

ifeq ($(CONFIG),Release)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Release
  JUCE_OUTDIR := build

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := 
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) "-DLINUX=1" "-DNDEBUG=1" "-DJUCE_DISPLAY_SPLASH_SCREEN=1" "-DJUCE_USE_DARK_SPLASH_SCREEN=1" "-DJUCE_PROJUCER_VERSION=0x70003" "-DJUCE_MODULE_AVAILABLE_juce_core=1" "-DJUCE_MODULE_AVAILABLE_juce_data_structures=1" "-DJUCE_MODULE_AVAILABLE_juce_events=1" "-DJUCE_MODULE_AVAILABLE_juce_graphics=1" "-DJUCE_MODULE_AVAILABLE_juce_gui_basics=1" "-DJUCE_GLOBAL_MODULE_SETTINGS_INCLUDED=1" "-DJUCE_STRICT_REFCOUNTEDPOINTER=1" "-DJUCE_STANDALONE_APPLICATION=1" "-DJUCER_LINUX_MAKE_6D53C8B4=1" "-DJUCE_APP_VERSION=1.0.0" "-DJUCE_APP_VERSION_HEX=0x10000" $(shell $(PKG_CONFIG) --cflags freetype2 libcurl pappl) -pthread -I../../JuceLibraryCode -I$(HOME)/JUCE/modules $(CPPFLAGS)
  JUCE_CPPFLAGS_APP :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=0" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0" "-DJucePlugin_Build_LV2=0"
  JUCE_TARGET_APP := radger

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -O3 $(CFLAGS)
  JUCE_CXXFLAGS += $(JUCE_CFLAGS) -std=c++17 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) $(shell $(PKG_CONFIG) --libs freetype2 libcurl pappl) -fvisibility=hidden -lrt -ldl -lpthread $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

OBJECTS_APP := \
  $(JUCE_OBJDIR)/adminutil_948eb7d7.o \
  $(JUCE_OBJDIR)/array_1736c4df.o \
  $(JUCE_OBJDIR)/auth_850bfcac.o \
  $(JUCE_OBJDIR)/backchannel_11193b42.o \
  $(JUCE_OBJDIR)/backend_c97fc61a.o \
  $(JUCE_OBJDIR)/debug_9ee1d259.o \
  $(JUCE_OBJDIR)/dest_8948c726.o \
  $(JUCE_OBJDIR)/dest-job_9a867b16.o \
  $(JUCE_OBJDIR)/dir_14f39a53.o \
  $(JUCE_OBJDIR)/encode_82b171da.o \
  $(JUCE_OBJDIR)/file_8ce76f80.o \
  $(JUCE_OBJDIR)/fuzzipp_12aa7b80.o \
  $(JUCE_OBJDIR)/getdevices_3e25ccb.o \
  $(JUCE_OBJDIR)/getifaddrs_f1c29d93.o \
  $(JUCE_OBJDIR)/getputfile_696e579.o \
  $(JUCE_OBJDIR)/globals_90b8f9b6.o \
  $(JUCE_OBJDIR)/hash_8fe39e92.o \
  $(JUCE_OBJDIR)/http_90efef8c.o \
  $(JUCE_OBJDIR)/http-addr_3ef450dc.o \
  $(JUCE_OBJDIR)/http-support_df0f130e.o \
  $(JUCE_OBJDIR)/ipp_153d36ef.o \
  $(JUCE_OBJDIR)/ipp-file_3c9d5224.o \
  $(JUCE_OBJDIR)/ipp-support_179c4771.o \
  $(JUCE_OBJDIR)/ipp-vars_577d0ed4.o \
  $(JUCE_OBJDIR)/langprintf_7d9216cb.o \
  $(JUCE_OBJDIR)/language_af03e6dc.o \
  $(JUCE_OBJDIR)/md5_156f4304.o \
  $(JUCE_OBJDIR)/md5passwd_44547ee2.o \
  $(JUCE_OBJDIR)/notify_7b314a4d.o \
  $(JUCE_OBJDIR)/options_e7986ba4.o \
  $(JUCE_OBJDIR)/ppd_159fae6a.o \
  $(JUCE_OBJDIR)/ppd-attr_427eabe.o \
  $(JUCE_OBJDIR)/ppd-cache_c9427cdf.o \
  $(JUCE_OBJDIR)/ppd-conflicts_fa4d8c7e.o \
  $(JUCE_OBJDIR)/ppd-custom_9d05d63e.o \
  $(JUCE_OBJDIR)/ppd-emit_a93b020.o \
  $(JUCE_OBJDIR)/ppd-localize_1f861cd6.o \
  $(JUCE_OBJDIR)/ppd-mark_1795509a.o \
  $(JUCE_OBJDIR)/ppd-page_1caec3dc.o \
  $(JUCE_OBJDIR)/ppd-util_2643c08f.o \
  $(JUCE_OBJDIR)/pwg-media_4bf2119d.o \
  $(JUCE_OBJDIR)/rasterbench_3b080e19.o \
  $(JUCE_OBJDIR)/raster-error_ac0655bc.o \
  $(JUCE_OBJDIR)/raster-interpret_fefa1801.o \
  $(JUCE_OBJDIR)/raster-interstub_43bd33e.o \
  $(JUCE_OBJDIR)/raster-stream_ec4d8d96.o \
  $(JUCE_OBJDIR)/raster-stubs_942ba5f9.o \
  $(JUCE_OBJDIR)/request_a2f59f55.o \
  $(JUCE_OBJDIR)/sidechannel_85e0d2.o \
  $(JUCE_OBJDIR)/snmp_a35d82c2.o \
  $(JUCE_OBJDIR)/snprintf_e6697df8.o \
  $(JUCE_OBJDIR)/string_87b00115.o \
  $(JUCE_OBJDIR)/tempfile_fd7264d4.o \
  $(JUCE_OBJDIR)/testadmin_b902f303.o \
  $(JUCE_OBJDIR)/testarray_d129c78d.o \
  $(JUCE_OBJDIR)/testcache_1d235e76.o \
  $(JUCE_OBJDIR)/testclient_d744e161.o \
  $(JUCE_OBJDIR)/testconflicts_c925ca95.o \
  $(JUCE_OBJDIR)/testcreds_3a405319.o \
  $(JUCE_OBJDIR)/testcups_3bdef54b.o \
  $(JUCE_OBJDIR)/testdest_3cb3b6b8.o \
  $(JUCE_OBJDIR)/testfile_40525f12.o \
  $(JUCE_OBJDIR)/testgetdests_f55d9d1.o \
  $(JUCE_OBJDIR)/testhttp_445adf1e.o \
  $(JUCE_OBJDIR)/testi18n_42444334.o \
  $(JUCE_OBJDIR)/testipp_33cd0d1d.o \
  $(JUCE_OBJDIR)/testlang_4a1fa704.o \
  $(JUCE_OBJDIR)/testoptions_f0d57ad2.o \
  $(JUCE_OBJDIR)/testppd_342f8498.o \
  $(JUCE_OBJDIR)/testpwg_3432be74.o \
  $(JUCE_OBJDIR)/testraster_b971ae93.o \
  $(JUCE_OBJDIR)/testsnmp_56c87254.o \
  $(JUCE_OBJDIR)/testthreads_25b8911d.o \
  $(JUCE_OBJDIR)/thread_748814ce.o \
  $(JUCE_OBJDIR)/tls_15d67341.o \
  $(JUCE_OBJDIR)/tlscheck_ce14cb31.o \
  $(JUCE_OBJDIR)/tls-darwin_fcde84bd.o \
  $(JUCE_OBJDIR)/tls-gnutls_e928c0e3.o \
  $(JUCE_OBJDIR)/tls-openssl_5597ecb6.o \
  $(JUCE_OBJDIR)/tls-sspi_b914c4af.o \
  $(JUCE_OBJDIR)/transcode_fb3bef9b.o \
  $(JUCE_OBJDIR)/usersys_8ef20f28.o \
  $(JUCE_OBJDIR)/util_a719e086.o \
  $(JUCE_OBJDIR)/Main_90ebc5c2.o \
  $(JUCE_OBJDIR)/MainComponent_a6ffb4a5.o \
  $(JUCE_OBJDIR)/lprint-common_7fc477ba.o \
  $(JUCE_OBJDIR)/lprint-dymo_1591e246.o \
  $(JUCE_OBJDIR)/lprint-epl2_16c68e00.o \
  $(JUCE_OBJDIR)/lprint-zpl_5cbab811.o \
  $(JUCE_OBJDIR)/array_f789b938.o \
  $(JUCE_OBJDIR)/auth_9ccc9933.o \
  $(JUCE_OBJDIR)/debug_7f34c6b2.o \
  $(JUCE_OBJDIR)/dest-job_70077c1d.o \
  $(JUCE_OBJDIR)/dest-localization_1b12e503.o \
  $(JUCE_OBJDIR)/dest-options_5474653e.o \
  $(JUCE_OBJDIR)/dest_a10963ad.o \
  $(JUCE_OBJDIR)/dir_1df9d0ec.o \
  $(JUCE_OBJDIR)/dnssd_8f7effd9.o \
  $(JUCE_OBJDIR)/encode_acbd08a1.o \
  $(JUCE_OBJDIR)/file_a4a80c07.o \
  $(JUCE_OBJDIR)/form_a4ff714f.o \
  $(JUCE_OBJDIR)/fuzzipp_2a11bd99.o \
  $(JUCE_OBJDIR)/getputfile_7fdbc0c0.o \
  $(JUCE_OBJDIR)/globals_a8203bcf.o \
  $(JUCE_OBJDIR)/hash_a7a43b19.o \
  $(JUCE_OBJDIR)/http-addr_199370b5.o \
  $(JUCE_OBJDIR)/http-addrlist_b6a911d3.o \
  $(JUCE_OBJDIR)/http-support_1a8a3895.o \
  $(JUCE_OBJDIR)/http_a8b08c13.o \
  $(JUCE_OBJDIR)/ipp-file_121e532b.o \
  $(JUCE_OBJDIR)/ipp-support_c6f2d50a.o \
  $(JUCE_OBJDIR)/ipp_1e436d88.o \
  $(JUCE_OBJDIR)/json_ac09d873.o \
  $(JUCE_OBJDIR)/jwt_1e54c2a6.o \
  $(JUCE_OBJDIR)/langprintf_f6d6f212.o \
  $(JUCE_OBJDIR)/language_8484e7e3.o \
  $(JUCE_OBJDIR)/md5_1e75799d.o \
  $(JUCE_OBJDIR)/notify_a53ce114.o \
  $(JUCE_OBJDIR)/options_feffadbd.o \
  $(JUCE_OBJDIR)/pwg-media_26913176.o \
  $(JUCE_OBJDIR)/rand_b8b25c70.o \
  $(JUCE_OBJDIR)/raster-error_e7817b43.o \
  $(JUCE_OBJDIR)/raster-stream_203718ef.o \
  $(JUCE_OBJDIR)/rasterbench_ea5e9bb2.o \
  $(JUCE_OBJDIR)/request_ba5ce16e.o \
  $(JUCE_OBJDIR)/string_b1bb97dc.o \
  $(JUCE_OBJDIR)/tempfile_d2f365db.o \
  $(JUCE_OBJDIR)/testarray_abc8e766.o \
  $(JUCE_OBJDIR)/testclient_5089bca8.o \
  $(JUCE_OBJDIR)/testcreds_14df72f2.o \
  $(JUCE_OBJDIR)/testcups_115ff652.o \
  $(JUCE_OBJDIR)/testdest_1234b7bf.o \
  $(JUCE_OBJDIR)/testdnssd_43be2e07.o \
  $(JUCE_OBJDIR)/testfile_15d36019.o \
  $(JUCE_OBJDIR)/testform_162ac561.o \
  $(JUCE_OBJDIR)/testgetdests_4ad0ff58.o \
  $(JUCE_OBJDIR)/testhash_18cf8f2b.o \
  $(JUCE_OBJDIR)/testhttp_19dbe025.o \
  $(JUCE_OBJDIR)/testi18n_17c5443b.o \
  $(JUCE_OBJDIR)/testipp_4b344f36.o \
  $(JUCE_OBJDIR)/testjson_1d352c85.o \
  $(JUCE_OBJDIR)/testjwt_4b45a454.o \
  $(JUCE_OBJDIR)/testlang_1fa0a80b.o \
  $(JUCE_OBJDIR)/testoptions_a02c086b.o \
  $(JUCE_OBJDIR)/testpwg_4b9a008d.o \
  $(JUCE_OBJDIR)/testraster_32b689da.o \
  $(JUCE_OBJDIR)/testtestpage_aacfcf7e.o \
  $(JUCE_OBJDIR)/testthreads_d50f1eb6.o \
  $(JUCE_OBJDIR)/thread_9e93ab95.o \
  $(JUCE_OBJDIR)/tls-gnutls_626d9c2a.o \
  $(JUCE_OBJDIR)/tls-openssl_4ee7a4f.o \
  $(JUCE_OBJDIR)/tls_1edca9da.o \
  $(JUCE_OBJDIR)/tlscheck_a395cc38.o \
  $(JUCE_OBJDIR)/transcode_d5db0f74.o \
  $(JUCE_OBJDIR)/usersys_a6595141.o \
  $(JUCE_OBJDIR)/util_beda7d0d.o \
  $(JUCE_OBJDIR)/BinaryData_ce4232d4.o \
  $(JUCE_OBJDIR)/BinaryData2_fa243da8.o \
  $(JUCE_OBJDIR)/include_juce_core_f26d17db.o \
  $(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o \
  $(JUCE_OBJDIR)/include_juce_events_fd7d695.o \
  $(JUCE_OBJDIR)/include_juce_graphics_f817e147.o \
  $(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o \

.PHONY: clean all strip

all : $(JUCE_OUTDIR)/$(JUCE_TARGET_APP)

$(JUCE_OUTDIR)/$(JUCE_TARGET_APP) : $(OBJECTS_APP) $(RESOURCES)
	@command -v $(PKG_CONFIG) >/dev/null 2>&1 || { echo >&2 "pkg-config not installed. Please, install it."; exit 1; }
	@$(PKG_CONFIG) --print-errors freetype2 libcurl pappl
	@echo Linking "radger - App"
	-$(V_AT)mkdir -p $(JUCE_BINDIR)
	-$(V_AT)mkdir -p $(JUCE_LIBDIR)
	-$(V_AT)mkdir -p $(JUCE_OUTDIR)
	$(V_AT)$(CXX) -o $(JUCE_OUTDIR)/$(JUCE_TARGET_APP) $(OBJECTS_APP) $(JUCE_LDFLAGS) $(JUCE_LDFLAGS_APP) $(RESOURCES) $(TARGET_ARCH)

$(JUCE_OBJDIR)/adminutil_948eb7d7.o: ../../../cups/cups/adminutil.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling adminutil.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/array_1736c4df.o: ../../../cups/cups/array.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling array.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/auth_850bfcac.o: ../../../cups/cups/auth.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling auth.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/backchannel_11193b42.o: ../../../cups/cups/backchannel.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling backchannel.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/backend_c97fc61a.o: ../../../cups/cups/backend.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling backend.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/debug_9ee1d259.o: ../../../cups/cups/debug.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling debug.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest_8948c726.o: ../../../cups/cups/dest.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest-job_9a867b16.o: ../../../cups/cups/dest-job.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest-job.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dir_14f39a53.o: ../../../cups/cups/dir.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dir.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/encode_82b171da.o: ../../../cups/cups/encode.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling encode.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/file_8ce76f80.o: ../../../cups/cups/file.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling file.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fuzzipp_12aa7b80.o: ../../../cups/cups/fuzzipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fuzzipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/getdevices_3e25ccb.o: ../../../cups/cups/getdevices.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling getdevices.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/getifaddrs_f1c29d93.o: ../../../cups/cups/getifaddrs.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling getifaddrs.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/getputfile_696e579.o: ../../../cups/cups/getputfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling getputfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/globals_90b8f9b6.o: ../../../cups/cups/globals.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling globals.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/hash_8fe39e92.o: ../../../cups/cups/hash.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling hash.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http_90efef8c.o: ../../../cups/cups/http.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http-addr_3ef450dc.o: ../../../cups/cups/http-addr.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http-addr.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http-support_df0f130e.o: ../../../cups/cups/http-support.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http-support.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp_153d36ef.o: ../../../cups/cups/ipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp-file_3c9d5224.o: ../../../cups/cups/ipp-file.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp-file.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp-support_179c4771.o: ../../../cups/cups/ipp-support.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp-support.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp-vars_577d0ed4.o: ../../../cups/cups/ipp-vars.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp-vars.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/langprintf_7d9216cb.o: ../../../cups/cups/langprintf.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling langprintf.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/language_af03e6dc.o: ../../../cups/cups/language.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling language.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/md5_156f4304.o: ../../../cups/cups/md5.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling md5.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/md5passwd_44547ee2.o: ../../../cups/cups/md5passwd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling md5passwd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/notify_7b314a4d.o: ../../../cups/cups/notify.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling notify.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/options_e7986ba4.o: ../../../cups/cups/options.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling options.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd_159fae6a.o: ../../../cups/cups/ppd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-attr_427eabe.o: ../../../cups/cups/ppd-attr.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-attr.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-cache_c9427cdf.o: ../../../cups/cups/ppd-cache.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-cache.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-conflicts_fa4d8c7e.o: ../../../cups/cups/ppd-conflicts.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-conflicts.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-custom_9d05d63e.o: ../../../cups/cups/ppd-custom.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-custom.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-emit_a93b020.o: ../../../cups/cups/ppd-emit.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-emit.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-localize_1f861cd6.o: ../../../cups/cups/ppd-localize.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-localize.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-mark_1795509a.o: ../../../cups/cups/ppd-mark.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-mark.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-page_1caec3dc.o: ../../../cups/cups/ppd-page.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-page.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ppd-util_2643c08f.o: ../../../cups/cups/ppd-util.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ppd-util.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pwg-media_4bf2119d.o: ../../../cups/cups/pwg-media.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pwg-media.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rasterbench_3b080e19.o: ../../../cups/cups/rasterbench.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rasterbench.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-error_ac0655bc.o: ../../../cups/cups/raster-error.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-error.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-interpret_fefa1801.o: ../../../cups/cups/raster-interpret.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-interpret.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-interstub_43bd33e.o: ../../../cups/cups/raster-interstub.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-interstub.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-stream_ec4d8d96.o: ../../../cups/cups/raster-stream.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-stream.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-stubs_942ba5f9.o: ../../../cups/cups/raster-stubs.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-stubs.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/request_a2f59f55.o: ../../../cups/cups/request.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling request.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sidechannel_85e0d2.o: ../../../cups/cups/sidechannel.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sidechannel.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/snmp_a35d82c2.o: ../../../cups/cups/snmp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling snmp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/snprintf_e6697df8.o: ../../../cups/cups/snprintf.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling snprintf.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/string_87b00115.o: ../../../cups/cups/string.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling string.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tempfile_fd7264d4.o: ../../../cups/cups/tempfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tempfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testadmin_b902f303.o: ../../../cups/cups/testadmin.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testadmin.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testarray_d129c78d.o: ../../../cups/cups/testarray.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testarray.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testcache_1d235e76.o: ../../../cups/cups/testcache.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testcache.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testclient_d744e161.o: ../../../cups/cups/testclient.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testclient.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testconflicts_c925ca95.o: ../../../cups/cups/testconflicts.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testconflicts.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testcreds_3a405319.o: ../../../cups/cups/testcreds.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testcreds.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testcups_3bdef54b.o: ../../../cups/cups/testcups.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testcups.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testdest_3cb3b6b8.o: ../../../cups/cups/testdest.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testdest.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testfile_40525f12.o: ../../../cups/cups/testfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testgetdests_f55d9d1.o: ../../../cups/cups/testgetdests.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testgetdests.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testhttp_445adf1e.o: ../../../cups/cups/testhttp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testhttp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testi18n_42444334.o: ../../../cups/cups/testi18n.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testi18n.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testipp_33cd0d1d.o: ../../../cups/cups/testipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testlang_4a1fa704.o: ../../../cups/cups/testlang.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testlang.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testoptions_f0d57ad2.o: ../../../cups/cups/testoptions.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testoptions.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testppd_342f8498.o: ../../../cups/cups/testppd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testppd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testpwg_3432be74.o: ../../../cups/cups/testpwg.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testpwg.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testraster_b971ae93.o: ../../../cups/cups/testraster.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testraster.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testsnmp_56c87254.o: ../../../cups/cups/testsnmp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testsnmp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testthreads_25b8911d.o: ../../../cups/cups/testthreads.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testthreads.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/thread_748814ce.o: ../../../cups/cups/thread.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling thread.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls_15d67341.o: ../../../cups/cups/tls.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tlscheck_ce14cb31.o: ../../../cups/cups/tlscheck.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tlscheck.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-darwin_fcde84bd.o: ../../../cups/cups/tls-darwin.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-darwin.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-gnutls_e928c0e3.o: ../../../cups/cups/tls-gnutls.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-gnutls.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-openssl_5597ecb6.o: ../../../cups/cups/tls-openssl.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-openssl.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-sspi_b914c4af.o: ../../../cups/cups/tls-sspi.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-sspi.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/transcode_fb3bef9b.o: ../../../cups/cups/transcode.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling transcode.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/usersys_8ef20f28.o: ../../../cups/cups/usersys.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling usersys.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/util_a719e086.o: ../../../cups/cups/util.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling util.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/Main_90ebc5c2.o: ../../Source/Main.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling Main.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/MainComponent_a6ffb4a5.o: ../../Source/MainComponent.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling MainComponent.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lprint-common_7fc477ba.o: ../../Source/Screens/lprint/lprint-common.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lprint-common.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lprint-dymo_1591e246.o: ../../Source/Screens/lprint/lprint-dymo.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lprint-dymo.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lprint-epl2_16c68e00.o: ../../Source/Screens/lprint/lprint-epl2.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lprint-epl2.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lprint-zpl_5cbab811.o: ../../Source/Screens/lprint/lprint-zpl.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lprint-zpl.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/array_f789b938.o: ../../../libcups/cups/array.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling array.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/auth_9ccc9933.o: ../../../libcups/cups/auth.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling auth.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/debug_7f34c6b2.o: ../../../libcups/cups/debug.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling debug.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest-job_70077c1d.o: ../../../libcups/cups/dest-job.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest-job.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest-localization_1b12e503.o: ../../../libcups/cups/dest-localization.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest-localization.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest-options_5474653e.o: ../../../libcups/cups/dest-options.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest-options.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dest_a10963ad.o: ../../../libcups/cups/dest.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dest.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dir_1df9d0ec.o: ../../../libcups/cups/dir.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dir.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dnssd_8f7effd9.o: ../../../libcups/cups/dnssd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dnssd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/encode_acbd08a1.o: ../../../libcups/cups/encode.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling encode.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/file_a4a80c07.o: ../../../libcups/cups/file.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling file.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/form_a4ff714f.o: ../../../libcups/cups/form.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling form.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fuzzipp_2a11bd99.o: ../../../libcups/cups/fuzzipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fuzzipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/getputfile_7fdbc0c0.o: ../../../libcups/cups/getputfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling getputfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/globals_a8203bcf.o: ../../../libcups/cups/globals.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling globals.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/hash_a7a43b19.o: ../../../libcups/cups/hash.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling hash.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http-addr_199370b5.o: ../../../libcups/cups/http-addr.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http-addr.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http-addrlist_b6a911d3.o: ../../../libcups/cups/http-addrlist.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http-addrlist.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http-support_1a8a3895.o: ../../../libcups/cups/http-support.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http-support.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/http_a8b08c13.o: ../../../libcups/cups/http.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling http.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp-file_121e532b.o: ../../../libcups/cups/ipp-file.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp-file.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp-support_c6f2d50a.o: ../../../libcups/cups/ipp-support.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp-support.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ipp_1e436d88.o: ../../../libcups/cups/ipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/json_ac09d873.o: ../../../libcups/cups/json.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling json.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/jwt_1e54c2a6.o: ../../../libcups/cups/jwt.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling jwt.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/langprintf_f6d6f212.o: ../../../libcups/cups/langprintf.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling langprintf.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/language_8484e7e3.o: ../../../libcups/cups/language.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling language.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/md5_1e75799d.o: ../../../libcups/cups/md5.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling md5.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/notify_a53ce114.o: ../../../libcups/cups/notify.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling notify.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/options_feffadbd.o: ../../../libcups/cups/options.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling options.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pwg-media_26913176.o: ../../../libcups/cups/pwg-media.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pwg-media.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand_b8b25c70.o: ../../../libcups/cups/rand.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-error_e7817b43.o: ../../../libcups/cups/raster-error.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-error.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/raster-stream_203718ef.o: ../../../libcups/cups/raster-stream.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling raster-stream.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rasterbench_ea5e9bb2.o: ../../../libcups/cups/rasterbench.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rasterbench.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/request_ba5ce16e.o: ../../../libcups/cups/request.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling request.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/string_b1bb97dc.o: ../../../libcups/cups/string.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling string.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tempfile_d2f365db.o: ../../../libcups/cups/tempfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tempfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testarray_abc8e766.o: ../../../libcups/cups/testarray.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testarray.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testclient_5089bca8.o: ../../../libcups/cups/testclient.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testclient.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testcreds_14df72f2.o: ../../../libcups/cups/testcreds.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testcreds.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testcups_115ff652.o: ../../../libcups/cups/testcups.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testcups.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testdest_1234b7bf.o: ../../../libcups/cups/testdest.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testdest.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testdnssd_43be2e07.o: ../../../libcups/cups/testdnssd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testdnssd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testfile_15d36019.o: ../../../libcups/cups/testfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testform_162ac561.o: ../../../libcups/cups/testform.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testform.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testgetdests_4ad0ff58.o: ../../../libcups/cups/testgetdests.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testgetdests.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testhash_18cf8f2b.o: ../../../libcups/cups/testhash.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testhash.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testhttp_19dbe025.o: ../../../libcups/cups/testhttp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testhttp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testi18n_17c5443b.o: ../../../libcups/cups/testi18n.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testi18n.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testipp_4b344f36.o: ../../../libcups/cups/testipp.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testipp.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testjson_1d352c85.o: ../../../libcups/cups/testjson.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testjson.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testjwt_4b45a454.o: ../../../libcups/cups/testjwt.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testjwt.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testlang_1fa0a80b.o: ../../../libcups/cups/testlang.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testlang.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testoptions_a02c086b.o: ../../../libcups/cups/testoptions.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testoptions.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testpwg_4b9a008d.o: ../../../libcups/cups/testpwg.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testpwg.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testraster_32b689da.o: ../../../libcups/cups/testraster.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testraster.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testtestpage_aacfcf7e.o: ../../../libcups/cups/testtestpage.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testtestpage.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/testthreads_d50f1eb6.o: ../../../libcups/cups/testthreads.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling testthreads.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/thread_9e93ab95.o: ../../../libcups/cups/thread.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling thread.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-gnutls_626d9c2a.o: ../../../libcups/cups/tls-gnutls.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-gnutls.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls-openssl_4ee7a4f.o: ../../../libcups/cups/tls-openssl.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls-openssl.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tls_1edca9da.o: ../../../libcups/cups/tls.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tls.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tlscheck_a395cc38.o: ../../../libcups/cups/tlscheck.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tlscheck.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/transcode_d5db0f74.o: ../../../libcups/cups/transcode.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling transcode.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/usersys_a6595141.o: ../../../libcups/cups/usersys.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling usersys.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/util_beda7d0d.o: ../../../libcups/cups/util.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling util.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/BinaryData_ce4232d4.o: ../../JuceLibraryCode/BinaryData.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling BinaryData.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/BinaryData2_fa243da8.o: ../../JuceLibraryCode/BinaryData2.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling BinaryData2.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_core_f26d17db.o: ../../JuceLibraryCode/include_juce_core.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_core.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o: ../../JuceLibraryCode/include_juce_data_structures.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_data_structures.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_events_fd7d695.o: ../../JuceLibraryCode/include_juce_events.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_events.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_graphics_f817e147.o: ../../JuceLibraryCode/include_juce_graphics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_graphics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o: ../../JuceLibraryCode/include_juce_gui_basics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_gui_basics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_APP) $(JUCE_CFLAGS_APP) -o "$@" -c "$<"

clean:
	@echo Cleaning radger
	$(V_AT)$(CLEANCMD)

strip:
	@echo Stripping radger
	-$(V_AT)$(STRIP) --strip-unneeded $(JUCE_OUTDIR)/$(TARGET)

-include $(OBJECTS_APP:%.o=%.d)
