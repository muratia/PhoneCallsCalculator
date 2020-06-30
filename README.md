# PhoneCallsCalculator

 
  Write an application that computes the cost of a telephone call.      
  The inputs are the time the call was placed (this should be written   
  as a 24-hour time, e.g., 2149 for a call placed a 9:49p.m.), the      
  duration of the call in minutes, and the distance in miles of the     
  destination of the call. The output is the cost of the call. Cost      
  is computed as follows:                                               
  Basic cost is $0.003 per minute per mile.                             
  Calls placed between 8am and midnight (800 to 2400) are subject to a  
  20% surcharge. (That is, basic cost is increased by 0.2.)              
  A tax of 6% is added to the cost.                                     
  The difficult part of this project is computing the surcharge, if     
  any.                                                                  
  To help do this, use the operation Math.ceil(E), which returns the    
  nearest integer value that is not less than E. For example,           
  Math.ceil(0.2359 - 0.0759) equals 1.0, but Math.ceil(0.0630 - 0.0759) 
  equals 0.0.                                                           
