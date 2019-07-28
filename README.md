# Xilinx Design Suite 14.7 patch for Win10 32/64
Allows running Xilinx Design Suite version 14.7 under Windows 10 32/64 bit.
All ISE Design Tools will be patched by replacing the libPortability.dll with a library that is Win10 compatible libPortabilityNOSH.dll that has SmartHeap disabled. The patch does not negatively impact operation and performance of the tools.

For PlanAhead 14.7 you still need to manually add '-m32' to the shortcut like so that the target becomes:
C:\Xilinx\14.7\ISE_DS\PlanAhead\bin\planAhead.bat -m32

# usage

cd c:\Xilinx
c:patch.bat

# revert

cd c:\Xilinx
c:revert.bat

