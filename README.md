# Development of an electric window shutter motor controller
- This is the second version of my project -> First version use two SSRs, this one use one SSR (zero-cross) and one relay
- The plan is to first select the direction with the relay, then turn on the motor with the SSR
- Varistors are not optional, they are required to protect the electronics
- There will be two boards, one for the high voltage components and one for the control logic
- There is a standard shutter ctrl switch (legrand) in the wall with 3 wires, that will be also utilized and will be connected to the controller board
- Shutter motor is generic, no electronic control, only internal end-stop switches (NC)
- Whole stuff should fit into an european standard 80mm round electric box
- Optional IR led is available on the controller board to control the AC units in the rooms (experimental)
  
