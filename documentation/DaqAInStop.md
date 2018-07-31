## [[Psychtoolbox]] &#8250; [[PsychHardware]] &#8250; [[Daq]]

err=[DaqAInStop](DaqAInStop)[(DeviceIndex)]((DeviceIndex))  
USB-1208FS stop analog input scan. You probably will never need to  
explicitly call this function because it's already called on your behalf  
by [DaqAInScan](DaqAInScan) and [DaqAInScanEnd](DaqAInScanEnd).  
"[DeviceIndex](DeviceIndex)" is a small integer, the array index specifying which HID  
      device in the array returned by [PsychHID](PsychHID)('Devices') is interface 0  
      of the desired USB-1208FS box.  
See also Daq, [DaqFunctions](DaqFunctions), [DaqPins](DaqPins), [DaqAInScan](DaqAInScan).  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychHardware/Daq/DaqAInStop.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychHardware/Daq/DaqAInStop.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychHardware/Daq/DaqAInStop.m</code>
</div>

