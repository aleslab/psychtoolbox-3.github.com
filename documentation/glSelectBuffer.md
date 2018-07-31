## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

glSelectBuffer  Interface to [OpenGL](OpenGL) function glSelectBuffer  
  
usage:  glSelectBuffer( bufsize, bufferptr )  
  
  
bufsize = The number of unsigned int values that can be placed into the buffer.  
  
bufferptr = Pointer to a buffer created via bufferptr=moglmalloc() or  
            bufferptr=moglcalloc().  
  
  
For principle of usage, see help glFeedbackBuffer. This buffer is meant  
to be used when [OpenGL](OpenGL) is switched into glRenderMode(GL.SELECT).  
  
C function:  void glSelectBuffer[(GLsizei]((GLsizei) bufsize, [GLuint](GLuint)\* bufferptr)  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glSelectBuffer.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glSelectBuffer.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/glSelectBuffer.m</code>
</div>

