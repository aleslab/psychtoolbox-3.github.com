## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

moglfree(ptr) -- Free a memory buffer inside mogl which was previously  
created via a call to ptr = moglmalloc(...) or ptr = moglcalloc(...).  
ptr = A pointer to the buffer to free. This is the handle returned by  
moglmalloc() or moglcalloc().  
  
After successfull release, ptr will be invalid, \*do not use it anymore\*  
or Matlab/Octave will possibly crash or do other nasty things!  
  
moglcalloc()'ed or moglmalloc()'ed memory buffers can be released as well  
all at once via moglfreeall, and they are automatically released when  
moglcore is clear'ed via clear moglcore, clear mex or clear all.  
  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/moglfree.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/moglfree.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/moglfree.m</code>
</div>

