#
### make PROG=xxx
#
### or, change this to reflect your own file (default is hello)

PROG	= full_adder

CC		= iverilog

$(PROG): $(PROG).v Testbench.v
	$(CC) -o $(PROG) $(PROG).v Testbench.v

clean:
	rm $(PROG)
