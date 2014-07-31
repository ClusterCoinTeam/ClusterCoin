.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. clustercoin_qt test_bitcoin_qt
clean: FORCE
	$(MAKE) -C .. clustercoin_qt_clean test_bitcoin_qt_clean
check: FORCE
	$(MAKE) -C .. test_bitcoin_qt_check
clustercoin-qt clustercoin-qt.exe: FORCE
	 $(MAKE) -C .. clustercoin_qt
