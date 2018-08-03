# [Datapixx('StopDoutSchedule')](Datapixx-StopDoutSchedule) 
## [Psychtoolbox](Pyschtoolbox)&#8250;[Datapixx](Datapixx).{mex*} subfunction


Stop running a digital output waveform playback schedule. The actual hardware  
schedule will be terminated by the next [RegWr](RegWr)\* command.  
Note that if maxScheduleFrames was assigned a non-0 value in [SetDoutSchedule](SetDoutSchedule),  
then the schedule can be left to terminate automatically without having to call  
[StopDoutSchedule](StopDoutSchedule).  
See [DatapixxDout](DatapixxDout)\*Demo files for examples.  
  


###See also:
[SetDoutSchedule](Datapixx-SetDoutSchedule), [StartDoutSchedule](Datapixx-StartDoutSchedule), [GetDoutStatus](Datapixx-GetDoutStatus)