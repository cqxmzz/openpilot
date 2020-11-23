CC := gcc
CXX := g++

index_log: index_log.cc
	$(eval $@_TMP := $(shell mktemp))
	$(CXX) -std=gnu++14 -o $($@_TMP) \
    index_log.cc \
    -lcapnp -lkj
	mv $($@_TMP) $@
