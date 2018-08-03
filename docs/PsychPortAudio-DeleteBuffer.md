# [PsychPortAudio('DeleteBuffer')](PsychPortAudio-DeleteBuffer) 
##### [Psychtoolbox](Pyschtoolbox)>[PsychPortAudio](PsychPortAudio).{mex*} subfunction


Delete an existing dynamic audio data playback buffer.  
'bufferhandle' is the handle for the buffer to delete. If it is omitted, all  
buffers will be deleted. 'waitmode' defines what happens if a buffer shall be  
deleted that is currently in use, i.e., part of the audio playback schedule of  
an active audio device. The default of zero will simply return without deleting  
the buffer. A setting of 1 will wait until the buffer can be safely deleted.  
  


###See also:
Open [FillBuffer](PsychPortAudio-FillBuffer) [GetStatus](PsychPortAudio-GetStatus) 
