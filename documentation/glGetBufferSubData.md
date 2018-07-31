## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

glGetBufferSubData  Interface to [OpenGL](OpenGL) function glGetBufferSubData  
  
usage:  glGetBufferSubData( target, offset, dsize, data )  
  
Caution: Caller needs to allocate 'data' as a matrix or vector of  
suitable format and capacity for the data, otherwise bad things will  
happen! Caller must request more than 1 Byte of data, ie. dsize \> 1!  
  
C function:  void glGetBufferSubData[(GLenum]((GLenum) target, [GLint](GLint) offset, [GLsizei](GLsizei) dsize, [GLvoid](GLvoid)\* data)  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glGetBufferSubData.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glGetBufferSubData.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/glGetBufferSubData.m</code>
</div>

