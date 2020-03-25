# TP2 Sensores y actuadores

Simulation: controller for 3-floor elevator implemented on Codesys. 
The elevator will respond to the calls in the same order they were made (chronologically).

## Interface 

### Inputs
- On electrical panel
  - Start PB
  - Stop PB
- On cabinet
  - Door closed LS
  - Door open LS
  - Go PB (x3, one per floor)
- On each floor (x3)
  - Call PB
  - Aligned LS 
  - _Door open LS (optional)_
  
### Outputs
- On electrical panel
  - Down motor
  - Up motor
- On cabinet
  - Open door motor
  - Close door motor
 
