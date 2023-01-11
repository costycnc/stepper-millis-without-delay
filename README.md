# stepper-millis-without-delay


      void loop ()
     {

      // Handling the steps of one motor
  
     if ( (millis () - Steptimer) >= Stepinterval)
     digitalWrite(solenoidPin, HIGH); //Switch Solenoid ON
     digitalWrite(dirPin, HIGH); 
       MoveStepper ();
     digitalWrite(solenoidPin, LOW); //Switch Solenoid OFF

     }  // end of loop
     
https://forum.arduino.cc/t/replacing-delay-between-steps/973689/17     
