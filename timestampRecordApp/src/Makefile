TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += timestampRecord
DBDINC += timestampRecord
HTMLS  += Recordref-timestamp.html

#USER_DBDFLAGS += -I.. -I $(EPICS_BASE)/dbd

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install timestampRecord.dbd into <top>/dbd
DBD += timestampRecord.dbd

# specify all source files to be compiled and added to the library
timestampRecord_SRCS += timestampRecord.c

timestampRecord_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

