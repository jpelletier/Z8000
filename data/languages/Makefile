GHI_DIR=/opt/apps/programming/ghidra
SLEIGH=$(GHI_DIR)/support/sleigh

all: z8001.sla z8002.sla

%.sla: %.slaspec
	$(SLEIGH) -u $<
