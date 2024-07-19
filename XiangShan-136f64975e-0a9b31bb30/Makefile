CXX := clang++
CFLAGS_WNO := -Wno-bool-operation -Wno-c++11-narrowing -Wno-constant-logical-operand -Wno-non-pod-varargs -Wno-parentheses-equality -Wno-shadow -Wno-sign-compare -Wno-tautological-bitwise-compare -Wno-tautological-compare -Wno-uninitialized -Wno-unused-but-set-parameter -Wno-unused-but-set-variable -Wno-unused-parameter -Wno-unused-variable
CFLAGS_INC := -I.
CFLAGS := -O3 -faligned-new -fbracket-depth=4096 -fcf-protection=none -Qunused-arguments --std=c++17 -fprofile-generate -DVM_COVERAGE=0 -DVM_SC=0 -DVM_TRACE=0 -DVM_TRACE_FST=0 -DVM_TRACE_VCD=0 -DVERILATOR -DNUM_CORES=1 -DVERILATOR_4_210 -DEMU_THREAD=8 -fcolor-diagnostics $(CFLAGS_WNO) $(CFLAGS_INC)

VSimTop___024root__DepSet_hd5918264__63.o: VSimTop___024root__DepSet_hd5918264__63.cpp
	$(CXX) $(CFLAGS) -c -o $@ $<

.PHONY: clean check

clean:
	rm -f VSimTop___024root__DepSet_hd5918264__63.o

check:
	$(MAKE) clean
	ulimit -t 900; $(MAKE) VSimTop___024root__DepSet_hd5918264__63.o
