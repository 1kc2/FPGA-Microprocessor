module register32 (
	input         CLK, 
	input         RST,
	input  [31:0] D, 
	output [31:0] Q);

  reg [31:0] r;

  always @(posedge CLK or posedge RST)
	if (RST == 1)
		r = 0;
	else
		r = D;	

  assign Q = r;


endmodule