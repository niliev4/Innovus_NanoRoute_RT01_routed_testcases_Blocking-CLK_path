# Innovus_NanoRoute_RT01_routed_testcases_Blocking-CLK_path
Detailed routed RT01 and other testcases with Innovus NanoRoute; includes RT01 random blockages.  Example routes include CLK paths avoiding all blockages and connecting all DFF pins. All modules are designed  with the  GSCLK45nm standard cell library. Note that NanoRoute is typically used for routing std cell placements;
in this case,  custom top-level (IP blocks around std cell rows) irregular placements, with random blockages (as in RT01 benchmark), have been successfully routed as well (all CLK nets routed).
