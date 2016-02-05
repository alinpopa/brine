LIBBRINE_URL = git://github.com/rlipscombe/libbrine.git
LIBBRINE_BRANCH = rl-keypair-from-seed

deps: libbrine/libbrine_s.a

libbrine/libbrine_s.a: libbrine
	make -C libbrine -f Makefile.embed libbrine_s.a

libbrine:
	git clone -b $(LIBBRINE_BRANCH) $(LIBBRINE_URL)
