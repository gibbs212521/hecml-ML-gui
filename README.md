# hecml-ML-gui
Open Source Educational GUI for Machine Learning

NOTUM BONUM:
  Directed Acyclical Graph: 
  
      maths   <---  algorithms  <---   gui  <---  tests
      
            OR
            
      maths   <---  algorithms  <---  tests
      
            OR
            
      maths   <---  gui  <---  tests
      
            OR
            
      maths   <---  tests
  
  Nothing should ever import tests except other tests.
  Gui modules may import algorithms or maths.
  Algorithms only import maths.
  Maths should only import external libraries such as numpy.
  
