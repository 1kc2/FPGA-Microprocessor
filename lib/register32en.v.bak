module register32_en(input         CLK, 
						   input         RST,
						   input         EN,
						   input  [31:0] D, 
						   output [31:0] Q);

  reg [31:0] r;

  always @(posedge CLK or posedge RST)
	if (RST == 1)
		r = 0;
	else if (EN == 1)
		r = D;	

  assign Q = r;
endmodule
