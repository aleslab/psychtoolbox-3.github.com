# [Datapixx('StopAdcSchedule')](Datapixx-StopAdcSchedule) 
## [[Psychtoolbox]] &#8250; [[Datapixx]].{mex*,dll} subfunction


Stop running an ADC analog acquisition schedule. The actual hardware schedule  
will be terminated by the next [RegWr](RegWr)\* command.  
Note that if maxScheduleFrames was assigned a non-0 value in [SetAdcSchedule](SetAdcSchedule),  
then the schedule can be left to terminate automatically without having to call  
[StopAdcSchedule](StopAdcSchedule).  
See [DatapixxAdc](DatapixxAdc)\*Demo files for examples.  
  


<<=====See also:=====
SetAdcSchedule, StartAdcSchedule, GetAdcStatus
<<