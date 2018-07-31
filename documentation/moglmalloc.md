## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

ptr = moglmalloc(nrbytes) -- Allocate a memory buffer inside mogl.  
This function allocates an internal memory buffer inside mogl for use  
with [OpenGL](OpenGL) functions that use buffers for passing data forth and back  
between Matlab and [OpenGL](OpenGL), e.g., glFeedbackBuffer() or glSelectBuffer().  
  
nrbytes = The number of bytes to allocate.  
  
On successfull allocation, ptr will be a handle for the memory buffer.  
You can think of ptr as a memory pointer in the C-language.  
  
moglmalloc()'ed memory buffers can be released - one by one - via  
moglfree(ptr), all at once via moglfreeall, and they are automatically  
released when moglcore is clear'ed via clear moglcore, clear mex or  
clear all.  
  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/moglmalloc.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/moglmalloc.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/moglmalloc.m</code>
</div>

