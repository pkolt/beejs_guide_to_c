.DEFAULT_GOAL := help

.PHONY: all clean pristine help \
	bgc.html bgc-wide.html split/index.html split-wide/index.html \
	bgc_usl_c_1.pdf bgc_usl_c_2.pdf bgc_usl_bw_1.pdf bgc_usl_bw_2.pdf \
	bgc_a4_c_1.pdf bgc_a4_c_2.pdf bgc_a4_bw_1.pdf bgc_a4_bw_2.pdf \
	bgc_amazon.pdf bgc_lulu.pdf

all:
	$(MAKE) -C src all

clean:
	$(MAKE) -C src clean

pristine:
	$(MAKE) -C src pristine

bgc.html bgc-wide.html split/index.html split-wide/index.html \
bgc_usl_c_1.pdf bgc_usl_c_2.pdf bgc_usl_bw_1.pdf bgc_usl_bw_2.pdf \
bgc_a4_c_1.pdf bgc_a4_c_2.pdf bgc_a4_bw_1.pdf bgc_a4_bw_2.pdf \
bgc_amazon.pdf bgc_lulu.pdf:
	$(MAKE) -C src $@

help:
	@echo "    all        build the Russian translation"
	@echo "    clean      remove temporary build products"
	@echo "    pristine   remove all build products"
	@echo ""
	@echo "  Specific targets:"
	@echo ""
	@echo "    bgc.html"
	@echo "    bgc-wide.html"
	@echo "    split/index.html"
	@echo "    split-wide/index.html"
	@echo "    bgc_usl_c_1.pdf"
	@echo "    bgc_usl_c_2.pdf"
	@echo "    bgc_usl_bw_1.pdf"
	@echo "    bgc_usl_bw_2.pdf"
	@echo "    bgc_a4_c_1.pdf"
	@echo "    bgc_a4_c_2.pdf"
	@echo "    bgc_a4_bw_1.pdf"
	@echo "    bgc_a4_bw_2.pdf"
	@echo "    bgc_amazon.pdf"
	@echo "    bgc_lulu.pdf"
