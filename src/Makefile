# Author: crifan
# Date: 2012-05-16
#
# -----------------------------------------------------------------
#  generate output from DocBook sources
#  this is entry makefile for docbook
# -----------------------------------------------------------------
# run this makefile under src directory:
# [office]
# pwd = /home/CLi/develop/docbook/books/xxx/src
# [home]
# pwd = /cygdrive/e/Dev_Root/docbook/dev/books/xxx/src

################################################################################
# Project Settings
################################################################################

# also means main source file name
PROJECT_NAME = cygwin_intro
SUB_SRC_FILES = \
    preface.xml \
    ch01_intro_cygwin.xml \
    ch02_download_install_cygwin.xml \
    ch03_cygwin_modules.xml \
    ch04_cygwin_note_tricks.xml \
    ch05_cygwin_common_errors.xml \
    ch06_cygwin_related.xml \
    reference.xml \

DOCBOOK_MAKEFILE_ROOT = ../../../config
################################################################################
# Include docbook makefile
################################################################################
include $(DOCBOOK_MAKEFILE_ROOT)/docbook.mk