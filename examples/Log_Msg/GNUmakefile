# -*- makefile -*-
#----------------------------------------------------------------------------
#       GNU ACE Workspace
#
# GNUmakefile,v 1.1.1.1 2007/09/03 07:58:13 shuston Exp
#
# This file was generated by MPC.  Any changes made directly to
# this file will be lost the next time it is generated.
#
# MPC Command:
# /export/anduriltmp/bczar/560/DOC_ROOT/stage-24190/ACE_wrappers/bin/mwc.pl -type gnuace -exclude TAO/TAO_*.mwc,TAO/CIAO/CIAO_*.mwc -recurse -hierarchy -relative ACE_ROOT=/export/anduriltmp/bczar/560/DOC_ROOT/stage-24190/ACE_wrappers -relative TAO_ROOT=/export/anduriltmp/bczar/560/DOC_ROOT/stage-24190/ACE_wrappers/TAO -relative CIAO_ROOT=/export/anduriltmp/bczar/560/DOC_ROOT/stage-24190/ACE_wrappers/TAO/CIAO
#
#----------------------------------------------------------------------------

MAKEFILE = GNUmakefile

ifeq ($(findstring k,$(MAKEFLAGS)),k)
  KEEP_GOING = -
endif

include $(ACE_ROOT)/include/makeinclude/macros.GNU

all: Log_Msg_Test_Callback Log_Msg_Test_Log_Msg Log_Msg_Test_Ostream

REMAINING_TARGETS := $(subst all, , $(TARGETS_NESTED:.nested=)) $(CUSTOM_TARGETS)

$(REMAINING_TARGETS):
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Callback $(@)
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Log_Msg $(@)
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Ostream $(@)

.PHONY: Log_Msg_Test_Callback
Log_Msg_Test_Callback:
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Callback all

.PHONY: Log_Msg_Test_Log_Msg
Log_Msg_Test_Log_Msg:
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Log_Msg all

.PHONY: Log_Msg_Test_Ostream
Log_Msg_Test_Ostream:
	@$(MAKE) -f GNUmakefile.Log_Msg_Test_Ostream all

project_name_list:
	@echo Log_Msg_Test_Callback
	@echo Log_Msg_Test_Log_Msg
	@echo Log_Msg_Test_Ostream
