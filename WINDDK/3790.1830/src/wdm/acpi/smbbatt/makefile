#
# DO NOT EDIT THIS FILE!!!  Edit .\sources. if you want to add a new source
# file to this component.  This file merely indirects to the real make file
# that is shared by all the driver components of the Windows NT DDK
#
# The XP DDK has also build environments for Win2k and WinME. This sample
# however, only compiles well with the XP build environment, Therefore we
# need to prevent compilation on the other build environments.
!if !defined(DDKBUILDENV) || (defined(DDK_TARGET_OS) && "$(DDK_TARGET_OS)"!="Win2K")
!INCLUDE $(NTMAKEENV)\makefile.def
!else
!message This project is for Windows XP (or later) only.
!endif