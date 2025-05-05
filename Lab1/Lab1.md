##Half Adder Example
This simulation demonstrates the behavior of a half adder circuit. The input signals are a and b, while the outputs are s (sum) and c (carry). The results follow expected logic: When both a and b are 0, 
s and c are also 0. When either a or b is 1 (but not both), s is 1 and c is 0. When both a and b are 1, the sum s becomes 0 and the carry c is set to 1.

##D Flip-Flop Example
This simulation illustrates the operation of a D Flip-Flop. It has three inputs: din (data), clk (clock), and rst (reset), and one output: dout. On each rising edge of the clock signal clk,
the output dout updates to match the current value of din. The reset signal rst is asynchronous: whenever rst is set to 1, dout is immediately forced to 0, regardless of the clock. Once rst returns to 0, dout remains at 0 until the next rising edge of clk, at which point it updates to the current value of din.
