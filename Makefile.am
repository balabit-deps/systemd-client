includedir=$(prefix)/include/systemd
pkgincludedir=$(includedir)/systemd

lib_LTLIBRARIES = libsystemd-client.la
libsystemd_client_la_SOURCES = sd-daemon.c
include_HEADERS = systemd/sd-daemon.h
extra_DIST = libsystemd-daemon.pc
pkg_configdir = ${libdir}/pkgconfig
pkg_config_DATA = libsystemd-daemon.pc
